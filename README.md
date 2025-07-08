# Purpose of This Repo

This repo is used to provide access to files for exercises as part of the Introduction to Machine Learning course,, ND 189, course #1


# scikit-Learn Resources

#### https://scikit-learn.org/stable/modules/grid_search.html
#### https://scikit-learn.org/stable/modules/generated/sklearn.cluster.BisectingKMeans.html#sklearn.cluster.BisectingKMeans
#### https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html
#### https://towardsdatascience.com/10-must-know-classification-metrics-for-machine-learning-2ce3a4ad256e/
#### https://scikit-learn.org/stable/api/index.html
#### https://scikit-learn.org/stable/user_guide.html

# Hyperparameter tuning
#### https://neptune.ai/blog/hyperparameter-tuning-in-python-complete-guide
#### https://mlflow.org/
#### https://arxiv.org/abs/1603.06560
#### https://www.automl.org/blog_bohb/

# Model Deployment workflow
![image](https://github.com/user-attachments/assets/9cd9c13a-647f-481d-8142-0c994a9f7562)

##### There are several scenarios where following a strict model deployment will be difficult.

##### In the case of having small datasets, it may be so small that you will be unable to perform a train/test or train/validation/test data split. In these cases, building a ##### model will be difficult regardless, because you may lack the data to even be able to train the model successfully.

 ##### There may be data that is already cleaned and processed. Which in this case, it may be useful and insightful personally to clean and process the data yourself. Often times you can skip doing this step altogether. Mainly because the data is already in an adequate state.

##### Only use new metrics if you understand how they relate to your data

##### Lastly, if using the default parameters of a model work well for you, then spending the time and effort doing a hyperparameter search may not be worth it.
### https://ml-ops.org/content/end-to-end-ml-workflow


## Building workflows using sagemaker
#### https://aws.amazon.com/blogs/machine-learning/building-automating-managing-and-scaling-ml-workflows-using-amazon-sagemaker-pipelines/
