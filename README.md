# correlation-calculator

PMCC and P-Value Calculator
Overview
The PMCC and P-Value Calculator is a web-based tool that allows users to calculate the Pearson Correlation Coefficient (PMCC) and the p-value between two sets of data. The tool helps in identifying the strength and significance of the relationship between the two variables. It also provides a scatter plot visualization with a line of best fit to better understand the data relationship.

Features
- Data Input: Paste data directly from Google Sheets, including headers.
- Data Cleaning: Automatically ignores null values, blank rows, and negative values.
- PMCC Calculation: Computes the Pearson Correlation Coefficient between two sets of data.
- P-Value Calculation: Calculates the p-value to determine the statistical significance of the correlation.
- Visualization: Generates a scatter plot with a line of best fit.
- Interpretation: Provides an interpretation of the results based on significance.
  
Technology Stack
HTML, CSS, JavaScript
Chart.js for visualizing data
jStat for statistical calculations


Getting Started
Prerequisites
To run this project locally, you need a web browser with JavaScript enabled.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/pmcc-pvalue-calculator.git
cd pmcc-pvalue-calculator
Open the HTML file: Simply open index.html in your web browser to start using the calculator.

Usage
Input Data: Copy and paste your data directly from a Google Sheet into the input area. Ensure the first row contains headers as they will be used as axis labels.

Calculate: Click the "Calculate PMCC and P-Value" button.

View Results: The calculator will display:

The PMCC value indicating the strength of the relationship.
The p-value to determine if the relationship is statistically significant.
A scatter plot with a line of best fit to visualize the data.
Interpretation: Read the provided spiel about the significance of the results.

Data Formatting Tips
Ensure the data has headers in the first row, as they are used for axis labels.
Data should be in two columns with numeric values. Blank rows, null values, and negative values are ignored automatically.
