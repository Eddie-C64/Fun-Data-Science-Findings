# Movie Recommendation System

## Overview
The code uses the [lightfm](https://github.com/lyst/lightfm) recommender system library to train a hybrid content-based + collaborative algorithm that uses the WARP loss function on the [movielens](http://grouplens.org/datasets/movielens/) dataset. The movielens dataset contains movies and ratings from over 1700 users. Once trained, our script prints out recommended movies for whatever users from the dataset that we choose to terminal.

## Dependencies

* numpy (http://www.numpy.org/)
* scipy (https://www.scipy.org/)
* lightfm (https://github.com/lyst/lightfm)

Install missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

## Usage

Once you have your dependencies installed via pip, run the script in terminal via

```
ipython Movie_Recommendation_System.ipynb
```

If you still have dependency version issues, use [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/). 

## Challenge
Use 3 different loss functions (so 3 different models), compare their results, and then only print the recommendations (products, songs, tv shows, etc.) for the best one. You'll 
find the available loss functions [here](https://github.com/lyst/lightfm/blob/master/lightfm/lightfm.py#L35).