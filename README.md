## [Project 1: Facility-Location and Location-Routing MILP Models]
Over the course of my masters thesis I formulated two MILP models (FLP,LRP) in order to analyze the cost structures of different last mile networks in the omni-channel grocery sector. The models were also used to propose an extensive sensitivity analysis as a means of identifying underlying mechanisms as well as general influencing factors on profitability.

The following figure displays the utilized modeling framework, which illustrates the interdependce between models as well as the indivudally required model parameters.

![](/images/models.svg)

Packages and Tools utilized:
* OSMNX: To generate weighted graphs and sample customer nodes as well as visually display the routing or clustering
* HERE API: In order to generate distance and travel time matrices, including historical traffic data
* Gurobi(py): To formulate the MILP models and solve them


Automated Route Plotting   |  Automated Customer Allocation
:-------------------------:|:-------------------------:
![](/images/wue_routes.svg)  |  ![](/images/color_pup_test123.svg)




<p align="center">
  <img alt="Automated Route Plotting" src="/images/wue_routes.svg" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Automated Customer Allocation" src="/images/color_pup_test123.svg" width="45%">
</p>

## [Project 2: NFL Data Science Project]
An extensive data science project focusing on data wrangling with large data sets (500.000 rows, 255 columns), as well as visualization of underlying insights in the sport of American Football. The data set stored play-by-play information for the seasons of 2009-2019. 
Through the use of some tidyverse data wrangling techniques and ggplots visualization capabilities interesting insights were derived.


Quarterback Analysis   |  Expected Points Added Run Plays
:-------------------------:|:-------------------------:
![](/images/QB_Analysis.png)  |  ![](/images/EPA_Runloc.png)




[Project 1: Facility-Location and Location-Routing MILP Models]: https://github.com/rennerm1/thesis
[Project 2: NFL Data Science Project]: https://github.com/rennerm1/NFL-Data-Science-Project
