# Automobile Dataset Analysis

This project aims to analyze the "Automobile Dataset" sourced from the UCI Machine Learning Repository. The dataset provides various attributes of automobiles, including features like make, fuel type, horsepower, price, etc. Throughout this project, we perform data cleaning, preprocessing, and exploratory data analysis to gain insights into the automotive industry.

## Dataset Information

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data)
- **Features**: 
  - symboling
  - normalized-losses
  - make
  - fuel-type
  - aspiration
  - num-of-doors
  - body-style
  - drive-wheels
  - engine-location
  - wheel-base
  - length
  - width
  - height
  - curb-weight
  - engine-type
  - num-of-cylinders
  - engine-size
  - fuel-system
  - bore
  - stroke
  - compression-ratio
  - horsepower
  - peak-rpm
  - city-mpg
  - highway-mpg
  - price

## Project Steps

1. **Data Import and Preprocessing**: 
   - Imported the dataset using Pandas
   - Added headers to the dataframe
   - Identified and handled missing values
   - Dealt with missing data by dropping rows, replacing with mean/frequency, or dropping columns
   - Corrected data format (dtype conversion)
   
2. **Data Transformation**:
   - Standardized and normalized data
   - Applied binning to categorize continuous variables
   - Created indicator variables for categorical features
   
3. **Exploratory Data Analysis**:
   - Visualized distributions and relationships between variables
   - Derived insights into factors affecting automobile prices, fuel efficiency, etc.
   
4. **Conclusion**:
   - Summarized findings and key takeaways from the analysis
   
## Files Included

- **Notebook File**: Contains the Python code for data analysis and preprocessing.
- **Cleaned Dataset**: CSV file containing the cleaned and processed dataset.
- **README.md**: This file, providing an overview of the project and instructions for running the code.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/automobile-dataset-analysis.git
