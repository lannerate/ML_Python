# Practical Machine Learning Tutorial with Python

## Regression Training and Testing
Welcome to part four of the Machine Learning with Python tutorial series. In the previous tutorials, we got our initial data, we transformed and manipulated it a bit to our liking, and then we began to define our features. Scikit-Learn does not fundamentally need to work with Pandas and dataframes, I just prefer to do my data-handling with it, as it is fast and efficient. Instead, Scikit-learn actually fundamentally requires numpy arrays. Pandas dataframes can be easily converted to NumPy arrays, so it just so happens to work out for us!

It is a typical standard with machine learning in code to define X (capital x), as the features, and y (lowercase y) as the label that corresponds to the features. As such, we can define our features and labels like so.

