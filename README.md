# Comprehensive-Analysis-of-NHANES-Body-Measurements
# Overview
This repository contains a capstone project that analyzes body measurements of adult males and females based on excerpts from the National Health and Nutrition Examination Survey (NHANES) dataset. The analysis is performed using Python with a focus on NumPy and data visualization libraries such as Matplotlib and Seaborn. The entire workflow is contained within a single, well-structured Jupyter Notebook.

# Objectives Of the project
1. Import and process multidimensional data using NumPy matrices.
2. Visualize and compare weight distributions between adult males and females.
3. Compute and interpret key statistical aggregates and correlation coefficients.
4. Standardize and analyze body measurement data, including BMI, waist-to-height, and waist-to-hip ratios.
5. Document findings and interpretations in a clear, formal report style.

# Dataset
The analysis uses two CSV files, which are excerpts from the NHANES dataset:

1. nhanes_adult_male_bmx_2020.csv
2. nhanes_adult_female_bmx_2020.csv

These files can be downloaded from the teaching-data repository.
Each file contains the following columns:

1. Weight (kg)
2. Standing Height (cm)
3. Upper Arm Length (cm)
4. Upper Leg Length (cm)
5. Arm Circumference (cm)
6. Hip Circumference (cm)
7. Waist Circumference (cm)

# Notebook Contents
The Jupyter Notebook guides you through the following workflow:

1. Data Acquisition
   
   Download and load the NHANES CSV files as NumPy matrices.
2. Initial Exploration

   Inspect the structure and summary statistics of the datasets.
3. Visualization

   Create histograms of male and female weights.
   Generate comparative box-and-whisker plots for weights.
   Visualize advanced metrics (BMI, waist-to-height, waist-to-hip) using boxplots.
4. Statistical Analysis

   Calculate measures of location, dispersion, and shape for weights.
   Compare distributions (e.g., skewness, variance).
5. Feature Engineering

   Compute BMI for females and add as a new column.
   Standardize columns to obtain z-scores.
   Compute additional ratios for both sexes.
6. Correlation and Pairwise Analysis

   Generate a scatterplot matrix (pairplot) for standardized variables.
   Compute and interpret Pearson’s and Spearman’s correlation coefficients.
7. Comparative Analysis

   Identify and display individuals with the lowest and highest BMIs.
   Discuss advantages/disadvantages of BMI and other ratios.
8. Reporting

   Each section is clearly documented with Markdown headings.
   Each code chunk is preceded by a brief explanation and followed by a summary and interpretation.
   
# Usage
1. Download the NHANES CSV files and place them in the project directory.
2. Open the Jupyter Notebook (.ipynb file) in your preferred environment (e.g., JupyterLab, VS Code, Google Colab).
3. Run the notebook cells sequentially to reproduce the analysis and visualizations.

# Requirements
1. Python 3.x
2. NumPy
3. Matplotlib
4. Seaborn
5. pandas (for convenience in some sections)
6. Jupyter Notebook

Install dependencies using:

pip install numpy matplotlib seaborn pandas.



**For questions or suggestions, please open an issue or contact the repository owner.**
