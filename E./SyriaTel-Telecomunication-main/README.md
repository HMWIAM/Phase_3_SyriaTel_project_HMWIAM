# SyriaTel-Telecomunication
![Untitled design (15)](https://user-images.githubusercontent.com/52035540/183046380-595a3cfc-c5f1-4767-a59a-bd68c53e8634.png)


Photo from [canva]

# BUSINESS UNDERSTANDING¶
The dataset comes from SyriaTel, Telecommunications company, and it is related to the number of clients lost and the financial impact it has in terms of money reduction to the company. The classification goal is to predict whether a customer will ('soon') stop doing business with SyriaTel.

One of the major challenges in the business sector is predicting and analyzing customer behavior patterns. Psychological (motivation, perception, learning, beliefs, and attitudes), personal (age and life cycle stage, occupation, economic circumstances, lifestyle, personality, and self concept), social (reference groups, family, roles, and status), and cultural (religious, ethnic, and racial) factors all have an impact on consumer behavior (culture, subculture, social class system).

Machine language can work in conjunction with Big Data tools to manage unstructured and rapidly expanding data thanks to technological advancements. Consumer behavior is one of the key factors taken into account in the commercial sector.

We may now employ machine learning algorithms to build a classifier to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company and this will also give the client that is SyriaTel a deeper insight on the variables mainly apprectiated by the customers and which are not appreciated so that they can close the needed gaps and have a higher retaining capacity of the clients.

# Data Understanding
The data that I will utilize for this project comes from SyriaTel Telecom and includes information on 3,333 users.

Since 2000, Syriatel has dominated the country's mobile communications industry. By putting a strong emphasis on social responsibility and consumer happiness, the company has effectively built its name.

At Syriatel, they consider it their first duty to provide customers with a wide selection of high-quality goods and services that satisfy their needs and improve their quality of life at competitive prices.

SyriaTel has created a network of 24 service sites that spans the entire country of Syria. Over 23,000 consumers' inquiries are answered each day at the 4 call centers in Damascus, Aleppo, Lattakia, and Tartous. One of the telecom companies with the quickest growth in the region is Syriatel. There are 371 young men and women among its 3,488 employees who were chosen via the Student Support Program. Syriatel personnel are happy to serve more over 8 million consumers today and are highly skilled. To serve its customers wherever they may be, SyriaTel has a network of radio base stations that, as of the end of 2016, included 6171 sites for 2G service and 3286 sites for 3G service. SyriaTel has 199 international roaming partners in 116 nations, which is not the least of its strengths.

The target variable is the churn variable that contains True or False on the factor that Syria will loose that client soon

# Features include:

state - Client's residence. <br>
account length - How long they have had the subscription. <br>
area code - Client's area code. <br>
phone number - Client's phone number. <br>
international plan - Is the client subscribed to the international plan?(yes/no). <br>
voice mail plan - Is the client subscribed to the voice mail plan?(yes/no). <br>
number vmail messages - The number of the voicemail messages. <br>
total day minutes, calls, charge - the client's daily minutes, calls, and charges. <br>
total eve minutes, calls, charge - the client's evening minutes, calls, and charges. <br>
total night minutes, calls, charge -the client's night minutes, calls, and charges. <br>
total intl minutes, calls, charge - the client's total international minutes, calls, and charges. <br>
customer service calls - how many times the customer service line was called. <br>
churn - The response variable we will be targeting.

# Project Plan
Data Preparation - Loading Libraries - Loading data - Descriptive Exploration - Data Cleaning - Exploratory Descriptive Analysis (EDA) - Pre-processing Data

Modelling - Train test split - Baseline Model - Logistic Regression- KNN  - Decision Tree 

Conclusion

Recommendation

# Conclusion
The best-performing model was picked as the final model. The best model was the Decision Tree Model. It had the highest area under the curve.


![download (13)](https://user-images.githubusercontent.com/52035540/183044179-4db1282e-a0bc-46a4-aebf-ab313ad1edfb.png)

# Recommendation
Allowing us to look closely into the poorly performing states and Identify whether the network coverage performance and if network coverage is off, we strategize on how to work on having more boosters in the state.
We will examine whether a more favorable international charge will make the customers consider SyriaTel's international plan while they are traveling.
We would like to consider using a different vendor or temporally partnering to offer incentives and promotions when a customer seems dissatisfied may increase satisfaction and reduce churning.
Ultimately, we will implement the new features to see whether churning was reduced and calculate the cost of retaining the customers.
