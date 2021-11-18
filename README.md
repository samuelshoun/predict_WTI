# predict_WTI

This objective for this project is to demonstrate various approaches to prediction of the West Texas Intermediate (WTI) crude oil price.

The initial phase will call data from various endpoints in the US Energy Information Administration (EIA) API. Those data will be chosen
based on those factors commonly known or suspected to predominantly influence the WTI price, and engineered as features for various machine
learning architectures. This phase will attempt to predict the forward-looking 30 days' average WTI price as a sole target for the model.

A secondary phase will expand the modeling architecture and approach to model multiple targets--most likely 1) forward-looking 30 days' average WTI
price, and 2) forward-looking 90 days' average WTI price.

A third phase will build an adjacent performance tracking application which automates the prediction based on most recent available data, routinely
makes and records prediction associated with the current date, then measures the accuracy of that prediction as actual data becomes available.

A fourth phase will productionize the model and performance tracking and deploy an associated web application.

The final phase will focus on ongoing model updates, improvements, and updates/maintenance to the associated web app.
