# Traffic Accident Hotspot Prediction using Graph Transformer Networks
Traffic accidents are a major public safety concern, causing numerous fatalities and injuries. Accurate identification and prediction of traffic accident hotspots are crucial for effective planning and intervention strategies.

This project proposes a novel data-driven approach using Graph Transformer Networks (GTNs) to predict traffic accident hotspots, thus advancing road safety management. We extract spatial and temporal features from traffic accident datasets and construct a graph to model complex spatial dependencies. The GTNs capture intricate interactions of accident-prone locations, generating highly accurate predictions.

Our method is compared with state-of-the-art techniques, showing superior precision, recall, and F1-score performance. Our approach provides valuable insights into underlying spatial patterns and contributing factors for traffic accidents, allowing better decision-making by transportation authorities and urban planners.

In conclusion, our research introduces a robust framework for traffic accident hotspot prediction using GTNs, enabling targeted interventions and improved transportation systems.

## Repository Contents
This repository contains the code for the implementation of our proposed approach for traffic accident hotspot prediction using Graph Transformer Networks. The repository consists of the following files:

data_preprocessing.py: This file contains the code for preprocessing the raw traffic accident datasets and extracting the relevant features.
graph_construction.py: This file contains the code for constructing the graph from the preprocessed data.
model_training.py: This file contains the code for training the GTN model on the constructed graph.
evaluation.py: This file contains the code for evaluating the performance of the trained GTN model against state-of-the-art techniques.
Requirements
This project requires the following dependencies:

Python 3.7 or higher
PyTorch 1.7 or higher
NetworkX 2.5 or higher
NumPy 1.19 or higher
Pandas 1.2 or higher
Getting Started
To get started with this project, follow these steps:

Clone this repository to your local machine.
Install the required dependencies by running pip install -r requirements.txt in your terminal.
Run data_preprocessing.py to preprocess the raw traffic accident datasets and extract the relevant features.
Run graph_construction.py to construct the graph from the preprocessed data.
Run model_training.py to train the GTN model on the constructed graph.
Run evaluation.py to evaluate the performance of the trained GTN model against state-of-the-art techniques.
## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
