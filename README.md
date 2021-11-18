# predict_WTI

TL;DR version:
Get data from EIA API and try different approaches to predicting the US oil price. Later will deploy a cool web app.


Long Version:

This objective for this project is to demonstrate various approaches to prediction of the West Texas Intermediate (WTI) crude oil spot 
price. This price is widely relied upon in the US and North America to indicate rising or falling costs of petroleum-derived products 
such as gasoline, operations activity and investments associated with oil exploration and production, and to gauge the impact of these
on the broader economy.
https://en.wikipedia.org/wiki/West_Texas_Intermediate

The initial phase will call data from various endpoints in the US Energy Information Administration (EIA) API.
https://www.eia.gov/opendata/
Those data will be chosen based on supply and demand related factors commonly known or believed to substantially influence the WTI price,
and will be engineered as features for various machine learning architectures. This phase will attempt to predict the forward-looking 30 
days' average WTI price as a sole target for the model.

A second phase will expand the modeling architecture and approach to accomodate multiple targets--most likely 
  1) forward-looking 30 days' average WTI price, and 
  2) forward-looking 90 days' average WTI price.

A third phase will build an adjacent performance tracking application which automates the prediction based on most recent available data,
routinely makes and records a prediction associated with the current date, then measures the accuracy of that prediction as actual data 
becomes available.

A fourth phase will productionize the model and performance tracking, and build+deploy an associated web application.

The final phase will focus on ongoing model updates, improvements, and updates/maintenance to the associated web app.

High five that you read this far. Seriously cool!
