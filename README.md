# kings_county_housing_price_program
Predicting prices of houses in Kings County, WA using contextual data

![alt text](https://www.langan.com/wp-content/uploads/2020/01/Seattle-996x554-1.jpg)

The housing market is incredibly lucrative and difficult to really nail down the value of a house. So much of it is rather subjective. The preference of brick over concrete, or the extra living room space in lieu of an extra bedroom. Houses are built around the people they are meant to house, so they are finicky when it comes to adjusting so many different tastes and needs. But as much as all of the former is true there are factors that allow houses to be priced on an open market. Factors such as the zip code, number of bedrooms, and whether they have waterfront access all help to add or subtract value from the property.

![alt text](https://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1537549832/Image2_ajaeo8.png)

In this project a sample set of data was provided to mess around with and get a handle for the details at play for Kings County, Washington. Things such as waterfront views and understanding lot size was important as the land covers west to the waters of Elliot Bay to the hills and open traces of Redmond Watershed Perserve in the east. But most things close to home were closer to home. Number of bedrooms, bathrooms, whether there is a basement, and living in a zip code with quality schools are some of the many number of features that help contextually develop value for the house.

![alt text](https://algotrading101.com/learn/wp-content/uploads/2020/06/training-validation-test-data-set.png)

In this project the goal was to move through the thicket of data to reach a clearing of understanding about not only what variables were pertinent but had the appropriate weight attached to them in their relation to the price of the house. Using methods of effective data analysis a scope was developed that helped to better understand the shape of the data, especially where the outliers were and how to best reign them in. Statistical methods and graphs also helped to better illustrate the trends between those variables and price or the lack thereof. 

![alt text](https://i.morioh.com/2020/04/14/57ff5c724e7c.jpg)

But it was in utilizing the power of python finding even more nuanced relationships were possible. A single variable such as waterfront would only explain so much, and the quality of the views from a house would too, but when passed together against price the way they interacted together became clear. Using things such as dummy variables and polynomial featuring allowed the subtle to become more prominent. The whole processes of picking which features, while daunting still with python, was made easier with the slate of various methods to process all of their interactions and return the best ones. Things like using recursive test selection made moving through hundreds of columns in tens of thousands of rows relatively easy. 

![alt text](https://miro.medium.com/max/1358/1*WCyPUnYwFajY-loYht2D8Q.png)

Using scalar methods allowed the data to be better fit to linear regression trends for training. Training the train and test datasets to run in things such as mean squared error, mean absolute error, and, most importantly, the root mean squared error. Doing this allowed better understanding of how effective the data was fit to the test, and if it was too great, the error would be problematic, and if the values were too similar there would be issues of overfitting for the test sample, leaving it vulnerable to being ineffective against a greater variance of samples. Though no real examples of deep parabolic relationships popped up, using logarithmic methods was also an option to better understand their trends along a linear regression. 

![alt text](https://cdn.geekwire.com/wp-content/uploads/2017/05/seattleskyline-630x473.jpg)

This project was able to show the ways that python can be used to extrapolate big pictures from many smaller facets. The fact that after the model was created, trained, tested, and optimized, it was able to pull similar contextual details about other houses, sans price, and make a estimate that was within the bounds of reason.
