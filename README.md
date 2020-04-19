# Overview dsend_project_3:
- [Project summary](#Summary)
- [Repository content](#Repository_content)
- [Software requirements](#Software_requirements)
- [How to run locally](#How_to_run)
- [Acknowledgements & licensing](#Acknowledgements)

## Project summary:<a name="Summary"></a>
On the web, recommendation systems are everywhere. Whether we want to buy, read, watch, listen or play something online, we are most likely presented content which is tailored to us. It can thus be interesting for anyone to understand how recommender systems work and why we get specific recommendations.

The goal of this Udacity project was to develop a recommendation engine for articles on the IBM Watson Studio platform.

## Repository content:<a name="Repository_content"></a>
This repository includes .ipynb & .html files. It does not contain the data that was used in the process of creating the recommender engine. It also does not include the custom package "project_tests.py" for testing some of the responses.

```bash
.
├── README.md
├── recommendations_notebook.html
└── recommendations_notebook.ipynb
```

## Software requirements:<a name="Software_requirements"></a>
Please use Python version 3.8.1 & the following packages:

```bash
matplotlib==3.2.0,
numpy==1.18.1,
pandas==1.0.1
```

I used [pip](https://pip.pypa.io/en/stable/) to install these packages. Further, I assume that you have installed [jupyter](https://jupyter.readthedocs.io/en/latest/install.html) already. 

## How to run locally:<a name="How_to_run"></a>
You first need to have access to the data from the Udacity Nanodegree. Then after cloning this repository, change to its directory in your terminal. Run the following command:

```bash
jupyter notebook recommendations_notebook.ipynb
```

Your Internet browser should open now. Otherwise follow the instructions in your terminal.

## Acknowledgements & licensing:<a name="Acknowledgements"></a>
Thanks to Udacity & IBM for providing the dataset.
