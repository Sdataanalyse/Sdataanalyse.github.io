---
layout: default
---

## **Decreasing number of Drug/Narcotic incidents in San Francisco from 2003-2017**

### Introduction to the dataset 
The data comes from DataSF which is a an official open data portal of the City and County of San Francisco. The DataSF portal provides access to a wide range of data sets, including crime incidents. The data sets are produced by various departments and agencies of the city government. (1)

In this project we use the dataset "Police Department Incident Reports: Historical 2003 to May 2018". The dataset has 14 columns and 2.13M rows, where each row is an incident report. The dataset includes information about the date and time of the incident, the location, the type of crime, and other details related to the incident. It's important to note that this data only reflects reported incidents to the San Francisco Police Department, and may not capture all crimes that occur in the city.

In this project we look at the crime category DRUGS/NARCOTICS for the periode from 2003 to 2017 since we're missing data for several of months of 2018. This crime category provides informations about drug-related crimes reported to the San Francisco Police Department. (2)

<br>

### Fig. 1: Number of DRUG/NARCOTIC incidents from 2003-2017

The plot below shows the number of drug/narcotic incidents by year, month and day of week from 2003-2017.

<img src="https://raw.githubusercontent.com/Sdataanalyse/Sdataanalyse.github.io/main/Files/Calandarplot.jpg" alt="Your Picture Name">


[Link to calender plot code](Calenderplot code.md)

From 2003 to 2017, there appears to have been an overall decrease in the number of drug-related incidents. However, between 2007 and 2009, there was a noticeable peak in incidents that suggests a possible surge in drug-related criminal activity during that period.

Subsequent to 2009, there was a decrease in incidents that could be attributed to the implementation of SB 678 and the exposure of unlawful drug-related arrests by the San Francisco Police. This led to a new approach to drug crime offenses and the cancellation of a significant number of drug arrests that were deemed illegal. These events resulted in reduced felony arrests and court filings for drug crimes in San Francisco, which could explain the declining trend in the number of DRUG/NARCOTIC incidents after 2009. (3)

<br>

### Fig. 2: Drug related incidents across districts 

The map below displays the distribution of drug/narcotic incidents across the districts of San Francisco.

<iframe src="https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/Files/choropleth_map.html" width="90%" height="600px"></iframe>

[Link to Choropleth map code](Choropleth map code.md)

The map illustrates that Tenderloin is the district with the highest number of reported incidents of drug/narcotic from 2003 to 2018. There has been reported 37.365 incidents in this district.

There can be several reasons behind Tenderloin's high incidence of drug-related issues. Although it covers a relatively small area of San Francisco, the district is densely populated and the area have a long history of poverty, homelessness, and drug abuse.

Many of the people living in Tenderloin are living in poverty and have limited opportunities for employment and education. This can lead to an increased risk of drug abuse and related problems. The district has a long-standing history of being a refuge for people suffering from addiction and in dire need, which has perpetuated the drug problem. (4)(5)(6)

<br>

### Fig. 3: DRUG/NARCOTIC incidents per year for each district

The visualization is interactive, where you have the option to select/deselect the various districts in the plot. Click on one of the districts in the box to deselect it and click again to select it.

<iframe src="https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Files/district6.html" width="90%" height="600px"></iframe>

[Link to district and year plot code](District code.md)

Not only is Tenderloin the district with the highest number of reported incidents of drug/narcotic from 2003 to 2018, but according to figure 3, the Tenderloin district has consistently experienced the highest number of drug/narcotic incidents. 

Specifically, between 2006 and 2009, there was a significant increase in drug/narcotic incidents in the Tenderloin district, which contributed to the overall increase in San Francisco during that period. However, there has been a decline in the number of drug/narcotic incidents in the Tenderloin district after 2009. This decline may be attributed to various factors, including the appointment of Police Chief George Gascón in 2009, who prioritized the Tenderloin district as a high-crime area (7) and, as pointed out in figure 1, the implementation of SB 678 and the exposure of the unlawful drug-related arrests in 2009.

<br>

### References:

(1) DataSF. (n.d.). Home page. Retrieved March 25, 2023, from https://datasf.org/

(2) DataSF. (n.d.). SFPD Incident Report 2018 to Present. DataSF Dataset Explainers. Retrieved from https://datasf.gitbook.io/datasf-dataset-explainers/sfpd-incident-report-2018-to-present

(3) Eliminating Mass Incarceration: How San Francisco Did It, James Austin (JFA Institute), p. 13, https://probation.acgov.org/probation-assets/files/resources-info/Reforming%20San%20Franciscos%20Criminal%20Justice%20System-JA4.pdf

(4) San Francisco Chronicle. (2022). Tenderloin: A History of San Francisco's Most Contentious Neighborhood. Retrieved from https://www.sfchronicle.com/projects/2022/san-francisco-tenderloin-history/

(5) ABC7 News. (2021, October 28). SF's Tenderloin sees more drug arrests, but Narcan program saves lives. Retrieved from https://abc7news.com/sf-tenderloin-drug-arrests-narcan-homeless/11535735/
   
(6) 60% of S.F. drug incidents are in the Tenderloin. That number’s rise is one factor in the debate over a state of emergency, Susie Neilson, Dec. 23, 2021, https://www.sfchronicle.com/bayarea/article/These-charts-show-how-drug-incidents-in-the-16723745.php

(7) S.F. police chief's first target: Tenderloin, C.W. Nevius, Sep. 5, 2009, https://www.sfgate.com/crime/article/S-F-police-chief-s-first-target-Tenderloin-3219336.php