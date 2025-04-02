# Book Recommender System

## Description
This project is a book recommendation system that suggests books to users based on popularity and collaborative filtering techniques. It utilizes three datasets—Books, Users, and Ratings—loaded into the system. The recommendation engine employs a popularity-based approach for general suggestions and collaborative filtering with cosine similarity to find related books tailored to user preferences.

## Required Tools and Libraries
- **Python 3.8+** - Core language for data processing and recommendation logic
- **Pandas** - Data manipulation and merging of Books, Users, and Ratings datasets
- **NumPy** - Numerical operations for similarity calculations
- **Scikit-learn** - Implementation of cosine similarity for collaborative filtering
- **Jupyter Notebook** - For data exploration and building the recommendation system

## Features
- Popularity-based recommendations to suggest widely liked books
- Collaborative filtering to provide personalized book suggestions
- Cosine similarity computation to identify books similar to a user’s preferences
- Integration of three datasets (Books, Users, Ratings) for comprehensive analysis

## Installation
1. Clone the repository: `git clone https://github.com/Ashtuosh-Jarag/Book-Recommender-System.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Download the datasets (e.g., from Kaggle or another source) and place them in the project’s root directory:
4. Serch for books data or "https://www.kaggle.com/datasets/saurabhbagchi/books-dataset"
   - `Books.csv`
   - `Users.csv`
   - `Ratings.csv`
5. Open the Jupyter Notebook (`Book_Recommender.ipynb`) to run the system

## Usage
1. Launch the Jupyter Notebook (`Book_Recommender.ipynb`) to:
   - Load and preprocess the `Books.csv`, `Users.csv`, and `Ratings.csv` files
   - Build the popularity-based recommendation model
   - Implement collaborative filtering with cosine similarity
2. Run the notebook cells to generate book recommendations:
   - Use the popularity-based model for top book suggestions
   - Input a book or user ID to get personalized recommendations based on cosine similarity

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
MIT License
