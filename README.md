# diamonds-are-forever
Data analysis of a database containing 54,000 diamonds data. Exploring why market size (carat) out values other factors such as color or clarity.

# 💎 The Diamond Paradox: A Data-Driven Analysis

## Project Overview
This repository contains an Exploratory Data Analysis (EDA) of the classic "Diamonds" dataset. The goal of this project was to determine which of the "4 Cs" (Carat, Cut, Color, Clarity) actually dictates the market price and to uncover hidden trends in how diamonds are valued.

## Insights: "The Diamond Paradox"
Through statistical analysis and visualization, this project reveals a fascinating market trend: **Quantity over Quality.**

1. **The Power of Carat:** There is a **0.92 correlation** between weight and price. It is the single most important predictor of value.
2. **The Color Paradox:** "Lower" grade colors (like J) often command higher median prices because they are typically found in much larger stones. Buyers willingly trade color for size.
3. **The Clarity Trade-off:** Flawless diamonds (IF) are rare but small; heavily included diamonds (I1) are common but huge. The data shows the market consistently pays a premium for "Big and Imperfect" over "Small and Perfect."
4. **The Science of Sparkle:** Total Depth % shows a **near-zero correlation** with price, suggesting that while depth is vital for brilliance, it is not a primary driver of market cost.

### Key Finding: Carat vs Price
Size is the biggest driver of price, with a massive 0.92 correlation.

### The Quality Paradox
As shown below, color and clarity don't always scale with price because people sacrifice quality for a higher carat weight.

## Visualizations Included
* **Carat vs. Price Correlation:** Visualizing exponential price growth.
* Price vs. depth
* Price vs. width

## Tech Stack
* **Language:** Python 3.13
* **Libraries:** * `Pandas` - Data manipulation
  * `Seaborn` - Statistical visualization
  * `Matplotlib` - Graph styling and layout
  * `Openpyxl` - Excel file processing

## Repository Structure
* `diamonds.xlsx`: The raw dataset.
* `analysis.py`: The Python script used to generate statistics and plots.
* `plots/`: Exported high-resolution charts for the presentation.

Database link: https://www.kaggle.com/datasets/shivam2503/diamonds
