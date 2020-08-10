# Problem Statement

A leading global leader of e-commerce has over 150 million paid subscription users. One of the many perks of the subscription is the privilege of buying products at lower prices. For an upcoming sale, the organization has decided to promote local artisans and their products, to help them through these tough times. However, slashed prices may impact local artists.

To not let discounts affect local artists, the company has decided to determine the lowest price at which a particular good can be sold. Your task is to build a predictive model using Machine Learning that helps them set up a lowest-pricing model for these products.

You have to predict the Low_Cap_Price column.




# Data ScreenShot

<img src="Screenshot 2020-08-10 at 10.48.28 AM.png">


# A Description of my Methodology


   ### Feature Engineering & Approach


1. Loan_Amount_Requested was converted to numeric by removing commas.
2. PreProcessed all of the data.
3. Filled all of the Nan Values.
4. Understanding the Data using descriptive statistics.
5. All the categorical features were Encoded to the numeric.
6. Handling the outliers in the data.
7. Created two new features.
8. I have used XGBoost which it has gave me 0.53663849301643, and Light GBM also given the same level of accuracy to me.


### Tools used


1. Python for programming.
2. sklearn and numpy libraries for methodology.
3. LightGBM and XGBoost for the final model.
4. matplotlib and seaborn was used for plotting and analyzing the data.


## Evaluation Metric
The evaluation metric for this competition is Weighted F1 Score.


# Competition Result


1. Rank: 3rd on public LB.

<img src = "Screenshot 2020-08-10 at 10.40.57 AM.png">


2. Rank: 3rd on private LB.

<img src = "Screenshot 2020-08-10 at 10.40.57 AM.png">

3. Top 1 percentile.

4. [Link to LeaderBoard](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-predict-the-lowest-price/leaderboard/predict-the-lowest-price-8-9ffabe00/)
