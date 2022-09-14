# Road Traffic Accidents Analysis

## Introduction
All road traffic accidents involving casualties are logged and reported in the United Kingdom, along with (probably) a majority of other non-fatal road traffic accidents. Every year, the government releases a large batch of data associated with these reports.<br>
This analysis will be using the data from 2019 as it represents a very complete sample with a lot of ancillary data available. <br><br>
The aim of this project is to develop a model that would predict accidents and the injuries that may be incurred, also to advise the government agencies about how the road safety can become better.

## Table of Contents
1. <a href="#technologies-and-platforms-used">Technologies and Platforms Used</a>
2. <a href="#data-used">Data Used</a>
3. <a href="#implementation-steps">Implementation Steps</a>
3. <a href="#analysis-performed">Analysis Performed</a>
4. <a href="#how-to-run-this-project">How To Run This Project</a>
4. <a href="#recommendation">Recommendation</a>
5. <a href="#author">Author</a>
6. <a href="#license">License</a>


## Technologies and Platforms Used

- [Python](https://www.python.org/)
- [Spark](https://spark.apache.org/documentation.html)
- [Jupyter Notebook](https://jupyter.org/)


## Data Used

- Brief-guide-to road-accidents-and-safety-data
<br><br>
This file contains a very short introduction to the data set produced by the government.

- Variable lookup
<br><br>
This spreadsheet details the large amount of variables present in each of the datasets.

- Road Safety Data - Accidents 2019
<br><br>
This spreadsheet contains the details of the accidents logged in 2019.

- Road Safety Data - Casualties 2019
<br><br>
This spreadsheet details the casualties contained in the logged accidents.

- Road Safety Data - Vehicles 2019
<br><br>
This spreadsheet contains the details of the vehicles involved in the accidents.

- Adjustment Files
<br><br>
These files contain government modelling for the probabilities of different injuries occurring for each accident.
    <br>
    (i)	Adjustment figure guidance: This provides a short amount of government guidance on the figures included. 
    <br>
    (ii) Cas_adjustment_lookup_2019: This spreadsheet contains the tabulated adjusted probabilities of injuries. 


## Implementation Steps

* Loading the data to be analysed
* Cleaning the data
* Analysis
* Visualisation
* Prediction
* Report generation


## Analysis Performed
#### <b>Problem statemens</b>
You are a data scientist confronted with this data. Your task is to advise government agencies about how to improve road safety and create a model that would predict such accidents and the injuries that they incur.
You are tasked with answering these questions, using visualisations where these would support your conclusions.

- Are there significant hours of the day, and days of the week, on which accidents occur?
- For motorbikes, are there significant hours of the day, and days of the week, on which accidents occur?
- For pedestrians involved in accidents, are there significant hours of the day, and days of the week, on which they are more likely to be involved?
- What impact, if any, does daylight savings have on road traffic accidents in the week after it starts and stops?
- What impact, if any, does sunrise and sunset times have on road traffic accidents?
- Are there particular types of vehicles (engine capacity, age of vehicle, etc.) that are more frequently involved in road traffic accidents?
- Are there particular conditions (weather, geographic location, situations) that generate more road traffic accidents?
- How does driver related variables affect the outcome (e.g., age of the driver, and the purpose of the journey)?
- Can we make predictions about when and where accidents will occur, and the severity of the injuries sustained from the data supplied to improve road safety? How well do our models compare to government models? 

## How To Run This Project

For this project, the platform used was Jupyter Notebook. 
<br>
All the processing was done via executable Notebooks, Scripts and Code. The solution was implemented using Python. 
<br><br>

```bash
# Clone or Download this repository
$ git clone https://github.com/crownytee/road_traffic_accidents_analysis.git

# Download all required data.

# Sign up on Jupyter Notebook(if you don't have an account)
• https://jupyter.org/

# Upload the data on the Jupyter Notebook platform.

# On Jupyter Notebook, import the `.ipynb` file(s) from the cloned repository.
# Open the Notebook and click on <Run All>. This will run all the cells in 
# the Notebook and give the result for the analysis.
• Run All
```

## Recommendation

* It can be suggested that government should construct new roads to reduce and divert traffic from congested areas and increase visibility such as road signs, markings etc.
* Some insights drawn from the type of vehicles, age of vehicles, age of drivers, involved in accidents and movement of pedestrians, locations of accidents are important information’s that law makers can use to understand the causes of accidents which help them to review their policy and provide solution to tackle the problems.
* To minimise road traffic accidents, measures such as alerting road traffic users against areas i.e., dangerous junctions etc prone to accidents, and organising drivers attitude programs should be put in place.
* Cities identified on the dot map distribution as areas with higher density of accidents should be investigated to find out the construction needs.
* Government should provide education to encourage all road users. Also, Safety features in vehicles should also be promoted.

## Author

Olaitan Ramon

## License

--

---