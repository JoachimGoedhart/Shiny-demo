# Shiny-demo

Step-by-step instructions for building a Shiny app, startimg with a histogram that shows a distribution of 'waiting times' from the geyser dataset. The first version of the app is at the "master" branch and is identical to the 'app' that is created when a new Shiny app is generated from R/Rstudio.
Changes and new features are added and the code can be obtained by selecting new branches (Update_1, Update_2 and so forth).
It is also possible to compare the changes differences between versions.

![alt text](https://github.com/JoachimGoedhart/Shiny-demo/blob/master/Compare-versions.png "Output")

To run the different Updates from R/Rstudio use:
shiny::runGitHub('Shiny-demo', 'JoachimGoedhart', ref="Update_1")
shiny::runGitHub('Shiny-demo', 'JoachimGoedhart', ref="Update_2")
......and so on.....
