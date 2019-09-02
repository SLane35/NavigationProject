# README – DRLND Navigation Project
### The Enviroment
In this project, an agent is trained to navigate in a large, square world and collect bananas. There is a reward of +1 for every yellow banana collected and reward of -1 for every blue banana collected. 
There are 37 dimensions in the state space, and they contain the agent’s velocity and the ray-based perception of objects around the agent’s forward direction. The agent chooses from four discrete actions based on the state: 
  -	0 – move forward
  - 1 – move backward
  - 2 – turn left
  - 3 – turn right

The task is episodic. In order for the environment to be considered solved, the agent must get an average score of +13 over 100 consecutive episodes.

### Requirements

1.	Download the Unity Environment that matches your operating system:
    - Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip
    - Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip
    - Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip
    - Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip
    - 
2.	Set up the Python environment:

    a.	Create and activate a new environment with Python 3.6.
    - Linux or Mac:
        ```
        conda create –name drlnd python=3.6
        source activate drlnd
        ```
    - Windows:
        ```
        conda create –name drlnd python=3.6
        activate drlnd
        ```
    b.	Do a minimal install of OpenAI gym using
    
        pip install gym
    c.	Install the classic control & box2d environments using
    
        pip install Box2D
        pip install gym[all]
        pip install piglet==1.2.4
        pip install gym[box2d]
    d.	Clone the repository, navigate to the python folder, and install dependencies using
    ```
    git clone https://github.com/udacity/deep-reinforcement-learning.git
    cd deep-reinforcement-learning/python
    pip install .
    ```
    e.	Create an IPython kernel for the drlnd environment.
    
        python –m ipykernel install –user –name drlnd –display-name “drlnd”
    f.	Before running the code in the notebook, change the kernel to the “drlnd” kernel that you just created by using the drop-down Kernel menu.
    
    g. In order to train the agent, run the code cells sequentially.
