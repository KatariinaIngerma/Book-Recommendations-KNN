# Book-Recommendations-KNN
This project implements a book recommendation algorithm using the K-Nearest Neighbors (KNN) algorithm. The algorithm utilizes the Book-Crossings dataset, which contains 1.1 million ratings of 270,000 
books by 90,000 users.<br> <br>
The goal of this project is to provide users with personalized book recommendations based on their input book. 
The KNN algorithm measures the distance between books to determine their similarity and recommends books that are 
close or similar to the input book.
### Problem statement
The goal of this project is to develop a book recommendation system that suggests similar books to a given book. 
The Nearest Neighbors algorithm is used to measure the distance between books and determine their similarity.
The algorithm takes a book title as an input and returns a list of 5 similar books along with their distances from the input book.
### Dataset
The Book-Crossings dataset is used in this project. It contains ratings on a scale of 1 to 10 given by users to various books.
The dataset is preprocessed and cleaned to ensure statistical significance by
removing users with less than 200 ratings and books with less than 100 ratings.
### Dependencies
The following Python libraries are required to run the project:
* pandas: For data manipulation and analysis.
* scikit-learn: For implementing the KNN algorithm.
