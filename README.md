
# Learning from the Master: Using ChatGPT for Reinforcement Learning - part 2

All resources from the second part of the blog series.

```src```folder contains the working versions of the chatGPT generated scripts with my comments what was chatGPT doing wrong and how did I fix the code etc.

```Data/Input/TM.npy``` contains the Time-matrix stored in numpy format provided by the university.

```notebooks``` folder contains a notebook that can be used to train the Deep Q Learning network and to visualize rewards, convergence etc. after training.

```
tree -a  -I '__pycache__|.git|.gitignore|.DS_*' .
.
├── Data
│   ├── Inputs
│   │   └── TM.npy
│   └── Outputs
├── LICENSE
├── README.md
├── notebooks
│   └── train_agent.ipynb
└── src
    ├── __init__.py
    ├── agent_chatGPT.py
    ├── environment.py
    ├── test_agent.py
    └── test_environment.py

6 directories, 9 files
```