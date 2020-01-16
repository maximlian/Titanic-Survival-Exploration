# Titanic-Survival-Exploration
Repository for Udacity Data Scientist Nanodegree Project - Create a Data Science Blogpost


### Outline
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [References](#references)

## Installation <a name="installation"></a>

For users of the Anaconda distribution of Python, the only package necessary to run all code is [SHAP](https://github.com/slundberg/shap). SHAP can be installed via:

<pre>
pip install shap
<i>or</i>
conda install -c conda-forge shap
</pre>

## Project Motivation <a name="motivation"></a>

For this Project I was interested in using Shapley values to interprete the results of a Gradient Boosting Classifier. Real data from passengers aboard the Titanic will be analyzed with the purpose of finding answers to the following questions:
- Which individual characteristics are most associated with surviving/not surviving?
- How do these explanatory features relate to surviving/not surviving?
- Are there any interactions between the explanatory features, and if so, what do they look like?

## File Descriptions <a name="files"></a>

- *Titanic.ipynb* - Jupyter Notebook containing all the code work - Dataset Understanding, Data Preparation, Data Modelling, Results - along with comments and interpretations. 
- *Titanic.csv* - Dataset used for analysis


## Results <a name="results"></a>

Findings can be found in the *Titanic.ipynb* Notebook or this [Blogpost](https://medium.com/@maximlian/titanic-survival-exploration-a75742129d44)

## References  <a name="references"></a>
- [Titanic Dataset](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/problem12.html)
- Lecture material from Udacity Data Scientist Nanodegree
- [Original paper](http://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions.pdf) on SHAP
- SHAP [GitHub Repository](https://github.com/slundberg/shap) 
- Shapley values and SHAP explained in [Interpretable Machine Learning Book](https://christophm.github.io/interpretable-ml-book/shapley.html)
