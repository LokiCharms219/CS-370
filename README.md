# CS-370
Current/Emerging Trends

Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

I worked on a pirate intelligent agent that uses deep Q-learning to learn how to navigate a maze and find the treasure. The starter code included the basic project structure, the maze environment in TreasureMaze.py, the experience replay support in GameExperience.py, the predefined maze, helper functions for displaying and testing the maze, the neural network model structure, and a skeleton for the qtrain() function. The code I created myself was the main deep Q-learning logic inside qtrain(). I completed the training loop so the agent could start from random free cells, observe the current state, choose actions through exploration or exploitation, store experiences, train from replay data, update the target model, decay epsilon, track win rate, and stop once the model successfully solved the maze. I also tested the trained model with the completion check and confirmed that the pirate could reach the treasure consistently.

What do computer scientists do and why does it matter?

Computer scientists solve problems by designing algorithms, building software systems, analyzing data, and creating models that can make decisions or automate tasks. Their work matters because computing systems affect almost every part of modern life. In this project, I saw how computer science concepts such as neural networks, reinforcement learning, and algorithmic decision-making can be applied to a real problem: teaching an agent to make better choices through trial, error, and feedback. Even though the pirate maze is a simple example, the same ideas can apply to larger real-world systems like robotics, autonomous vehicles, routing systems, and game AI.

How do I approach a problem as a computer scientist?

I would first try to understand the goal, the constraints, and the available data or environment. In this project, the goal was not just to move the pirate randomly, but to train it to find an optimal path to the treasure. To solve that, I had to understand how the maze environment worked, how actions changed the agent’s state, how rewards and penalties shaped learning, and how the neural network used past experiences to improve future decisions. I also learned the importance of testing and iteration. The first solution is not always correct, so a computer scientist has to review errors, adjust the logic, test results, and improve the system until it performs reliably.

What are my ethical responsibilities to the end user and the organization?

Basically, I am responsible for creating systems that are reliable, fair, secure, and transparent about their limitations. For the end user, this means the system should behave as expected, avoid unnecessary harm, and protect any data involved. For the organization, this means the solution should be maintainable, tested, and aligned with the intended purpose rather than simply optimized for one narrow metric. In this project, the stakes were low because the agent was only solving a maze, but the same reinforcement learning concepts could be used in real-world systems where poor decisions could affect people. Because of that, developers need to think carefully about training data, reward design, unintended behavior, accountability, and whether the final system can be trusted in the environment where it will be used.
