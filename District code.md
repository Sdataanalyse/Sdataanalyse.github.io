[back](./)

DRUG/NARCOTIC incidents per year for each district

```
# Add new "Year" column
df_drug['Year'] = df_drug['Date'].dt.year

# Create a crosstab with year and district
drug_district = pd.crosstab(df_drug.Year, df_drug.PdDistrict)

# Reset index
drug_district = drug_district.sort_values('Year').reset_index()

# Set the output to be shown in Jupyter Notebook
pandas_bokeh.output_notebook()

# Plot the line plot
p = drug_district.plot_bokeh.line(
    x='Year',
    y=['BAYVIEW','CENTRAL','INGLESIDE','MISSION','NORTHERN','PARK','RICHMOND','SOUTHERN','TARAVAL','TENDERLOIN'],
    figsize=(990, 650),
    xlim = (2003, 2017),
    ylim = (0, 5000),
    xlabel='Year',
    ylabel='No. of incidents',
    title='No. of DRUG/NARCOTIC incidents per year for each district',
    fontsize_title = "20pt"
)
```