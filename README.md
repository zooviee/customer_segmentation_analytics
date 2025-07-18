# 📊 Customer Segmentation with KMeans & Hierarchical Clustering

This project applies unsupervised learning techniques—KMeans and Hierarchical Clustering—to perform customer segmentation based on engagement and spending behavior. It includes a full data pipeline from preprocessing to visualization and delivers a PDF report with actionable marketing insights.


## 🔍 Objectives
Segment customers based on minutes_watched, CLV, and region
Visualize clustering patterns using dendrograms and elbow plots
Identify high-value customer groups and recommend targeted marketing strategies


## 📁 Project Structure


├── customer_analytics_segmentation.ipynb   # Jupyter notebook for analysis
├── Report.pdf                              # Final PDF report
└── customer_segmentation_data.csv          # Dataset 


## 🧠 Insights Summary
Instagram Explorers: Moderate engagement/spending, globally distributed
LinkedIn Networkers: High engagement from Rest of World
European Multi-Channel: Highest CLV, from Western Europe
Anglo-Saxon Multi-Channel: High spend, mostly from USA/UK/Canada/Australia
Twitter Devotees: Small, low-engagement group → deprioritize


## 💡 Future Enhancements
Add PCA or t-SNE visualization
Expand features (e.g., subscription type, time since signup)
Integrate engagement scoring for dynamic segmentation
