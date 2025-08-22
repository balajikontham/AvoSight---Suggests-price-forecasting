# Avocado Price Prediction Project

## Project Overview
This project focuses on analyzing avocado price trends and building regression models to predict avocado prices based on various features. The analysis is conducted using Python with popular data science libraries like pandas, numpy, matplotlib, and scikit-learn.

## Dataset
- **Source**: [Avocado Prices Dataset](https://www.kaggle.com/neuromusic/avocado-prices)
- **File**: `avocado.csv`
- **Size**: ~1.9 MB
- **Records**: 18,249
- **Features**: 13 columns

### Dataset Description
The dataset contains the following columns:
1. `Date` - The date of the observation
2. `AveragePrice` - The average price of a single avocado
3. `Total Volume` - Total number of avocados sold
4. `4046` - Total number of avocados with PLU 4046 sold
5. `4225` - Total number of avocados with PLU 4225 sold
6. `4770` - Total number of avocados with PLU 4770 sold
7. `Total Bags` - Total number of bags
8. `Small Bags` - Number of small bags
9. `Large Bags` - Number of large bags
10. `XLarge Bags` - Number of extra large bags
11. `type` - Conventional or organic
12. `year` - The year of observation
13. `region` - The city or region of the observation

## Project Files
1. `Eda.ipynb` - Jupyter notebook containing exploratory data analysis
2. `Price Regression.ipynb` - Jupyter notebook with regression model implementation
3. `Comparison-of-all-regression-models.ipynb` - Comparison of different regression models
4. `Fruti.jpg` - Image file (possibly used in the analysis)
5. `avocado.csv` - The dataset file

## Key Questions Addressed
1. Which regions have the lowest and highest avocado prices?
2. Which region has the highest avocado production?
3. What is the average avocado price each year?
4. What is the average avocado volume each year?

## Technologies Used
- Python 3.x
- pandas - Data manipulation and analysis
- numpy - Numerical operations
- matplotlib - Data visualization
- scikit-learn - Machine learning models
- seaborn - Statistical data visualization

## Getting Started
1. Clone the repository
2. Install the required packages:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open and run the Jupyter notebooks in the following order:
   - `Eda.ipynb`
   - `Price Regression.ipynb`
   - `Comparison-of-all-regression-models.ipynb`

## Key Findings
- Analysis of price trends across different regions
- Identification of seasonal patterns in avocado prices
- Comparison of conventional vs. organic avocado prices
- Performance evaluation of different regression models

## License
This project uses the Avocado Prices dataset from Kaggle. Please refer to the original dataset's license for usage terms.

## Author
[Your Name]

## Acknowledgments
- Dataset provided by Justin Kiggins on Kaggle
- Special thanks to the open-source community for the libraries used in this project
