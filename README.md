# Predictive Analytics for California Real Estate

### An Integrated Approach Using Regression and Clustering Techniques



---

## Project Overview

This project explores predictive analytics on the California real estate market using comprehensive regression and clustering methodologies. Utilizing a dataset of over 35,000 residential listings from early 2021, the analysis aims to identify key determinants of housing prices and segment distinct real estate market regions.

---

## Objectives

* Identify the primary factors influencing real estate prices in California.
* Predict home prices accurately using advanced machine learning regression models.
* Segment real estate markets geographically and economically using clustering techniques.

---

## Dataset

The dataset includes 35,389 residential listings with detailed attributes such as:

* Geographic coordinates (latitude, longitude)
* Price
* Property size (square footage)
* Number of bedrooms and bathrooms
* Property age
* Listing type (auction, bank-owned, etc.)

Data preprocessing involved meticulous cleaning, handling of missing values, outlier detection, feature engineering, and standardization.

---

## Methodology

### Data Preprocessing

* Missing value imputation
* Outlier removal using Interquartile Range (IQR)
* Feature engineering (age, price per square foot)
* Standardization

### Regression Techniques

The following models were implemented and rigorously evaluated:

* **Decision Tree Regression**
* **Random Forest Regression**
* **Gradient Boosting Regression**
* **Ridge Regression (with Cross-Validation)**
* **ElasticNet Regression (with Cross-Validation)**

**Evaluation Metrics:** MSE, RMSE, MAE, R²

### Clustering Techniques

* **KMeans Clustering**: Identified economically meaningful geographic clusters.
* **DBSCAN Clustering**: Detected naturally occurring clusters based on density.

---

## Results

### Regression Analysis

| Model                 | MSE      | RMSE     | MAE      | R²       |
| --------------------- | -------- | -------- | -------- | -------- |
| Decision Tree         | 0.04     | 0.19     | 0.15     | 0.92     |
| **Random Forest**     | **0.00** | **0.03** | **0.01** | **1.00** |
| **Gradient Boosting** | **0.00** | **0.04** | **0.02** | **1.00** |
| Ridge CV              | 0.12     | 0.35     | 0.22     | 0.70     |
| ElasticNet CV         | 0.35     | 0.59     | 0.43     | 0.17     |

### Clustering Analysis

The clustering analysis successfully segmented the market into distinct economic and geographic clusters, as visualized in the detailed clustering maps provided in the results.

---

## Visualizations

Several high-quality visual outputs illustrate the depth of analysis, including:

* Histograms and density plots for data distributions.
* Geographic-economic clustering visualizations.
* Kernel Density Estimation plots for detailed price distributions.
* Correlation analyses and detailed exploration of pricing by city, bedrooms, and bathrooms.

See the project repository images folder for detailed visualizations.

---

## Applications and Impact

This analysis provides critical insights beneficial to stakeholders including home buyers, sellers, investors, and urban planners. The combination of predictive accuracy (regression) and market segmentation (clustering) facilitates informed decision-making and strategic planning.

---

## Technologies

* **Python**
* **Pandas, NumPy**
* **Scikit-learn**
* **Matplotlib, Seaborn**

---

## Future Scope

Future enhancements could involve:

* Incorporating broader economic data.
* Advanced geographic information systems (GIS) analyses.
* Exploring deep learning approaches.

---

## Contributors

* Dev Shah - https://github.com/ShahDev007
* Roshini Padmanabha - https://github.com/roshinip21

---

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
