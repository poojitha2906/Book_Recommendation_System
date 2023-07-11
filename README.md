# Book Recommender System Using Machine Learning


Recommendation systems are becoming increasingly important in today’s busy world. The purpose of a recommendation system is to search for content that would be interesting to an individual, based on their profile, browsing history, and similarities with other users. This project focuses on collaborative filtering, a type of recommendation system that utilizes user-item interactions to make personalized book recommendations.

## Types of Recommendation System:

### 1) Content-Based:

- Content-based systems use characteristic information and item attributes to make recommendations.
- Examples include platforms like Twitter and YouTube, which recommend content based on user-specific actions or similar items.
- These systems create vectors based on item features and make recommendations based on a user's past interests.

### 2) Collaborative Filtering:

- Collaborative filtering systems are based on user-item interactions.
- These systems cluster users with similar ratings or preferences and recommend items based on similar users' choices.
- They assume that if a user likes item A and another user likes both item A and item B, the first user might be interested in item B as well.
- Challenges include the computational expense of working with large user-item matrices and the tendency to recommend only popular items.

### 3) Hybrid Systems:

- Hybrid systems combine both content-based and collaborative filtering approaches to leverage the benefits of both types.
- They aim to overcome the limitations of working with a single type of information.

## About this Project:

This project is a web application built with Streamlit that recommends books based on user interests. The application utilizes collaborative filtering to generate recommendations.

## Dataset:

The dataset used for this project can be found [here](https://github.com/poojitha2906/Book_Recommendation_System/tree/main/data).

## Model Concept: Nearest Neighbors

The model.pkl file was generated using the Nearest Neighbors algorithm. The steps involved are as follows:

1. Load the data.
2. Initialize the value of k.
3. For each test data point, calculate the Euclidean distance to all training data points.
4. Sort the distances in ascending order.
5. Retrieve the top k rows from the sorted array.

## How to Run:

### 1. Clone the repository:

```bash
git clone https://github.com/poojitha2906/Book_Recommendation_System.git
```


### 2. Create a conda environment:

```bash
conda create -n books python=3.7.10 -y
```
```bash
conda activate books
```


### 3. Install the requirements:

```bash
pip install -r requirements.txt
```


### 4. Generate the models:
```bash
Run the "Books Recommender.ipynb" file to generate the models.
```


### 5. Run the application:
```bash
streamlit run app.py
```


```bash
Author: Paltasingi Poojitha
Student
Email: poojithapaltasingi2906@gmail.com

```
