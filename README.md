# Demonstration of Sharing RStudio Assignment Through Binder 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dhard/data_visualization_binder_demo/HEAD?urlpath=rstudio)

Uses a Git repository to set up a binder that can run R code with RStudio on the browser via [mybinder.org](https://mybinder.org) or any JupyterHub (such as UC Merced's 2i2c hub).

Based on the [rocker/geospatial](https://hub.docker.com/r/rocker/geospatial) image.

# Version 2.

This project contains version 2 of the RMarkdown notebook, containing a variety of corrections and improvments.

# How To Use this Demonstration

Click on the Binder Badge at the top to launch the demonstration.
After starting up in Binder, an instance of RStudio will start in your
web-browser. Inside there, navigate to `File -> Open File...`, open
the Rmarkdown file called `Reproducible_Data_Visualization_Demonstration.Rmd` included with the RStudio instance, and then press the `Knit` button to generate a complete data science report in HTML based on data included with the RStudio instance. You may press and hold the Knit button to generate the same report in PDF or Microsoft Word formats.

You may change the code in the notebook and those changes will be reflected in the output when you knit again. 
