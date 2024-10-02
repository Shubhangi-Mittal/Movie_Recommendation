# Movie Recommendation System

This repository contains a Movie Recommendation System built with Natural Language Processing (NLP) techniques using Python. The system leverages a dataset of 9,000 movies to provide personalized movie recommendations. A simple, user-friendly UI is implemented using the Gradio library to allow users to interact with the recommendation system seamlessly.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Dataset](#dataset)
- [How to Use](#how-to-use)
- [Future Enhancements](#future-enhancements)


## Features

- Get personalized movie recommendations based on movie titles and descriptions.
- Uses NLP to capture the relationships between movies and recommend similar movies.
- Simple and intuitive UI built with Gradio to allow easy interaction.
- Recommendations are based on movie similarities derived from a dataset of 9,000 movies.

## Tech Stack

- **Programming Language**: Python
- **Libraries**: 
  - [Pandas](https://pandas.pydata.org/) - For data manipulation
  - [Scikit-learn](https://scikit-learn.org/stable/) - For NLP and building recommendation models
  - [Gradio](https://gradio.app/) - To build the user interface
  - [Numpy](https://numpy.org/) - For numerical computations
  - [NLTK/Spacy](https://www.nltk.org/ or https://spacy.io/) - For text preprocessing

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/movie-recommendation-system.git
    cd movie-recommendation-system
    ```

2. **Create a virtual environment**:

    ```bash
    python -m venv venv
    ```
3. **Run the code**:

## Dataset

The dataset contains information on 9,000 movies, including movie titles, genres, overviews, and other details. This dataset is used to create a content-based recommendation system. You can find the dataset in the `data/` folder or download it from [Kaggle](https://www.kaggle.com/) and place it in the appropriate directory.

## How to Use

1. **Get Movie Recommendations**:

    - Enter the title of a movie that you like in the input box.
    - The system will provide you with a list of recommended movies that are similar to the one you entered.


## Future Enhancements

- Implement collaborative filtering to further improve the recommendation accuracy.
- Add more features to the Gradio UI for filtering movies by genre, release year, etc.
- Expand the dataset to include more movies.
- Integrate user feedback to refine recommendations.
