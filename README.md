# LITERACY TRENDS IN INDIA: ANALYSIS AND FORECASTING
## Overview
This project presents a comprehensive analysis of historical literacy trends in India and forecasts future literacy rates using time series modeling. The ARIMA (AutoRegressive Integrated Moving Average) model, specifically ARIMA(1,2,2), was implemented to project future values. The model achieved a high predictive accuracy of over 98% and forecasts India’s literacy rate to reach approximately 83.54% by 2033.

## Project Structure
### code/
#### analysis.ipynb: 
This notebook explores <b>literacy rate</b> trends in India over several decades, identifies temporal patterns in <b>age-specific fertility rates</b>, and highlights persistent <b>rural-urban</b> disparities and <b>gender-based</b> gaps—key challenges that continue to impact educational development in the country.

#### forecast.ipynb
This notebook applies the ARIMA model for time series forecasting, following the <b>Box-Jenkins methodology</b> (1976), which consists of four main stages:

<br>1. Data Preparation: Assessing stationarity using the Augmented Dickey-Fuller (ADF) test.

<br>2. Model Identification & Estimation: Selecting appropriate parameters for the ARIMA model.

<br>3. Diagnostic Checking: Validating the model through residual analysis.

<br>4. Forecasting: Using the finalized model to predict future literacy rates.

### dataset:
The dataset includes literacy rate statistics obtained from secondary sources, primarily the <b>Census of India</b>. To maintain consistency with governmental data, the analysis focuses on post-independence literacy figures from 1951 to 2011. As per the latest report by the <b>National Statistical Office (NSO)</b>, India’s average literacy rate stood at 77.7% in 2021.

### toi-article/
The ARIMA(1,2,2) model predicted India’s literacy rate for 2026 to be 80.9%. This project was submitted on 27th May 2025, and a Times of India article published on 3rd June 2025 reported a matching literacy rate of 80.9% based on a Periodic Labour Force Survey (PLFS)—validating the model’s real-world relevance.
