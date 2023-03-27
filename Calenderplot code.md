---
layout: default
---

[back](./)

## Number of DRUG/NARCOTIC incidents from 2003-2017, by Year, Month and Day of Week 

```
# Aggregate number of DRUG/NARCOTIC incidents by day
daily_counts = df_drug.groupby([df_drug.Date.dt.date]).size()

# Create a Series with daily counts for the entire time period (2003-2017)
all_days = pd.date_range(start='2003-01-01', end='2017-12-31',freq='D')
events = pd.Series(index=all_days, data=0)
events.loc[daily_counts.index] = daily_counts.values

# Create a calendar heatmap as subplot for year 2003-2017
fig, ax = calmap.calendarplot(events, monthticks=3, daylabels='MTWTFSS',
                    dayticks=[0, 1, 2, 3, 4, 5, 6],
                    fillcolor='grey',
                    fig_kws=dict(figsize=(20, 25)))

fig.suptitle('Incidents of DRUG/NARCOTIC by Year, Month and Day of Week (2003-2017)', fontsize=18,y=1.02, x=0.5) 

# Create a colorbar
cbar = plot.colorbar(ax[0].get_children()[1], ax=ax, orientation='vertical', aspect=85, fraction =0.2)
cbar.set_label('No. of incidents')

plot.show()
```
[back](./)