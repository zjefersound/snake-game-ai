# Reinforcement learning with PyTorch and Pygame

This is a Deep Learning project made following the [freeCodeCamp.org tutorial on YouTube](https://www.youtube.com/watch?v=L8ypSXwyBds) 

## What was made?
The project combines concepts from [Q Learning](https://towardsdatascience.com/reinforcement-learning-explained-visually-part-4-q-learning-step-by-step-b65efb731d3e) and [Deep Q Networks](https://towardsdatascience.com/reinforcement-learning-explained-visually-part-5-deep-q-networks-step-by-step-5a5317197f4b#:~:text=The%20Q%20Network%20is%20a,regular%20CNN%20or%20RNN%20architecture.).

- ```Game```: is the snake game itself with modifications to return the desired rewards and verify collisions from the ```agent```
- ```Agent```: is the "virtual player", that runs the game and trains the ```model``` 
- ```Model```: is the part of the application that saves the learned values into a Q table and predicts the next moves based on previous rewards.

## What is missing?
Improvements in reward values and how to dodge itself without getting locked.

## Setup

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

## Versões:
```python:3.7```

## Prerequisites:
- VSCode: https://code.visualstudio.com/download
  - Extensions:
    - Docker: https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker
    - Remote development: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack
- Docker: https://www.docker.com/products/docker-desktop/

##  How to install:

1 - First clone this repository with the following command:

```bash
git clone https://github.com/zjefersound/snake-game-ai
```

2 - Open with VSCode:
You can open directly in your VSCode app or using the command ```code```:

```bash
code snake-game-ai
```

3 - Open in container
When you open the folder the following message should appear. Select "Reopen in container"

![image](https://github.com/zjefersound/poc-devcontainer-geekie/assets/62676057/8d37eae8-d723-4fb9-9be2-d420b02d52be)

If it disappears use the shortcut:
```
Ctrl+Shift+P ou Command+Shift+P
```
Search for "Dev Containers":

![image](https://github.com/zjefersound/poc-devcontainer-geekie/assets/62676057/f2848dcb-3e02-4ae6-b557-5feb489b8203)

Select "Rebuild and Reopen in Container".

4 - Run the project: 

to run 
```
python agent.py
```


### Preview: 
![image](https://github.com/zjefersound/snake-game-ai/assets/62676057/8caeb753-784f-432a-812c-322363148e22)

