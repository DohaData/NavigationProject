# NavigationProject

## Project details

This project consists of navigating an agent through an environment composed of yellow and blue bananas. The agent gets a reward of +1 when collecting a yellow banana and a reward of -1 when collecting a blue banana.
The state of the agent is continuous composed of 37 dimensions. Whereas the action space is discrete composed of 4 actions.
The environment is considered solved when the average score is 13 over 100 episodes.

## Repository structure

This repository is composed of:
- Navigation.ipynb: A notebook containing the all the project code
- checkpoint.pth: the model weights
- report.pdf: the project report

## Getting started

The first cells of Navigation.ipynb are used to install dependencies.
Then a few cells to explore the environment in sections 2 and 3.
Section 4 is composed of the following:
- Utilities function to retrieve from an action, the reward, the next state and whether the episode is done
- The network used in Q-learning architecture
- Agent class representing the agent acting and learning
- Agent training
- Score ploting
