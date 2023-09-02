# Hospital Cost Analysis
This project provides an analysis of hospital costs based on different service codes. The main objectives are to identify the cheapest and costliest hospitals for each service code and to calculate the mean and standard deviation of the costs.

## Table of Contents
* Installation
* Usage
* Main Processes
* Contact

## Installation
  1. Clone the repository:

```git clone https://github.com/Rkpani05/Hospital_Cost_Analysis.git ```

  2. Navigate to the project directory:

``` cd path_to_directory```

  3. Install the required packages using the requirements.txt file:

``` pip install -r requirements.txt```

## Usage
1. Ensure you have the necessary data file (path_to_your_file.xlsx) in the project directory.
   
2. Run the Jupyter notebook to perform the analysis:

```jupyter notebook Hospital_Cost_Analysis.ipynb```

3. Follow the instructions in the notebook for a step-by-step analysis.

## Main Processes
**Data Loading:** The data is loaded from an Excel file into a Pandas dataframe.

**Data Exploration and Cleaning:** The dataset is explored to understand its structure, and any missing values or duplicates are handled.

**Outlier Detection:** Outliers in the cost column are detected using the IQR method.

**Ranking Hospitals:** Hospitals are ranked based on their costs for each service code to identify the cheapest and costliest ones.

**SQLite Database Operations:** The data is stored in an SQLite database for further SQL-based analysis.

**SQL Analysis:** SQL queries are used to calculate the mean and standard deviation of the costs for each service code.

## Contact
For any queries or feedback, please reach out to:

**Name:** Rohit Kumar Pani

**Email:** rk.pani2002@gmail.com

LinkedIn: https://www.linkedin.com/in/rohit-pani-2b9090204
