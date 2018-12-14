# Introduction
This repo contains code for [AI Challenger 2018](https://challenger.ai/competition/fsauor2018) aspect-level sentiment analysis. With proper tuning and ensemble, it achieves the third place in test B. 

I haven't include the ensemble part since it is not elegant by my standard. This repo is presented as a preliminary try for good Tensorflow coding style. Its efficient multi-gpu implementation enables faster iteration. It also provides good logging and configuration facility.

# How to run it
Simply run

`python main.py --name <your_experiment_name>`

It shall read the contents in `data`. Logs and checkpoints are in `output/<your_experiment_name>`。

Have fun tuning!