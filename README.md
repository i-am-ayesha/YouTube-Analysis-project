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
Video Title
Views
Likes, Dislikes
Comments
Load the video data into a Pandas DataFrame for analysis.
#### 6. Visualize Video Data
Create visualizations to analyze:
Which videos have the most views.
Like and comment distribution across videos.
📊 Example Visualizations
Subscribers vs Views: A bar chart comparing subscriber count with total views for selected channels.
Video Analysis: Visualize which videos got the highest likes, comments, and views.
## 🎯 Key Takeaways
1. Learn how to access and use YouTube Data API.
2. Build a Pandas DataFrame from YouTube data for analysis.
3. Create meaningful visualizations using Seaborn.
4. Compare multiple channels and their performance metrics.
## 🔧 Future Enhancements
1. Implement sentiment analysis on YouTube video comments.
2. Add real-time data scraping and analysis.
3. Automate periodic data scraping to track changes over time.
 
