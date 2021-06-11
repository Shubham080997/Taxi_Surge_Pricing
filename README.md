# Taxi_Surge_Pricing

The cab platforms adjust their prices using a
specific algorithm which is real time and
dynamic known as “Surge Pricing” or
“Dynamic Pricing”. We were provided with
three such already classified labels in our
data set.
Our experiment can help understand what
could be the reason for the classification of
such labels by feature selection, data
analysis and prediction with machine
learning algorithms taking into account
previous trends to determine the correct
classification.

**Problem Statement**

Data provided by an Indian cab aggregator
service Sigma Cabs. Their customers can
download their app on smartphones and
book a cab from anywhere in the cities they
operate in. They, in turn, search for cabs
from various service providers and provide
the best option to their clients across
available options. They have been in
operation for a little less than a year now.
During this period, they have captured surge
pricing types from the service providers.The main objective is to build a predictive
model, which could help them in predicting
the surge pricing type proactively. This
would in turn help them in matching the
right cabs with the right customers quickly
and efficiently.
● Trip_ID: ID for TRIP

● Trip_Distance: The distance for the
trip requested by the customer

● TypeofCab: Category of the cab
requested by the customer

● CustomerSinceMonths: Customer
using cab services since n months; 0
month means the current month

● LifeStyleIndex: Proprietary index
created by Sigma Cabs showing the
lifestyle of the customer based on
their behaviour

● ConfidenceLifeStyle_Index:
Category showing confidence on the
index mentioned above

● Customer_Rating: Average of
lifetime ratings of the customer till
date CancellationLast1Month:
Number of trips cancelled by the
customer in last 1 month


● Var1, Var2 and Var3: Continuous
variables masked by the company.
Can be used for modelling purposes


● Gender: Gender of the customer


● SurgePricingType: Target (can be of
3 types) - DV

**Reasons for surge pricing**

The reasons for surge pricing are:
● normal peak-hours

● bad weather conditions (rain, snow,
etc)

● events (concerts, movie-premiere)

● traffic conditions

● unseen emergencies and so on.

**How Surge pricing works**


● Demand for rides increases
There are times when so many people are
requesting rides that there aren’t enough cars
on the road to help take them all. Bad
weather, rush hour, and special events, for
instance, may cause unusually large
numbers of people to want to request a
ride with Sigma all at the same time.


● Prices go up
In these cases of very high demand, prices
may increase to help ensure that those who
need a ride can get one. This system is
called surge pricing, and it lets the app
continue to be a reliable choice.


● Riders pay more or wait
Whenever rates are raised due to surge
pricing, the app lets riders know. Some
riders will choose to pay, while some will
choose to wait a few minutes to see if the
rates go back down.
