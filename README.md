
# Book Recommender System Using Machine Learning! | Collaborative Filtering Based

This project presents a book recommendation system developed using collaborative filtering and the k-Nearest Neighbors (k-NN) approach.

![Drop down + Type in option](projectpic1.png)

![Example 1](projectpic2.png)

## Table of Contents
1. [Introduction](#introduction)
2. [Technique Used](#technique-used)
3. [Directory Structure](#directory-structure)
4. [Setup and Installation](#setup-and-installation)
5. [Usage](#usage)
6. [License](#license)

## Introduction

The book recommendation system suggests books based on user ratings. By understanding the behavior of users and their preferences, the system identifies and suggests similar books.

## Technique Used


Collaborative filtering is a technique used by recommender systems wherein recommendations are based on the preferences and behaviors of similar users. The underlying principle is that if two users have similar preferences on a set of items, they will likely have a similar taste for other items as well. Collaborative filtering can be broadly categorized into:

1. **User-based Collaborative Filtering**: This method identifies users similar to the targeted user and recommends items based on the preferences of these similar users. For example, if Alice and Bob both liked the books "A" and "B", and Bob also liked the book "C", then the system might suggest book "C" to Alice.
2. **Item-based Collaborative Filtering**: This approach identifies items that are similar to the ones liked by the user. Recommendations are made based on this item similarity. For instance, if the book "A" is frequently liked by individuals who also prefer the book "B", then a user who appreciated "A" might be recommended "B".

In this project, the k-Nearest Neighbors (k-NN) model is employed, which operates on the premise of item-based collaborative filtering. The k-NN algorithm computes the similarity between items based on user ratings. It identifies the "k" most similar items to a given book and recommends these to the user.


## Directory Structure

```
- env/
- src/
- data/
- artifacts/
- src.egg-info/
- app.py
- requirements.txt
- setup.py
- LICENSE
```

## Setup and Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required packages using:
```bash
pip install -r requirements.txt
```

## Usage

To run the Streamlit app, execute:
```bash
streamlit run app.py
```
Navigate to the provided local URL in your browser and interact with the UI to get book recommendations.

## License

This project is licensed under the terms of the MIT License. You can check the license [here](LICENSE).
