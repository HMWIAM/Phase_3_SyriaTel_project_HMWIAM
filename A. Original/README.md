# SyriaTel Customer Churn Analysis

Author: Henry Mativo Wamunyu



### Company Overview 

Established in January 2000, SyriaTel has emerged as the premier telecommunications company in the region. With its headquarters situated in Damascus, Syria, the company has garnered a strong reputation for providing reliable and innovative communication services. SyriaTel has continuously demonstrated its commitment to delivering cutting-edge technology and seamless connectivity to its vast customer base.

## Business Understanding

In the business sector, accurately predicting and analyzing customer behavior patterns is a significant challenge. Various factors, including psychological, personal, social, and cultural aspects, influence consumer behavior such as motivation, perception, learning, beliefs, attitudes, age, occupation, lifestyle, and cultural background. Understanding these factors is crucial for businesses to effectively cater to customer needs and preferences.

As a data scientist, I have been hired to develop a robust model that can effectively predict which customers are likely to discontinue their services with SyriaTel.


### Data Understanding

SyriaTel has provided me with that includes information about their customers. The dataset contains information of 33,333 of SyriaTel customers and the features are as follows:

* `state` - Client's residence.
* `account length` - How long they have had the subscription.
* `area code` - Client's area code.
* `phone number` - Client's phone number.
* `international plan` - Is the client subscribed to the international plan?(yes/no).
* `voice mail plan` - Is the client subscribed to the voice mail plan?(yes/no).
* `number vmail messages` - The number of the voicemail messages.
* `total day minutes, calls, charge` - the client's daily minutes, calls, and charges.
* `total eve minutes, calls, charge` - the client's evening minutes, calls, and charges.
* `total night minutes, calls, charge` -the client's night minutes, calls, and charges.
* `total intl minutes, calls, charge` - the client's tital international minutes, calls, and charges.
* `customer service calls` - how many times the customer service line was called.
* `churn` - The response variable we will be targeting.


### Modelling 
Various models are created using logistic regression, decision tree and random forest algorithms. Hyperparameter tuning is applied to ldecision tree and random forest algorithms.<br>
A pipeline is used to prevent data leakage. Data is scaled in the pipeline.<br>
The image below shows a summary of the models and their performance.
 
![Alt Text](A. Original/Models.png)
             
### Evaluation
 
#### 1. **Accuracy:** 

Accuracy represents the proportion of correctly classified instances out of the total number of instances. Higher accuracy values indicate better performance.
 
In this case, the scaled random forest, the tuned random forest and the tunned bagged tree achieve the highest accuracy scores of above 0.97, indicating that they have the highest overall classification accuracy among the models.

#### 2. **F1-Score:** 

The F1-score is the harmonic mean of precision and recall. It provides a balanced measure between precision (ability to correctly identify positive instances) and recall (ability to correctly identify all positive instances). Similar to accuracy, higher F1-scores indicate better performance. 

In this case, the tuned bagged tree, the resampled bagged tree and the scaled random forest achieve the highest f1 scores of above 0.94, indicating that they have the highest overall classification f1 among the models.

#### 3. **Precision:** 

Precision represents the proportion of true positive predictions out of all positive predictions. It measures the model's ability to avoid false positives. Higher precision values indicate fewer false positives. 

In this case, the scaled random forest, the tuned random forest and tuned bagged tree have the highest precision scores, above 0.97.

#### 4. **Recall:**

Recall (also known as sensitivity or true positive rate) represents the proportion of true positive predictions out of all actual positive instances. It measures the model's ability to identify positive instances correctly. Higher recall values indicate fewer false negatives.

Tuned bagged tree, resampled bagged tree and resampled decision tree achieve the highest recall scores, above 0.93.

## Business Recommendations:

* Improve international plan to attract customers.

* For greater satisfaction, revamp its helpdesk(customer service).

* Accept a deal at discount with enough cumulative day moments.

## Next Step

Ensure smooth functioning of the XGBT design(completed model).

To understand how parameter influences the performance, browse for it properly

To facilitate a better understanding and familarity of each parameter exploited in grid search.

Analyze the influence of additional hyperparameter.

To evaluate performance of the model and to alter parameters, use a scaled f1 score that emphasizes recall more accuracy



