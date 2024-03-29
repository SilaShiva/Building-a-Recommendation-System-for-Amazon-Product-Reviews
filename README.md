# Building-a-Recommendation-System-for-Amazon-Product-Reviews
Welcome to the GitHub repository dedicated to our project on building a robust recommendation system using labeled data from Amazon reviews. The primary objective of this project is to leverage customer ratings to provide meaningful product recommendations for online consumers.

**Key Features:**

Data Collection: The dataset comprises labeled Amazon reviews, providing a rich source of information for training and evaluating recommendation models. Click [here](https://drive.google.com/file/d/1KXNThV7-7XBR_VpH6E7Bf4bqAPmx63hD/view?usp=sharing).

**Recommendation Systems:**

Rank-Based System: Utilizes a rank-based approach to recommend products based on their overall popularity and ratings.
Collaborative Filtering (using Surprise library): Implements both user-user and item-item collaborative filtering techniques to enhance recommendation accuracy.
Model-Based Collaborative Filtering - Matrix Factorization: Utilizes matrix factorization to capture latent features in the data and enhance personalized recommendations.

**Evaluation Metrics:**
- Precision@k: It is the fraction of recommended items that are relevant in top k predictions. The value of k is the number of recommendations to be provided to the user. One can choose a variable number of recommendations to be given to a unique user.

+ Recall@k: It is the fraction of relevant items that are recommended to the user in top k predictions.
  
* F1-score@k:It is the harmonic mean of Precision@k and Recall@k. When precision@k and recall@k both seem to be important then it is useful to use this metric because it is representative of both of them.

These metrics provide a comprehensive assessment of the recommendation system's performance, ensuring a balance between accuracy and coverage.

**Project Structure:**

The repository is organized with clear directories for data preprocessing, model development, and evaluation metrics implementation.
Detailed documentation is available for each component, facilitating easy navigation and understanding of the codebase.
Feel free to explore the code, provide feedback, or contribute to further improving the recommendation system. Together, let's enhance the online shopping experience for consumers through effective product recommendations.
