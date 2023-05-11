---
title: Crime complaints and arrests saw a big decrease in NYC under COVID-19 – Why?
feature_text: |
  ## COVID-19's impact on crime trends in New York
  A Jekyll boilerplate theme designed to be a starting point for any Jekyll website
feature_image: "https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Pictures/NewYork.jpg"
excerpt: "Alembic is a starting point for [Jekyll](https://jekyllrb.com/) projects. Rather than starting from scratch, this boilerplate is designed to get the ball rolling immediately. Install it, configure it, tweak it, push it."
---

Intro

### Changing criminal behavior in NYC due to COVID-19

hej hej 

#### Higher level of crime in NYC after COVID-19

#### More complaints after COVID-19 in all five districts 
Looking at the distribution of complaints across the five boroughs in New York City, it is clear that all of boroughs follow a similar pattern: complaints dropped in 2020 and then began to rise again in 2021, ultimately resulting in the highest number of complaints in 2022 as compared to the previous three years. 

<iframe src="https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Pictures/Complaints_map_per_100.html" width="110%" height="650px"></iframe>


Furthermore, the distribution of complaints across the five boroughs shows a consistent trend, with Manhattan having the highest number of complaints per 100,000 residents, followed by the Bronx, Brooklyn, and Queens, with Staten Island at the bottom.
Manhattan, as the borough with the highest population density, represents a vibrant tapestry of residents hailing from diverse backgrounds, cultures, and socioeconomic statuses. This unique amalgamation of people can give rise to a greater likelihood of potential conflicts, which subsequently contributes to a higher volume of reported complaints.
Conversely, The Bronx, while not as ethnically diverse as Manhattan, faces its own distinct set of challenges. The borough is characterized by a comparatively higher poverty rate, with median incomes roughly half of what is seen in areas such as Staten Island or Queens. This economic disparity can be correlated with higher crime rates and, consequently, a greater number of reported complaints (https://www.sciencedirect.com/science/article/pii/S0047235222000496)

#### Less arrests after COVID-19 in all five boroughs
When we look at the distribution of arrests across the five boroughs of New York City, we notice that the pattern is similar to the one observed for complaints. Manhattan stands out with the highest number of arrests per 100,000 residents, followed by the Bronx, Brooklyn, and Queens, while Staten Island has the lowest number of arrests.

<iframe src="https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Pictures/Arrest_map_per_100.html" width="110%" height="700px"></iframe>

However, there is an interesting twist in the data for the year 2020 when the COVID-19 pandemic emerged. While all districts experienced a decrease in arrests, Manhattan saw a larger drop compared to the Bronx, with arrests per 100,000 residents declining from 1856 to 1152, while the Bronx decreased from 1785 to 1196. Surprisingly, this resulted in the Bronx having the highest arrest rate per capita that year, despite Manhattan consistently holding that position in other years. This raises the question: what factors contributed to the Bronx surpassing Manhattan in arrests per 100,000 residents in 2020?"
There can be many underlying factors, but it is interesting to note that deaths and hospitalizations due to COVID-19 were nearly twice as high in the Bronx as in Manhattan (Kisser et al., 2020). This may have been influenced by people's ability to work from home and the opportunities to leave the city, which were primarily available to those in the wealthiest neighborhoods. As a result, residents in the Bronx were more exposed to the risks of COVID-19 and faced a greater risk of violence compared to residents in Manhattan. These factors may help explain the higher number of complaints per resident in the Bronx in 2020 when COVID-19 was at its peak (Wollf et al., 2022).

### Less crime in NYC during COVID-19, but prostitution, murder and burglary kept increasing 

#### Record high number of prostitution complaints in NYC under COVID-19, but the number of arrests keeps falling



###### Prostitution spike in the Bronx in 2020 as other boroughs witness downturn

<iframe src="https://raw.githack.com/Sdataanalyse/Sdataanalyse.github.io/main/Pictures/Complaints_map_per_100.html" width="110%" height="650px"></iframe>



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
