# CS370_PirateMaze

## Briefly explain the work that you did on this project: 
### 1A. What code were you given? 
I was provided with initial code that set up the maze environment, including classes for the maze itself (TreasureMaze), the game experience (GameExperience), and visualization (show). This code established the environment, reward structure, and interaction mechanics of the game.
### 1B. What code did you create yourself?
I created the main training loop, model architecture, and reinforcement learning algorithm to guide the intelligent agent (pirate) through the maze using deep Q-learning. I implemented the exploration-exploitation trade-off, where the agent learned optimal policies by interacting with the environment and updating its Q-values based on rewards. To finish, I developed completion checking and printing of performance metrics to monitor the agent's learning progress.

## Connect your learning from throughout this course to the larger field of computer science:
### 2A. What do computer scientists do and why does it matter?
Computer scientists, in the simplest terms, create solutions. They use computer science to design algorithms, create software, analyze data, and develop intelligent agents that can work towards solving complex problems. Their work drives technological advancements, from improving everyday software applications to creating cutting-edge artificial intelligence systems. In the context of this project, computer scientists design algorithms that enable agents to learn and make optimal decisions in uncertain environments.
### 2B. How do I approach a problem as a computer scientist?
As a computer scientist, approaching a problem involves understanding the problem domain, breaking down the problem into smaller components, and designing solutions to address each component. It's important to choose appropriate data structures and implement efficient algorithms. In this maze-solving project, I identified the need for reinforcement learning to handle the exploration-exploitation trade-off and implemented deep Q-learning with neural networks to tackle the pathfinding problem.
### 2C. What are my ethical responsibilities to the end user and the organization?
Computer scientists have ethical responsibilities to both end users and the organization. They must ensure that their algorithms and software are transparent, fair, and ultimately do not perpetuate biases. In this project, ethical considerations include designing a reward structure that encourages fair exploration and exploitation, avoiding overfitting that may lead to poor generalization, and ensuring that the agent's actions are ethical within the context of the simulated environment.

