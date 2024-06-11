

# Sales Conversation Dataset Generation

## Overview

This project aims to generate an extensive sales conversation dataset for training language models and generative AI systems. The dataset is created based on the guidelines provided in the problem statement, focusing on contextual relevance, coherence, creativity, engagement, and ethical considerations.

## Dataset Generation Process

The dataset generation process involves the following steps:

1. Topic Selection: Topics related to various products or services are chosen to simulate sales conversations effectively.

2. Question Formulation: Questions relevant to each topic are formulated to initiate the sales conversation.

3. Salesman Response Generation: Salesman responses are generated based on the selected topic and corresponding question. The responses aim to provide information about the product or service, address customer queries, and engage potential clients.

4. User Response Generation: User responses are generated to simulate customer interaction. These responses may include queries, feedback, concerns, or expressions of interest.

5. Dataset Compilation: The generated salesman and user responses are compiled into a structured dataset format, ensuring consistency and organization.

## Evaluation Criteria

The generated dataset is evaluated based on the following criteria:

- Minimum Data Size Requirement: The dataset should contain a minimum of 100 sets of dialogues.
- Contextual Relevance and Understanding: Conversations should be relevant to the sales context and demonstrate an understanding of the product or service being offered.
- Coherence, Fluency, and Readability: Responses should maintain a seamless flow, exhibit grammatical accuracy, and adhere to principles of effective communication.
- Creativity and Engagement: Conversations should showcase creativity in capturing the interest of prospective clients and presenting the product in novel, captivating ways.
- Toxicity and Bias Mitigation: Conversations must be devoid of toxic language, personal attacks, or discriminatory content. Bias and stereotypes must be meticulously avoided.
- Accuracy and Completeness of Information: The information conveyed in the sales pitch should be accurate and complete, providing relevant details about the product or service.

## Usage Instructions

The dataset is provided in CSV format, with columns for Salesman, User, and TimeStamp. Users can utilize this dataset for training language models, generative AI systems, conversational agents, and other natural language processing tasks.

## License

This dataset is released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode). Users are free to share and adapt the dataset under the terms of this license.

---

# Neural Network Implementation and Visualization

## Overview

This project involves the implementation of neural networks for specific tasks, such as logic gate classification or MNIST digit classification. Additionally, it includes the creation of a visualization interface similar to TensorFlow Playground for interactive exploration of the neural network model.

## Neural Network Implementation

### Task Selection

Participants can choose between two tasks:
- Option A: Logic Gate Implementation: Implement a neural network for a logic gate (AND, OR, XOR, etc.).
- Option B: MNIST Digit Classification: Implement a neural network to classify handwritten digits from the MNIST dataset.

### Implementation Steps

1. Neural Network Model Definition: Define the architecture of the neural network model using PyTorch.
2. Dataset Preparation: Prepare the dataset for the chosen task (logic gate or MNIST).
3. Model Training: Train the neural network model on the training data using appropriate loss functions and optimizers.
4. Model Evaluation: Evaluate the trained model on the test data and report relevant metrics such as accuracy.

## Visualization Interface

### Design Considerations

- Design a visualisation similar to TensorFlow Playground that allows users to interact with the neural network model.
- Enable users to adjust hyperparameters (e.g., learning rate, number of hidden units) and observe their effects on the model's performance.

### Visualization Features

- For Logic Gate:
  - Visualize the decision boundary learned by the model.
  - Allow users to input different logical conditions and see the model’s predictions.

- For MNIST:
  - Visualize the weights of the first layer and how they change during training.
  - Provide a way to input custom digit images and see the model’s predictions.

## Usage Instructions

The code for neural network implementation and visualization interface is provided in the repository. Users can run the `run.py` script to train the neural network model and launch the visualization interface. Detailed instructions on usage are provided in the README file.

## License

This project is released under the [MIT License](https://opensource.org/licenses/MIT). Users are free to use, modify, and distribute the code for both non-commercial and commercial purposes.

---
