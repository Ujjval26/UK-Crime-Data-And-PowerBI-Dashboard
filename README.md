# UK Crime Activity Forecasting

### Overview

This project analyzes and forecasts crime activity in the UK using **open-access data from the UK Police Open Data Portal**. The objective is to identify **temporal, categorical, and spatial crime patterns** and to classify crime activity into **High Crime** and **Low Crime** periods using a **Logistic Regression model**. An interactive **Power BI dashboard** is used to visualize trends and geographic hotspots.



### Data

* Source: UK Police Open Data Portal ([https://data.police.uk](https://data.police.uk))
* Location: Central London
* Period: January 2024 – March 2024
* Features:

  * Crime category
  * Month
  * Crime outcome
  * Latitude and longitude


### Methodology

* Crime data aggregated by **month and category**
* Mean crime count used as a threshold to define:

  * High Crime (above mean)
  * Low Crime (below mean)
* Categorical features encoded using **Label Encoding**
* **Logistic Regression** applied for binary classification
* Data split into **75% training** and **25% testing**


### Dashboard Insights

* Theft-related crimes are the most common reported incidents
* Crime activity peaks in **February** and declines in **March**
* A large proportion of cases remain under investigation
* Crime hotspots are concentrated in **central London**


### Tools Used

* Power BI (dashboard and visualization)
* Python (Logistic Regression modeling)
* UK Police Open Data API
* GitHub (version control)

### Conclusion

This project demonstrates how open crime data and interpretable machine learning models can support **data-driven policing**. The combination of predictive modeling and visualization provides actionable insights for crime analysis and resource planning.




