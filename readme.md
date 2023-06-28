# Funnel Analysis

This repository contains code for performing data analysis and exploratory data analysis (EDA) on a funnel dataset. The dataset consists of user data, including user IDs, stages, and conversion information.

## Dataset

The dataset contains the following columns:

- `user_id`: User ID
- `stage`: Stage in the funnel
- `conversion`: Boolean value indicating whether the user converted or not

## Analysis Techniques

The following analysis techniques are applied to the dataset:

1. Exploratory Data Analysis (EDA):
   - Counting the number of unique stages
   - Calculating the conversion rate
   - Visualizing the stage distribution using a bar chart

2. Additional Analysis Techniques:
   - Grouping and aggregation: Calculating conversion rate by stage
   - Filtering: Selecting only the users who converted
   - Pivot tables: Creating a pivot table to analyze conversion rate by stage
   - Visualizations: Pie chart to show the distribution of converted vs. non-converted users and stacked bar chart to compare conversion rates across stages

## Code

The code for performing the analysis and generating the visualizations is written in Python. The following libraries are used:

- pandas: Data manipulation and analysis
- NumPy: Numerical operations
- Matplotlib: Data visualization

The code can be found in the [analysis.py](analysis.py) file.

## Usage

To use this code and perform the analysis on your own dataset, follow these steps:

1. Clone the repository or download the [funnel.ipynb](funnel.ipynb) file.
2. Make sure you have Python and the required libraries installed.
3. Update the code to specify the path or filename of your dataset.
4. Run the code to perform the analysis and visualize the results.

Feel free to modify the code based on your specific requirements and explore additional analysis techniques or visualizations.

## License

This project is licensed under the [MIT License](LICENSE).
