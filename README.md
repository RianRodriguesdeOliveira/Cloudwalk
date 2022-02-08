# About the Project
This project was made as a part of an interview process for the position of Risk Analyst in Cloudwalk Inc, in the topic of chargeback fraud. It involves answering questions related to the acquiring market and analysing the transaction data sent to discover trends and identify key insights regarding the chargeback fraud.
The main report is given as a pdf file, named "CloudwalkRiskAnalystTest.pdf". The notebook and data are in their respective folders.

# Tools used
Python 3 (Pandas, Numpy, Matplotlib and Seaborn libraries)

# Conclusions
The data shows us that the majority of chargeback requests are not malicious in nature. We cannot identify any noticeable trends in chargeback requests by looking at time of day or day of month: the chargebacks increase because the amount of transactions increase.
The majority of cardholders have a chargeback rate of <=10%. However, there is a visible group of users with chargeback rates surpassing 50%, some even reaching 100%. The same behaviour is seen with merchants, the majority of which have really low chargeback rates, but a small group can be identified, having over 50% chargeback rates.
As such, while we would benefit from protecting ourselves from criminal and friendly fraud, it would be more beneficial to dedicate resources to reducing the charback rates of those clients who request them sparingly, for that is the greater mass.



