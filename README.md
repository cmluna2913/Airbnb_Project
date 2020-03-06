<img
     src='images/airbnblogo.jpg' alt='Airbnb Logo' width='250' height='250'>
</img>

# Airbnb and You
There are many features that go into an Airbnb listing that ultimately affect 
its price. My goal is to explore some data on Airbnb listings to let me explore 
the specific features that significantly affect the price. To do this, I will 
perform some quick exploratory data analysis and also apply an ordinary least 
squares regression test that will give me a better insight into Airbnb prices.

<img
     src='images/Kaggle_logo.png' alt='Kaggle Logo' width='250' height='250'>
</img> 
# The Data
The data we are working with was obtained from Kaggle. It includes information 
on the property type, the bedroom type, the price in a log transformation, the
number of accommodates, and much more. I will do my best incorporate as much
data as I can in the best way possible. We will have to do some cleaning
as well as try to create new features from other columns. We will also
encode some of the features listed in order to make our OLS regression model.


# Questions
1. What accommodate size is the most common?
2. Using each city's downtown as the our reference, what is the average distance
   each accommodate size must travel to downtown?
3. What is the average price per person, per accommodate size?
#### After running an OLS Model
4. Which features will serve as our baseline?
5. What is our R<sup>2</sup>? How does it compare to our train data? What is
   the R<sup>2</sup> of our final model?
5. Which features are not significant?
6. How are the remaining features correlated to our price?

# What's next?
If possible, I would love to explore for other Airbnb data that provides more
data on each of the listings, especially numerical data that let's me have
more information on the size of the listing. I also want to narrow down on which
ammenities impact price and matter to the customers. Arranging the data by city 
and providing the corresponding models would be great to have a much better
comparison(Chicago will be the first one I explore).