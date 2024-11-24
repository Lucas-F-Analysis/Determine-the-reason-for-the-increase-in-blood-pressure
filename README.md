# Determine the Reason for the Increase in Blood Pressure

## Project Overview
An independent physician requested an analysis to determine the reasons behind the increase in blood pressure observed in their patients. The dataset provided contains the following variables:
- Height
- Weight
- Gender
- Age
- BP_max (maximum blood pressure)

Using this dataset, the project aims to uncover the factors contributing to higher blood pressure levels and propose actionable insights.

## Objectives
1. Perform data cleaning and preprocessing.
2. Engineer new features such as BMI, body fat percentage, and basal metabolic rate.
3. Visualize data to understand distributions and correlations.
4. Apply statistical techniques and linear regression to identify key variables influencing blood pressure.
5. Provide recommendations based on findings.

## Techniques and Tools Used
- **Data Cleaning**: Handled missing values, unrealistic weights, and heights.
- **Feature Engineering**: Created new variables like BMI and fat percentage.
- **Data Visualization**: Used tools such as Seaborn and Matplotlib to explore relationships in the data.
- **Linear Regression**: Analyzed the impact of individual features on BP_max.
- **Age Ranges Analysis**: Studied BP trends across different age groups.

## Key Findings
- **Age** is the most significant factor influencing blood pressure.
- BP_max tends to increase with age, peaking in the 60-64 age group before slightly decreasing in older groups.
- Younger individuals (15-39 years) exhibited lower BP_max, indicating better cardiovascular health.

## Final Recommendations
- Encourage adopting healthier lifestyles, including balanced diets, physical activity, and stress management.
- Monitor blood pressure more frequently in individuals over 60 years old to manage hypertension risks effectively.

## Project Structure
- `data/`: Contains the dataset used for analysis.
- `notebooks/`: Jupyter Notebook with the detailed analysis and code.
- `results/`: Visualizations and summary tables generated during the analysis.
- `README.md`: Project documentation.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/blood-pressure-analysis.git
