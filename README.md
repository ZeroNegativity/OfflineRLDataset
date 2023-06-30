# Research Repository: How to Improve Synergy and Reduce Gap between Off-Policy and Offline RL: A Case Study in Gridworld Setting

This repository contains code developed as part of a research project conducted at Nazarbayev University. The research project focused on improving synergy and reducing the gap between off-policy and offline reinforcement learning (RL) in a gridworld setting.

## Research Details

- Research Name: How to Improve Synergy and Reduce Gap between Off-Policy and Offline RL: A Case Study in Gridworld Setting
- Contributor: Kuanysh Tokayev

## Abstract

The trend in reinforcement learning is leaning towards the adoption of offline policy methods as a solution to address challenges related to high computational costs and the risks associated with data collection in off-policy RL.Compared to off-policy policy RL, offline RL utilizes pre-collected data for more efficient and scalable learning, making it less sensitive to environmental changes. This paper presents a systematic approach for transitioning from off-policy to an offline learning framework in the Gridworld setup, employing Reinforcement Learning (RL). The proposed structure achieves an approximation of the Q value of 93\% and an approximation of the Bellman operator of 88\% using the Multi-Layer Perceptron model. Overall, this document serves as a practical guide to using offline RL for real-world applications, especially for Gridworld-based applications.

## Contents

The repository includes the following code files:

- `Gridworld Setup.ipynb`: Python code implementing the gridworld environment.
- `DataCollection.ipynb`: Python code implementing dataset collection from off-policy RL algorithm.
- `DataPreprocessing.ipynb`: Python code implementing preprocessing of the collected datasets.
- `ModelPerformanceAndResults.ipynb`:Python code implementing various approximations models on the obtained datasets.
- `README.md`: This file, providing an overview of the research repository.
- `Reduction Of Dataset Size.ipynb`: Python code implementing the uniform dataset size reduction and further training of the MLP model on the reduced dataset.

And this repository includes the following dataset files:

- `DatasetBeforeUniform.csv`: Uniformly collected dataset before the preprocessing.
- `DatasetBeforeNonUniform.csv`: Non-Uniformly collected datset before the preprocessing.
- `DatasetAfterUniform.csv`: Uniformly collected dataset after the preprocessing.
- `DatasetAfterNonUniform.csv`: Non-Uniformly collected datset after the preprocessing.
