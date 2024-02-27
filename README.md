# Yelp Data Analysis Project

## Project Overview

This project aims to explore, analyze, and derive insights from Yelp data regarding various types of restaurants in Madrid. Utilizing a full-stack approach, it encompasses data collection through the Yelp API, data preprocessing and exploratory data analysis (EDA), and application development to communicate results effectively. This project demonstrates skills in data file ingest, ETL processes, interaction with data storage systems, and code version control.



## Project Structure

The project is divided into two main parts:

1. **Data Collection and EDA (`01_Data_Collection_and_EDA.ipynb`):** This notebook includes the initial data collection from the Yelp API, covering various restaurant categories in Madrid. It also contains an exploratory data analysis to understand the dataset better.

2. **Data Processing and Analysis (`02_Data_Processing_and_Analysis.ipynb`):** Following the initial data collection, this notebook focuses on preprocessing the data, including cleaning and transformation, and conducting a detailed analysis to extract meaningful insights.

## Technologies Used

- Python
- YelpAPI
- Pandas for data manipulation
- Pandas Profiling for exploratory data analysis
- Orchestration tool (Airflow)
- Model tracking (MLFlow or similar)



### Prerequisites

- Python 3.x
- Jupyter Notebook or Databricks Community Edition account for running `.ipynb` notebooks
- Required Python packages: `requests`, `json`, `yelpapi`, `pandas`, `pandas_profiling`

### Installation

1. Clone the repository to your local machine or download the project files.
2. Install the required Python packages using pip:

    ```
    pip install requests yelpapi pandas pandas_profiling
    ```

3. Open the notebooks in Jupyter Notebook or upload them to Databricks Community Edition to run.

## Usage

- To explore the dataset and initial analysis, start with the `01_Data_Collection_and_EDA.ipynb` notebook.
- For data preprocessing and deeper analysis, proceed to the `02_Data_Processing_and_Analysis.ipynb` notebook.

## Contributing

This project is a collaborative effort for educational purposes. Contributions, bug reports, and feature requests are welcome. Please refer to the project's issues tab on GitHub or contact one of the team members directly.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
