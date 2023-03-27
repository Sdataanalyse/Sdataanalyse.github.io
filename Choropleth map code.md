---
layout: default
---

## Welcome to another page


[back](./)

## Choropleth map of San Francisco
To investigate how the the DRUG related crimes are distributed in the San Francisco districts we will create a choropleth map.

```
#Importing libraries
import plotly.express as px
from urllib.request import urlopen
import json
import matplotlib.pyplot as plt
import plotly.io as pio

#Group data by police district
df_drug = Data_drug2.groupby(['PdDistrict'])['PdDistrict'].count().rename('Number of DRUG/NARCOTIC')

#retrieve the geojson data from a URL using urlopen and load it into a dictionary
with urlopen('https://raw.githubusercontent.com/suneman/socialdata2022/main/files/sfpd.geojson') as response:
    counties = json.load(response)

counties["features"][0]

# create a DataFrame containing the number of DRUG related crimes for each police district
df_map = pd.DataFrame(list(df_drug.items()), columns=['PdDistrict', 'Number of DRUG/NARCOTIC'])

# create a choropleth map
fig = px.choropleth_mapbox(df_map, geojson=counties, locations='PdDistrict', color='Number of DRUG/NARCOTIC',
                           color_continuous_scale="Reds",
                           range_color=(0, 40000),
                           mapbox_style="carto-positron",
                           zoom=10, center = {"lat": 37.773972, "lon": -122.431297},
                           labels={'PDistrict'},
                           opacity=0.5,
                        )

fig.update_layout(margin={"r":0,"t":0,"l":0,"b":0})

# display the plot
fig.show() 

#Write to html file
pio.write_html(fig, file='choropleth_map.html', auto_open=True)
```