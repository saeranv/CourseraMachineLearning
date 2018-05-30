### Introduction

- ML definition:
- Tom Mitchell (1998):
- A computer program is said to learn from experience E wrt task T and some performance measure P if its performance on T, as measured by P, improves with experience E

- T task
- E experience
- P performance measure

- 2 Algorithms that we can generally clasify ML as:
- supervised learning
- unsupervised learning


### Supervised learning

- we are given a dataset where "right answers" given
- there is a relationship between input and output (function)
- classified into regression, classification problems:

  - regression prob:
    - can predict continuous valued output (price)
    - map input to a continuous function
    - i.e predict price of house based on size

  - classification prob:
    - can predict predict discrete valued output
    - map inputs to discrete categories
    - given patient with tumour predict wheter tumour is malignant or benign

### Unsupervised Learning

- allows us to approach problem without having an idea of what the results should look like
- it derives the structure based from data where we don't know effect of Variables
- the structure is derived by clustering data according to the relationships among the variables
- there is no feedback based on prediction results because no prior training set of relationship clusters exist

- 2 types:
- clustering: take a collection of 1 million different genes and find ways of cluster them into groups that are related by different variables i.e. lifespan, location, gender etc

- nonclustering: find structure in chaotic environment, identify individual voices in a mesh of sounds i.e cocktail party
