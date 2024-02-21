# Movie-Clustering-and-Rating-Prediction-for-Content-Organization
This project aimed to develop a system for movie clustering and rating prediction to enhance content organization and user experience. 

Technical Skills: Python, Pandas, Scikit-learn, K-Means Clustering, Hierarchical Clustering, Linear Regression, Random Forest, Principal Component Analysis (PCA)
Project Type: Academic project for Data Mining Course
Project Duration: 3 months (October 2023 - December 2023)
Project Description:

This project aimed to develop a system for movie clustering and rating prediction to enhance content organization and user experience. We addressed two key challenges in the digital entertainment landscape:

Movie Clustering: 
Traditional genre-based categorization often fails to capture nuanced relationships between movies. We implemented K-Means and Hierarchical clustering algorithms to group movies based on content attributes like genre, cast, crew, and user ratings, revealing latent connections and facilitating personalized recommendations.

Rating Prediction: 
Current models can overlook individual preferences, leading to inaccurate predictions. I employed Linear Regression, Lasso Regression, Ridge Regression, and Random Forest algorithms to predict user ratings for unrated movies, aiming to deliver more tailored content experiences.

Data and Preprocessing:
Utilized a comprehensive IMDB dataset from Kaggle, encompassing over 10 million movie entries. Data cleaning techniques addressed missing values and data inconsistencies. Feature engineering presented a significant challenge due to the large number of categorical features (over 1500 after one-hot encoding). Employed a combination of manual binning, feature creation based on domain knowledge, and PCA dimensionality reduction to create a workable data frame with 37 features.

Data:
![image](https://github.com/Saravanan-Arumugam3/Movie-Clustering-and-Rating-Prediction-for-Content-Organization/assets/128452325/84460d67-917d-4b2a-b13b-3eee5225fd0a)

Exploratory Data Analysis:
![image](https://github.com/Saravanan-Arumugam3/Movie-Clustering-and-Rating-Prediction-for-Content-Organization/assets/128452325/978d7e46-1ab1-412c-9468-7e4f19265acb)
![image](https://github.com/Saravanan-Arumugam3/Movie-Clustering-and-Rating-Prediction-for-Content-Organization/assets/128452325/0eef5112-b4ef-4143-82ed-d07fea75e9dd)

Modeling and Evaluation:
![image](https://github.com/Saravanan-Arumugam3/Movie-Clustering-and-Rating-Prediction-for-Content-Organization/assets/128452325/8f969599-9add-4ff9-986c-d2694461c7fb)

Rating Prediction: 
The data was split into training and testing sets. Employed PCA for dimensionality reduction and compared the performance of different models with and without PCA. Random Forest achieved the highest accuracy (R-squared: 0.227, RMSE: 1.234) but required longer training times compared to linear models (e.g., Linear Regression: R-squared: 0.162, RMSE: 1.285).

![image](https://github.com/Saravanan-Arumugam3/Movie-Clustering-and-Rating-Prediction-for-Content-Organization/assets/128452325/f9e9e933-856b-401e-b148-7c8539ca409c)

Movie Clustering: K-Means clustering proved more efficient than Hierarchical clustering for handling large datasets. We identified the optimal number of clusters using the elbow method and visualized the resulting clusters for analysis.

Key Insights:
Clustering Validation: 
The clustering results were cross-verified to ensure meaningful relationships between movies within each cluster, providing valuable insights into movie similarities beyond traditional genre classifications.
Rating and Vote Correlation: We disproved the hypothesis that a higher number of user ratings for a movie necessarily translates to a lower overall rating, offering valuable data for understanding user engagement and movie popularity.

Conclusion:
The project successfully implemented movie clustering and rating prediction. While linear models exhibited similar performance with limited PCA impact, Random Forest offered superior accuracy at the cost of higher computational burden. K-Means clustering emerged as the preferred choice for efficiency with large datasets.
![image](https://github.com/Saravanan-Arumugam3/Movie-Clustering-and-Rating-Prediction-for-Content-Organization/assets/128452325/5c6e6675-20c5-40c7-b877-d91f3d303562)

Future Scope:
Incorporating textual features through Natural Language Processing (NLP) can potentially improve rating prediction models.
Exploring more complex clustering models might capture intricate relationships between movies for enhanced content organization.
