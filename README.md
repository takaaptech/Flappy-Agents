# flAppy bIrd - Reinforcement learning of flap using the Unity ML-Agents

This is a project that allows to train an AI able to solve the Flappy Bird game:

![Flappy AI](https://cdn-images-1.medium.com/max/800/1*G-uGz8s2ti5rgVTz7AHU1w.gif)

This is the code for an accompanying [Medium article](https://medium.com/p/70f7b661663d), for details on the content, please check the article.

## Requirements
This project needs the ML-Agents environment to be set up. At best I'd suggest to follow the [official installation guide](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md). However the following steps should suffice:

1. Get Python 3.6 64-bit (the 64 bit is necessary at least on Windows)
2. Make sure this python and pip are in the [Path](https://projects.raspberrypi.org/en/projects/using-pip-on-windows/5).
3. Get Unity 2018.1+
4. `git clone https://github.com/Unity-Technologies/ml-agents.git`
5. Install dependencies:
    1. `cd ml-agents`
    2. `pip install ml-agents` (note that the folder ml-agents is nested in the repo ml-agents)
6. Open the repo in Unity.
7. Get [TensorflowSharp](https://s3.amazonaws.com/unity-ml-agents/0.5/TFSharpPlugin.unitypackage) and import into the project.
8. Clone this repository into the `UnitySDK/Assets` folder.
9. Open the `FlappyAgents.unity` scene.