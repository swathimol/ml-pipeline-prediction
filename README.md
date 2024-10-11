# Comparative Study: Machine Learning Model with and without Pipeline

Machine learning pipelines allow for efficient workflows, making it easier to preprocess data, train models, and evaluate results. This project showcases how to implement such a pipeline in Python using popular ML libraries like `scikit-learn`, `pandas`, and `numpy`.

This repository contains a comparative study demonstrating the advantages of using a machine learning (ML) pipeline versus writing separate preprocessing and model-building code. The goal is to show how a pipeline simplifies the process, improves code readability, and avoids repetition.

### Overview
The comparison focuses on two approaches:

###### Without a Pipeline: Manual preprocessing, model training, and evaluation done step by step.
##### With a Pipeline: Combining preprocessing, model training, and evaluation into a streamlined scikit-learn pipeline.


## Key Advantages of Using a Pipeline:

Simplifies Workflow: A pipeline integrates data preprocessing and model training in a single sequence.
Reduces Code Complexity: Minimizes the need for repetitive code by chaining multiple steps together.
Improves Code Readability: Makes the code cleaner and easier to understand.
Prevents Data Leakage: Ensures that data preprocessing is applied consistently to both training and testing data.
