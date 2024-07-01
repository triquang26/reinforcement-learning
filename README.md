# Reinforcement Learning Projects

## Table of Contents
1. [Project 1: Taxi-v3 Q-Learning](#project-1-taxi-v3-q-learning)
    - [Project Purpose](#project-purpose)
    - [Knowledge Contribution](#knowledge-contribution)
    - [Pipeline Architecture](#pipeline-architecture)
    - [Instructions to Run](#instructions-to-run)
    - [Libraries and Versions](#libraries-and-versions)
    - [References and Further Reading](#references-and-further-reading)
2. [Project 2: LunarLander-v2 Policy Gradient](#project-2-lunarlander-v2-policy-gradient)
    - [Project Purpose](#project-purpose-1)
    - [Knowledge Contribution](#knowledge-contribution-1)
    - [Pipeline Architecture](#pipeline-architecture-1)
    - [Instructions to Run](#instructions-to-run-1)
    - [Libraries and Versions](#libraries-and-versions-1)
    - [References and Further Reading](#references-and-further-reading-1)

## Project 1: Taxi-v3 Q-Learning

### Project Purpose
The purpose of this project is to implement a Q-learning algorithm to solve the Taxi-v3 environment from OpenAI Gym. The agent learns to navigate the taxi to pick up and drop off passengers at specified locations within a grid environment.

### Knowledge Contribution
- **Algorithm Implementation**: Detail the implementation of the Q-learning algorithm and how you executed it.
- **Hyperparameter Tuning**: Describe the process of searching for and optimizing hyperparameters.
- **Evaluation and Analysis**: Present the methods used for evaluation and analysis of results.
- **Visualization and Documentation**: Describe the tools and methods you used for visualizing and documenting the project.

### Pipeline Architecture
1. **Environment Setup**: Initialize the Taxi-v3 environment.
2. **Q-Table Initialization**: Create a Q-table to store Q-values for state-action pairs.
3. **Training Phase**: Train the agent using the Q-learning algorithm with an epsilon-greedy policy.
4. **Evaluation Phase**: Evaluate the performance of the trained agent.
5. **Video Recording**: Record a video of the agent's performance.

### Instructions to Run
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/triquang2615/reinforcement-learning.git
    cd reinforcement-learning
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Running Colab**:
    ```bash
    https://drive.google.com/file/d/1cC4qNur-oqFzwFOTleY5SHHaBfDVDnxC/view?usp=sharing
    ```
### Libraries and Versions
- Python 3.8
- NumPy 1.19.2
- Matplotlib 3.3.2
- OpenAI Gym 0.18.0
- tqdm 4.50.2

### References and Further Reading
- [OpenAI Gym Documentation](https://gym.openai.com/docs/)
- [Q-learning Algorithm](https://en.wikipedia.org/wiki/Q-learning)
- [Reinforcement Learning Keynote](https://drive.google.com/file/d/1cn1YwdCApTZIpHm4bParQtfAT6W9I__D/view?usp=drive_link)

## Project 2: LunarLander-v2 Policy Gradient

### Project Purpose
The purpose of this project is to implement a policy gradient algorithm using a neural network to solve the LunarLander-v2 environment from OpenAI Gym. The agent learns to control the lunar lander to land it safely on the landing pad.

### Knowledge Contribution
- **Algorithm Implementation**: Detail the implementation of the policy gradient algorithm and how you executed it.
- **Neural Network Design**: Describe the architecture of the neural network policy and how you designed it.
- **Training and Optimization**: Explain the process of training the neural network using the REINFORCE algorithm and the optimization techniques applied.
- **Evaluation and Analysis**: Present the methods used for evaluation and analysis of results.
- **Visualization and Documentation**: Describe the tools and methods you used for visualizing and documenting the project.

### Pipeline Architecture
1. **Environment Setup**: Initialize the LunarLander-v2 environment.
2. **Policy Network Initialization**: Create a neural network policy to determine actions.
3. **Training Phase**: Train the agent using the REINFORCE algorithm.
4. **Evaluation Phase**: Evaluate the performance of the trained agent.
5. **Video Recording**: Record a video of the agent's performance.

### Instructions to Run
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/triquang2615/reinforcement-learning.git
    cd reinforcement-learning
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Running on Colab**
   ```bash
    https://drive.google.com/file/d/1f-KwFePzsa9Uk1wPFSIOUkPM1ghnqINf/view?usp=sharing
   ```
### Libraries and Versions
- Python 3.8
- NumPy 1.19.2
- Matplotlib 3.3.2
- OpenAI Gym 0.18.0
- PyTorch 1.7.0
- tqdm 4.50.2

### References and Further Reading
- [OpenAI Gym Documentation](https://gym.openai.com/docs/)
- [Policy Gradient Methods](https://spinningup.openai.com/en/latest/spinningup/rl_intro3.html)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [Reinforcement Learning Keynote](https://drive.google.com/file/d/1cn1YwdCApTZIpHm4bParQtfAT6W9I__D/view?usp=drive_link)
