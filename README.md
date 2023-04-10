# NYC-Taxi-Trip-Duration-Prediction

## Project Summary

Let's say you are have reached to an airport after completing a business trip and you want to reach home as soon as possible. Now you have opened you phone and start looking for Cabs which could take you to the home. While searching for cabs you have noticed, the application is providing you a very vital information, which is the duration, you require to reach home. You felt that how an application can calculate the duration of an journey even before its completion ,whether this duration is just an assumption or have been calculated after evaluating a rigorous algorithm.
So, the answer to this question lies inside this beautiful project.The project revolves around the prediction of regression values after evaluating some independent variables. In addition with it, project performs a EDA on the NYC dataset to find out hidden secrets for the business.

## Problem Statement
NYC taxi Dataset consisted with some important independent features which explains everything about journey of a taxi. The study revolves around the passenger , its booking time, trip duration, pick up location and drop location.We need to take help from the new advanced technologies of Machine Learnig and provide the best user experience to customers by providing the most accurate trip duration they would require to reach there destination.

Question of EDA.

1.What are the number of rides taken by each vendor?

2.What is the count for network failure and loose connection?

3.Which vendor have failed in connecting with servers maximum times?

4.What is the variation in distance travelled by the passengers.

5.What is the maximum distance travelled by taxies per day in all the six months.?

6.What are the number of taxi trips per day?

7.What is the on an average distance travelled by the taxies per day.

8.Find out on which hour of day taxies are bussiest.

9.Find out which day of the week is busiest

## Drop_off Locations by NYC Taxies.

![image](https://user-images.githubusercontent.com/122529968/230848901-bb9000e5-2722-4e16-90ea-465c9ddb8162.png)


## Project Insights

For calculting the various insights and values mostly I used the groupby funtion of pandas,describe funtion to gain a basic overview of the outliers present in the dataset and some other basic functionalities.

I found out that the vendor first require to work upon some new technologies and improve its user experience.

I have found out that there are some trips which require more than a day to complete.

there are some trips with more than 500 km travel distance. It means taxies of NYC have been used for short journeys, medium distance journeys and even for long journeys.

We have found out that at 6PM the taxies are bussiest.These peak time again accumulated on week ends.

Again one astonishing fact which we have found in our EDA is, the taxies on an average travel the same distance daily. When I find the mean for all the distance travelled by taxies, the output was either 3 or 4.

## Conclusion

The first basic conclusion is that, the DF which was treated with outliers and transformed exponentially has performed excellent on every model. Even though in the initial models it was half of its journey to the optimum accuracy but later on with more advanced algorithms it outperforms with some basic hyper parameters.

So when we deploy our XGBM to NYC taxi businesses we can expect a high level accuracy while predicting the most expected and most correct required trip duration.

So here XGBM shows 97% accuracy on training and testing datasets.
The distance travelled by the taxies and the respective pickup and drop off time are the most important features with maximum contribution.
On Decision tree regressor and random forest regressor the model was not optimally fitted and was lacking in the desired amount of accuracy.
