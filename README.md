# Customer lifetime value analysis for a contract and non-contract based business

Unfortunately, many businesses calculate CLV using historical customer behavior without accounting for variation in that behavior. For example, a customer who buys several expensive items at once might be assigned a higher value than a customer who consistently buys moderately priced items — even if he or she never buys from the business again after the initial purchase. 

There are two classes of business contexts that influence how a data scientist should go about modeling customer lifetime value: 

1. Whether purchases are discrete or continuous.

2. Whether the setting is contractual or non-contractual. 

Discrete purchases occur at fixed periods or frequencies, whereas continuous purchases occur at any time. <strong>Whether purchases are contractual or not determines whether customer churn is visible or must be inferred;</strong> This example is for non-contractual, but you can hook up <strong>AutoML for Customer Churn</strong> project, [here](https://github.com/joehoeller/AutoML-with-Genetic-Algorthims-to-Accurately-Predict-Customer-Churn), for a contractual business.

CLV models can provide lots of actionable information, like the probability that a customer will churn or a population-level prediction of how many orders customers will be placing at a given time. These insights are critical for data-driven retention measures and sales forecasts, respectively.

Additional reading:

* [Modelling customer lifetime value in contractual settings](https://pdfs.semanticscholar.org/0d02/c0faa1ada84a1a67a5dc134826b453394966.pdf)

* ["What's a Customer Worth?" (non-contractual setting), by Susan Li](https://towardsdatascience.com/whats-a-customer-worth-8daf183f8a4f)

* [Gamma Gamma Model](http://kpei.me/blog/?p=921)


## How to set up the project
#### TODO: Turn this into a Docker container

```
Pandas:           $ sudo pip install pandas
numpy:            $ sudo pip install numpy
scipy:            $ sudo pip install scipy
matplotlib: 
                  $ sudo apt-get install libfreetype6-dev libpng-dev
                  $ sudo pip install matplotlib 
seaborn:          $ sudo pip install seaborn
jupyter notebook: $ sudo apt-get -y install ipython ipython-notebook
                  $ sudo -H pip install jupyter
lifetimes:        $ sudo pip install lifetimes

```

## Dataset

* Data set can be download from this [link](http://archive.ics.uci.edu/ml/datasets/online+retail)
* There is no need to download dataset because it is already downloaded. 
* Path of dataset is `./input_data/`

## Usage
Run the code given in ipython notebook `customer_lifetime_value.ipynb`

## Credit
Boilerplate code credits for this code go to [Susan Li](https://github.com/susanli2016), I just made it more accessible to a contractual lifetime value analysis which can be coupled with my [AutoML for Customer Churn](https://github.com/joehoeller/AutoML-with-Genetic-Algorthims-to-Accurately-Predict-Customer-Churn) project.

If Machine Learning for Customer Lifetime Value for your customers is important to you or your business, and you need expert skills to get the job done, please [get in touch](https://www.linkedin.com/in/computer-vision-engineer/).


