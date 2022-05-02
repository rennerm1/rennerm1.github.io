## [Project 1: Facility-Location and Location-Routing MILP Models (Python)]
Over the course of my masters thesis I formulated two MILP models (FLP,LRP) in order to analyze the cost structures of different last mile networks in the omni-channel grocery sector. The models were also used to propose an extensive sensitivity analysis as a means of identifying underlying mechanisms as well as general influencing factors on profitability.

The following figure displays the utilized modeling framework, which illustrates the interdependce between models as well as the indivudally required model parameters.

![](/images/models.svg)

Packages and Tools utilized:
* OSMNX: To generate weighted graphs and sample customer nodes as well as visually display the routing or clustering
* HERE API: In order to generate distance and travel time matrices, including historical traffic data
* Gurobi(py): To formulate the MILP models and solve them


<p align="center">
  <img alt="Automated Route Plotting" src="/images/wue_routes.svg" height="450">
  <img alt="Automated Customer Allocation" src="/images/color_pup_test123.svg"  height="450">
</p>

## [Project 2: NFL Data Science Project (R)]
An extensive data science project focusing on data wrangling with large data sets (500.000 rows, 255 columns), as well as visualization of underlying insights in the sport of American Football. The data set stored play-by-play information for the seasons of 2009-2019. \
Through the use of some tidyverse data wrangling techniques and ggplots visualization capabilities, interesting insights were derived.

<p align="center">
  <img alt="Expected Points Added Run Plays" src="/images/EPA_Runloc.png" width="100%">
</p>

The project also included the scraping of college and combine stats of collegiate athletes. \
The scraped data was subsequently used to once more gain a deeper understanding about player performance as well as performance in relation to college location. The data was also utilized in order to train a machine learning model capable of predicting in which rounds players would be drafted in the yearly NFL draft.
We decided to use a random forest model and achieved the following performance metrics: 69.3% Accuracy, 0.609 ROC Score
<p align="center">
  <img src="/images/draft_locations.png" width="100%">
</p>


##[Project 3: Deep Learning - Image Classification and Object Detection (Python)]
Kaggle competition 

[Project 1: Facility-Location and Location-Routing MILP Models (Python)]: https://github.com/rennerm1/thesis
[Project 2: NFL Data Science Project (R)]: https://github.com/rennerm1/NFL-Data-Science-Project
[Project 3: Deep Learning - Image Classification and Object Detection (Python)]: https://github.com/rennerm1/Deep-Learning-Project



