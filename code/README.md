# stock_clustering

Repo for research project in My University '23.

Data: [link](https://disk.yandex.com.am/d/Y5rAN8ZC0vz8FA)

## Quick Start

All the requirements are listed in `requirements.txt`
For install all packages run 

```
pip install -r requirements.txt
```

After you need to create folders `checkpoints` for saving classifier weights and `results` for saving adversarial attacks results. 

Where are three basic steps: train classifier, attack model, train discriminator.
To run these steps you need to change assosiated config files in "config" folder and after that run assosiated python scrits `train_classifier.py`, `attack_run.py` and `train_discriminator.py`.

For example:
```
python train_classifier.py
```
## Describtion

The goal of the project is to create hardly detected adversarial attacks for time-series models. 

## Content


| File or Folder | Content |
| --- | --- |
| checkpoints| folders for saving weights of the models |
| config | folder contains config files with params of models and paths |
| data | folder contains datasets For LSTM model (Ford_A) and datasets UCR, UEA datasets for TS2Vec models |
| docker_scripts | folder for set environment in docker container (if needed) |
| notebooks | folder with notebooks for data visualisation and small experiments|
| src | folder with code|
