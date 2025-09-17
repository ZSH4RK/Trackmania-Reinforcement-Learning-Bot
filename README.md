# Trackmania-Reinforcement-Learning-Bot
In this project my goal is to teach an AI to play trackmania using Reinforcement Learning based on the framework of TMRL. My inspiration for this project was from watching the videos by [Yosh](https://www.youtube.com/@yoshtm) and [Linesight] about their journeys in creating their own AI
## TMRL -- [Github Link](https://github.com/trackmania-rl/tmrl)

The [gym](https://github.com/yannbouteiller/rtgym) is directly run which simulates the bots interaction with the environmetn with a [rollout worker](https://medium.com/@sophiezhao_2990/rollout-in-rl-how-its-structured-ca6c106cfc80)
> A "rollout worker" in reinforcement learning (RL) is a component that simulates an agent's interaction with an environment to collect data for training, often using a specific policy to generate experience trajectories.

The [inputs](https://github.com/trackmania-rl/tmrl/blob/master/tmrl/custom/tm/utils/control_gamepad.py) are controlled by simulating an analog controller
