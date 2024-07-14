# Machine Learning Mini Project 4 - Spring 1403

## Introduction

Welcome to the repository for the **fourth mini project** of the Machine Learning course for the Spring 1403 semester at **Khaje Nasir Toosi University of Technology**. This project explores advanced topics in machine learning, focusing on reinforcement learning algorithms such as Q-learning and Deep Q-Network (DQN).

## Project Overview

This repository includes the code, datasets, and reports for the fourth mini project. The project involves implementing and comparing reinforcement learning algorithms in a simulated environment, specifically the Wumpus World. Detailed instructions and requirements for each part are provided below.

### Important Dates

- **Project Submission Deadline**: 18:00, Monday, June 20, 1403

### Project Requirements

1. **Report**: A comprehensive textual report is required, covering all aspects of the project. This includes explanations and results for each section.
2. **Code Submission**: All code must be uploaded to both the university portal and GitHub.
3. **Structured Presentation**: The report should follow a structured format, with clear explanations for each question and section.
4. **Google Colab Integration**: Ensure your Colab notebooks are set to Public access and include all necessary outputs and code cells.

### Links


- [Google Drive](https://drive.google.com/drive/folders/1EeBXkm5LsYM1jJWfFuhPwsqjQjZTgV5h?usp=drive_link)

## Project Tasks

### Task 1: Q-learning Implementation in Wumpus World

1. **Environment Setup**: Initialize the Wumpus World environment using a 4x4 grid with a fixed window size. Define the observation space and action space, including movements and shooting actions.
2. **Algorithm Implementation**: Implement the Q-learning algorithm. Define the Q-table, reward structure, and learning parameters. Ensure the agent can learn to navigate the environment and avoid hazards.
3. **Training and Evaluation**: Train the agent using Q-learning and evaluate its performance. Adjust the parameters as needed to improve learning efficiency and success rate.

### Task 2: Deep Q-Network (DQN) Implementation

1. **Network Architecture**: Define the architecture for the Deep Q-Network (DQN), including input layers, hidden layers, and output layers. Use appropriate activation functions and optimizers.
2. **Replay Buffer**: Implement a replay buffer to store experiences and use them for training to break the correlation between consecutive experiences.
3. **Training Process**: Train the DQN agent using the experiences stored in the replay buffer. Periodically update the target network to stabilize training.
4. **Evaluation**: Evaluate the performance of the DQN agent and compare it with the Q-learning agent. Use metrics such as cumulative reward and success rate to assess performance.

### Task 3: Enhanced Reward Structure and Additional Scenarios

1. **Modified Reward Structure**: Experiment with different reward structures to encourage the agent to find gold and avoid dangers more effectively. Compare the performance of agents with different reward settings.
2. **Scenario Testing**: Test the agents in various scenarios, including fixed and moving Wumpus, and varying positions of gold and pits. Evaluate how these changes affect the learning and performance of the agents.

## Tools and Libraries

- **Python**: Ensure Python is installed.
- **Libraries**: `numpy`, `pandas`, `gym`, `tensorflow`, `keras`, `pygame`
- **Google Colab**: For running and sharing notebooks.
- **GitHub**: For code versioning and sharing.

## Contribution Guidelines

1. **Fork the Repository**: Make a copy of this repository on your GitHub account.
2. **Clone the Repository**: Download your copy to your local machine.
3. **Create a New Branch**: Work on a separate branch for your changes.
4. **Commit and Push**: Save your changes and push them to your GitHub.
5. **Pull Request**: Submit a pull request to merge your changes into the main repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [OpenAI Gym](https://gym.openai.com/)
- [Google Colab](https://colab.research.google.com/)
- [TensorFlow Documentation](https://www.tensorflow.org/)

---

This README provides a comprehensive guide for anyone looking to understand, contribute to, or use the project. Ensure all links and information are up to date before finalizing the document.