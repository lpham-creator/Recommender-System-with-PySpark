# Recommender System with PySpark ⭐
## Introduction
Product recommendation and clustering are critical components for enhancing user experience in e-commerce platforms. Grouping similar products helps businesses understand their inventory better and tailor recommendations to individual customers. This project applies clustering techniques and a personalized recommendation system to achieve these goals.

## Business Problem
The objective is to build a system that can automatically group similar products and provide personalized recommendations based on user interactions. This capability can improve product discoverability and increase customer engagement. 

## Technology I Used
- Language: Python
- Frameworks & Libraries:
- PySpark
- OpenAI API (for text embeddings)
- Scikit-Learn
- Matplotlib & Seaborn

## Approach: 
- Prepare Data
  
  ↳  Built a PySpark pipeline to clean, transform, and prep product data for analysis.

- Cluster Products Using K-Means
  
  ↳ Implemented K-means clustering with OpenAI text embeddings to group similar products.
  
  ↳ Employed dimensionality reduction techniques like PCA to visualize the clusters effectively.

- Recommender System
  
  ↳ Developed a personalized recommendation system that identifies and suggests relevant products based on recent user interactions with the platform
  
(I have blocked out my API Key for security.)

  ↳ The system suggests product based on recent interactions.

## Key Learnings
- Utilizing Spark using Python code
- Learning about Spark's parallel programming and RDD, which is fault-tolerance
- Building a recommendation system from scratch

## Key Challenges

- Managing large-scale text data efficiently.
- Optimizing the clustering model to find the right number of clusters.
- Handling API rate limits during the text embedding process.

## Conclusion 
- The project successfully implemented a product clustering and recommendation system using PySpark, OpenAI embeddings, and K-means clustering. This system can help businesses better understand their product landscape and improve customer experience with personalized suggestions.


