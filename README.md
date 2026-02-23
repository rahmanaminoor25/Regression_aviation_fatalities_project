# Regression project
## Predicting the number of fatalities from airplane crashes and fatalities

This project has its aims at predicting the number of fatalities of an aircraft accident by fitting a regression model. The dataset can be accessed from the github repository, or from the kaggle: https://www.kaggle.com/datasets/thedevastator/airplane-crashes-and-fatalities





Data dictionary:

- index: the index of the row
- Date: the date of the incident
- Time: the time of the incident
- Location: the location of the incident
- Operator: the operator of the aircraft
- Flight #: the flight number of the aircraft
- Route: the route of the aircraft
- Type: the type of aircraft
- Registration: the registration of the aircraft
- cn/In: the construction number/serial number of the aircraft
- Aboard: the number of people on board the aircraft
- Fatalities: the number of fatalities in the incident
- Ground: the number of people on the ground killed in the incident
- Summary: a summary of the incident



Models used:

- Lasso regression
- SVR (radial kernel)
- Linear SVR
- Gradient boosted regression


Note to reader: This project was set by Rockborne's advanced data training programme. For this project, the dataset from kaggle was split by the course supervisor- to data and unseen data. With the unseen data, we submit our predictions using our model, which is then evaluated by the course supervisor.
