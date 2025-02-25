# Machine Learning Zoomcamp

<a href="https://datatalks.club/courses/2021-winter-ml-zoomcamp.html"><img src="../images/zoomcamp.jpg" /></a>

* [Course overview video](https://www.youtube.com/watch?v=rowoDjPc8HU) and [slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-course-overview-and-logistics)
* [Course playlist](https://www.youtube.com/watch?v=rowoDjPc8HU&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR)
* [Register for the course here](https://airtable.com/shr6Gz46UZCgJ9l6w)
* [Public calendar](https://calendar.google.com/calendar/?cid=cGtjZ2tkbGc1OG9yb2lxa2Vwc2g4YXMzMmNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ) (subscribing works from desktop only)
* Register at [DataTalks.Club](https://DataTalks.Club) and join the `#course-ml-zoomcamp` channel to talk about the course 


## 1. [Introduction to Machine Learning](01-intro/)

- 1.1 [Introduction to Machine Learning](01-intro/01-what-is-ml.md)
- 1.2 [ML vs Rule-Based Systems](01-intro/02-ml-vs-rules.md)
- 1.3 [Supervised Machine Learning](01-intro/03-supervised-ml.md)
- 1.4 [CRISP-DM](01-intro/04-crisp-dm.md)
- 1.5 [Model Selection Process](01-intro/05-model-selection.md)
- 1.6 [Setting up the Environment](01-intro/06-environment.md)
- 1.7 [Introduction to NumPy](01-intro/07-numpy.md)
- 1.8 [Linear Algebra Refresher](01-intro/08-linear-algebra.md)
- 1.9 [Introduction to Pandas](01-intro/09-pandas.md)
- 1.10 [Summary](01-intro/10-summary.md)
- 1.11 [Homework](01-intro/homework.md)

## 2. [Machine Learning for Regression](02-regression/)

- 2.1 [Car price prediction project](02-regression/01-car-price-intro.md)
- 2.2 [Data preparation](02-regression/02-data-preparation.md)
- 2.3 [Exploratory data analysis](02-regression/03-eda.md)
- 2.4 [Setting up the validation framework](02-regression/04-validation-framework.md)
- 2.5 [Linear regression](02-regression/05-linear-regression-simple.md)
- 2.6 [Linear regression: vector form](02-regression/06-linear-regression-vector.md)
- 2.7 [Training linear regression: Normal equation](02-regression/07-linear-regression-training.md)
- 2.8 [Baseline model for car price prediction project](02-regression/08-baseline-model.md)
- 2.9 [Root mean squared error](02-regression/09-rmse.md)
- 2.10 [Using RMSE on validation data](02-regression/10-car-price-validation.md)
- 2.11 [Feature engineering](02-regression/11-feature-engineering.md)
- 2.12 [Categorical variables](02-regression/12-categorical-variables.md)
- 2.13 [Regularization](02-regression/13-regularization.md)
- 2.14 [Tuning the model](02-regression/14-tuning-model.md)
- 2.15 [Using the model](02-regression/15-using-model.md)
- 2.16 [Car price prediction project summary](02-regression/16-summary.md)
- 2.17 [Explore more](02-regression/17-explore-more.md)
- 2.18 [Homework](02-regression/homework.md)


## 3. Machine Learning for Classification

- Churn prediction project
- Initial data preparation
- Setting up the validation framework
- EDA
- Feature importance: Churn rate
- Feature importance: Risk ratio
- Feature importance: Mutual information
- Feature importance: Correlation
- One-hot Encoding
- Logistic regression
- Logistic regression with sklearn
- Using logistic regression (?)
- Logistic regression - interpretation
- Applying logistic regression
- Summary
- Explore more
- Homework

## 4. Evaluation Metrics for Classification

- Evaluation metrics
- Accuracy
- Baseline solution
- Confusion table
- Calculating the confusion table
- Precision and recall
- Receiver operating characteristic (ROC)
- ROC: Random baseline
- ROC: Ideal model
- The ROC Curve
- ROC curve with skilearn
- Area under the ROC Curve (AUC)
- intepretation of AUC
- K-fold cross-validation
- Selecting the best parameter C
- summary
- explore more
- homework

## 5. Deploying Machine Learning Models

- Using the model
- pickle
- Deploying a model as a Web Service
- Introduction to Flask
- Model serving with flask
- Managing dependencies with Pipenv
- Introduction to Docker
- Testing it locally
- AWS beanstalk
- summary
- explore more
- homework

## 6. Decision Trees and Ensemble Learning

- Credit risk scoring project
- Data cleaning
- Data preparation
- Decision trees
- Decision tree learning algorithm
- impurity
- split
- stopping criteria
- Decision trees parameter tuning
- Ensembles and random forest
- Random forest in sklearn
- Random forest parameter tuning
- Gradient boosting
- eXtreme Gradient Boosting - XGBoost
- training
- watchlist
- XGBoost parameter tuning
- learning rate
- max_depth
- min_child_weight
- Testing the final model
- summary
- explore more
- homework

## 7. Midterm Project

## 8. Neural Networks and Deep Learning

- Clothes classification project
- TensorFlow and Keras
- loading the images
- etc
- Using a pre-trained model
- CNNs: convolutional layers
- CNNs: dense layers
- Transfer learning
- Creating the clothes classification model
- Keras functional components
- optimizer
- training the model
- Learning Rate
- Model checkpointing
- Adding more layers
- Dropout
- Data augmentation
- Training a larger clothes classification model
- Using the model with Keras
- summary
- explore more
- homework

## 9. Serverless Deep Learning

- intro
- serverless and AWS Lambda
- tensorflow-lite
- converting the model to TF-lite
- preparing images
- using the model in TF-lite
- putting everything together in a Lambda function
- preparing the docker image
  - testing the image locally
- pusting the image to ECR
- creating the lambda function
- creating the API gateway
- summary
- explore more
- homework

## 10. Kubernetes and TensorFlow-Serving

- intro, serving architecture overview
- saved_model format
- tensorflow-serving
  - running TF-serving locally
- communicating with tf-serving from Jupyter
- creating the gateway service
- introduction to Kubernetes
- creating a cluster on AWS (article)
- preparing the images
  - the TF-serving image
  - the gateway image
- deploying to Kubernetes
  - deployment for tf-serving
  - service for tf-serving
- creating the gateway on Kubernetes
  - deploymnet
  - servince - load balancer
- testing it
- deleting the cluster
- summary
- explore more
- homework

## 11. Kubeflow and KFServing

- intro
- installing Kubeflow on AWS
- preparing the model: uploading to S3
- deploying TF models with KF-serving
- accessing the model
- tranformers
- testing it
- deleting the cluster
- summary
- explore more
- homework - no homework

## 12. Capstone Project

## 13. Article

