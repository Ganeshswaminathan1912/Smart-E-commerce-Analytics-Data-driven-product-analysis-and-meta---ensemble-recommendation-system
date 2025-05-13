Download the dataset from the following link
https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset/data

Download all the packages by running each cell from first, run all the cells till the third cell in the <b>"Using CF (SVD, ALS) and CBF and stacking them with XGBoost to get better recommendations"</b> section and rerun from first by skipping the third cell in the <b>"Using CF (SVD, ALS) and CBF and stacking them with XGBoost to get better recommendations"</b> section.

<h1>Problems addressed:</h1>

1. Customers often struggle to find relevant products in a vast marketplace. Lack of personalized recommendations leads to missed sales opportunities.
2. Unclear price distribution trends make it difficult to set competitive discounts.
3. Inaccurate demand forecasting leads to inventory inefficiencies and lost sales.

<h1>Solution developed - Models in this python notebook file:</h1>

1. Develop a recommendation system using collaborative filtering (SVD and ALS) and stack it on XGBoost Ensemble learning (Meta Ensemble) to suggest products based on customer interactions within relevant categories – Meta ensemble recommendation system.
2. Analyze price distribution trends across different categories to optimize discount strategies for maximizing sales – K means clustering tier based discount suggestion system.
3. Predict future sales or demand for a product using available features using LSTM neural network.
