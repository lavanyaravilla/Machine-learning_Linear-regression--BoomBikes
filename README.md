# Machine-learning_Linear-regression--BoomBikes
Welcome to the Machine-learning Module -Linear-regression--BoomBikes wiki!

## [General Information](https://github.com/lavanyaravilla/Machine-learning_Linear-regression--BoomBikes/wiki/_new)
* Multiple linear regression is performed on the Day dataset of US boombikes for the year 2018 &2019
* The project is done as part of coursework in the Machine Learning module 1 Linear Regression.
* We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday ,month, year etc.
* The Boom bikes rental 'Day'dataset is being used.
 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

##[Conclusion](https://github.com/lavanyaravilla/Machine-learning_Linear-regression--BoomBikes/wiki/_new)
1. -The R-squared value of the train set is 83.0% whereas the test set has a value of 81.0% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.
2. - The adjusted R-squared value of the train set is 82.9% whereas the test set has a value of 79.80% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.
3. -Our developed model's mean squared error is almost  0.0092 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values<0.05 and VIF<5% were used to select the significant variables. RFE was also conducted for automated selection of variables.
4. Q-Q plot between residual distribution and normal distribution shows that residuals follow a normal distribution for all interpolations. Extraplorations show significant deviation, not affecting Linear Regression applicability.
5. The Best fitted equation 
 cnt=0.253+(0.253×yr)-(0.098×holiday)+(0.450×temp)−(0.140×windspeed)-(0.073×Jul)+(0.057×sep)-(0.112×spring)+(0.045×winter)−(0.080×Mist + Cloudy)-(0.285*light rain/snow)
6.We can conclude that the bike demands for the Boom Bikes is company is dependent on the following features
7.Final Selected Variables: ['yr', 'holiday', 'temp', 'windspeed', 'Jul', 'Sep', 'spring', 'winter', 'Mist + Cloudy', 'light rain/snow']
8. Additionally more rentals seem to be demanded on the winters,Sep and temp as compared to where the total rental decreases when their is summer ,cloudy and light rain/snow and spring,Jul,windspeed.
9.In 2019 during fall their was a peek in demand and sudden dip in until winter. In 2018 lower demand and sustained the same through out winter
10.From spring to summer their is a steady rise seen in both the years 
11.In terms of days the maximum focus was on days like Sundays, Saturday and Monday and more on holidays.
12.The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set. 

13.These interpretations help us derive meaningful insights in the bike rental market and the behaviour of the people. One of the recommendations based on this model are that there should be aggressive marketing in the summer and spring season to drive up rentals. Since the summer months also show low rental levels, a strong marketing strategy for the first 6 months of the year can assist in driving up the rental numbers. There has to be an approach required to introduce more users on days where the weather is less clear, perhaps with incentives or strategic deals. Rentals were more in 2019 than 2018 which suggests that over time more people would be exposed to this idea and there has to a strong analysis done to retain the repeat customers. 
14. Concepts such as EDA, p-value, VIF, RFE were used and model building was done using stats models library


##[Technologies Used](https://github.com/lavanyaravilla/Machine-learning_Linear-regression--BoomBikes/wiki/Home/_edit)

* pandas
* seaborn
* matplotlib
* statsmodels
* sci-kit learn
* numpy

##[Contact](https://github.com/lavanyaravilla/Machine-learning_Linear-regression--BoomBikes/wiki/Home/_edit)

Created by [@lavanyaravilla] - feel free to contact me!

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



