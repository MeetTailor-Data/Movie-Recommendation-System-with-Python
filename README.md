# Movie Recommendation System with Python

## Project Description

This project builds a movie recommendation system using the MovieLens 100K dataset. It implements collaborative filtering techniques to recommend movies based on user preferences and evaluates the recommendation model using cross-validation.

The project demonstrates how recommendation systems work using the Surprise library and Singular Value Decomposition (SVD).

---

## Dataset

Dataset: MovieLens 100K

Files Used:

* u.data
* Movie_Id_Titles

Dataset contains:

* User IDs
* Movie IDs
* Ratings
* Movie Titles

---

## Project Workflow

### Data Exploration

The notebook includes:

* Loading movie ratings dataset
* Loading movie titles dataset
* Merging both datasets
* Viewing dataset information
* Statistical summary
* Creating a ratings dataframe
* Calculating:

  * Average Rating
  * Number of Ratings

---

## Exploratory Data Analysis (EDA)

The notebook includes:

* Histogram of movie ratings
* Histogram of number of ratings
* Joint distribution of ratings
* Correlation analysis for movie recommendations

---

## Recommendation System

The project uses the Surprise library to build a collaborative filtering recommendation model.

Algorithm:

* Singular Value Decomposition (SVD)

Steps:

1. Load the ratings dataset.
2. Prepare the dataset using Surprise.
3. Split the dataset into training and testing sets.
4. Train the SVD recommendation model.
5. Predict movie ratings.
6. Evaluate model performance.

---

## Model Evaluation

The recommendation model is evaluated using:

* Root Mean Squared Error (RMSE)
* Cross Validation

---

## Concepts Used

* Recommendation Systems
* Collaborative Filtering
* Matrix Factorization
* Singular Value Decomposition (SVD)
* Data Exploration
* Data Visualization
* Correlation Analysis
* Surprise Library
* Cross Validation
* RMSE

---

## Project Structure

```text
Movie-Recommendation-System-with-Python/
│
├── 02-Advanced Recommender Systems with Python.ipynb
├── u.data
├── Movie_Id_Titles
└── README.md
```

---

## Requirements

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn
* Surprise

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scikit-surprise
```

---

## How to Run

1. Clone this repository.
2. Place the `u.data` and `Movie_Id_Titles` datasets in the project folder.
3. Open `02-Advanced Recommender Systems with Python.ipynb`.
4. Run all cells from top to bottom.

---

## Author

Meet Tailor — Data Science Learner

GitHub: https://github.com/MeetTailor-Data

---

## License

Created for learning and educational purposes only.
