# Predicting Electric Vehicle (EV) Adoption at the Census Block Group Level

This project was a collaboration between Cameron Wright, Ally Novales, Payton McSweeney, and Kunal Malhotra. We use California DMV data on EV adoption measured at the census block group level along with data from the Census Bureau to train a machine learning model. This model uses the features {income}, {educational attainment}, {race}, and {commute time} for individuals in a given geographical region to predict the target {EV adoption} (number of electric vehicles divided by total number of passenger vehicles) for that same region. A census block group is a unit of geographical measure that is smaller than a census tract but larger than a census block. Most states offer data on our features at the census block group level, but do not offer data on EV adoption at a granularity this fine. However, California is an exception: it does offer EV adoption data at the census block group level. We chose to train our model using this California data and the model can be used to predict EV adoption at the census block group level for other states. 

The full project can be found in the "Final Notebook" Jupyter notebook above. However, this notebook is very long, so I've broken it apart into 3 smaller notebooks as well: "In-depth Description", "EDA", and "Prediction". The In-depth Description gives a more comprehensive overview of the project than this README.md, the EDA notebook presents our exploratory data analysis, and the Prediction notebook presents our main prediction problem (the Final Notebook describes two other related problems as well). The data cleaning and derived variable creation can only be found in the Final Notebook (it is near the beginning). 
