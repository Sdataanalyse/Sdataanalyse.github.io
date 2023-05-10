---
title: COVID-19’s impact on the criminal behavior in NYC from 2019 to 2022
feature_text: |
  ## COVID-19's impact on crime trends in New York
  A Jekyll boilerplate theme designed to be a starting point for any Jekyll website
feature_image: "https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Pictures/NewYork.jpg"
excerpt: "Alembic is a starting point for [Jekyll](https://jekyllrb.com/) projects. Rather than starting from scratch, this boilerplate is designed to get the ball rolling immediately. Install it, configure it, tweak it, push it."
---

## Background/introduction 


### More complaints after COVID-19 in all five boroughs 
As previously noted, the number of complaints in 2022 exceeded that of 2019, despite a decline during the COVID-19 pandemic. In order to delve deeper into this phenomenon, we will examine the five boroughs of New York City to determine if this trend is uniform across the board. 
The accompanying map illustrates the frequency of complaints per 100,000 residents in each borough.

<iframe src="https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Plots/Complaints_map_per_100.html" width="110%" height="800px"></iframe>

The maps show that all five districts share a common pattern: complaints dropped in 2020 and then began to rise again in 2021, ultimately resulting in the highest number of complaints in 2022 as compared to the previous three years. However, only Queens had already exceeded the number of complaints per 100,000 residents in 2021 compared to 2019.
Likewise, the distribution of complaints across the five boroughs shows a consistent trend, with Manhattan having the highest number of complaints per 100,000 residents, followed by the Bronx, Brooklyn, and Queens, with Staten Island at the bottom.
Manhattan, as the borough with the highest population density, represents a vibrant tapestry of residents hailing from diverse backgrounds, cultures, and socioeconomic statuses. This unique amalgamation of people can give rise to a greater likelihood of potential conflicts, which subsequently contributes to a higher volume of reported complaints.
Conversely, The Bronx, while not as ethnically diverse as Manhattan, faces its own distinct set of challenges. The borough is characterized by a comparatively higher poverty rate, with median incomes roughly half of what is seen in areas such as Staten Island or Queens. This economic disparity can be correlated with higher crime rates and, consequently, a greater number of reported complaints (https://www.sciencedirect.com/science/article/pii/S0047235222000496)

# Less arrests after COVID-19 in all five boroughs 
As previously mentioned, there was a decline in arrests following the COVID-19 outbreak when compared to 2019. To gain more insight into this trend, we will take a closer look at the boroughs and determine whether the decrease in arrests is consistent across all of them as we saw for complaints. The map illustrates the number of arrests per 100,000 residents.

<iframe src="https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Plots/Arrest_map_per_100.html" width="110%" height="800px"></iframe>

When we look at the distribution of arrests across the five boroughs of New York City, we notice that the pattern is similar to the one observed for complaints. Manhattan stands out with the highest number of arrests per 100,000 residents, followed by the Bronx, Brooklyn, and Queens, while Staten Island has the lowest number of arrests.
However, there is an interesting twist in the data for the year 2020. While all districts experienced a decrease in arrests, Manhattan had a larger drop than Bronx, going from 1856 to 1152 arrests per 100,000 residents, while Bronx decreased from 1785 to 1196 arrests per 100,000 residents. As a result, the Bronx had the most arrests per capita that year, even though Manhattan had the most complaints. There can be many factors related to this. However, it may be explained by the aftermath of the killing of George Floyd in May 2020. According to a study (reference) examining violence in New York City throughout the COVID-19 pandemic, there was an increase in assault incidents during the social unrest following the killing of George Floyd. Interestingly, this increase was particularly driving by the Bronx, offering a potential explanation for the borough having the highest number of arrests per 100,000 residents in 2020
It's worth noting that despite the increase in arrests in 2021 and 2022, none of the boroughs have yet reached the same level of arrests as before the COVID-19 pandemic. This trend is consistent across all five boroughs, and it begs the question of what factors may be contributing to this overall decrease in arrests when comparing 2022 to 2019, even as complaints continue to rise.


# Features

- Available as a **theme gem** and **GitHub Pages** theme
- Clear and elegant design that can be used out of the box or as solid starting point
- Tested in all major browsers, including **IE and Edge**
- Built in **Service Worker** so it can work offline and on slow connections
- **Configurable colours** and typography in a single settings file
- Extensive set of **shortcodes** to include various elements; such as buttons, icons, figure images and more
- Solid **typographic framework** from [Sassline](https://sassline.com/)
- Configurable navigation via a single file
- Modular Jekyll components
- Post category support in the form of a single post index page grouped by category
- Built in live search using JavaScript
- **Contact form** built in using [Formspree](https://formspree.io/)
- Designed with **[Siteleaf](https://www.siteleaf.com/)** in mind
- Has 9 of the most popular networks as performant sharing buttons
- Has documentation

## Examples


<iframe src="https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Plots/Complaints_map.html" width="110%" height="800px"></iframe>

test

<iframe src="https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Plots/Complaints_map.html" width="100%" height="600px"></iframe>


Here are a few examples of Alembic out in the wild being used in a variety of ways:

- [bawejakunal.github.io](https://bawejakunal.github.io/)
- [case2111.github.io](https://case2111.github.io/)
- [karateca.org](https://www.karateca.org/)


- [Skriv tekst](https://sdataanalyse.github.io/elements/)


## Installation

### Quick setup

To give you a running start I've put together some starter kits that you can download, fork or even deploy immediately:

- ⚗️🍨 Vanilla Jekyll starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-kit){:style="background: none"}
- ⚗️🌲 Forestry starter kit  
  [![Deploy to Forestry](https://assets.forestry.io/import-to-forestry.svg)](https://app.forestry.io/quick-start?repo=daviddarnes/alembic-forestry-kit&engine=jekyll){:style="background: none"}  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-forestry-kit){:style="background: none"}
- ⚗️💠 Netlify CMS starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-netlifycms-kit&stack=cms){:style="background: none"}

- ⚗️:octocat: GitHub Pages with remote theme kit  
  {% include button.html text="Download kit" link="https://github.com/daviddarnes/alembic-kit/archive/remote-theme.zip" color="#24292e" %}
- ⚗️🚀 Stackbit starter kit  
  [![Create with Stackbit](https://assets.stackbit.com/badge/create-with-stackbit.svg)](https://app.stackbit.com/create?theme=https://github.com/daviddarnes/alembic-stackbit-kit){:style="background: none"}

### As a Jekyll theme

1. Add `gem "alembic-jekyll-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the theme and its dependancies
3. Add `theme: alembic-jekyll-theme` to your `_config.yml` file to set the site theme
4. Run `bundle exec jekyll serve` to build and serve your site
5. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a GitHub Pages remote theme

1. Add `gem "jekyll-remote-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
3. Add `jekyll-remote-theme` to the list of `plugins` in your `_config.yml` file
4. Add `remote_theme: daviddarnes/alembic@main` to your `_config.yml` file to set the site theme
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a Boilerplate / Fork

_(deprecated, not recommended)_

1. [Fork the repo](https://github.com/daviddarnes/alembic#fork-destination-box)
2. Replace the `Gemfile` with one stating all the gems used in your project
3. Delete the following unnecessary files/folders: `.github`, `LICENSE`, `screenshot.png`, `CNAME` and `alembic-jekyll-theme.gemspec`
4. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

## Customising

When using Alembic as a theme means you can take advantage of the file overriding method. This allows you to overwrite any file in this theme with your own custom file, by matching the file name and path. The most common example of this would be if you want to add your own styles or change the core style settings.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.

If you're looking to set your own colours and fonts you can overwrite them by matching the variable names from the [`_settings.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_settings.scss) file in your own `styles.scss`, make sure to state them before the `@import "alembic";` line so they take effect. The settings are a mixture of custom variables and settings from [Sassline](https://medium.com/@jakegiltsoff/sassline-v2-0-e424b2881e7e) - follow the link to find out how to configure the typographic settings.
