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
