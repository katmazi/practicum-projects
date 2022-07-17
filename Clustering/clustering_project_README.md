# practicum
AB project description.

**Description:**
We have to analyze data from fitness center clients and identify signs of users who are most likely to fall into churn. Also we have to cluster users and write recommendations for the groups.
    
**Data description:**
    
       * **gender** — gender;
       * **Near_Location** — living or working in the area where the fitness center is located;
       * **Partner** — an employee of the club's partner company;
       * **Promo_friends** — used a promo code from a friend when paying for the first subscription;    
       * **Phone** — availability of a contact phone;
       * **Age** — age;
       * **Lifetime** — time since the first visit to the fitness center (in months)
       * **Contract_period** — duration of the current valid subscription (month, 6 months, year);
       * **Month_to_end_contract** — the period until the end of the current valid subscription (in months);
       * **Group_visits** — the fact of attending group classes;
       * **Avg_class_frequency_total** — average frequency of visits per week for the entire time since the beginning of the subscription;
       * **Avg_class_frequency_current_month** — average frequency of visits per week for the previous month;
       * **Avg_additional_charges_total** — total revenue from other fitness center services: cafes, sporting goods, beauty and massage parlors.
       * **Churn** — the fact of churn in the current month.
       
**Project Stack:**
"Matplotlib, Pandas, Python, Scikit-learn, Seaborn.

**Knowledge skills used:**
Classification, clustering, machine learning.

**Key conclusion/result of the project:** 
    We trained two models to predict user churn, using `LogisticRegression` and `RandomForestClassifier`. Having evaluated the metrics of the proportion of correct answers (_Accuracy_), accuracy (_Rrecision_) and completeness (_Recall_), we can say that the logical regression model has performed better and it is worth using it.
    We performed clustering of users by defining a matrix of feature relationships and visualizing it using a dendrogram. On the dendrogram, we will see four groups(four colors), but one of the groups remains quite extensive and in the future we try to split the data into 5 clusters using _KMeans()_.

**Project status:**
The project has been successfully completed on time.
