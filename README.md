# Zomato-Restaurant-Clustering-And-Sentiment-Analysis
![image](https://user-images.githubusercontent.com/95522639/232321277-17a8930a-9ee2-44c8-9d85-a652568afe53.png)


This project aims to cluster Zomato restaurants into different segments using clustering algorithms such as K Means Clustering and Agglomerative Hierarchical Clustering. It also involves sentiment analysis to classify the sentiments of the reviewers based on their reviews and ratings using machine learning algorithms such as Random Forest, K-Nearest Neighbours, Logistic Regression, XGBoost, Multinomial Naive Bayes, and Light Gradient Boosting Machines.

## Dataset
The dataset contains information from 105 Zomato Restaurants in Hyderabad. We were provided with two datasets - Zomato Restaurants Name and Zomato Restaurants Reviews. We used different imputers to deal with the missing values and manipulated necessary columns to make it analysis-ready. We performed EDA and feature engineering for both the models separately. We used Textual Data PreProcessing Using NLP for the Sentiment Analysis Model.

## Clustering Model
We used K Means and Agglomerative Hierarchical Clustering Algorithms to cluster the Zomato Restaurants. We have come up with 4 clusters of Restaurants based on the features provided in the dataset.

## Sentiment Analysis Model
We built a separate Sentiment Analysis model to classify the Sentiments as Positive and Negative. We used Logistic Regression as the model to predict the sentiments of the reviewers based on their reviews and ratings. We also used Word Cloud to visualize the most frequent words in both Positive and Negative sentiments reviews. We compared the evaluation metrics of different models and chose the best one.

## Business Recommendations
Based on the EDA, we have come up with some business recommendations, which are as follows:

* The median cost per dining of the restaurants is between Rs.500 - Rs.1000.
* Restaurants with a 2.5 rating are the most popular. However, if they don't raise their standards, these restaurants' business would eventually suffer.
* Strategies should be made to increase the popularity of rarely served cuisines such as North Eastern, Indonesian, Lebanese, Malaysian, and others.
* Restaurant owners can determine the discrepancies between their price point and the average ratings they receive and based on that they can upgrade the services they offer or reconsider their price point.
* The clustering model has helped in grouping restaurants based on the other attributes of the restaurants, which will ultimately aid the company in developing targeted revenue-boosting measures.
* The sentiment analysis model has helped the business in classifying the positive and negative reviews of the customers, which can help improve their business position.

## Future Scope
* Recommendation System: Based on the clustering model and sentiment analysis, we can build a recommendation system that suggests the best restaurants to customers based on their preferences and sentiments.

* Real-Time Sentiment Analysis: We can use this project to perform real-time sentiment analysis of restaurant reviews posted on social media platforms like Twitter, Facebook, or Instagram. This would help the restaurants to quickly respond to negative feedback and improve customer satisfaction.

* Multi-City Analysis: We can extend this project to analyze restaurant data from multiple cities and countries. This would provide insights into the regional preferences and help Zomato to expand its services globally.

* Improvement in Sentiment Analysis: We can explore advanced techniques for sentiment analysis such as deep learning-based approaches to improve the accuracy of the sentiment classification.

* Integration with Zomato: We can integrate this project with the Zomato platform and provide real-time insights to customers and restaurants. This would enhance the user experience and help restaurants to improve their services.

* Exploring other Clustering Algorithms: We can explore other clustering algorithms like DBSCAN, Spectral Clustering, and Mean-Shift Clustering to compare their performance with K Means Clustering and Agglomerative Hierarchical Clustering.

These are some of the potential future directions for this project that can add value to the Zomato platform and enhance the user experience.

## Conclusion
This project demonstrates the application of clustering algorithms and sentiment analysis in analyzing Zomato Restaurant data. The results obtained from this analysis can be useful for the customers in finding the best restaurant in their locality, and the analysis can be beneficial for the company to grow up and work on the fields where they are currently lagging.





