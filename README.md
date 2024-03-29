![Data Vis Logo](https://raw.githubusercontent.com/jhu-data-services/data-visualization-resources/main/images/datavislogo.png)

A set of data visualization resources to accompany the Data Visualization in R and Interactive Data Visualization in R with Shiny workshops at Johns Hopkins University.

[![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)

# Table of Contents

1. [Open Access Textbooks](#r-books)
2. [Tutorials](#r-tutorials)
3. [Examples and Resources](#r-examples)
4. [Packages](#r-packages)
5. [Opinions](#r-opinion)
6. [Getting Practice](#r-practice)

<a name="r-books"/>

# Open Access Textbooks

## General Data Visualization
- [Data Visualization - A practical introduction](https://socviz.co/) - The online version of Kieran Healy's book on data visualization in R.
- [Data Visualization with R](https://rkabacoff.github.io/datavis/) - Data Visualization with R by Rob Kabacoff. Focused mostly on ggplot2, but also covers interactive data visualization and spatial data visualization in R.
- [R Graphics Cookbook](https://r-graphics.org/) - A practical guide that provides more than 150 recipes to help you generate high-quality graphs quickly, without having to comb through all the details of R’s graphing systems. 

## ggplot2
- [ggplot2: elegant graphics for data analysis](https://ggplot2-book.org/) - Hadley Wickham's (ggplot2 creator) book on ggplot2. 

## Shiny
- [Mastering Shiny: Build Interactive Apps, Reports & Dashboards Powered by R](https://mastering-shiny.org/) - Hadlley Wickham's open-access textbook on Shiny. This book covers both introductory concepts in Shiny all the way to advanced concepts that allow you to build maintainable and performant apps. 
- [R powered web applications with Shiny](http://zevross.com/blog/2016/04/19/r-powered-web-applications-with-shiny-a-tutorial-and-cheat-sheet-with-40-example-apps/) - ZevRoss's Shiny tutorial, with 40 example apps. This tutorial provides an in-depth understanding of the Bootstrap grid system that Shiny utilizes to enable mobile-friendly apps. 

<a name="r-tutorials"/>

# Tutorials

## Base R
- [Creating Publication Quality Base R Graphics](https://www.jumpingrivers.com/blog/styling-base-r-graphics/) - A tutorial on creating publication quality graphics using just the base R plot function.

## ggplot2 
- [Visualizing COVID-19](https://www.datacamp.com/projects/870) - Visualize the rise of COVID-19 cases globally with ggplot2.
- [Data Carpentry - Data visulization with ggplot2](https://datacarpentry.org/R-ecology-lesson/04-visualization-ggplot2.html) - A tutorial in ggplot2 focused on ecology data.
- [The Complete ggplot2 Tutorial](http://r-statistics.co/Complete-Ggplot2-Tutorial-Part1-With-R-Code.html) - An advanced ggplot2 tutorial that covers modifying components, aesthetics, legends, and plot style. Also included is a library of 50 ggplot2 visualizations, with code, for 8 categories: Correlation, Deviation, Ranking, Distribution, Composition, Change, Groups, and Spatial Data.
- [Tufte in R](http://motioninsocial.com/tufte/) - Producing plots in the style of Edward Tufte in R. 

## Shiny
- [RStudio Shiny Tutorial](https://shiny.rstudio.com/tutorial/) - A three-part video tutorial, with accompanying slides and code, by the creators of Shiny. This is an excellent starting place for learning and improving your understanding of Shiny.

<a name="r-examples"/>

# Examples and Resources

## General R Visualization
- [R Graph Gallery](https://www.r-graph-gallery.com/index.html) - A gallery of hundreds of charts in R, with the corresponding code to reproduce them. A great place to see the vast diversity of plots that can be generated in R using a number of libraries such as ggplot2.

## Shiny 

- [Awesome-RShiny](https://github.com/grabear/awesome-rshiny) - A curated list of **awesome** Shiny resources, including resource guides, tutorials, galleries, app examples, and app sharing and hosting. 

- [Awesome Shiny Extensions](https://github.com/nanxstats/awesome-shiny-extensions) - A curated list of R pacakges that offer extended UI or server components for Shiny, allowing for enhanced functionality and aesthetics over base Shiny apps.

- [shinyapps.io](https://www.shinyapps.io/) - Share your Shiny applications online. Up to five apps can be shared publicly using a free account.

- [Shiny Galler](https://shiny.rstudio.com/gallery/) - R Studio's gallery of Shiny apps, both official demos designed to highlight specific Shiny features and a showcase of user submitted Shiny apps.

<a name="r-packages"/>

# Packages

## ggplot2
- [ggplot2](https://ggplot2.tidyverse.org/) - A powerful data visulization library in R, based on the Grammar of Graphics.
- [ggprism](https://github.com/csdaw/ggprism) - The ggprism package provides various themes, palettes, and other useful functions to customise ggplots and give them the ‘GraphPad Prism’ look.
- [ggfortify](https://github.com/sinhrks/ggfortify) - This package offers functions to allow automatic visualization of statistical results of popular R packages in ggplot2.

## Data Exploration
- [visdat](https://github.com/ropensci/visdat) - Create preliminary exploratory data visualisations of an entire dataset to identify problems or unexpected features using 'ggplot2'.
- [DataExplorer](https://boxuancui.github.io/DataExplorer/) - Library for conducting exploratory data analysis, including identifying dataframe memory usage and visualizing missing observations.

## 3D Visualization
- [RGL](https://cran.r-project.org/web/packages/rgl/index.html) - A library for visualizing 3D scatterplots, good for visualizing multivariate data in 3D.
- [plotly](https://plotly.com/r/3d-charts/) - An interactive data visualization library in R that can be used to visualize 3D scatter plots, line plots, surface plots, mesh plots, streamtube plots, isosurface plots, and tri-surf plots.

## Interactive Data Visualization
- [plotly](https://plotly.com/r/3d-charts/) - An interactive data visualization library in R for producing interactive, publication-quality graphs.
- [Shiny](https://shiny.rstudio.com/) - Shiny is an R package that makes it easy to build interactive web apps straight from R. 
- [leaflet](https://rstudio.github.io/leaflet/) - Integrate and control Leaflet interactive JavaScript maps in R.

<a name="r-opinion"/>

# Opinions 

Choosing between ggplot2 and base R graphics is not straightforward. Your choice of graphics library will depend heavily on your application and need. These articles are not meant to persuade you in choosing a particular graphics library, but instead help identify some common pitfalls with choosing a library without considering your application and audience. 

- [Why I don't use ggplot2](https://simplystatistics.org/posts/2016-02-11-why-i-dont-use-ggplot2/) - JHU professor Jeff Leek's opinion on why he doesn't use ggplot2. 
- [Why I use ggplot2](http://varianceexplained.org/r/why-I-use-ggplot2/) - David Robinson's rebuttal to Jeff Leek, arguing in favor of ggplot2.
- [Comparing ggplot2 and R Base Graphics](https://flowingdata.com/2016/03/22/comparing-ggplot2-and-r-base-graphics/) - An objective comparison of ggplot2 and R base graphics.

<a name="r-practice"/>

# Getting Practice

- [Tidy Tuesday Visualization Challenge](https://github.com/rfordatascience/tidytuesday) - TidyTuesday is a weekly social data project, organized by the [R4DS Online Learning Community](https://www.rfordatasci.com/). Each week a new dataset is released, and your challenge is to to clean and visualize it!
