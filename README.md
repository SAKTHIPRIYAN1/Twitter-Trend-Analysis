# Twitter-Trend-Analysis


## Overview
The **Twitter Trend Analysis** project explores trending topics on Twitter using **data mining and association rule learning** techniques such as **Apriori**, **FP-Growth**, and **K-Means clustering**.  
The goal is to uncover hidden relationships between trending hashtags, analyze user interests, and identify key communities or clusters based on tweet content and engagement patterns.

---

##  Objectives
- Collect real-time trending data from Twitter using the **Tweepy API** or pre-stored datasets.  
- Analyze the **frequency and co-occurrence** of trending hashtags.  
- Apply **Apriori** and **FP-Growth** algorithms to extract association rules.  
- Evaluate **support**, **confidence**, and **lift** to identify strong correlations.  
- Use **K-Means clustering** to group related trends or users.  
- Visualize distributions, correlations, and lift patterns using charts and histograms.

---

##  Key Concepts
| Technique | Purpose | Description |
|------------|----------|-------------|
| **Apriori Algorithm** | Association Rule Mining | Identifies frequent itemsets and rules from large datasets. |
| **FP-Growth Algorithm** | Efficient Frequent Pattern Mining | Improves over Apriori by using a compact FP-tree structure, making it faster. |
| **K-Means Clustering** | Trend Grouping | Clusters similar hashtags or users based on tweet embeddings or frequency metrics. |


##  Visualizations
- **Histogram of Lift Values** – Shows strength and spread of associations.  
- **Support vs Confidence Scatter Plot** – Helps identify the most reliable rules.  
- **Cluster Plots (K-Means)** – Displays groups of related trends.  
- **Word Clouds** – Highlights most frequent hashtags.

---

##  Tech Stack
- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` – Data preprocessing  
  - `mlxtend` – Apriori and FP-Growth  
  - `scikit-learn` – K-Means clustering  
  - `matplotlib`, `seaborn` – Data visualization  
---

## Workflow
1. **Data Collection** – Gather Twitter data (hashtags, text, engagement metrics).  
2. **Preprocessing** – Tokenize, clean, and filter hashtags or words.  
3. **Association Rule Mining** – Apply Apriori and FP-Growth.  
4. **Cluster Analysis** – Group similar trends using K-Means.  
5. **Evaluation** – Compare algorithms based on speed, Lift, and rule quality.  
6. **Visualization** – Generate insightful plots and charts.

---

