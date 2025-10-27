# Customer-Segmentation-using-K-Means-Clustering.ipynb

🛍️ Customer Segmentation using K-Means Clustering

I recently worked on this project to understand how businesses can segment their customers based on spending behavior and income levels. Using K-Means Clustering, I grouped mall customers into different clusters that share similar purchasing patterns.

This kind of analysis helps companies plan targeted marketing strategies, personalized offers, and better customer relationship management.

📘 Project Overview

In this project, I used the Mall Customers dataset, which contains information like age, gender, annual income, and spending score of customers.
The main goal was to find distinct customer groups using their Annual Income and Spending Score.

⚙️ Steps I Followed
1️⃣ Importing Libraries

I started by importing Python libraries like Pandas, NumPy, Matplotlib, Seaborn, and KMeans from Scikit-learn.

2️⃣ Data Exploration

Loaded the dataset and checked for missing values, data types, and basic info.
Luckily, the dataset was clean with no missing data.

3️⃣ Feature Selection

I selected only two important features for clustering —

Annual Income (k$)

Spending Score (1–100)

These two features give a good idea of a customer’s purchasing power and spending habits.

4️⃣ Finding the Optimal Number of Clusters

I used the Elbow Method to find the best number of clusters by plotting the WCSS (Within Cluster Sum of Squares).
The elbow graph showed that 5 clusters would be ideal.

5️⃣ Training the Model

Trained the K-Means model with 5 clusters and assigned each customer to a cluster label.

6️⃣ Visualization

Plotted all the clusters using Matplotlib and Seaborn.
Each color in the graph represents a different group of customers, and the centroids show the center of each cluster.


💡 Insights Gained

Here’s what I learned from the clustering results:

Customers with high income and high spending score are premium customers — most valuable segment.

Medium income and medium spending customers form the average group.

Some customers have high income but low spending, which can be potential targets for promotional offers.


🧰 Tech Stack

Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Algorithm: K-Means Clustering


📊 Results

Found 5 meaningful customer groups.

Clear segmentation helps in understanding customer purchasing patterns.

The visual clusters make it easy to identify high-value and low-value customer groups.


🚀 Future Improvements

Add Age and Gender to make clustering more detailed.

Try Hierarchical Clustering and compare results.

Build a Streamlit app for real-time customer segmentation visualization.

📂 Project Link

👉 Click here to view the full project on GitHub
https://github.com/Fajlurrahman219/Customer-Segmentation-using-K-Means-Clustering.ipynb/tree/main


👨‍💻 About Me

Hi, I’m Fajlur Rahman, a Data Science enthusiast passionate about building real-world projects using Python and Machine Learning.
If you found this project interesting, feel free to ⭐ star the repo or connect with me on LinkedIn https://www.linkedin.com/in/fajlurrahman219/
