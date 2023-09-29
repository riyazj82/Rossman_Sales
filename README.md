# Rossman_Sales
Rossmann operates over 3,000 drug stores in 7 European countries. The primary challenge at hand is to accurately forecast the daily sales of these stores for the upcoming six weeks. To address this challenge, the project leverages historical sales data, comprising 1,017,209 rows and 18 columns, to develop predictive models that can provide valuable insights into future sales trends and patterns.¶

Field Descriptions:
Id: Unique identifier for each (Store, Date) pair in the test set.
Store: Unique store identifier.
Sales: Daily turnover (the prediction target).
Customers: Number of customers on a given day.
Open: Store open status (0 = closed, 1 = open).
StateHoliday: Type of state holiday (a = public holiday, b = Easter, c = Christmas, 0 = None).
SchoolHoliday: Indicates if the store was affected by the closure of public schools.
StoreType: Store model categorization (a, b, c, d).
Assortment: Assortment level (a = basic, b = extra, c = extended).
CompetitionDistance: Distance to the nearest competitor store (in meters).
CompetitionOpenSince[Month/Year]: Approximate opening month and year of the nearest competitor.
Promo: Store running a promo on that day (0 = no, 1 = yes).
Promo2: Store participating in consecutive promotions (0 = no, 1 = yes).
Promo2Since[Year/Week]: Year and calendar week when Promo2 started.
PromoInterval: Months when Promo2 is active (e.g., "Feb,May,Aug,Nov").
