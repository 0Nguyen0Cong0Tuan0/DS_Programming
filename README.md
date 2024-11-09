# DS_Programming - YouTube Trending Videos Dataset Analysis
## Team Members:
- Trần Nguyễn Nhật Cường - 22127048 - Leader
- Nguyễn Công Tuấn - 22127436 - Member
- Trần Đăng Tuấn - 22127438 - Member

## Overview

This repository contains our team's analysis of the YouTube Trending Videos Dataset, which provides data on the top trending YouTube videos across multiple countries and regions over several months. The dataset includes information about video statistics, such as views, likes, comments, and more, collected from YouTube's top trending list.

## Dataset Description

The dataset contains daily records of YouTube videos that were trending in several regions. The data is collected from the following countries:

- United States (US)
- Great Britain (GB)
- Germany (DE)
- Canada (CA)
- France (FR)
- Russia (RU)
- Mexico (MX)
- South Korea (KR)
- Japan (JP)
- India (IN)

Each country's data is provided in separate files, and the dataset includes up to 200 trending videos per day. The data columns for each video include:

- `video_title`: Title of the YouTube video.
- `channel_title`: The channel that published the video.
- `publish_time`: Time when the video was published.
- `tags`: Tags associated with the video.
- `views`: Number of views the video has received.
- `likes`: Number of likes on the video.
- `dislikes`: Number of dislikes on the video.
- `description`: Description of the video.
- `comment_count`: Number of comments on the video.
- `category_id`: An identifier for the video category (specific to each region).

Additionally, there are JSON files that map category IDs to human-readable category names for each region.

## Purpose and Use Cases

This dataset can be used for a variety of analyses, including but not limited to:

- **Sentiment Analysis**: Analyze the sentiment of comments on trending videos.
- **Video Categorization**: Classify videos based on their comments and metadata.
- **Popularity Prediction**: Investigate the factors that determine a video's popularity, such as views, likes, comments, and category.
- **Statistical Analysis**: Perform time-series analysis on video trends over the months.

### Potential Analyses Include:
- Investigating trends in video topics, categories, or channels over time.
- Analyzing the relationship between likes, views, and comments to predict video popularity.
- Performing sentiment analysis on video descriptions and comments.
- Exploring the impact of video publish time on video performance.

## Data Source

The dataset was collected using the YouTube API and is publicly available on [Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new).

## Files in this Repository

- `youtube_data/`: Directory containing the dataset for each region.
- `analysis_notebooks/`: Jupyter notebooks with the analysis performed on the dataset.
- `category_mappings/`: JSON files mapping category IDs to human-readable names for each region.
