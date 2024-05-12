## Data Analysis of Commodity Market

### Overview
This project provides an in-depth analysis of the commodity market, focusing on various commodities such as natural gas, crude oil, precious metals like gold and silver, and cryptocurrencies like Bitcoin and Ethereum. Utilizing data from 2019 to 2024, the project aims to uncover underlying patterns, test economic hypotheses, and predict future price movements using advanced statistical techniques and machine learning models.

### Objectives
- **Data Cleaning**: To prepare the raw dataset for analysis by handling missing values, correcting data formats, and removing unnecessary data.
- **Exploratory Data Analysis (EDA)**: To explore and visualize the data to understand trends, patterns, and outliers.
- **Hypothesis Testing**: To test theories about the relationships between different commodities and economic indicators.
- **Predictive Modeling**: To build machine learning models that can predict price movements of commodities based on historical data.

### Methodologies
1. **Data Preprocessing**
   - **Cleaning**: Removed non-numeric characters, filled missing values for key commodities, and standardized date formats.
   - **Feature Selection**: Identified relevant features that influence commodity prices, such as 'european_avg' for natural gas prices.
   
2. **Exploratory Data Analysis**
   - Utilized matplotlib and seaborn for visualizing data distributions, price volatility, and correlations between commodities.
   - Created boxplots to analyze price distributions and identify outliers in commodity prices.

3. **Statistical Analysis**
   - Conducted hypothesis testing using the Pearson correlation coefficient to evaluate the relationship between different commodities and economic factors.
   - Analyzed volatility and price trends to provide insights into market behavior.

4. **Machine Learning**
   - Developed a K-Nearest Neighbors (KNN) model and a Decision Tree model to forecast future prices.
   - Evaluated models using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to assess accuracy.
   - Performed feature importance analysis to understand the drivers behind the model predictions.

### Tools Used
- **Pandas & NumPy**: For data manipulation and numerical calculations.
- **Scikit-learn**: For building and evaluating machine learning models.
- **Matplotlib & Seaborn**: For creating static, interactive, and animated visualizations.

### Results
- The analysis highlighted the significant volatility in cryptocurrency prices compared to more stable commodities like natural gas and crude oil.
- The machine learning models demonstrated potential in predicting commodity prices, with the KNN model slightly outperforming the Decision Tree model in terms of prediction accuracy.
