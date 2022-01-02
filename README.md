<p align="center">
  <img src="https://user-images.githubusercontent.com/57759154/140659027-396b5850-35dd-408e-8a57-51adbcfd9bdc.png" />
 </p>

# Emerging-Technologies

**Name:** Krystian Opryszek

**Student ID:** G00366895

## Table Of Content
- [Overview](#Overview)
- [How to run the notebooks](#How-to-run-the-notebooks)
- [Technologies used](#Technologies-used)
- [Weekly Labs](#Weekly-Labs)
- [Requirements](#Requirements)
- [References](#References)

## Overview
This repository consists of two notebooks `scikit-learn.ipynb` and `quantum-deutsch.ipynb`. 

- **scikit-learn.ipynb**

  This notebook contains a clear and consise overview of the scikit-learn Python library. In this notebook, I have performed Classification, Regression and Clustering Analysis using scikit-learn algorithms such as Nearest Neighbors Algorithm, SVR algorithm, K-means algorithm and DBSCAN algorithm. In order to showcase the following algorithms, I have used datasets from [Kaggle](https://www.kaggle.com/) and [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality). To visualise the notebook I have added some plots and Heatmaps.
  
  **Classification Analysis:** Wine Data Set
  
  **Regression Analysis:** Fuel Consumption
  
  **Clustering Analysis:** Mall Customer Segmentation Data

- **quantum-deutsch.ipynb**

  This notebook contains a clear and consise comparison of quantum computing and classical computing. This notebook explains what Quantum Computing is, how it works and clear comparison of Quantum and Classical Computing. This notebook also consists of explination of Deutsch’s algorithm and code showcasing it using qiskit. 

## How to run the notebooks
To run the notebooks follow the below instructions:

### Quick steps

You can view notebooks in static form by clicking the following image:

Scikit-learn notebook

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/krystianopryszek99/Emerging-Technologies/blob/main/scikit-learn.ipynb)

Quantum-deutsch notebook

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/krystianopryszek99/Emerging-Technologies/blob/main/quantum-deutsch.ipynb)

### Run using jupyter lab 
*You may have to install anaconda to run with jupyter lab, look the [Requirements](#Requirements)*
1. Clone this repository `git clone https://github.com/krystianopryszek99/Emerging-Technologies.git`
2. Open the folder `Emerging-Technologies` and open the cmd 
3. Run the following command `jupyter lab`

### Run using docker
1. Clone this repository onto your machine `git clone https://github.com/krystianopryszek99/Emerging-Technologies.git`
2. Open the folder `Emerging-Technologies` and open the cmd 
3. Run the following command `docker-compose up`
4. Copy the link provided and paste it into the web browser 
5. After viewing the notebook, remove the container by the following command `docker-compose down`

## Technologies used
Some of the technologies used in this assessement as follow:

- **Python**
  
  Python is a high-level, general-purpose programming language that is interpreted.
  
- **Jupyter Project**
  
  Open-source software, open standards, and Interactive computing services for dozens of programming languages
  
- **Scikit-learn**
  
  Scikit-learn is a Python-based machine learning package
  
- **Qiskit**

  Qiskit is an open-source software development kit that allows you to deal with quantum computers at the circuit, pulse, and algorithm level.
  
- **Docker**

  Docker is a collection of the platform as service tools that distribute software in containers using OS-level virtualization.

- **Anaconda** 

  Anaconda is a Python and R programming language distribution for computer science that aims to make package management and deployment easier.

## Weekly Labs
I have seperate repository for the weekly labs to keep this repository tidy for the assessment.

[nupy-random](https://github.com/krystianopryszek99/numpy-random)

[scikit-learn](https://github.com/krystianopryszek99/scikit-learn)

[jupyter-notebooks-labs](https://github.com/krystianopryszek99/jupyter-notebooks-labs)

## Requirements

In order to run these notebooks with jupyter lab, you may be required to have Python and anaconda installed on your machine. Anaconda is the recommended solution for installing both Python and Jupyter. You can download the following: [Python](https://www.python.org/downloads/) and [Anaconda](https://www.anaconda.com/). You can follow installation steps from [Jupter Documentation](https://test-jupyter.readthedocs.io/en/latest/install.html) to install Jupyter Notebook. More on running the notebook on [Jupter Documentation](https://test-jupyter.readthedocs.io/en/latest/running.html#running)

## References

https://scikit-learn.org/stable/index.html

https://en.wikipedia.org/wiki/Quantum_computing#:~:text=Quantum%20computing%20is%20a%20type,and%20entanglement%2C%20to%20perform%20calculations.&text=The%20study%20of%20quantum%20computing%20is%20a%20subfield%20of%20quantum%20information%20science.

https://docs.docker.com/compose/compose-file/compose-file-v3/

https://jupyter-docker-stacks.readthedocs.io/en/latest/

https://qiskit.org/textbook/ch-algorithms/deutsch-jozsa.html

https://qiskit.org/
