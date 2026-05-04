# Used Car Sales EDA & Data Visualization Project

## Project Overview

This project is an **Exploratory Data Analysis (EDA)** and **Data Visualization** project based on a used car sales dataset.

The main goal of this project is to analyze used car sales data and understand the factors that affect the selling price of used cars. The project uses Python libraries to clean, explore, and visualize the dataset.

---

## Problem Statement

In the used car market, buyers and sellers often face difficulty in understanding the correct selling price of a car. The price of a used car can depend on many factors such as brand, model, mileage, manufacturing year, body type, drive type, number of cylinders, and location.

This project aims to answer the question:

**What factors influence the selling price of used cars?**

---

## Objective

The main objectives of this project are:

- To analyze the used car sales dataset
- To identify the most popular car brands and models
- To understand the relationship between mileage and selling price
- To compare average selling prices based on car features
- To visualize important trends in the used car market
- To find useful insights that can help buyers, sellers, and dealerships

---

## Dataset Information

The dataset contains information about used cars, including:

- Selling price
- Year sold
- Zipcode
- Mileage
- Car make
- Car model
- Manufacturing year
- Trim
- Engine
- Body type
- Number of cylinders
- Drive type

Some important columns used in this project are:

| Column Name | Description |
|---|---|
| `pricesold` | Selling price of the used car |
| `Mileage` | Distance traveled by the car |
| `Make` | Brand/company of the car |
| `Model` | Model name of the car |
| `Year` | Manufacturing year of the car |
| `BodyType` | Type of car body |
| `DriveType` | Type of drive system |
| `NumCylinders` | Number of engine cylinders |
| `zipcode` | Location where the car was sold |

---

## Tools and Libraries Used

This project was created using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## Project Workflow

The project follows these steps:

1. Import required libraries
2. Load the dataset
3. Display basic information about the dataset
4. Check missing values
5. Check duplicate values
6. Clean the dataset
7. Create useful new columns such as car age
8. Perform exploratory data analysis
9. Create visualizations
10. Write insights and conclusion

---

## Visualizations Included

This project includes different charts and graphs such as:

- Top 10 most sold car brands
- Distribution of used car selling prices
- Mileage vs selling price
- Average selling price by body type
- Drive type vs selling price
- Number of cylinders vs selling price
- Manufacturing year vs average selling price
- Top 10 most common car models
- Car age distribution
- Price comparison among top brands
- Market share of top car brands
- Average mileage by brand
- Correlation heatmap

---

## Key Insights

Some important insights from this project are:

- Certain car brands appear more frequently in the used car market.
- Mileage plays an important role in determining the selling price.
- Newer cars generally have higher selling prices than older cars.
- Body type and drive type can affect the resale value of a car.
- Cars with different numbers of cylinders show different pricing patterns.
- Some models are more popular and have higher availability in the market.

---

## Conclusion

This project helps in understanding the used car market through data visualization and analysis. It shows how different car features can affect the selling price of a used car.

The analysis can be useful for:

- Used car buyers
- Used car sellers
- Car dealerships
- Data analysis learners
- Students working on EDA projects

---

## How to Run This Project

1. Download or clone this repository.
2. Open the notebook file in Google Colab or Jupyter Notebook.
3. Upload the dataset file.
4. Run all the cells step by step.

If using Google Colab, upload the CSV file and use:

```python
import pandas as pd

df = pd.read_csv("used_car_sales.csv")
df.head()