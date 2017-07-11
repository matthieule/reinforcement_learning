## WIP

This is a work in progress: the code seems to run somewhat smoothly, 
but I have not taken the time to get 1 week worth of GPU to train it
entirely :crying_cat_face:

## Code Organization

### Classes

### Organization of action / reward

## Description

Implementation of [1]

## Installation

Clone this repository

```bash
git clone https://github.com/matthieule/reinforcement_learning.git
cd reinforcement_learning
conda env create -f environment.yml
```

Activate the environment

```bash
source activate openai
```

Export the path to the repository
```bash
export PYTHONPATH={path_to_reinforcement_learning}:$PYTHONPATH
```

You might need to install the following:
```bash
pip install gym'[all]'
conda install -c conda-forge tensorflow
```

## Example Usage

Training

```bash
cd reinforcement_learning
python script/training.py
```

Inference

```bash
python script/inference.py
```

This should create a video in the `/tmp/` folder to visualize the results.

## References

[1] Mnih, Volodymyr, et al. "[Human-level control through deep reinforcement learning.](http://www.davidqiu.com:8888/research/nature14236.pdf)" Nature 518.7540 (2015): 529-533.]

