# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Web APIs & NLP
<br>

# Misread - Classification Modeling
Modeling the fakest news on the internet. Enjoy, with a smile :)

## Objective

* Gather posts and comments from subreddits [r/TheOnion](https://www.reddit.com/r/TheOnion/) and [r/worldnews](https://www.reddit.com/r/worldnews/) using [PushShift](https://github.com/pushshift/api) API.
* Use machine learning algorithms to classify new posts as either "Fake News" (TheOnion) or "Real News" (worldnews).\
An assumption of "real news" is being made of r/worldnews. The subreddits community rules can be found [here](https://www.reddit.com/r/worldnews/).
* This project is intended to be light hearted. It is an exploration into Natural Language Processing. The goal was to remain politically **unbiased.** If you would like to argue about politics, well, there is a [subreddit](https://www.reddit.com/r/PoliticalDebate/) for that.

## Problem Statement
* Can we successfully classify the difference between two subreddits utilizing machine learning and Natural Language Processing techniques?

## Target Audience
* Reddit's cross discipline directors.

<br>

<br>

# Notebooks

## Data Collection
### [Gather Data via PushShift API](https://git.generalassemb.ly/genewoodstock/submissions/blob/master/projects/project-3-master/0_scraper.ipynb)

 * PushShift uptimes can be spotty occasionally, so if the scraper doesn't work, try again later.


<br> 

## Classification Models
<p>

### [Exploratory Data Analysis & Data Cleaning](https://git.generalassemb.ly/genewoodstock/submissions/blob/master/projects/project-3-master/1_data_cleaning.ipynb)

* Data collected from API is cleaned and explored.
* Comment and Post data merged and exported to .csv. Data is saved [here](https://git.generalassemb.ly/genewoodstock/submissions/blob/master/projects/project-3-master/datasets/clean.csv).
* Raw comment & post data is indexed [here](https://git.generalassemb.ly/genewoodstock/submissions/tree/master/projects/project-3-master/datasets).

<br>

### [Proof of Modeling Concept](https://git.generalassemb.ly/genewoodstock/submissions/blob/master/projects/project-3-master/2_word_vectorize.ipynb)

* Basic Naive Bayes model with minimal tuning.

<br>

### [Model Exploration](https://git.generalassemb.ly/genewoodstock/submissions/blob/master/projects/project-3-master/3_model_exploration.ipynb)
Exploration of various modeling techniques cosisting of the following list are explored in this workbook. Initial insights explored and discussed.
* Naive Bayes
* Logistic Regression
* K Nearest Neighbors
* Decision Tree
* Random Forest
* Extra Trees
* Ensemble

<br>

### [Vectorizer Comparison](https://git.generalassemb.ly/genewoodstock/submissions/blob/master/projects/project-3-master/4_tfidf.ipynb)
Two common corpus vectorizers are [count vectorization](https://en.wikipedia.org/wiki/Bag-of-words_model) and [term frequency](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) with inverse document frequency.\
The results of tuning an ensemble model utilizing the algorithms explored in the above section are shown in this workbook.\
The final couple lines deploy a function for making predictions on a string of your choice. Feel free to experiment and make some predictions of your own.


<br>

# Presentation and beyond...
A slide deck containing a more narrative driven version of the project can be found [here](https://git.generalassemb.ly/genewoodstock/submissions/blob/master/projects/project-3-master/Misread.pdf).
<p>
On the final page of the slide deck is a list of future steps this project could evolve into with time, effort, and energy. I encourage you to check them out. Feedback is always welcome.

<br>

---
If you've made it this far, I thank you for your time and hope you enjoy this exploration into Natural Language Processing half as much as I enjoyed putting it together.

Gene Woodstock, Data Scientist