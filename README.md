# Exploratory-Data-Analysis1
# Cardiographic Data Analysis

This repository contains a Python script for analyzing cardiographic data. The script performs data cleaning, exploratory data analysis (EDA), and visualization to uncover patterns and insights in the dataset.

## Dataset
The dataset used in this project is a CSV file named `cardiographic.csv`. It contains cardiographic metrics and other related variables. Key steps in the analysis include handling missing values, outlier treatment, and correlation analysis.

## Features of the Script

### 1. **Data Cleaning**
- **Handling Missing Values**: Missing values are filled with the median of respective columns.
- **Data Type Conversion**: Attempts to convert object-type columns to numeric. If conversion fails, a message is displayed.
- **Outlier Treatment**: Outliers are capped using the Interquartile Range (IQR) method.

### 2. **Exploratory Data Analysis (EDA)**
- **Statistical Summary**: Summary statistics including IQR.
- **Visualization**: 
  - Histograms for data distribution.
  - Boxplots to detect outliers.
  - Scatter plots for relationships between variables.
  - Correlation heatmap to identify strong relationships.
  - Pairplot for multi-variable distribution and relationships.

### 3. **Visualization Highlights**
- Histograms and boxplots to explore data distribution and detect anomalies.
- Correlation heatmap to understand the relationships among variables.
- Time-series plot (if a `Time` column is present) to observe trends in baseline fetal heart rate (LB).

### 4. **Output**
The cleaned dataset is saved as `cleaned_cardiographic.csv` for further analysis or modeling.

## Prerequisites
Make sure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/cardiographic-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd cardiographic-analysis
   ```
3. Place the `cardiographic.csv` file in the project directory.
4. Run the script:
   ```bash
   python cardiographic_analysis.py
   ```

## Visualizations
- **Histograms**: Visualize the distribution of variables.
- **Boxplots**: Detect and visualize outliers.
- **Scatterplots**: Understand relationships between key variables like LB and ASTV.
- **Correlation Heatmap**: Identify highly correlated variables.
- **Pairplot**: Visualize pairwise relationships and distributions.

## Insights
- Statistical and visual insights are derived to better understand the cardiographic data.
- Highlights include the identification of highly correlated variables and trends over time.

## Output File
The cleaned and processed dataset is saved as `cleaned_cardiographic.csv`.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements
Special thanks to the contributors of Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn for their powerful data analysis tools.

---

Feel free to fork and contribute to this repository by creating pull requests or opening issues for discussion
