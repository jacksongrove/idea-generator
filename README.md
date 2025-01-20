# Predictive Idea Generation Through Clustering Narrow Word Embeddings

## Project Overview
This project explores a novel approach for idea generation using a clustering-based methods to represent and predict ideas, rather than individual words. Traditional generative models like LLMs predict text word-by-word, but this project focuses on generating ideas by clustering words and phrases into semantically meaningful groups. An n-gram model is used to generate the tokens while k-means clustering is used to define idea-level representation.

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