# Disney-Movies-and-Box-Office-Success-Using-Python-NumPy-Pandas
 

## Overview
This project is a data analytics and machine learning project performed using Python, including popular libraries like NumPy, Pandas, Seaborn, and scikit-learn. The primary goal of this project is to analyze the top ten movies at the box office and make data-driven recommendations based on the findings.

## Steps

### 1. Top Ten Movies at the Box Office
- Collected data on the top ten movies at the box office.
- Analyzed the box office performance of these movies.

### 2. Movie Genre Trend from the Top Ten Movies
- Explored the movie genre trend within the top ten movies.
- Identified which genres were most prevalent among the top movies.

### 3. Visualizing Genre Popularity Trend
- Utilized Seaborn to create visualizations that showcased the genre popularity trend among the top movies.
- Created a relational plot (relplot) to visualize this trend.

### 4. Data Transformation on Categorical Columns
- Performed data transformation on categorical columns to make them suitable for machine learning.
- Prepared the data for the regression model by converting categorical variables into dummy variables.

### 5. Linear Regression Model
- Developed a linear regression model to predict the adjusted gross of movies based on the generated dummy variables.
- Evaluated the model's performance and determined its accuracy.

### 6. Confidence Intervals
- Computed 95% confidence intervals for the intercept and coefficients of the linear regression model.
- Analyzed the significance of each feature in predicting the adjusted gross.

## Final Conclusion
Based on the data analysis and the linear regression model, the conclusion is that Disney should make more action and adventure movies. These genres tend to perform better in terms of adjusted gross compared to other genres, as indicated by our data and analysis.


## How to Run
- You can run this project by following the instructions in the [documentation](docs/README.md).

## Project Structure
- The project is structured as follows:
  - `data/`: Contains the data used for analysis.
  - `notebooks/`: Jupyter notebooks with the data analysis and model development.
  - `src/`: Python source code.
  - `docs/`: Documentation and additional information.

## Dependencies
- Python
- NumPy
- Pandas
- Seaborn
- scikit-learn

## Getting Started
To get started with this project, follow the steps below:

1. Clone the repository to your local machine.
2. Install the required dependencies.
3. Explore the Jupyter notebooks in the `notebooks/` directory to see the data analysis and model development process.
4. Run the code to replicate the analysis and model building.