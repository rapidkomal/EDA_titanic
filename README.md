# EDA on Titanic and Twitter Datasets
This is a Python script that performs exploratory data analysis (EDA) on the Titanic and Twitter datasets, and then uses the scikit-learn library to make predictions based on the data. The script uses the MechanicalSoup library to scrape Twitter data, and the pandas, matplotlib, and seaborn libraries for data visualization.

### MechanicalSoup

A Python library for automating interaction with websites. MechanicalSoup automatically stores and sends cookies, follows redirects, and can follow links and submit forms. It doesn't do JavaScript. MechanicalSoup was created by M Hickford, who was a fond user of the Mechanize library.

### scikit-learn

Scikit-learn (Sklearn) is the most useful and robust library for machine learning in Python. It provides a selection of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction via a consistence interface in Python. This library, which is largely written in Python, is built upon NumPy, SciPy and Matplotlib.

### matplotlib

Matplotlib is an amazing visualization library in Python for 2D plots of arrays. Matplotlib is a multi-platform data visualization library built on NumPy arrays and designed to work with the broader SciPy stack. It was introduced by John Hunter in the year 2002. One of the greatest benefits of visualization is that it allows us visual access to huge amounts of data in easily digestible visuals. Matplotlib consists of several plots like line, bar, scatter, histogram etc.

### Prerequisites
Before getting started, you should have the following tools installed on your machine:

Python 3.x
pandas
matplotlib
seaborn
scikit-learn
MechanicalSoup

### Installation
```pip install pandas matplotlib seaborn scikit-learn MechanicalSoup```

## Usage
### Titanic Dataset
The Titanic dataset contains information about the passengers on the Titanic, including their survival status. The script reads the dataset from titanic.csv, performs EDA on the data, and then uses scikit-learn to make predictions about whether a passenger survived based on their age, sex, and class.

The EDA includes visualizations of the following:

*The distribution of ages among passengers.
*The survival rate among passengers of different classes.
*The survival rate among passengers of different sexes.


### Twitter Dataset
The Twitter dataset contains recent tweets of any topic. in those tweets finding those username, comments of corresponded tweets and peform EDA and make prediction 

The EDA includes visualizations of the following:

The distribution of tweet lengths.
The distribution of positive and negative tweets.
The most common words in positive and negative tweets.
