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

![image](https://user-images.githubusercontent.com/81223941/160312097-00d9efab-ab3b-4cbf-8eaf-ea5e3110e61e.png)
![image](https://user-images.githubusercontent.com/81223941/160312132-2aef77c2-fb14-4916-9b0a-a12d4f5cc9d1.png)
![image](https://user-images.githubusercontent.com/81223941/160312199-b02af0ae-d97c-4bad-a32d-2ec556decbd0.png)

## Resources Used

I looked at several sources to understand how the models work and how I can improve them. They are linked here:

https://medium.com/analytics-vidhya/prediction-and-data-visualization-of-breast-cancer-using-k-nearest-neighbor-knn-classifier-df7adadc4872

https://www.upgrad.com/blog/random-forest-classifier/

## Limitations

The final model used has not been fine tuned for simplicity. This project can be further improved by hyperparameter tuning the random forest model chosen. Also, in this project, I did not consider the words used in the ad topic lines. Thus, it can be improved by splitting the ad topic line into a word matrix and looking at what words influenced people to click.

## License

MIT License
