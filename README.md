Predicting Energy Behaviour of Prosumers in Estonia - A Project on Minimizing Imbalance Costs by Enefit

The objective of this project is to develop a prediction model for prosumer energy patterns in Estonia to minimize future imbalance costs.

The project was divided into three parts :
1. Data Wrangling : Compiling the dataset with features such as county name, consumption pattern, production pattern, installed capacity of solar panel by merging client, train and county name json files.

2. Exploratory Data Analysis : Analysing the data through visualization in Seaborn, Matplotlib and ArcGIS
- Total Production and Consumption Pattern Over the years
- Installed Capacity, Production and Consumption per County
- Installed Capacity, Production and Consumption per Year
- Consumption and Energy Prices over 2021 - 2023
- Mean Solar Radiation, Mean Installed Capacity and Mean Production

3. Feature Engineering and Machine Learning : Predicting the production and consumption per hour of a day in the future using historical data. 
Steps as follows 
- Separating consumption and production pattern for prediction
- Separating the train set, test set and validation set
- Getting Hyperparameter
- Training consumption and production for different kind of prosumers using LightGBM, CatBoost and Ensembled Model of the two.
4. Evaluation
- Mean Absolute Error (MAE) for  calculation

Data 
Access to our raw data through link below : https://wageningenur4.sharepoint.com/:f:/r/sites/course239381/Gedeelde%20documenten/Group%204/Data?csf=1&web=1&e=s6zTE2

Folders
In the repository named "main": Each folder containing our deliverables in each step and named under the process taken
"Graph and Figures" contains our deliverables of visualization    
The code files, data files, and model files for the machine learning section can be found at this link.: https://drive.google.com/drive/folders/1PQZAo9CL5MsiguuBFTxHoRHoiDbpg5aY?usp=drive_link

This project is part of our Data Science for Smart Environments GRS35306 course.
Group 4
- Changling Wang (1123556)
- Michelle Natali M (1336029)
- Qilanxin Kang (1365029)
- Sudarshan Ethirajah (1311638)
- Yalin Chi (1332449)
