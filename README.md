# Explainable-AI-Mini-Project

## Project Overview
A heterogeneous GNN model for user movie link prediction with ~0.95 AUC, enhanced by Captum to provide per–link interpretability through influential nodes and relations.

### Features
- Builds and trains a GNN on the MovieLens graph  
- Generates clear explanations for each predicted link using Captum  
- Offers transparent, trustworthy recommendations

## Execution
1. Run the Files independently on Google Colab
2. Remove the comments of the first cell on both files to make sure appropriate dependencies are installed

## Data Description
When installed manually, the project skips the dataset download step. Instead, it relies on the MovieLens ratings data modeled as a heterogeneous graph that brings together user profiles, movie metadata, and genre information alongside the rating edges.  In total, the dataset spans 610 distinct users and a 20 column feature set for each movie, covering genre flags such as Action, Adventure, Animation, Children, Comedy, Crime, Documentary, Drama, Sci-Fi, and Thriller.

| Data  | Graphs  |
|-------|--------|
| Number of nodes | 10,334  |  
| Number of edges | 100,836  |  
