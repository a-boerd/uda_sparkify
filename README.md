# Sparkify project

1. [Project Motivation](#motivation)
2. [File Descriptions](#files)
3. [Results](#results)
4. [Licensing, Authors, and Acknowledgements](#licensing)




## Project Motivation<a name="motivation"></a>

For this project, the goal was to be able to predict wether or not a user would cancel his subscription to the streaming-platform "sparkify". The scope of this repository is only to show what was done with 1% of the data (without deploying a spark cluster and working with 100% of the data).


## File Descriptions <a name="files"></a>

The .ipynb file where the exploratory analysis/cleaning/feature engineering and model training was done can be found in this directory.

Also there is a blog post describing the project under this [link](https://medium.com/@boerdolf/should-i-stay-or-should-i-go-3acbd49b29c8).

## Results<a name="results"></a>

With a F1 score of .375 on the test data the gradient boosted tree model yielded the best results. However these results are certainly still far away from being decent.
Potential ways to improve results are:
1. Increase the number of features.
2. While gridsearch was used already, there might still be room for improvement trying it on other parameters.
3. Using a larger part of the dataset and not only 1% or a little more than 200 users.

Please check the blog post mentioned above to get an overview and more details on all the trained models.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Thanks to [udacity](https://www.udacity.com) for providing the dataset!
