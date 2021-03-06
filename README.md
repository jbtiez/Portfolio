Welcome to my Data Science Portfolio!  

## Gender, Politics & Twitter

- As part of my master's program at UVA, we created a pipeline to capture Tweets about the 2020 democratic primary, and then analyzed whether there were differences in how Twitter talked about  male vs. female candidates. 
- Among the methods we utilized were basic word frequency analysis, sentiment analysis using [VADER](https://github.com/cjhutto/vaderSentiment), and word embeddings (w/ Word2Vec). This project culiminated in a published academic paper ([click here for abstract](https://ieeexplore.ieee.org/document/9106584)). 
- As part of the project, I created an interactive visual in D3 that shows the relative word usages when Twitter discussed male and female candidates (see [here](https://jbtiez.github.io/Demos.io/)).

## Text Analytics of Cookbooks
- In this project, we analyzed differences in cookbooks from mid-1800s through early 1900s (Whole project [here](https://github.com/jbtiez/Cookbooks_ETA))
- We utilized  [TF-IDF](https://github.com/jbtiez/Cookbooks_ETA/blob/master/TFIDF.ipynb) and [PCA](https://github.com/brigittehogan/Cookbook-Analytics/blob/master/PCA.ipynb), which showed how terms of measurement for recipes (e.g., cup, tablespoon, teaspoon) became far more common as time passed. 
- We implemented [topics models](https://github.com/jbtiez/Cookbooks_ETA/blob/master/LDA.ipynb) to show that dessert and fruit receipes became more prominent in later years. Topic models also supported our earlier findings regarding terms of measurement. 
- We used [word embeddings](https://github.com/jbtiez/Cookbooks_ETA/blob/master/Word_Embeddings.ipynb) to explore changes in how measurement terms were used over time, showing that in earlier cookbooks, words like "sprinkle" and "season" were used in similar contexts to spices, while in later cookbooks, "teaspoon" and "tablespoon" were closely associated with spices. 
- We explored applying several standard sentiment analysis methods to the domain of cookbooks (see [here](https://github.com/jbtiez/Cookbooks_ETA/blob/master/Sentiment%20Analysis.ipynb), and showed they are poorly suited to the domain of cookbooks

