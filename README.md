# GWU CS6365

This repo contains executable slides for the  ML course at The George Washington University (Fall 2024 edition).

## Contents

This repo is organized as follows.

```
.
├── README.md
├── Lectures...               # Course slides 
└── requirements.txt      # Packages needed for your virtualenv
```

## Setup

### Requirements

You should be able to run all the contents of this repo using the packages provided in `requirements.yml` using Anaconda or `requirements.txt` using virtualenv.

For `Anaconda` run this:
```
conda create --name gw-cs6365 --file requirements.yml
conda activate gw-cs6365
python -m ipykernel install --user --name=gw-cs6365
```

In a new `virtualenv`, run this:
```
pip install -r requirements.txt
```

Credits: The slides and course materials are collected from multiple sources. Including,
- the ML course thought by Xavier Amatriain at SPHERE
- Stanford CS224W (https://web.stanford.edu/class/cs224w/)
- Poolparty graph academy (https://www.poolparty.biz/academy)
