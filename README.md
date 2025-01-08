# 🎥 YouTube Data Scraper 📊

## 📋 Project Overview
Using the YouTube Data API, this project will scrape data from various YouTube channels and videos, analyze it using Python, and create visualizations to compare the data.

This project is divided into two parts:

Part 1 focuses on channel-level data (subscribers, total views, and video count).

Part 2 extracts and analyzes video-level data (views, likes, comments, and more).

## 🌟 Features
1. Access YouTube Data: Use YouTube Data API to fetch channel and video details.
2. Data Analysis: Load the data into Pandas DataFrames for analysis.
3. Data Visualization: Generate visualizations using Seaborn to compare channels and video metrics.
4. Portfolio-Ready Project: A hands-on project for aspiring Data Analysts or anyone interested in exploring YouTube data.
## 🛠️ Tools & Libraries
1. Python: Python is the programming language used for this project.
2. YouTube Data API: API to fetch YouTube data (channels, videos, etc.).
3. Pandas: For data manipulation and analysis.
4. Seaborn: For generating beautiful visualizations.
5. Jupyter Notebook: For writing and running the code.
6. Anaconda: To create a virtual environment and manage dependencies.
## 🚀 Project Workflow
#### 1. Setup YouTube API
Create your YouTube API Key from the Google Developers Console.
#### 2. Environment Setup
Use Anaconda to create a virtual environment for the project.
Install the required libraries using:

`pip install google-api-python-client pandas seaborn`
#### 3. Extract Channel Data
Fetch channel details such as:
Channel Name
Total Subscribers
Total Views
Total Videos
Compare data across multiple channels and load this into a Pandas DataFrame for further analysis.
#### 4. Visualize Channel Data
Use Seaborn to visualize:
Subscriber comparison across channels.
Video count and view count analysis.
#### 5. Extract Video Data
For each channel, extract details of individual videos such as:
. Video Title
. Views
. Likes, Dislikes
. Comments
Load the video data into a Pandas DataFrame for analysis.
#### 6. Visualize Video Data
Create visualizations to analyze:
Which videos have the most views.
Like and comment distribution across videos.
📊 Example Visualizations
1. A bar chart showing which channel  has most videos. 
![image](https://github.com/user-attachments/assets/1aa6b507-bcd9-4cf2-836b-608614ff9f5d)
2. A bar chart showing which channel  has most views.
![image](https://github.com/user-attachments/assets/4be54e53-4ad1-4899-ba68-c311a13e5668)
3. A bar chart showing which channel  has most subscribers.
![image](https://github.com/user-attachments/assets/e4fb13ba-79d2-4cbc-bc96-8e358c2d10fb)
4. A bar chart showing which topic  has most views.
![image](https://github.com/user-attachments/assets/15bb5240-0099-4903-b1b9-1046681327a4)
5. Visualize which videos got the highest likes, comments, and views every month.
![image](https://github.com/user-attachments/assets/305ac40e-d94b-4ea7-a039-d8fe3f1bb16f)

## 🎯 Key Takeaways
1. Learn how to access and use YouTube Data API.
2. Build a Pandas DataFrame from YouTube data for analysis.
3. Create meaningful visualizations using Seaborn.
4. Compare multiple channels and their performance metrics.
## 🔧 Future Enhancements
1. Implement sentiment analysis on YouTube video comments.
2. Add real-time data scraping and analysis.
3. Automate periodic data scraping to track changes over time.
 
