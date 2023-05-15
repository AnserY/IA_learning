# Deploy Machine Learning Models with Django

This is a source code from the tutorial available at [deploymachinelearning.com](https://deploymachinelearning.com)


- It keeps information about many ML models in the web service. There can be several ML models available at the same endpoint with different versions.

- There can be many endpoint addresses defined.

- It stores information about requests sent to the ML models, this can be used later for model testing and audit.

- It has tests for ML code and server code. 

- It run [A/B tests](https://medium.com/@henoktilaye7/a-b-testing-using-machine-learning-eb6bbb8d91e7).

## The code structure

In the `research` directory there are:

- Code for training machine learning models on Adult-Income dataset [link](https://github.com/pplonski/my_ml_service/blob/master/research/train_income_classifier.ipynb)
 
- Code for simulating A/B tests [link](https://github.com/pplonski/my_ml_service/blob/master/research/ab_test.ipynb).

- In the `backend` directory there is Django application.

- In the `docker` directory there are dockerfiles for running the service in the container.



