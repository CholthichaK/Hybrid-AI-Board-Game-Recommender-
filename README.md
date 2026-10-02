# Board Game Recommender

An AI-powered board game recommendation system that combines a recommendation model with the **Google Gemini API** to provide personalized board game suggestions based on user preferences.

## Features

* Board game recommendations based on user preferences
* Similarity-based recommendation system
* Google Gemini API integration
* Natural-language recommendation and explanations
* Interactive interface

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Google Gemini API
* Streamlit

## How It Works

The system analyzes board game data and identifies games that match the user's preferences. The recommended games are then enhanced with Gemini to provide more personalized, natural-language suggestions and explanations.

```text
User Preferences
      ↓
Recommendation Model
      ↓
Matching Board Games
      ↓
Gemini API
      ↓
Personalized Recommendations
```

## Setup

Install the dependencies:

```bash
pip install -r requirements.txt
```

Set your Gemini API key as an environment variable:

```text
GEMINI_API_KEY=your_api_key_here
```

Run the application:

```bash
streamlit run app.py
```

## What I Learned

* Building a recommendation system
* Data preprocessing and feature engineering
* Integrating Generative AI with an existing ML application
* Working with the Gemini API
* Building an interactive AI application with Streamlit


Author
Cholthicha Khanijomdi
