# Movie Recommendation System

### Business Objectives
Recommender systems help users navigate vast catalogs of items by narrowing down choices to match user preferences. In entertainment and online retail, these systems personalize content, creating dynamic, targeted experiences. Major platforms like Netflix and Amazon rely heavily on these recommendation engines.

**Business Objective**:  
- Develop a **Collaborative Filtering-based Movie Recommendation System**.
- **Predict** user ratings for movies not yet rated.
- **Minimize prediction error** between actual and predicted ratings using **RMSE** and **MAPE**.

---

### Data Collection
The dataset, sourced from [GroupLens](https://grouplens.org/datasets/movielens/20m/), contains user ratings and tags from MovieLens, a movie recommendation platform. The data includes 20,000,263 ratings and 465,564 tag applications for 27,278 movies, rated by 138,493 users between January 9, 1995, and March 31, 2015.

**Files used**:
- **`ratings.csv`**: Contains user ratings for movies.
- **`movies.csv`**: Contains movie information.

---

### Modelling Approach
1. **Load and Explore Data**: Begin by loading the `ratings.csv` and `movies.csv` files and examining the data structure and contents.
   
2. **Create Similarity Matrices**:
   - **User-Item Matrix**: Map each user’s ratings for different movies.
   - **User-User and Movie-Movie Similarity Matrices**: Calculate similarity between users and between movies.

3. **Model Training**:
   - **Collaborative Filtering**: Use matrix factorization and similarity-based approaches to predict ratings for unseen movies.
   - Evaluate models using **RMSE** and **MAPE** metrics to measure accuracy.

---

### Results
**User-User and Movie-Movie Similarity Results**  
- Example outputs for test cases here.

**Feature Importance**  
- Displays feature weights impacting rating predictions.

**Model Comparison**  
- Results for various models and approaches tested for recommendation accuracy.

**Collaborative Filtering Example**  
- Sample movie recommendation generated based on user similarity.

---

### Conclusions
- **Key Learnings**: Gained insights into the importance of recommendation systems and explored matrix factorization to enhance recommendations.
- **Model Summary**: Built a system incorporating user-user similarity, movie-movie similarity, and matrix factorization.
- **Evaluation**: The model predicts user movie ratings based on past behaviors, with **RMSE** and **MAPE** as performance metrics.
- **Future Work**: Additional methods in machine learning and deep learning can further improve prediction accuracy and recommendation quality.

---

*For more details, refer to the code in the `.ipynb` file.*
