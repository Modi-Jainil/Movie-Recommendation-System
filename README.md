# Movie Recommendation System

A comprehensive web-based movie recommendation system built with Flask that provides intelligent movie suggestions using content-based filtering and sentiment analysis of user reviews.

## 🎬 Features

-   **Smart Movie Recommendations**: Get personalized movie suggestions based on content similarity
-   **Auto-complete Search**: Intelligent search with movie title suggestions
-   **Sentiment Analysis**: Analyze user reviews from IMDB to determine positive/negative sentiment
-   **Detailed Movie Information**: View comprehensive movie details including:
    -   Cast information with actor profiles
    -   Movie posters and metadata
    -   Genre classification
    -   Release dates and ratings
    -   User reviews with sentiment highlighting
-   **Modern Web Interface**: Responsive design with Bootstrap and custom CSS
-   **Real-time Data**: Fetches live movie data and reviews from external APIs

## 🚀 Technology Stack

-   **Backend**: Python Flask
-   **Machine Learning**: scikit-learn, pandas, numpy
-   **NLP**: NLTK for text processing
-   **Web Scraping**: BeautifulSoup4 for IMDB reviews
-   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 4
-   **Data Processing**: Pandas for data manipulation
-   **Model Persistence**: Pickle for saving trained models

## 🎯 How It Works

### Content-Based Filtering

The system uses content-based filtering to recommend movies based on:

-   Movie genres
-   Cast information (actors, directors)
-   Plot similarities
-   User preferences

### Sentiment Analysis

-   Fetches user reviews from IMDB
-   Uses a pre-trained NLP model to classify reviews as positive or negative
-   Highlights sentiment-related words in reviews
-   Provides overall sentiment analysis for each movie

### Recommendation Algorithm

1. User searches for a movie
2. System finds similar movies based on content features
3. Calculates cosine similarity between movies
4. Returns top similar movies with detailed information
5. Fetches and analyzes user reviews for sentiment

## 📊 Dataset

The system uses a comprehensive movie dataset containing:

-   **36,984+ movies** with detailed metadata
-   Cast information (actors, directors)
-   Genre classifications
-   Movie titles and descriptions
-   User ratings and reviews

## 🔧 Configuration

The application uses several pre-trained models:

-   `nlp_model.pkl`: Trained sentiment analysis model
-   `tranform.pkl`: TF-IDF vectorizer for text processing
-   `main_data.csv`: Main movie dataset

## 🌐 API Integration

-   **IMDB Integration**: Fetches real-time movie reviews and metadata
-   **TMDB API**: Used for movie poster images and additional metadata
-   **Web Scraping**: Extracts user reviews from IMDB pages

## 🎨 Features in Detail

### Search Interface

-   Auto-complete functionality for movie titles
-   Real-time search suggestions
-   Error handling for misspelled movie names

### Recommendation Results

-   Movie posters and basic information
-   Similar movies with similarity scores
-   Cast and crew details
-   Genre information
-   Release dates and ratings

### Review Analysis

-   Live IMDB review fetching
-   Sentiment classification (Positive/Negative)
-   Keyword highlighting in reviews
-   Review statistics and summaries

## 🚀 Usage

1. **Search for a Movie**: Type a movie name in the search box
2. **Get Recommendations**: Click "Enter" to see similar movies
3. **Explore Details**: View detailed information about recommended movies
4. **Read Reviews**: Check user reviews with sentiment analysis