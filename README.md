# Projects Overview

Welcome to a collection of projects that cover various aspects of artificial intelligence, machine learning, distributed computing, and data analysis. Below, you'll find an overview of each project with links to their respective files and documentation.

## Project 1: Basic Ray Tutorial and Deep Q Learning

### Overview

In this project, we explore the capabilities of Ray, a powerful distributed computing framework. The tutorial is divided into three parts:

1. **Introduction to Ray**: We demonstrate how Ray can speed up Python functions by parallelizing and distributing them across nodes. A simple decorator function enables regular Python functions to run in a parallelized manner.

2. **Cart-Pole Problem**: In this section, we focus on solving the cart-pole problem using Ray. The goal is to keep a pole fixed on a cart while preventing it from falling. The tutorial runs in a Jupyter notebook and showcases the full capabilities of Ray and Ray Tune.

3. **Custom RL Environment**: We demonstrate how to create a custom reinforcement learning environment, simulating a robot walking down a corridor. This section provides insights into creating custom environments for RL projects.

### [Link to Project 1 Files](https://github.com/jddavis-ai/rev-3-advanced-data-science/blob/main/Rev3_Advanced_Data_Science-main/Basic_Ray_Tutorial_with_Deep_Q_Learning.ipynb)

## Project 2: Analysis of Polio Incidences Tutorial using XGboost and Dask 

### Overview

This tutorial is designed for beginners and focuses on analyzing polio incidences. We primarily use CPUs in this notebook, but GPUs can be utilized in other approaches, which we cover in a separate tutorial. Here's what this tutorial covers:

1. **Machine Learning with sklearn**: We use the sklearn and xgboost libraries to perform machine learning on a dataset containing polio incidence ratios by year, starting in 1928. We create a simple classifier to predict incidence ratios in the test dataset.

2. **Comparison of Different Regressors**: We explore the canonical scikit-learn tutorial on the comparison of different regressors (classifiers) on predefined datasets to learn about sklearn and dask.

3. **xgboost and Dask**: We delve into using xgboost and dask to enhance our machine learning capabilities.

4. **Creating a Classifier**: We use xgboost's tree method, 'hist,' to create a classifier for our polio data.

### [Link to Project 2 Files](https://github.com/jddavis-ai/rev-3-advanced-data-science/blob/main/Rev3_Advanced_Data_Science-main/Dask_Tutorial-Distributed-Examples.ipynb)

## Project 3: What is Spark?

### Overview

Spark is a powerful data analytics platform for processing large datasets. This project introduces you to the world of Spark and its applications. We cover the following key aspects:

1. **Introduction to Spark**: Spark is a data analytics platform that can work with Hadoop, making it ideal for large datasets. It truly shines when dealing with datasets in the gigabytes or more. We discuss Spark's resilient distributed datasets (RDDs) and its integration with Python libraries like pandas.

2. **Calculating Pi with Spark**: We illustrate the power of Spark by calculating pi. Each Spark worker node plays a crucial role in parallelism and distribution of work.

3. **Initiating and Testing Spark Workers**: We demonstrate how to set up and test Spark workers, making Spark a useful tool for large data analysis.

### [Link to Project 3 Files]([project3_files/](https://github.com/jddavis-ai/rev-3-advanced-data-science/blob/main/Rev3_Advanced_Data_Science-main/PySpark%20Beginner%20Tutorial.ipynb))

## Project 4: A "Hello World" Example of MPI on Domino

### Overview

In this example project, we compare using a distributed system on GPUs with calculating pi on a single GPU. For both instances, we use a simple inference to approximate pi, demonstrating a significant reduction in time when using distributed systems.

MPI (Message Passing Interface) is a powerful tool used in supercomputing. We provide a "hello world" example to introduce you to MPI. For more complex MPI examples, feel free to reach out to jennifer.d.davis.ai@gmail.com.

### [Link to Project 4 Files](https://github.com/jddavis-ai/rev-3-advanced-data-science/blob/main/Rev3_Advanced_Data_Science-main/Calculate_Pi_MPI.ipynb)

## Additional Information

Feel free to explore each project's files and documentation by following the provided links. Each project offers valuable insights into various aspects of AI, machine learning, distributed computing, and more. If you have any questions or need further assistance, don't hesitate to reach out.

Enjoy your journey through these projects!
