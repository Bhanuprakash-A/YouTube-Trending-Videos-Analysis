#YouTube Trending Videos Data Analysis
This project performs a detailed analysis of trending YouTube videos, focusing on various attributes such as views, likes, comments, and title characteristics. It uses the YouTube Data API to collect data and employs data visualization techniques to answer questions regarding trends in YouTube content.

Project Overview
This analysis covers:

Fetching YouTube trending videos using the YouTube API
Extracting video details like views, likes, comments, and category
Analyzing video attributes to understand what makes videos trend
Visualizing correlations between video metrics
Determining common trends in titles, categories, and publication times
Features
API Integration: Utilizes YouTube's Data API to fetch real-time data.
Data Analysis: Includes comprehensive analysis using Pandas and Seaborn.
Visualization: Generates scatter plots, histograms, and correlation matrices.
Trending Video Insights: Analyzes factors like views, likes, comments, and title lengths.

Ensure you have a valid API key from the Google Cloud Console, with access to YouTube Data API v3.

Usage
Open the Jupyter notebook or run the Python script to start the analysis.

The main script main.py fetches trending videos, extracts the data, and saves it to a CSV file (trending_videos.csv).
Analysis includes answering questions such as:
How many views do trending videos have?
Are likes and comments related to the video’s rank?
What are the common characteristics of trending videos' titles?
Example API setup:

Set your API key in the script:
python
Copy code
API_KEY = "YOUR_API_KEY"
Run the script to fetch data

Views Analysis:

Total views of trending videos and distribution of views.
Scatter plots of rank vs. views and histograms.
Likes and Comments:

Analysis of how likes and comments are related to video popularity.
Visualizations of the correlation between likes, comments, and views.
Title Characteristics:

Examination of title lengths and the occurrence of fully capitalized words.
Insights into how titles might affect video trendiness.
Most Common Words in Titles:

Extraction of the most common words from video titles.
Top Trending Channels and Categories:

Identification of channels with the highest number of trending videos.
Analysis of which video categories (e.g., entertainment, gaming) are the most popular.
Dataset
The dataset used in this project is dynamically fetched from YouTube via the YouTube Data API and is specific to the region of India. Data includes:

Video titles, channel names
Views, likes, dislikes, comments
Video category and publication date
Visualizations
Various visualizations are generated to represent data insights, including:

Scatter plots
Histograms
Heatmaps of correlation between video metrics
