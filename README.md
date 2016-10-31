# Training A Smartcab How to Drive
<p align="center">
![Image](https://github.com/gmsardane/training-a-smartcab/blob/master/smartcab.gif) </p>
This project uses reinforcement Q-learning to train an agent to drive in a grid-like environment. 
Based on rewards and penalties to simulate correct driving in the real-word. Environment parameters are:

+ Light: {*RED*, *GREEN*}
+ Left : {*Oncoming*, *left*, *right*, *None*}
+ Right : {*Oncoming*, *left*, *right*, *None*}
+ Oncoming : {*Oncoming*, *left*, *right*, *None*}

The Q-learning update rule is discussed [here](http://www.cs.rutgers.edu/~mlittman/courses/cps271/lect-16/node16.html).

#Tools/Software Requirements:

+ Pygame, random, numpy.

### Install

This project requires **Python 2.7** with the [pygame](https://www.pygame.org/wiki/GettingStarted
) library installed


### Note that I had to run simulation in Python3, since this is the simplest I could make Pygame to install!

### Template Code

Template code is provided in the `smartcab/agent.py` python file. Additional supporting python code can be found in `smartcab/enviroment.py`, `smartcab/planner.py`, and `smartcab/simulator.py`. Supporting images for the graphical user interface can be found in the `images` folder. While some code has already been implemented to get you started, you will need to implement additional functionality for the `LearningAgent` class in `agent.py` when requested to successfully complete the project. 

### Run

In a terminal or command window, navigate to the top-level project directory `smartcab/` (that contains this README) and run one of the following commands:

```python smartcab/agent.py```  
```python -m smartcab.agent```

This will run the `agent.py` file and execute your agent code.
