# Coffee Bean Quality Prediction Analysis

This is a Jupyter Notebook project that analyzes and predicts coffee bean quality. Each coffee bean has been evaluated and given taste scores in eleven different categories. Ten of them are different specific aspects of the coffee, such as aroma and acidity, all rated out of ten. The last category is the total taste score, which is the sum of all the other category scores, and is out of 100. The objective is to use the Naive Bayes classifier to classify a cup of coffee as either good or bad, where "good" is defined as an above average total taste score. The last part of this project tests linear regression on the dataset and builds a graph of which countries have the best coffee. 

## Usage and Requirements

To view the project, no requirements are necessary and you can view the notebook [here](http://htmlpreview.github.io/?https://github.com/nickolaiposs/coffeebean-quality-prediction/blob/main/coffee_quality_prediction.html). To run the code, the [Anaconda](https://www.anaconda.com/) environment is recommended, and the .ipynb file can be opened with JupyterLab or Visual Studio Code with the Jupyter extension. 

## Credits

The dataset from this notebook comes from the [Coffee Quality Institute](https://database.coffeeinstitute.org/), scraped by [jldbc on GitHub](https://github.com/jldbc/coffee-quality-database), and [merged and shared on Kaggle by Diego Volpatto](https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi). Volpatto's merged Kaggle dataset is the one in this repository. 