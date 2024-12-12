# Capstone Project: Train an AI Agent to Play Flappy Bird

This capstone project was an exciting deep dive into the world of reinforcement learning! I took on the challenge of training an AI agent to play the classic game Flappy Bird, combining computer vision and reinforcement learning techniques.

**Project Overview:**

* **Environment Setup:** I started by setting up the Flappy Bird game environment for the AI agent to interact with.
* **Feature Extraction:**  To help the agent "see" the game, I integrated a pre-trained MobileNet V2 model for efficient feature extraction from the game screen.
* **Deep Q-Network (DQN):** I implemented a DQN algorithm to train the agent. This involved:
    * **Experience Replay:** Storing past experiences to improve learning efficiency.
    * **Epsilon Decay:** Gradually reducing random exploration to encourage the agent to exploit learned strategies.

**Challenges Encountered:**

* **Performance Improvement:**  One of the main challenges was achieving significant improvements in the agent's performance. The agent's score only improved slightly, from an average of -5.0 to -4.0.
* **Hyperparameter Tuning:** Finding the optimal hyperparameters for the DQN algorithm and the game environment proved to be a complex and iterative process.

**Tools and Technologies:**

* **W&B (Weights & Biases):** I used W&B for experiment tracking, visualization, and analysis of the agent's training progress.
* **Optuna:**  I leveraged Optuna for automated hyperparameter optimization, helping me explore a wider range of parameter values.

**Key Takeaways:**

Despite the limited success in achieving high scores, this project provided invaluable experience in:

* **Reinforcement Learning:** I gained a deeper understanding of reinforcement learning concepts and how to apply them to a real-world problem.
* **Model Architecture:** I learned how to design and implement a DQN model, including feature extraction using a pre-trained CNN.
* **Parameter Tuning:** I developed skills in hyperparameter tuning and optimization, using tools like Optuna to automate the process.
* **Advanced Logging:** I learned how to use advanced logging tools like W&B to effectively track and analyze experiments.

This capstone project solidified my understanding of reinforcement learning and its practical applications, and it equipped me with valuable skills for future AI projects.
