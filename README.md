# TestTechnique

This folder contains the Technical Test I had to realize for an interview (without mentioning the company I'm doing it for).

I do realize that I started (and did, in fact) all of the work in French, and just switched to English for this Readme. Please excuse me for that.

## The questions

Here follows the different questions that were asked:

What we want you to do is to create a python program that is able to import this dataset inside a MongoDB.

What we need is:
*   Using jupyter notebook or another similar solution, group all transactions by invoice
*   Using jupyter notebook or another similar solution, which product sold the most?
*   Using jupyter notebook or another similar solution, which customer spent the most money?
*   Using jupyter notebook or another similar solution, give as a chart showing the distribution of each product for each of the available countries (for this you can answer by providing a view or a new collection, you can provide the chart with a graphic outside the code).
*   Using jupyter notebook or another similar solution, what is the average unit price?
*   Using jupyter notebook or another similar solution, give us a chart showing the distribution of prices.
*   Using jupyter notebook or another similar solution, give us the ratio between price and quantity for each invoice.
*   Using jupyter notebook or another similar solution, map the different transactions to countries, making visible the amount of transaction each country has.
*   Using jupyter notebook or another similar solution, try to qualify the products in order to create relevant groups based on their name and visualize them in order to show which group made the most transactions.
You can use docker and ready-made docker images.
You need to push your code in a public repository (github, bitbucket etc).

## Interpretation and Realisation

I did interpret the first part (concerning MongoDB) as a need to be able to work by connecting to a MongoDB database.
To this end, I created a MongoDB on a Cloud provider (I choose [Clever Cloud](https://www.clever-cloud.com/fr/) as there is no need to register with a Credit Card)

As for notebooks I choose to work in [Google - Colab](https://colab.research.google.com) as in this way I have an environment ready to go.

I realized this Evaluation in two steps

### Step 1 : storing the dataset in a MongoDB
This is done in the notebook **Mise_en_place**

I do need to mention that I modified the CSV with Excel to get rid of the £ symbols (replacing them with the code GBP)
And then I uploaded the CSV to the Git and then uploaded it.

### Step 2 : The Assesment
This is done in the notebook **Analyse**
This analysis is a classic one, with a long first part for data cleaning, looking at the different variables etc etc
And a second part consisting of the answers to the different questions.

All in all, it was fun and I enjoyed doing it.
