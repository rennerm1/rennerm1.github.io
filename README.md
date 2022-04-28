## [Project 1: Facility-Location and Location-Routing MILP Models]
Over the course of my masters thesis I formulated two MILP models (FLP,LRP) in order to analyze the cost structures of different last mile networks in the omni-channel grocery sector. The models were also used to propose an extensive sensitivity analysis as a means of identifying underlying mechanisms as well as general influencing factors on profitability.

The following figure displays the utilized modeling framework, which illustrates the interdependce between models as well as the indivudally required model parameters.

![](/images/models.svg)

Packages and Tools utilized:
* OSMNX: To generate weighted graphs and sample customer nodes as well as visually display the routing or clustering
* HERE API: In order to generate distance and travel time matrices, including historical traffic data
* Gurobi(py): To formulate the MILP models and solve them



<p align="middle">
  <img src="/images/wue_routes.svg" width="49%" />
  <img src="/images/color_pup_test123.svg" width="49%" /> 

</p>










[Project 1: Facility-Location and Location-Routing MILP Models]: https://github.com/rennerm1/thesis
