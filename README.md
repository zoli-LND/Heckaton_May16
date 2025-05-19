# Credit Card Customer Churn Analysis
### - by Zoli Greczi



The task is to analyse the given data and determine the reasons for the clients' attrition, using the ETL method.

Looking at the dataset in Excel, it is clear that there could have been several reasons why the customers were leaving the credit card service of the bank. The aim is to identify the possible causes and trends.

## Dataset content

Information about the bank's customers, including personal information and about their transactions executed by credit cards. The entire dataset was used, all 10,127 lines.

### Hypothesis 1.

The attrition depends on the age of the customer and how long they have been with the bank.

### Hypothesis 2.

Customer age and the total transaction count affect the attrition.

### Hypothesis 3.

Relation among the Marital Status, the Months on Book and Card Category, on the Attrition Status.

## ETL pipeline

Steps before analysis:

* importing data
* data cleaning
* checking if there is N/A information

## Basic correlation test

Checking how the different data correlate to each other, but mainly to the customer churning.

* Customer Age and Months on Book
* Credit Limit,	Total Revolving Balance and 	Total Transaction Amount
* Customer Age,	Months on book and	Dependent count

## Data visualisation

Seeing the charts helps the analysis. Different charts with different contents were tried. The most useful were the following ones:

* Customer Age vs. Total Transaction Count
* Age, Transactions and Revolving Balance
* Marital Status, Months on Book and Card Category
* Customer Age Distribution by Attrition Status
* Parallel Categories: Customers by Attrition Status and Attributes

## Conclusion

1. Customers with the blue card are the most loyal ones.
2. Though the 36-60 age customers are the ones who make out most of the churning, the same age group represents the highest amount among the customers.
3. Single people are more loyal than any other group.
4. Customers with higher transaction numbers tend to be more loyal, regardless of their age.

## Ethical considerations

All financial data falls into the highly sensitive category, therefore, GDPR must be strictly followed.

## Technologies used

* Visual Studio Code
* Python
* Jupyter notebook
* ChatGPT

## Data Analysis Libraries

Pandas, Numpy, Plotly, Seaborn and Matplotlib.

## Credits

* Code Institute SLM, Visualisation chapter, where I checked the options.
* John Rearden from Code Institute, who helped me solve technical issues, such as establishing a connection between VS and GitHub.
* ChatGPT, where I got corrections and ideas for coding.
* Dataset is provided by kaggle.

## Acknowledgements

Special thanks to the tutors, Emma Lamont, Mark Briscoe, John Rearden and Niel McEwan from Code Institute, for their help and guidance.


