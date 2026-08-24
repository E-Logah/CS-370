# CS 370: Current and Emerging Trends in Computer Science

## Project Two – Pirate Intelligent Agent

### Briefly explain the work that you did on this project. What code were you given? What code did you create yourself?

For Project Two, I worked with a treasure hunt game in which an intelligent pirate agent learns how to navigate through a maze and reach the treasure. The goal was to apply reinforcement learning and neural networks to create an agent capable of determining an effective path through the environment.

I was provided with starter code, including the TreasureMaze.py and GameExperience.py classes. TreasureMaze.py represented the maze environment and controlled how the pirate interacted with it. GameExperience.py stored experiences from previous actions so that the agent could learn from them. I was also provided with the basic neural network structure and supporting functions.

My main responsibility was completing the deep Q-learning training algorithm in the qtrain() function. I implemented the process that allowed the pirate to repeatedly interact with the maze, select valid actions, receive rewards, store experiences, and improve its decisions through training. The algorithm balanced exploration and exploitation so the agent could explore different paths while gradually using what it learned to select better actions. I also used experience replay and monitored the win rate while training the neural network. Finally, I verified the trained model to make sure the pirate could successfully reach the treasure rather than relying only on a single successful training result.

## What do computer scientists do and why does it matter?

Computer scientists use computational methods to analyze problems and design solutions that can be implemented through software and technology. Their work involves much more than simply writing code. They identify requirements, design algorithms, evaluate different approaches, test solutions, analyze results, and continuously improve systems.

This project demonstrated why that work matters. Instead of explicitly programming every movement the pirate should make, I developed a system that could learn from its interactions with an environment. Reinforcement learning techniques like these can be applied to much larger real-world problems, including robotics, cybersecurity, autonomous systems, optimization, and artificial intelligence. Computer scientists help transform these concepts into practical systems that can solve problems efficiently and reliably.

## How do I approach a problem as a computer scientist?

I approach problems by first understanding the desired outcome and then breaking the larger problem into smaller, manageable components. In this project, I needed to understand the maze environment, the possible actions available to the pirate, the reward system, the neural network, and the relationship between exploration and exploitation before completing the training algorithm.

I then used an iterative process of implementation, testing, observation, and improvement. Instead of assuming that a successful run meant the algorithm was finished, I examined how the agent performed over repeated training episodes. The project reinforced the importance of testing a solution under different conditions and using measurable results to determine whether it actually solves the original problem. This systematic approach is something I can apply to future software development, cybersecurity, and artificial intelligence projects.

## What are my ethical responsibilities to the end user and the organization?

As a computer scientist, I have an ethical responsibility to develop systems that are secure, reliable, transparent, and designed with the interests of users and organizations in mind. This includes protecting sensitive information, respecting privacy, reducing unnecessary risks, testing systems thoroughly, and being honest about the limitations of a system.

Artificial intelligence creates additional responsibilities because decisions may be influenced by training data, algorithms, and reward structures. Developers should evaluate whether an intelligent system behaves as intended rather than assuming that a high performance measurement automatically means that the system is reliable. In this project, for example, achieving a high win rate was not enough by itself. The trained pirate also needed to be tested to determine whether it could consistently reach the treasure from different valid starting positions.

For an organization, I also have a responsibility to produce maintainable and properly documented software and to consider security throughout the development process. For end users, I have a responsibility to create technology that functions as expected while protecting their information and avoiding preventable harm. These responsibilities are essential for maintaining trust in software and artificial intelligence systems.
