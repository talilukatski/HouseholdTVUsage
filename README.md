Project 1
Distributed Media Data Management and Spam Detection

Part 1: Spam Detection in Media Data This part of the project focuses on identifying and removing malicious records from a large media dataset. Using PySpark, we analyze the "Daily Program Data" and apply a set of conditions to detect potentially harmful data introduced by a rival organization. By combining program viewing data with demographic and household information, we use seven conditions to flag malicious records, ensuring that we remove inaccurate data that could hinder user experience. The goal is to optimize data quality and maintain a high standard of content reliability.

Part 2: DMA Popularity and Data Distribution In the second part, the task shifts towards designing an efficient distributed database system. The focus is on organizing media data across different DMAs (Designated Market Areas) based on their popularity and wealth. We rank genres by their popularity within the top 10 DMAs, and later assign media genres to servers based on each DMA's wealth score. The aim is to balance performance, cost, and user experience in a resource-constrained distributed system.

Project 2
Lukewarm Cable: Channel Recommendation System for New Clients
In this project, the objective is to develop a recommendation system for LukewarmTM cable company to suggest 10 channels to new clients based on their household demographic information, without prior knowledge of their viewing habits.

Part 1: Static Data Analysis The project starts with feature extraction from demographic data, including normalizing numerical values and applying one-hot encoding to categorical variables. The normalized data is then reduced to a 2-dimensional space using SVD (Singular Value Decomposition) for visualization, followed by clustering the households into 8 groups using the K-means algorithm. The project then continues by analyzing the clusters based on their distance to centroids, creating subsets of households for further analysis.

Part 2: Dynamic Data Analysis with Streaming The second part involves using Spark Streaming with Kafka to process real-time viewing data. The goal is to analyze viewing patterns for the households within the same clusters, focusing specifically on the "7ths subset" to identify any similarities in station preferences. The streaming component helps LukewarmTM to dynamically adjust recommendations as new data comes in, ensuring relevance and accuracy in real-time.
