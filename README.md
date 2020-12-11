# project4_mrs
This is the GitHub repo for Project 4: Movie Recommendation System (MRS)



#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to create seven models, using three different types of recommendation techniques, to build a movie recommendation system which recommend top 10 movies to the user.

### Libraries Needed
| Libraries      |             |              |
| :----------- | :----------- | :----------- |
| numpy| pandas | matplotlib |
| scipy | sys | ast |
| random | seaborn | plotly |
| sklearn | math | time |
| pickle | os | surprise |


### Technologies
* Python 3
* Anaconda 3
* Jupyter Notebook (6.0.3)
* Surprise


## 1. Data Acquisiotion
Three datasets were used:
* movies_metadata.csv: The main file containing all the information of the movies.

  [movies_matadata.csv](movies_metadata.csv)
* ratings_small.csv: This file contains 100,004 ratings of 9,066 movies from 671 users.

  [ratings_small.csv](ratings_small.csv)
* links_small.csv: This file contains TMDB and IMDB ids of the movies in ‘ratings_small.csv’.

  [datasets_links_small.csv](datasets_links_small.csv)


## 2.	Data Preparation and Exploration
This task aims to transform the raw data into the format suitable for various downstream purposes. 
#### Data Checking 
Detects and cleans data errors/issues.

[S2.2	Data Checking and Reporting](S2.2%20Data%20Checking%20and%20Reporting.ipynb)
#### Data Filtering 
Selects subsets of data to keep and carrying out appropriate transformations.

[S2.3.1 Data  Filtering](S2.3.1%20Data%20Filtering.ipynb)
#### Data Integration
Combines the data from the different datasets.

[S2.3.2	Data Integration](S2.3.2%20Data%20Integration.ipynb)
#### Data Exploration
Explores data to gain a deeper understanding.

[S2.4	Data Exploration & Reporting](S2.4%20Data%20Exploration%20%26%20Reporting.ipynb)



## 3. Data Modelling

Developing and training models on the data, testing them and evaluating their performances.
#### Training and Test Sets
Generates train and test sets. User may set the size by changing ‘test_sample_size’.

[S3.2 Creating Training and Test Sets](S3.2%20Creating%20Training%20and%20Test%20Sets.ipynb)
#### Content-based Model
Uses movie features to recommend other movies similar to what the user likes.

[S3.3 Content-Based Filtering](S3.3%20Content-Based%20Filtering.ipynb)
#### Item-based collaborative filter (memory-based)
Uses user rating data to compute similarity between movies.

[S3.4.1 Memory-based Collaborative Filter (Item-based)](S3.4.1%20Memory-based%20Collaborative%20Filter%20(Item-based)%20.ipynb)
#### User-based collaborative filter (memory-based)
Uses movie rating data to compute similarity between users.

[S3.4.2 Memory-based Collaborative Filter (User-based)](S3.4.2%20Memory-based%20Collaborative%20Filter%20(User-based).ipynb)
#### Model-based collaborative filter
Extracts some information from the dataset of ratings to use as the model to make recommendation.

[S3.4.3 Model-based Collaborative Filter](S3.4.3%20Model-based%20Collaborative%20Filter.ipynb)
#### Hybrid Approach A
Combines content-based and item-based collaborative filter, applies RandomForest regressor to gain better performance.

[S3.5.1 Hybrid approach A (CB & Item-Based CF)](S3.5.1%20Hybrid%20approach%20A%20(CB%20%26%20Item-Based%20CF)%20.ipynb)
#### Hybrid Approach B
Combines content-based and model-based collaborative filter, applies Linear Regressor to gain better performance.

[S3.5.2 Hybrid Approach B (CB & Model Based CF)](S3.5.2%20Hybrid%20Approach%20B%20(CB%20%26%20Model%20Based%20CF)%20.ipynb)
#### Hybrid Approach C
Combines content-based and user-based collaborative filter, applies Linear Regressor to gain better performance.

[S3.5.3 Hybrid Approach C (CB and User-Based CF)](S3.5.3%20Hybrid%20Approach%20C%20(CB%20and%20User-Based%20CF)%20.ipynb)
#### Performance evaluation, comparison and analysis
Performance measured in root mean square error and mean absolute error.

[S3.6 Performance Evaluation, Comparison and Analysis](S3.6%20Performance%20Evaluation.ipynb)
#### Recommending top 10 movies
Predicts ratings of all unrated movies for each user and recommends 10 movies with the highest predicted ratings.

[S3.7 Recommending Top-10 Movies](S3.7%20Recommending%20Top-10%20Movies.ipynb)






## Team Members

|Name     |  Student ID   | 
|---------|-----------------|
|[Nakib Al Kauser](https://github.com/nakib-kauser)| 102848613        |
|[Promita Shabnam Khan](https://github.com/PromiSKhan) |     102839361    |
|[Asif Rana](https://github.com/asifranaar01)| 10866893   |



### Contact
* nakib.kauser@gmail.com  
* promiskhan@gmail.com
* asifranaar01@gmail.com
* Feel free to contact us with any questions or if you are interested in contributing!
