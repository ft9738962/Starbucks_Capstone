# 1. Motivation & Target
It is a machine learning project for optimizing the efficiency of Starbucks offer reward app by using data.

The data contains profile of customers, portfolio of offers, and customer's transcripts (including transaction and offer status).

Process of the prject would be:
1. Understand the dataset
2. Clean the dataset
3. Build the machine learning models that can provide best prediction
4. Discuss further improvement

The target is to create a model that can sort the offer priority for one customer based on demographic information and a model that can give us the most likely prediction of the average transaction amount and percentage of the consuption incentived by offer.

P.S. This project is my capstone project for [Udacity Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)

# 2. File Description
- data(folder):
data from Starbucks for the project

- clf_results(folder):
store cross-validation process data of classification models

- clf_best_mdls(folder):
store classification models

- rgr_results(folder):
store cross-validation process data of regression models

- rgr_best_mdls(folder):
store regression models

- fig(folder):
figure files

- Starbucks_Capstone_notebook.ipynb:
jupyter notebook of the project

- Starbucks_Capstone_notebook.html:
html version of the project

- profile_trans_1.csv: dataset in process

# 3. Main chapter of the project
1. Walk through and Clean dataset
2. Training model
3. Conclusion

# 4. Summary of the project
The classification model has an average 0.77 F1 score on each offer type. An function is built on these classifiers to provide the customed number of most appropriate offer suggestion to either customer with id or new customer.

A series of models has been built up to select the best appropriate offer to customer, to estimate the customer's average transaction amount and to predict whether the customer consumes only affected by offer or not.

Here's a sample of the combined function of both models with input of a fictional female, aged 40, income 53000 and ask the result to include only the top 3 offer.

<img src="https://github.com/ft9738962/Starbucks_Capstone/blob/master/fig/pred.png", width="500", height="400"/>

# 5. How to Interact with the Project

Any improvement suggestion or idea is appreciated

The pushed code should follow PEP-8 style

# 6. Licensing

BSD 3-clause

# 6. Authors
[Max Qiu](https://github.com/ft9738962)
