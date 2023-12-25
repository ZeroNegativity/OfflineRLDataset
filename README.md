# Research Repository: How to Improve Synergy and Reduce Gap between Off-Policy and Offline RL: A Case Study in Gridworld Setting

This repository contains code developed as part of a research project conducted at Nazarbayev University. The research project focused on improving synergy and reducing the gap between off-policy and offline reinforcement learning (RL) in a gridworld setting.

## Research Details

- Research Name: How to Improve Synergy and Reduce Gap between Off-Policy and Offline RL: A Case Study in Gridworld Setting
- Contributor: Kuanysh Tokayev

## Abstract

In the emerging landscape of off-policy reinforcement learning (RL), challenges arise due to the significant costs and risks tied to data collection. To address these issues, there is an alternative path for transitioning from off-policy to offline RL, known for its fixed data collection practices. This stands in contrast to online algorithms, which are sensitive to changes in data during the learning phase.However, the inherent challenge of offline RL lies in its limited interaction with the environment, resulting in inadequate data coverage.Hence, we underscore the convenient application of offline RL, 1) starting from the collection of a static dataset, 2) followed by the training of offline RL agents, and 3) culminating with testing in the same environment as off-policy RL methodologies. This involves the utilization of a uniform dataset gathered systematically via non-arbitrary action selection, covering all possible states of the environment. Utilizing the proposed approach, the Offline RL agent employing a Multi-Layer Perceptron (MLP) achieves a testing accuracy that falls within 1\% of the results obtained by the off-policy RL agent.
Moreover, we provide a practical guide with datasets, offering valuable tutorials on the application of Offline RL in Gridworld-based real-world applications.

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
