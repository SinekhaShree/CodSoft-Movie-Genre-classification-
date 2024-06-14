# Movie Genre Classification

This repository contains the code and documentation for a machine learning project that classifies movie genres based on plot summaries.

## Project Description

The goal of this project is to build a machine learning model that can predict the genre of a movie given its plot summary. The project uses text data for training and testing, applies various preprocessing steps, and employs a logistic regression model for classification.

## Dataset

The dataset used in this project consists of movie plot summaries and their corresponding genres. It is divided into the following files:

- `train_data.txt`: Training data containing movie titles, genres, and descriptions.
- `test_data.txt`: Test data containing movie IDs, titles, and descriptions.

## Project Structure

The project repository is structured as follows:

├── data
│ ├── train_data.txt
│ ├── test_data.txt
│ ├── test_data_solution.txt
│ └── description.txt
├── notebooks
│ └── movie_genre_classification.ipynb
├── models
│ └── model.pkl
├── .gitignore
├── README.md
└── requirements.txt

- `data/`: Contains the dataset files.
- `notebooks/`: Contains the Jupyter notebook with the project code and analysis.
- `models/`: Contains the saved machine learning model.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `README.md`: Project documentation.
- `requirements.txt`: List of dependencies required to run the project.

## Installation

To run this project, you need to have Python 3.x installed. Follow the steps below to set up the project:

## Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-genre-classification.git
   cd movie-genre-classification

python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`

pip install -r requirements.txt

## Usage
To run the project and train the model, open the Jupyter notebook movie_genre_classification.ipynb in the notebooks/ directory and follow the steps provided.

jupyter notebook notebooks/movie_genre_classification.ipynb
The notebook contains detailed explanations and code for each step of the project, including data loading, preprocessing, model training, evaluation, and prediction.

Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please create a pull request or open an issue.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
The dataset used in this project is sourced from Kaggle.
Special thanks to the open-source community for providing useful libraries and tools for machine learning and data science.


This `README.md` file provides an overview of the project, including its description, structure, installation instructions, usage, results, and other relevant information. Adjust the content as necessary to fit the specifics of your project.

