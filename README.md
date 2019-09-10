# EECS 731 Project 1

This is Andre Kurait and Thor Lyches' first project for EECS 731, Data Science in Fall 2019. For the project one, we combined several AirBnB datasets over NYC to prepare for future analysis of changing price trends.

The project requirements were the following:

1. Set up a data science project structure in a new git repository in your GitHub account
2. Install Jupyter notebook prerequisites (Anaconda, Python, etc.)
3. Select an industry
4. Select two to three public data sets from that industry
5. Load the data sets into panda data frames following the 10 minutes to pandas guide
6. Formulate one or two ideas on how the data sets could be combined to establish additional value using exploratory data analysis
7. Transform the data sets into a single data set while following data preparation processes to clean and transform features (use pandas documentation for help)
8. Document your process and results
9. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

## Project structure

```bash
.
├── Data
│   ├── listings-2017-08-02.csv
│   ├── listings-2018-08-06.csv
│   └── listings-2019-08-06.csv
└── README.md
```

## Industry

We selected the AirBnB industry because we couldnt find datasets covering several moments in time. 

## Data
We selected AirBnB data from NYC because of NYC's infamous high housing pricing in addition to wide avaliablility of AirBnB listing snapshots over several moments in time.

We got the data from http://insideairbnb.com/get-the-data.html

Used the listings.csv from the following dates:
* 06 August, 2019
* 06 August, 2018
* 02 August, 2017

These were selected all from August to minimize fluctuations due to seasonality.

## Transfromation

We combined the data sets and included date information from each of the points.

Converted "last review date" to "days since last review" to provide more meaningful data in analysis.
