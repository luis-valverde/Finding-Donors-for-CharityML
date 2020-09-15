# Finding Donors for CharityML

## Table Of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Neccessary Files](#neccessary-files)
- [How to Run](#how-to-run)

## Introduction

This repository contains all my work for the Udacity's Machine Learning Introduction Nanodegree Program.

The goal in this project was to build a model that accurately predicts whether an individual makes more than $50.000,
to identify likely donors for a fictional non-profit organization.

To accomplish this, I applied data preprocessing techniques such as normalization and one-hot encoding. Then, trained
and tested several supervised machine learning models (Gradient Boosting, Random Forest) and picked the best model
based on F-beta and training time metrics. Finally, I increased the performance of the chosen model using grid search
(F-beta increased by 2.03%).

## Project Overview

CharityML is a fictitious charity organization located in the heart of Silicon Valley that was established to provide
financial support for people eager to learn machine learning. After nearly 32,000 letters were sent to people in the
community, CharityML determined that every donation they received came from someone that was making more than $50,000
annually. To expand their potential donor base, CharityML has decided to send letters to residents of California, but
to only those most likely to donate to the charity. With nearly 15 million working Californians, CharityML has brought
you on board to help build an algorithm to best identify potential donors and reduce overhead cost of sending mail.
Your goal will be evaluate and optimize several different supervised learners to determine which algorithm will
provide the highest donation yield while also reducing the total number of letters being sent.

## Requirements

This project uses the following software and Python libraries:

- [Python](https://www.python.org/downloads/release/python-364/)
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [scikit-learn (v0.17)](https://scikit-learn.org/0.17/install.html)
- [Matplotlib](https://matplotlib.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the
[Anaconda](https://www.anaconda.com/distribution/) distribution of Python, which already has the above packages and
more included.

## Neccessary Files

This repository contains three files needed to solve the project.

1. **finding_donors.ipynb:** This is the main file where I performed the work on the project.
2. **finding_donors.html:** This is an HTML report of the Jupyter notebook.
3. **census.csv:** The project dataset.
4. **visuals.py:** This Python script provides supplementary visualizations for the project.

## How to Run

In the Terminal or Command Prompt, navigate to the folder on your machine where you've put the project files, and then
use the command:

```bash
jupyter notebook finding_donors.ipynb
```

 to open up a browser window or tab to work with your notebook.
 Alternatively, you can use the command:

 ```bash
jupyter notebook
```

or

```bash
ipython notebook
```

and navigate to the notebook file (finding_donors.ipynb) in the browser window that opens.
