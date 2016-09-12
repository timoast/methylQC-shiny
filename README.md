## methylQC web app

An interactive web app for the [methylQC](https://github.com/timoast/methylQC) R package, built using [shiny](http://shiny.rstudio.com/). To run the app locally, first make sure a couple of dependencies are installed:

```R
install.packages(c("shiny", "ploty"))
```

Then just run the app by either running `R -e "shiny::runApp('methylQC/shiny')"` on the command line, or by running `shiny::runApp('methylQC/shiny')` within R. If you use RStudio, you will also be able to run by opening the `app.R` script and pressing the 'Run app' button. This will open a browser window where you can interact with the data.

An online demo of the app can be found on [shinyapps.io](https://timoast.shinyapps.io/shiny/).
