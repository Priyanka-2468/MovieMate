# MovieMate

## Introduction

The Movie Recommendation System leverages content-based filtering to suggest movies tailored to users' preferences. By analyzing movie metadata and similarities with past liked movies, it provides personalized recommendations.

## Features

- **Content-Based Filtering:** Recommends movies based on the similarity to movies the user has liked.
- **Metadata Utilization:** Uses detailed movie metadata to calculate similarity.
- **User-Friendly Interface:** Offers a simple and intuitive user experience.

## Technologies Used

- **Python:** Core programming language.
- **Pandas:** For data manipulation and analysis.
- **Scikit-learn:** Machine learning library for calculating movie similarities.
- **Flask:** Web framework for building the web application.
- **HTML/CSS:** Frontend technologies for the user interface.
- **Pickle:** Library for saving and loading models.

## Installation

### Prerequisites

- Python 3.x
- Pip (Python package installer)

### Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/AnujSingh2003/Movie_recommendation_content_filtering.git
   cd Movie_recommendation_content_filtering
   ```

2. **Create and Activate a Virtual Environment:**

   ```bash
   python -m venv venv
   ```
   - **For Windows:**

     ```bash
     .\venv\Scripts\activate
     ```
   - **For Mac/Linux:**

     ```bash
     source venv/bin/activate
     ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Ensure Model Files are in the Correct Directory:**

   Make sure the `model` directory contains the following `.pkl` files:
   - `movie_list.pkl`
   - `similarity.pkl`

5. **Run the Application:**

   ```bash
   python main.py
   ```

6. **Access the Application:**

   Open your browser and navigate to [http://localhost:5000](http://localhost:5000).
