# Predictive Idea Generation Through Clustering Narrow Word Embeddings

## Project Overview
Through this project we explore a novel approach for LLM-powered idea generation by altering the representation of latent space vectors, using clustering-based methods to represent and predict idea-based tokens directly, rather than individual word-based tokens. 

Traditional language models focus on predicting the next token in a sequence—with tokens typically defined as words or partial words—but this project instead defines tokens as _ideas_ to generate ideas directly. In this project, we have defined _ideas_ as sets of words and phrases (word sequences) that collectively represent similar concepts—allowing for direct representation of abstract and complex concepts in the model's latent space. These ideas are created by clustering words and phrases into semantically meaningful groups. K-means clustering and Word2Vec embeddings are used to create idea-level latent representation vectors while an n-gram model is used to generate the resulting tokens and evaluate the methods.

## Inspiration & Intuition

What language do babies think in? In other words, what is the underlying, natural structure of human thought before we learn formal language? Looking at patterns of human languages, there are many different ways of structuring and describing ideas but one similarity is they all are designed to be communicated sequentially. And for most, inner thought exists sequentially in the form of events and objects as well (albeit in a much more abstract space). At it's core, language simply exists to represent natural human thought. When designing language models, especially for use cases like novel idea generation, research and creative insight, it may feel silly to train them with  tokens that are just a derivative of human thought, instead of modelling them off of humans directly. In this project, instead of building language models that think how humans communicate, we instead create one that thinks how we imagine humans might think. Through this, we can generate concepts and ideas directly.

## How to Run
NOTE: The dataset is too large for GitHub but following the steps found within `idea_generator.ipynb` will guide you through all necessary setup.

### Step 1: Install Dependencies
Install the following if not already installed:

```
pip install pandas numpy tqdm gensim matplotlib scikit-learn plotly kaggle
```

### Step 2: Run the Jupyter Notebook
Open and execute the `idea_generator.ipynb` notebook cell-by-cell:
Further instructions are included in the notebook to guide you through setup and purpose of each code block.
