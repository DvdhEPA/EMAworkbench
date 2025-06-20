# README File EPA133a - Assignment 3

Created by: EPA133a Group 9

|        Name         | Student Number |
|:-------------------:|:---------------|
|  Amaryllis Brosens  | 5307554        |
| Madelon van Haften  | 5163110        |
| Daan van der Hoeven | 5066271        |
|  Quinty Okhuijsen   | 5628060        |
|   Nynke Steinmetz   | 5186455        |

## Project description
This project focuses on automatically generating a Mesa-based simulation model to study the impact of bridge maintenance and unavailability on traffic throughput along the N1 and N2 highway and their sideroads longer than 25km in Bangladesh. The primary objective is to analyze how different bridge failure probabilities affect truck travel times and delays.

Delays and travel time will be measured by sending trucks from randomly chosen starts of roads every 5 minutes with a "business as usual" model and 8 scenarios. 

## Installation and setup
For this project, it is important to install the packages in 'reguirements.txt' and ensure they are up to date

## Folder structure 
```
├── archives
│   └── optimization.tar.gz
│   └── optimization_Scenario 608_run0.tar.gz
│   └── optimization_Scenario 608_run1.tar.gz
│   └── optimization_Scenario 608_run2.tar.gz
│   └── optimization_Scenario 608_run3.tar.gz
│   └── optimization_Scenario 608_run4.tar.gz
│   └── optimization_Scenario 654_run0.tar.gz
│   └── optimization_Scenario 654_run1.tar.gz
│   └── optimization_Scenario 654_run2.tar.gz
│   └── optimization_Scenario 608_run3.tar.gz
│   └── optimization_Scenario 608_run3.tar.gz




## How to Use the Code

In principle, you only need to run the notebook MORDM Clean.ipynb. This notebook calls all the necessary functions and scripts internally, so no separate preprocessing or postprocessing steps are required.

All data preparation, simulation runs, and result processing are handled from within this single notebook.
