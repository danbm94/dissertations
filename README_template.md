# Title

[Insert here a figure explaining your approach or main results]

![results](/SMART_HOME_N_ENERGY/behavioural_theories/Plots/AverageEnergyConservationIntention.png)

**Type:** Master's Thesis / Bachelor's Thesis

**Author:** xxx

**Supervisor:** xxx (only if different from 1st or 2nd Examiner)

**1st Examiner:** xxx 

**2nd Examiner:** xxx 

**Date of submission:** 01.01.2022

## Abstract

(Short summary of motivation, contributions and results)

**Keywords**: xxx (please name at least 5 keywords / phrases).

## Working with the repo

### Dependencies

Which Python version is required? 

Does a repository have information on dependencies or instructions on how to set up the environment?

### Setup

[This is an example]

1. Clone this repository

2. Create an virtual environment and activate it
```bash
python -m venv thesis-env
source thesis-env/bin/activate
```

3. Install requirements
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

## Reproducing results

Describe steps how to reproduce your results.

Here are some examples:
- [Paperswithcode](https://github.com/paperswithcode/releasing-research-code)
- [ML Reproducibility Checklist](https://ai.facebook.com/blog/how-the-ai-community-can-get-serious-about-reproducibility/)

### Training code

Does a repository contain a way to train/fit the model(s) described in the paper?

### Evaluation code

Does a repository contain a script to calculate the performance of the trained model(s) or run experiments on models?

### Pretrained models

Does a repository provide free access to pretrained model weights?

## Results

Does a repository contain a table/plot of main results and a script to reproduce those results?

## Project structure

(Here is an example from SMART_HOME_N_ENERGY, "Appliance Level Load Prediction" repo)

```bash
├── README.md
├── requirements.txt                                -- required libraries
├── data                                            -- stores csv file (only available via gdrive link)
├── plots                                           -- stores image files
└── src
    ├── prepare_source_data.ipynb                   -- preprocesses data
    ├── data_preparation.ipynb                      -- preparing datasets
    ├── model_tuning.ipynb                          -- tuning functions
    └── run_experiment.ipynb                        -- run experiments 
    └── plots                                       -- plotting functions                 
```