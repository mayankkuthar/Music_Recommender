# Music Recommendation System

Welcome to the Music Recommendation System project! This application utilizes Python, machine learning, and the Spotify Web API to recommend songs based on user input.

## Overview

This project aims to create a user-friendly web application for recommending music to users based on their preferences. The system employs machine learning techniques, particularly cosine similarity, to recommend songs similar to those input by the user.

## Features

- Tokenization and textual data processing for input text
- TF-IDF vectorization for numerical representation of textual data
- Cosine similarity calculation for song recommendations
- Integration with the Spotify Web API for accessing song information and album covers
- Web application development using the Streamlit library

## Getting Started

To run the application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies by running `pip install -r requirements.txt`.
3. Obtain Spotify API credentials and update the configuration file (`config.py`) with your client ID and client secret.
4. Run the Streamlit app by executing `streamlit run app.py` in your terminal.
5. Access the web application in your browser at the provided URL (usually `http://localhost:8501`).

## Usage

1. Enter a song name or keywords related to the type of music you're interested in.
2. Click the "Show Recommendation" button to receive song recommendations based on your input.
3. Explore the recommended songs and enjoy!

## Dependencies

- Python 3.x
- Streamlit
- Scikit-learn
- Spotipy (Python library for Spotify Web API)

## Contributing

Contributions to this project are welcome! If you find any bugs, have suggestions for improvements, or would like to add new features, please submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Results

![Landing Page](https://github.com/mayankkuthar/Music_Recommender/assets/39026182/f8a1e556-0602-4266-9b3b-1fbef86beb06)

![Select your music from the list](https://github.com/mayankkuthar/Music_Recommender/assets/39026182/820d9171-362e-4626-8844-fe9b0d904a89)

![Results as Recommendation](https://github.com/mayankkuthar/Music_Recommender/assets/39026182/d4b786b2-45f8-4c21-8503-3791e9aee1c4)

## Acknowledgments

Special thanks to Cassie Hosale for the inspiration and guidance in building this music recommendation system.

