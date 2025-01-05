# Movie Recommendation System

## Overview
This project is a personalized movie recommendation system created as part of the CS5100 Final Project by Abdelrahman Zeidan. The system recommends movies to users based on their preferences using Python and machine learning techniques. 

The project involves:
- Loading and exploring the movie dataset.
- Building a recommendation system using **TF-IDF vectorization** and **cosine similarity**.
- Evaluating and visualizing results.

## Installation and Setup
To run this project on your local machine:
1. Clone the repository:
   `git clone https://github.com/AbdelrahmanZeidan5/Movie-Recommendation-System.git`

2. Navigate to the project directory:
   `cd Movie-Recommendation-System`

3. Install the required dependencies:
   `pip install -r requirements.txt`

4. Launch Jupyter Notebook:
   `jupyter notebook`

   Open the `Final_project_code.ipynb` file and execute the cells sequentially.

## Dataset
The project uses the **MovieLens dataset**, which provides a rich collection of movie ratings and metadata.

- **Source**: [MovieLens Dataset](https://grouplens.org/datasets/movielens/)
- **File Used**: `movies.csv` from the `ml-latest-small` dataset.
- **Description**: This file contains movie IDs, titles, and genres.

### Example of the dataset structure:
| movieId | title                    | genres               |
|---------|--------------------------|----------------------|
| 1       | Toy Story (1995)         | Adventure|Animation |
| 2       | Jumanji (1995)           | Adventure|Children  |
| 3       | Grumpier Old Men (1995)  | Comedy|Romance      |

## Results
The system provides personalized movie recommendations based on the similarity of movies. For example:




## Requirements
This project requires the following Python libraries:
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:
`pip install -r requirements.txt`

## License
This project is licensed under the MIT License.

## Author
**Abdelrahman Zeidan**  
CS5100 Final Project
