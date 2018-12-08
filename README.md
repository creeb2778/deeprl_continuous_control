# deeprl_-continuous-_control
deep reinforcement learning: Continuous Control 


## System Dependencies

python 3.6+
torch 0.4.1
unityagents 0.4.0

For Linux:
[reacher multi agent environment](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)

## Project Details

[Reacher Unity Env](https://youtu.be/2N9EoF6pQyE)

The goal of this project is to train 20 robotic arms to stay withing a specific spheres in the environment. The agents are given a reward of +0.1 for every time step they are inside the target sphere. The state space consist of a vector (for each agent) containing 33 numbers that represent the position, velocity, rotation, and angular velocities of the robotic arm. The agent can take 4 actions, corresponding to torque at joins in the agents arms (values between -1 and 1). 

The environment is considered solved when the average score (of all agents) is greater than 30 for the past 100 episodes. 

## Running the Code
The code is compiled in the report.ipynb file. The model and agent architecture are stored in python files (model.py and ddpg_multiagent.py). 

The network is imported in the ddpg agent script, and the ddpg agent is imported in the unity environment in the report.ipynb file. The code to step the agent through the environment is found in the ipynbs. There are also other experimentation versions of training the agent in the playground directory located in the repo. 

The final solved agents weights are saved in the model_weight directory in the repo.  


Good luck and happy learning :) 























