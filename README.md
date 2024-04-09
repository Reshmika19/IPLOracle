# IPLOracle
IPLWINPredictor : A predictive model and web app for forecasting IPL match outcomes, providing users with real-time insights into team win probabilities based on match parameters.


IPL Oracle

IPL Oracle is a predictive model and web application designed to forecast the outcomes of Indian Premier League (IPL) cricket matches. Leveraging machine learning techniques and historical IPL data, IPL Oracle provides users with insights into the potential winner of a match based on various factors such as team composition, venue, target score, current score, overs completed, and wickets lost.

Features:

Predicts the probability of each team winning a match based on live match data.
Allows users to select the batting and bowling teams, along with the host city and match parameters such as target score, current score, overs completed, and wickets lost.
Displays the predicted outcome along with the probability of each team winning the match.
Technologies Used:

Python: For data preprocessing, model training, and web application development.
Streamlit: For building the user interface of the web application.
Scikit-learn: For implementing machine learning models.
Pandas and NumPy: For data manipulation and analysis.
Dataset:
The dataset used for training the model consists of historical IPL match data, including details such as match id, season, city, date, teams, toss winner, toss decision, result, and more. The dataset can be accessed here.

Code Structure:

ipl.ipynb: Jupyter Notebook containing the code for data loading, preprocessing, EDA, feature engineering, model training, and evaluation.
app.py: Streamlit web application for interacting with the IPL Oracle model and making predictions.

Conclusion:
IPL Oracle provides cricket enthusiasts with a valuable tool for making informed predictions about IPL matches. By leveraging machine learning and historical data, IPL Oracle aims to enhance the excitement and engagement of IPL fans worldwide.
