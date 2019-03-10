# drlnd-navigation
My implementation of the Navigation Project in the scope of Udacity's Deep Reinforcement Learning Nanodegree

The task was to train an agent to master a task using the PyTorch package (https://pytorch.org/).
The complete solution is included in the my_solution.ipnyb

# Installation
In order to run the ipython notebook you'll need a a working Python environment with a couple of different non-standard libraries.
A simple way to get everything set-up correctly is:
- Install Anaconda from https://www.anaconda.com/
- Follow the instructions from the Deep Reinforcement Learning Repository: https://github.com/udacity/deep-reinforcement-learning
to install the base packages needed.
- You'll also need to download a pre-compiled Unity Environment, the link can be found under "Getting started" at 
https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation
While I only tested this approach on Ubuntu Linux, it should work on Windows or Mac OS in the same way.

# Description of the Banana Collector Environment
The agent navigates in an environment with the goal to collect yellow bananas while avoiding yellow bananas.
The environment is described in https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation.
In summary, it has a state-space with a dimension of 37, some of these dimensions represent attributes like the agents velocity
or perception of objects from different viewing directions. 
The action space has only four differnet actions: move forward, move backwards, turn left, turn right.

# Running the Agent
To run the agent you just need to open my_solution.ipnyb in Jupyter Notebook and run the cells.

# References
A list of references that were used while working on the project, besides the Udacity Deep Reinforcement Learning course:

[1] Juliani, A., Berges, V., Vckay, E., Gao, Y., Henry, H., Mattar, M., Lange, D. (2018). Unity: A General Platform for Intelligent Agents. arXiv preprint arXiv:1809.02627. https://github.com/Unity-Technologies/ml-agents.

[2] Mnih, Volodymyr, et al. "Human-level control through deep reinforcement learning." Nature 518.7540 (2015): 529.

[3] van Hasselt, Hado, Arthur Guez, and David Silver. "Deep Reinforcement Learning with Double Q-learning." arXiv preprint arXiv:1509.06461v3 (2015).

[4] Wang, Ziyu, et al. "Dueling network architectures for deep reinforcement learning." arXiv preprint arXiv:1511.06581v3 (2015).

[5] https://github.com/udacity/deep-reinforcement-learning, last accessed: 10.03.2019

[6] https://github.com/openai/baselines, last accessed: 10.03.2019

[7] https://pytorch.org/tutorials/, last accessed: 10.03.2019

[8] Hessel, Matteo, et al. "Rainbow: Combining Improvements in Deep Reinforcement Learning." arXiv preprint arXiv:1710.02298 (2017).

[9] Schaul, Tom, et al. "Prioritized experience replay." arXiv preprint arXiv:1511.05952 (2015).

[10] Sutton, Richard S., and Andrew G. Barto. Reinforcement learning: An introduction. MIT press, 2018.
