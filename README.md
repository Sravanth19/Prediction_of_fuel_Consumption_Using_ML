# 🚗 Fuel Consumption Analysis (Auto MPG)

This repository contains a comprehensive analysis of the **Auto MPG dataset** to understand and predict vehicle fuel efficiency. The project places a strong emphasis on **Data Visualization** to uncover trends between vehicle specifications and fuel consumption.

## 📄 Project Overview

The primary goal of this project is to explore the factors affecting a car's Miles Per Gallon (MPG). By leveraging various Python visualization libraries, we identify key correlations between attributes like cylinders, displacement, horsepower, and weight.

## 📂 Repository Contents

* **`auto_mpg_dataset.csv`**: The dataset containing technical specifications of various car models.
* **`fuel_consumption.pdf`**: A detailed report containing the visualized plots, insights, and model conclusions.

## 🛠️ Tech Stack & Libraries Used

The analysis was conducted using Python with the following key libraries:

* **Pandas**: For data manipulation and cleaning.
* **NumPy**: For numerical computations.
* **Seaborn**: Used for advanced statistical data visualization (Heatmaps, Pair plots, Regression plots).
* **Matplotlib**: Used for basic plotting and figure customization.
* **Scikit-Learn**: For building the predictive regression model.

## 📊 Visualizations & Analysis

We utilized **Seaborn** and **Matplotlib** to create the following visualizations (detailed in the PDF):

1.  **Correlation Heatmaps:** To identify which variables (e.g., Weight, Displacement) have the strongest negative impact on MPG.
2.  **Pair Plots:** To visualize the pairwise relationships between all numerical variables in the dataset.
3.  **Box Plots:** To check for outliers in horsepower and acceleration across different origin countries.
4.  **Scatter Plots:** To observe the linear relationship between Horsepower and MPG.
5.  **Distribution Plots:** To check the skewness of the target variable (MPG).

## 📉 Key Insights

* **Weight vs. MPG:** Strong negative correlation; heavier vehicles drastically reduce fuel efficiency.
* **Origin Influence:** Vehicles originating from **Japan (3)** and **Europe (2)** generally show higher MPG compared to **USA (1)** models in this dataset.
* **Cylinders:** Cars with 4 cylinders are significantly more fuel-efficient than those with 8 cylinders.

## ⚙️ How to Run

1.  Ensure you have Python installed.
2.  Install the required libraries:
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn
    ```
3.  Load the dataset using Pandas and run the analysis script (or open the Jupyter Notebook if available).

## 🤝 Contributing

If you have ideas for more complex visualizations or different modeling techniques (like Random Forest or XGBoost), feel free to fork this repo and submit a Pull Request!
