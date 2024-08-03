## Sales Forecasting Models

### Exploratory data analysis and Charts

<img src="https://i.imgur.com/DH1fl1U.png" alt="visitortypespiechart" width="400" height="400">
<img src="https://i.imgur.com/8lVPBg2.png" alt="revenuebyVisitortype" width="900" height="500">
<img src="https://i.imgur.com/ga0T5CL.png" alt="revenuebyweeddaytype" width="600" height="400">
<img src="https://i.imgur.com/TzzVh9o.png" alt="traffictype" width="900" height="500">

## Models Training and Tests
scikit-learn documentation
- https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html

### Model Performance Metrics Resume

|Metric|SVM_Model_1|SVM_Model_2|SVM_Model_3|SVM_Model_4|
|---|---|---|---|---|
|**Kernel**|Linear|Linear with Standardized Data|RBF Standardized|Polynomial Standardized|
|**Precision**|0.52|0.48|0.52|0.4|
|**Recall**|0.722|0.857|0.867|0.769|
|**F1 Score**|0.605|0.615|0.650|0.526|
|**Accuracy**|0.943|0.950|0.953|0.940|
|**AUC**|0.751|0.736|0.756|0.695|

- _Precision_: Measures how many positive predictions were correct. Higher precision means fewer false positives.
- _Recall_: Measures how many actual positives were correctly identified. Higher recall means fewer false negatives.
- _F1 Score_: Combines precision and recall into a single metric, balancing the two. Higher F1 Score indicates a good balance between precision and recall.
- _Accuracy_: The overall correctness of the model, showing the proportion of correctly predicted instances out of all instances.
- _AUC (Area Under the ROC Curve)_: Indicates the model’s ability to distinguish between classes. Higher AUC means better performance in class separation.

## dataset Information

The [dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset) consists of feature vectors belonging to 12,330 sessions. 
The dataset was formed so that each session
would belong to a different user in a 1-year period to avoid
any tendency to a specific campaign, special day, user
profile, or period. 

### Variables

- **Administrative**: Number of pages visited by the visitor about account management.
- **Administrative_Duration**: Total amount of time spent on administrative pages.
- **Informational**: Number of pages visited by the visitor about site information.
- **Informational_Duration**: Total amount of time spent on informational pages.
- **ProductRelated**: Number of pages visited by the visitor about products.
- **ProductRelated_Duration**: Total amount of time spent on product-related pages.
- **BounceRates**: The percentage of visitors who enter the site and then leave ("bounce") rather than continuing to view other pages within the same site.
- **ExitRates**: The percentage of visitors who exit the site after viewing a specific page.
- **PageValues**: The average value of the pages visited by the visitor before completing an e-commerce transaction.
- **SpecialDay**: The closeness of the site visiting time to a special day (e.g., Mother's Day, Valentine's Day), represented by values closer to 1 indicating closeness to a special day.
- **Month**: The month in which the visit occurred, represented as a string (e.g., "Jan", "Feb").
- **OperatingSystems**: The operating system used by the visitor during the session.
- **Browser**: The browser used by the visitor during the session.
- **Region**: The geographical region of the visitor.
- **TrafficType**: The source through which the visitor accessed the site, such as a direct link, search engine, or ad.
- **VisitorType**: Categorizes visitors into types, such as "Returning" or "New".
- **Weekend**: A binary variable indicating whether the visit happened on a weekend.
- **Revenue**: A binary variable indicating whether the session resulted in a transaction (revenue).
	
### Documentação oficial do scikit-learn



- 
