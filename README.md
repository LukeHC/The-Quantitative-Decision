# Who am I

Someone who loves to make data-informed decisions 

[LinkedIn](https://www.linkedin.com/in/lukehcliu/)

# Machine Learning with Python

## [Survival Prediction (link to Kaggle)](https://www.kaggle.com/skywalkerhc/titanic/machine-learning-for-survival-prediction-2)
From data wrangling, exploration to feature engineering, the simple logistic regression model predicts who can survive in the Titanic tragedy.

![](https://github.com/LukeHC/The-Quantitative-Decision/raw/master/Kaggle/Coefficient%20Est.png)

# SQL

## [GIVEasia Transaction Data Wrangling](https://github.com/LukeHC/The-Quantitative-Decision/tree/master/GIVEasia-transaction-data-wrangling)
I wrote SQL to simply transaction data cleaning process.
```
    (SELECT 
        cleaned_data.Email,
            Donor_Name AS 'Name',
            MIN(Donation_Date) AS 'First Donation to Charity',
            MAX(Donation_Date) AS 'Last_Charity',
            COUNT(cleaned_data.Email) AS 'Number of Donations to Charity',
            SUM(Net_Amount) AS 'SUM_Charity',
            FORMAT(AVG(Net_Amount), 2) AS 'AVG_Charity'
    FROM
        cleaned_data
    WHERE
        cleaned_data.Email <> ' '
            AND charity <> 'GIVEasia Website'
            AND charity <> 'GIVE.asia'
    GROUP BY cleaned_data.Email) AS T_Donation_to_Charities
```

# Strategic Planning

From partnership assessment, new technology evaluation to market entry strategy.

![](https://github.com/LukeHC/The-Quantitative-Decision/raw/master/Strategic%20Planning/1.png)


![](https://github.com/LukeHC/The-Quantitative-Decision/raw/master/Strategic%20Planning/2.png)

# Data Visualizations
 
# Funnel Optimization

# Operations



