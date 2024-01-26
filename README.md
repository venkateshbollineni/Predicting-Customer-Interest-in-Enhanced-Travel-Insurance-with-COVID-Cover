Predicting Customer Interest in Enhanced Travel Insurance with COVID cover

A tour & travels company is offering travel insurance package to their customers. The new insurance 
package also includes covid cover. The company wants to know which customers would be interested to 
buy it based on their database history. The insurance was offered to some of the customers in 2019 and 
the given data has been extracted from the performance/sales of the package during that period. The data 
is provided from its previous customers and the goal is to build a model that can predict if 
the customer will be interested to buy the travel insurance package. Finally tested on the unseen customer data to see 
how your model performs, found that Gradient Boosting model given the best performance of Test error rate 16.9%, Accuracy 83.1% and Recall 90.8% by applying the cross validation & shrinkage. Also this model out performed Random Forest, Support Vector Machine, Logistic Regression and Linear Discrimitant Analysis models.

A: Target Variable/Label
TravelInsurance - Did the customer buy travel insurance package.

B: Predictor Variables/Features

Age - Age of the customer

Employment Type - The sector in which customer is employed

GraduateOrNot - Whether the customer is college graduate or not

AnnualIncome - The yearly income of the customer 

FamilyMembers - Number of members in customer's family

ChronicDiseases - Whether the customer suffers from any major disease 

FrequentFlyer - Derived data based on customer's history of booking air tickets on at least 4 

different instances in the last 2 years

EverTravelledAbroad - Has the customer ever travelled to a foreign country.
