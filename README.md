![Popular San Antonio Pools project banner](img/popular%20sa%20public%20pools%20banner.png)

Hey there!

This repo contains all my code and data for the San Antonio Express-News' story that looked at the most popular public pools in San Antonio, Texas.

## About the data

The data was provided by the City of San Antonio's Parks and Recreation Department through an open records request sent through the city's [records request portal](https://www.sa.gov/Directory/Departments/CE/Open-Records-Request) on January 27, 2023. The department returned the data to me on February 15, 2023.

The data returned to me included pool visitation numbers broken down by age and pool for fiscal years 2018 through 2022 for both outdoor and indoor pools.

For our analysis, we only looked at fiscal years 2018 and 2019, because every other year was either missing or incomplete due to the COVID-19 pandemic. We also only looked at outdoor pools, although outdoor pools could be analyzed in the future.

## How to replicate

If you'd like to run the code yourself, use the following steps:

1. Clone the repo.
2. Install the requirements with `pip install -r requirements.txt`.
3. You can either run the jupyter notebook or `cd` into the notebooks folder and use the `nbexec pool-analysis.ipynb` command to run it as a script.