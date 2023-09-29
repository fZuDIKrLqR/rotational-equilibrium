# Rotational Equilibrium: How Weight Decay Balances Learning Across Neural Networks

## Repository Structure
* **experiments**: Scripts to run the experiments, as reported in the paper
* **shared/optimizers**: Contains implementation of the rotational variant of the baseline optimizers (AdamW, SGD, Lion)
* **submodules**: Contains the **FairSeq**, **LLM-Baselines** and **TIMM** libraries, that are used to run experiments with the baseline and rotationl variants of the optimizers.

## Experiments
The scripts to run the experiments as reported in the paper are provided in experiments folder.
In order to run the bash experiments the environment variables `TMUX_SESSION`, `EXPERIMENT`, `DATA_DIR`, `PPATH` and `CONDA_ENV` need to be set.
Note that the scripts are based on existing conda environments. How to set up the individual libraries, can be found in the respective libraries.
