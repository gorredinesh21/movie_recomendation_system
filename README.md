# recomendor

# Movie Recommendation System

A machine learning project for recommending movies based on text-based features such as genres, keywords, and more. This project uses a Bag of Words vectorization approach and cosine similarity to find similar movies.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Model Building](#model-building)
- [Website](#website)
- [Usage](#usage)
- [Getting Started](#getting-started)
- [Acknowledgments](#acknowledgments)

## Overview

This project aims to recommend movies to users based on the textual information associated with each movie. It uses a machine learning model that leverages text vectorization and cosine similarity to find similar movies in terms of their story, cast, and crew.

## Dataset

The dataset used in this project contains information about 5000 movies, including details such as genres, keywords, titles, overviews, cast, and crew.

## Data Cleaning

To prepare the dataset for modeling, we performed data cleaning and feature selection. We narrowed down the columns to 'genres,' 'id,' 'keywords,' 'title,' 'overview,' 'cast,' and 'crew.'

## Model Building

We used a Bag of Words text vectorization approach to convert textual data into numerical form. Then, we employed cosine similarity to find movies with similar content. The resulting model was saved using the Pickle library.

## Website

We built a website using Streamlit to provide an interactive interface for users. The website takes a movie as input and generates a list of 10 similar movies based on various attributes, including story, cast, and crew. It also utilizes an API key from TMDb to fetch movie posters.

## Usage

To use the Movie Recommendation System, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running:

## pip install -r requirements.txt

3. Run the Streamlit web app using:
   streamlit run app.py

4. Visit the provided URL to access the web application and start recommending movies.

## Getting Started

To get started with the project, you can follow the instructions in the [Usage](#usage) section. Additionally, you can explore the code and the Jupyter Notebook provided in this repository for more details on data preprocessing, model training, and website development.

## Acknowledgments

We would like to acknowledge the [TMDb API](https://www.themoviedb.org/documentation/api) for providing access to movie posters and other movie-related information, which enhances the user experience in our web application.


