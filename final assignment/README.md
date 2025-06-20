# README File EPA141

Created by: EPA141 Group 21

|        Name         | Student Number |
|:-------------------:|:---------------|
|  Milan Sonneveld    |    5624770     |
| Madelon van Haften  |    5163110     |
| Daan van der Hoeven |    5066271     |
|  Batuhan Tazegül    |    5264235     |


# Multi-Scenario MORDM for Flood Risk Governance in Deventer

[![Build Status](https://github.com/quaquel/EMAworkbench/actions/workflows/ci.yml/badge.svg?master)](https://github.com/quaquel/EMAworkbench/actions)
[![Coverage Status](https://coveralls.io/repos/github/quaquel/EMAworkbench/badge.svg?branch=master)](https://coveralls.io/github/quaquel/EMAworkbench?branch=master)
[![Documentation Status](https://readthedocs.org/projects/emaworkbench/badge/?version=latest)](http://emaworkbench.readthedocs.org/en/latest/?badge=master)
[![PyPi](https://img.shields.io/pypi/v/ema_workbench.svg)](https://pypi.python.org/pypi/ema_workbench)
[![PyPi](https://img.shields.io/pypi/dm/ema_workbench.svg)](https://pypi.python.org/pypi/ema_workbench)

This repository contains the implementation of a Multi-Scenario Many-Objective Robust Decision Making (MORDM) approach for designing robust flood risk strategies under deep uncertainty. The focus case is the Deventer region, located in the IJssel basin, the Netherlands.

## Overview
This study applies exploratory modeling and robustness techniques using the EMA Workbench. Key features:
- Generation of 10,000 uncertainty scenarios using Latin Hypercube Sampling
- Diversity-based selection of representative scenarios
- Multi-objective optimization with NSGA-II or Borg across multiple scenarios
- Robustness analysis (acceptability, signal-to-noise, regret)
- Vulnerability analysis using PRIM and Sobol’ sensitivity indices


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
