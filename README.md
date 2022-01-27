# python-learning-snakeAI
# AI-Project
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development. See Deployment for notes on how to deploy the project on a live system.
Clone the repository
```
git clone https://github.com/PhucTran125/python-learning-snakeAI.git

cd python-learning-snakeAI
```
### Prerequisites

You will need to have python, conda installed. For instructions on installing Python, please visit [Python's documentation on installing and using Python](https://docs.python.org/3/using/index.html).

### Installing

<!-- Here we use conda to manage the environment -->
```
conda create -n pygame_env python-python's verion
```
<!-- Then we activate the environment -->
```
conda activate pygame_env
```
<!-- We need to setup some libraries (pygame, pytorch, matplotlib,...) -->
```
pip install pygame
pip install torch torchvision
pip install matplotlib ipython
```

### How to Play

<!-- You open the folder that contain file agent.py, open cmd from that folder-->
<!-- Activate the environment, and run the AI training -->
```
conda activate pygame_env
python agent.py
```

## Authors

* **Tran Thai Phuc** - *Initial work* - [PhucTran125](https://github.com/PhucTran125)

## Acknowledgments

* Inspired by [Thomas Hikaru Clark's tutorial](https://towardsdatascience.com/training-a-snake-game-ai-a-literature-review-1cdddcd1862f)