# Company Forecast App

Company Forecast is a Free, open source C++ program made as a scientific research. It's main purpose is to use web provided data and a mathematic model to predict wether a stock is going up or down, based solely on news that were broadcasted referring to the company, as described below:

## How does it Work?

This refers to a evaluation of the stock current state, given its closing price, its current price (if the market is open), and wether it is higher or lower then it was. This serves as a base for the system to run a preliminary scan, establishing the base parameters for what is a news of "good influence" and a news of "bad influence" in a stock price. For this, we're using what we call PCA (Principal Component Analysis). This is a mathematical thechnique used to establish correlation between possibly correlated variables. We can establish a relatioship between any kind of parameters. We must only remember that this does not mean that such correlation will necessarily exist. For example: establishing a correlation between certain words appearing in news veichles (such as "up" or "down") and the price of the stock (increase or decrease). Actually, this is one of our main goals!

### PCA explained as fast as humanly possible

Imagine you have a set of words describing two colors: red and blue. Let red be a value, e. g. -1. Let blue also be represented as a value, e. g. 1. These are two opposits in our color spectrum/dataset. Our goal now is to find out, amongst our words, wich of them are related to blue and wich of them is related to red. To do this, we assign a value to each word. The closest this value is to -1, the more the word is related to "red". On the other hand, the closest this value is to 1, the more the word is related to "blue". This is as simple as it get. 

To determine the value of a word, it is necessary to establish the context of a word, and wether it appears closer to "blue" or "red" in this context. This is achieved through some rough math, witch will not be explained here, though if you're interested in finding out more about the matter, StatQuest has some AMAZING content about PCA [here](https://www.youtube.com/watch?v=Lsue2gEM9D0).


# Licence

Please note that this software is currently maintained as it is under MIT License, therefore any further use of it must contain the necessary Copyrights. This is subject to changes without previous warnings. If a further version of this software is changed to another License, previous versions will not be affected.

# Dependencies

* Gumbo lib 0.10.1

