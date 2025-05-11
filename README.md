### **Final Report of Customer Segmentation with K-Means**

#### **Objective of the Project:**
The goal of this project was to identify customer groups based on their purchasing behavior and divide them into different clusters.

#### **Steps Completed:**
1. **Data Loading:**
   - The file `Online Retail.xlsx` was successfully loaded.

2. **Data Preprocessing:**
   - Missing values were removed.
   - Important columns such as `CustomerID` and `Description` were cleaned.

3. **Feature Extraction:**
   - Features like `Frequency`, `Monetary`, and `Quantity` were extracted for each customer.

4. **Data Standardization:**
   - Data was standardized using `StandardScaler`.

5. **Determining Optimal Number of Clusters (K):**
   - Using the Elbow Method and Silhouette Score, $ K = 4 $ was chosen as the optimal number of clusters.

6. **Training the K-Means Model:**
   - The K-Means model was trained with $ K = 4 $, and cluster labels were assigned to customers.

7. **Cluster Analysis:**
   - Clusters were analyzed based on `Frequency`, `Monetary`, and `Quantity`.
   - Results from box plots and scatter plots showed that customers were divided into distinct groups.

8. **Model Evaluation:**
   - The Silhouette Score was calculated and found to be 0.77, indicating a good clustering result.

9. **Marketing Strategies:**
   - Marketing strategies were designed for each cluster.
   - For example, promotional emails with discounts were suggested for low-activity customers.

#### **Conclusion:**
- The K-Means algorithm performed well and divided customers into 4 distinct groups.
- These results can help the business develop personalized marketing strategies.
- For model evaluation, unsupervised metrics like Silhouette Score and WCSS were used.