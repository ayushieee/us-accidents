# Data Analytics Project: US Accidents Analysis

## Overview

This project focuses on analyzing US traffic accidents using the dataset available at [US Accidents Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents). The dataset provides comprehensive information on accidents across different cities in the United States. The analysis is performed using the Pandas library in Python.

## Dataset

The dataset contains detailed information about accidents, including location coordinates, time, weather conditions, and severity. You can download the dataset from [this Kaggle link](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents). Please make sure to include the dataset in the project directory before running the code.

## Dependencies

Make sure you have the following dependencies installed to run the project:

- Python 3.x
- Pandas
- Matplotlib
- NumPy
- Jupyter Notebook (optional)

You can install these dependencies using the following command:

```bash
pip install pandas matplotlib numpy jupyter
```

## Project Structure

- `us_accidents_analysis.ipynb`: Jupyter Notebook containing the main analysis code.
- `data/`: Folder containing the dataset (`US_Accidents.csv`).
- `README.md`: Project documentation.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/us-accidents-analysis.git
cd us-accidents-analysis
```

2. Download the dataset from the provided Kaggle link and place it in the `data/` folder.

3. Open and run the `us_accidents_analysis.ipynb` notebook using Jupyter Notebook or your preferred Python environment.

## Summary and Conclusion

### Insights:

1. **No Data from New York:**
   - The dataset lacks information about accidents in New York. Further investigation may be required to understand the reasons behind this gap.

2. **Exponential Decrease in Accidents per City:**
   - The number of accidents per city shows an exponential decrease, indicating that a few cities experience a large number of accidents, while the majority have fewer incidents.

3. **Less than 5% of Cities with More than 1000 Yearly Accidents:**
   - A small percentage of cities account for a significant portion of yearly accidents, highlighting areas that may require targeted safety measures.

4. **Over 1200 Cities with Just One Reported Accident:**
   - There are over 1200 cities that have reported only one accident. Investigating the reasons behind this low occurrence in these cities may provide valuable insights.

## Conclusion

This analysis offers valuable insights into the patterns and trends of traffic accidents across different cities in the United States. The findings can be used to guide further research and inform decision-making in implementing safety measures to reduce the number of accidents.

