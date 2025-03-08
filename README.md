# Intent-Clustering

Project developed for a Hackathon Event offered by Netcompany on the Bootcamp: Data Science and Business Intelligence offered by WE LEAD & Code.Hub

The goal was to create Clustering-Based Intent Identification Engine in Greek, which would cluster a demand placed by a customer. 

Developed a Clustering Algorithm using K-means. Utilized Multilingual SBERT for embeddings, UMAP for Dimensionality Reduction & Silhouette Score for finding optimal number of clusters and Evaluation.

# Setup

## Create Virtual Enviroment 
*Please ensure you have installed python 3.11*

### MacOS
In terminal:

```python3.11 -m venv venv```

```source venv/bin/activate```

```pip install -r requirements.txt```

Run notebooks in deliverable-1, deliberable-2 and the notebooks in deliverable-3 (D3_Enseble_Models.ipynb, D3_NN.ipynb, D3_knn.ipynb) in that suggested order.

### Windows 
In terminal: 

```python3.11 venv venv```

```venv\Scripts\Activate```

If security error arises try running: ```Set-ExecutionPolicy Unrestricted -Scope Process```

Then again: ```venv\Scripts\Activate```

```pip install -r requirements.txt```
