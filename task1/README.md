This project implements a Movie Recommendation System using a Restricted Boltzmann Machine (RBM) in PyTorch.
It is based on the MovieLens dataset, where the system predicts whether a user would like (1) or not like (0) a movie, based on past ratings.

🛠️ Tech Stack

Python 🐍

Google Colab

NumPy, Pandas

PyTorch (Neural Networks)
📂 Dataset

We use the MovieLens 100k dataset, which contains:

movies.dat → Movie details

users.dat → User information

ratings.dat → User ratings

u1.base → Training set

u1.test → Test set


Ratings are converted into binary values:

1 (Liked) → ratings >= 3

0 (Not liked) → ratings < 3

-1 → No rating
