SupervisedLearning5509

DTSA Supervised Learning Class Final Project 

CU Boulder DTSA-5509

# Determining Water Potability Final Project

This is a project to classify water potability using supervised learning techniques. First, we will explore the data then train a few models. We will compare the models and choose the best one. Finally, we will suggest further study which could be performed using the same data. 

Data can be found here: https://www.kaggle.com/datasets/adityakadiwal/water-potability
The downloadable CSV file: https://www.kaggle.com/datasets/adityakadiwal/water-potability/download

This data was chosen because it has good usability rating and more than 3000 entries which will allow us to analyze the data more completely.


## Conclusion

We have taken data from online, imputed and standardized it to find the best supervised learning model. We tried four generic models and chose the top two models to fine-tune and test. After testing mutliple SVM and Random Forest models, we found that the best model was a random forest classification model which resulted in 66% testing accuracy. We also see that the precision for both classes is about the same, while recall and f1-scores are quite different. There may be a few reasons for such results, such as poor data to start with or not enough data. In addition, there could be factors beyond the given data that impact water quality. Further research is needed to find a better model, perhaps using a unsupervised learning technique and/or a neural network. It is important to not that even the best models on Kaggle failed to surpass our model's performance, with the highest accuracy I could find was only at 76% using a stochastic gradient descent classifier or a bagging classifier. The concensus is that perhaps these are not good predictors of what water is good for drinking or not.
