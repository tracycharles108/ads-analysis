# ads-analysis

Created by Tracy Charles

## Description 

A basic data analysis project on a dataset of advertisements that include features such as topic lines and timestamps of ads as well as demographics of consumer. In this project, I created visualizations to understand correlations of the variables and models to predict the clicks of advertisements.

## Dataset

The dataset is public on Kaggle and can be found here: https://www.kaggle.com/datasets/gopalchettri/advertisement

## Learning Goals and Outcomes

I created this project to deepen my understanding of machine learning models and their use cases. In this project, I used K-Nearest Neighbors and Random Forest at a surface level. I also learned how to use modules like `pycountry_convert` and `datetime`.

## Select Visualizations

I used `matplotlib.pyplot` and `seaborn` to make data visualizations. Visualizations shown here are just some of the ones created on this project.

![image](https://user-images.githubusercontent.com/81223941/160311291-447924b9-d48f-425a-9a19-89372f5fbb74.png)
![image](https://user-images.githubusercontent.com/81223941/160311364-fbaff2ec-7067-4a72-9da1-d1c582bf6c90.png)
![image](https://user-images.githubusercontent.com/81223941/160311321-a213f81f-ec16-4f3b-8092-33a951ad2c73.png)

## Resources Used

I looked at several sources to understand how the models work and how I can improve them. They are linked here:

https://medium.com/analytics-vidhya/prediction-and-data-visualization-of-breast-cancer-using-k-nearest-neighbor-knn-classifier-df7adadc4872
https://www.upgrad.com/blog/random-forest-classifier/

## Limitations

The final model used has not been fine tuned for simplicity. This project can be further improved by hyperparameter tuning the random forest model chosen. Also, in this project, I did not consider the words used in the ad topic lines. Thus, it can be improved by splitting the ad topic line into a word matrix and looking at what words influenced people to click.

## License

MIT License
