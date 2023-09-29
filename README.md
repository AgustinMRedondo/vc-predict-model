# vc-predict-model
Final Project for IronHack DATA23. LRM and AI models to predict if an investment in an startup will be successful

API:

In the API notebook you will find the connection to CrunchBase. Due to data description only very limited features can be access. Therefore the data for training the model and making predictions will come from big_startup_secsees_dataset.csv located in the data_cleaning folder.

Data set:

The sata set it's composed of 53.000 companies (useful), with a target column (status). We can use this column to check the companies that have closed, that have IPO or been acquired or that are still just operating. Our training data will be the one of the companies we know about there success (IPO/Acquired/Closed) and we will make predictions on the operating ones.

Data cleaning:

This cleaning cleans Nan and makes assumptions on the data, leaving it ready to split into training and test. NLP is used to cluster the industries into 10 clusters.

Models:

The first notebook in the folder, it's a model comparison of supervised models, where Logistic Reggression model is chosen.   

Then, the complete developement and predictions of the LRM and also a notebook with two Neural Network algorithms one with Adam another one with SGD.

Streamlit:

To make it user friendly, the models where deployed in streamlit localhost. With that code you can run the model and make custom predictions.

Tableau:

Interactive visuals about the dataset, with predictions and clusters


SQL:
All data one processed it saved in a local SQL, which is also used in Tableau. If you want to replicate this project you will have to replicate the SQL or change it for CSV. files (saving and uoloading it to each notebook). Tableau wont work (I leave here a link for Tableau server useful for 14 days from the 29/09/2023)

Disclaimer: All the research and insights generated are NOT recommended for implementing in real life.