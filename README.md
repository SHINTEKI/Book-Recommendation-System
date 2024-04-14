# Book-Recommendation-System
This repository showcases the final project from the DTU Computational Tools for Data Science course.

**Project Summary: Building a Book Recommendation System**

**1. Introduction**         
When seeking new books to read, individuals often rely on recommendations from friends or library searches. However, these methods may not always yield desired results due to varying interests. To address this, a recommender system is proposed. Such a system should consider user interactions with recommendations, aiming to suggest books tailored to their preferences.

**2. Dataset**         
The dataset, sourced from Kaggle, comprises information on 10,000 books and 53,424 users. Book data includes unique identifiers, ISBN, authors, language codes, average ratings, and reader counts. User data includes unique identifiers and ratings (1-5) for books read. Due to dataset size constraints, a subset of 999 users and their reading records was utilized for analysis.

**3. Design and Implementation:**
   - **Collaborative Filtering:** Employed techniques include:
     - **Item-Based Filtering:** Recommends items based on similarity calculated from user ratings.
     - **Content-Based Filtering:** Utilizes additional user and item information to recommend similar items.
     - **User-Based Filtering:** Predicts items a user might like based on similar users' ratings.
   - **A-Priori Algorithm:** Used for finding frequent item sets in large databases, particularly useful in Market-Basket Analysis. 
   
**4. Conclusion**     
The project implemented two methods for book recommendations, incorporating results from various filters. For new users, top 10 most popular books are recommended. For existing users, personalized recommendations are provided based on reading history. While the system demonstrated effectiveness in recommending books, it faces limitations, notably computational time with the A-Priori algorithm, which could be mitigated with optimization techniques like hash tables.
