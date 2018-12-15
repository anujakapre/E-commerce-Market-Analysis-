# E-commerce-Market-Analysis-
This repository consists of two folders: 
  1) Code: This contains all notebooks and dataset.
    A. Topic Extraction of Customer Reviews.ipynb:
       This notebook loads data from olist_order_reviews_dataset.csv.It discuss topic modeling of customer reviews using PLSA and LDA.
    B.a. TS_LSTM_Weekly.ipynb:
       This notebook loads raw data from olist_orders_dataset.csv, olist_order_items_dataset.csv,   olist_customers_dataset.csv,olist_products_dataset.csv and product_category_name_translation.csv to merge and prepare data for further analysis. This merged data is written to daily_data.csv which is used in 1.c. and 1.d.
    B.b. TS_Traditional_Methods.ipynb:
    This notebook loads daily_data.csv and discusses Moving average, Simple Exponential Smoothing, Holt Linear and Holt Winter models and determine which works best for our data. Also, it decomposes the time series to view seasonality, trend and level.
    B.c. LSTM_Differance.ipynb:
    This notebook loads daily_data.csv and differencing time series and walk forward validation method using LSTM.
    
   Please see Part B in order of B.a , B.b and B.c.
   
  2) Portfolio:This this contains same folder structure as code, but each technical concept is discussed before applying.
