# MovieLens Data Visualization Project

## Introduction

This project focuses on the visualization of the MovieLens dataset to explore patterns and insights in movie ratings. Inspired by the Netflix Prize challenge that sought to improve the accuracy of movie recommendations, this project aims to understand user preferences through visual analysis rather than predictive modeling. By leveraging the MovieLens dataset, we create a series of visualizations to analyze movie ratings and genres, providing a deeper understanding of user behavior and movie characteristics.

## Background

The Netflix Prize, launched in late 2006, challenged participants to develop a recommender system to predict user movie ratings more accurately than Netflix's own system, Cinematch. The challenge concluded in 2009 with the victory of "BellKor’s Pragmatic Chaos" team. While the original challenge focused on prediction, our project shifts the focus towards visualization, using the smaller but rich MovieLens Dataset.

## Dataset

The MovieLens dataset includes 100,000 ratings from 943 users across 1682 movies, ensuring each user has rated at least 20 movies. The dataset is divided into:

- **movies.csv**: Contains movie details, including ID, title, and genres (1682 movies).
- **data.csv**: Includes user ID, movie ID, and ratings (100,000 instances).
- **train.csv**: Training set with 90,000 instances.
- **test.csv**: Testing set with 10,000 instances.

Each movie is associated with various genres, represented by binary indicators. Ratings are integer values from 1 to 5.

## Visualization Goals

The project aims to produce visualizations that offer insights into:

- The distribution of movie ratings.
- Genre popularity and user preferences.
- Relationships between different genres.
- Any other patterns or trends discernible from the dataset.

## Tools and Technologies

- Python for data processing and analysis.
- Libraries such as Matplotlib, Seaborn, or Plotly for creating visualizations.

## Getting Started

To replicate this project or explore the visualizations:

1. Clone this repository.
2. Ensure you have Python installed, along with necessary libraries (e.g., Pandas, Matplotlib).
3. Download the MovieLens dataset from the provided links.
4. Run the visualization scripts to generate insights.

## Project Work Distirbution
Team Members: Jonayet Lavin, A. Yusuf Kavranoglu, Dereje Lambert, Ismail Abouamal
Work Division:
• Jonayet worked on Data Preprocessing and Basic Visualizations, as well as the off-the-shelf imple-
mentation for Matrix Factorization Visualizations.
• Ismail worked on the non-bias implementation for Matrix Factorization Visualizations and its com-
parison with the biased version.
• Dereje worked on the bias implementation for Matrix Factorization Visualizations and comparisons
between methods.
• Yusuf worked on improving the bias implementation for Matrix Factorization Visualizations and com-
parison of model performances.

## License

[MIT License](LICENSE)

