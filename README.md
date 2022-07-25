## **<h1 align="justify"> Cryptocurrencies**
  	
---
## Overview of the project: 
<p align="justify">In this project, we use Python to build and evaluate several machine learning models to predict credit risk.
We adopted the following procedure:
. <p>
	
---

<p align="justify">This project consists of four technical analysis deliverables. <p>

- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results
	

### Resources
- Data Source: crypto_data.csv ( Retrived from CryptoCompare : https://min-api.cryptocompare.com/data/all/coinlist   , 
- Software: Python 3.7 and accompanying Anaconda package, Conda 4.8.4, Jupyter Notebook

## Random Over Sampler model:
	
<p align="center">
  <img width="600" src=https://github.com/sharifbhuiyan/Cryptocurrencies/blob/main/Resources/Elbow_Curve.png
</p>  
	

- Calculation of the confusion matrix.
	
<p align="center">
  <img width="200" src=https://github.com/sharifbhuiyan/Cryptocurrencies/blob/main/Resources/3D-Scatter.png
</p>  
		
- Imbalanced classification report

<p align="center">	
  <img width="600" src=https://github.com/sharifbhuiyan/Cryptocurrencies/blob/main/Resources/Tradable_crypto.png
</p>  
	

- The balanced accuracy score is 62%. The high_risk precision is about 1% only with 60% sensitivity which makes a F1 of 2% only. Low_risk precision is almost 100% with a sensitivity of 68%.

	
	
	
## SMOTE model:
	
<p align="center">
  <img width="400" src=https://github.com/sharifbhuiyan/Cryptocurrencies/blob/main/Resources/scatter%20plot.png
</p>  
	
- Calculation of the confusion matrix.


</p>



- The balanced accuracy score is 93%. The high_risk precision is about 7% only with 91% sensitivity which makes a F1 of 14% only. Low_risk precision is almost 100% with a sensitivity of 94%.
