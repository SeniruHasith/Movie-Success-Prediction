# Movie Success Prediction Model

This project predicts the success of a movie based on multiple factors, including YouTube trailer sentiment, cast popularity, and visual features extracted from the trailer using computer vision techniques. The model combines sentiment analysis, machine learning, and computer vision to make accurate predictions on a movie's potential box office performance.

## Overview

The movie success prediction model leverages various machine learning algorithms and deep learning models to analyze data from different sources:
- **YouTube Trailer Sentiment**: Sentiment analysis on user comments from YouTube trailers to assess audience reaction.
- **Cast Popularity**: Data about the movie's cast to gauge the influence of well-known actors and actresses.
- **Trailer Visual Analysis**: Computer vision techniques, including pretrained convolutional neural networks (CNNs), to extract features from the trailer's visuals and identify potential success factors.
- **Prediction Output**: A success score is generated based on the analysis, which can be used to estimate box office success.

## Features

- **Sentiment Analysis**: Analyzes the sentiment of YouTube trailer comments to understand audience excitement or concerns.
- **Cast Popularity**: Includes data about the cast's influence on movie success, leveraging public metrics and popularity indices.
- **Trailer Visual Features**: Uses pretrained CNN models (e.g., ResNet, VGG) to analyze the trailer's visuals for patterns that correlate with successful movies.
- **Prediction Score**: Provides a numerical prediction of movie success based on sentiment, cast data, and visual features.

## Technologies Used

- **Machine Learning**: 
  - Algorithms like Random Forest, XGBoost for making predictions.
- **Natural Language Processing**:
  - Sentiment analysis on YouTube comments.
- **Computer Vision**:
  - Pretrained CNN models (ResNet, VGG) for visual feature extraction.
  - OpenCV for image processing.
- **Backend**: 
  - Flask API to serve the prediction model.
- **YouTube API**: To fetch movie trailer metadata and comments.
  
## Setup

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/movie-success-prediction.git
cd movie-success-prediction

```

### 2. Set Up the Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Run the Flask Application
```bash
python app.py
```

By default, the server will run on http://127.0.0.1:5000/.
