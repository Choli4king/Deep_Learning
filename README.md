# Homework Project README

## Overview

This repository contains a deep learning homework project focusing on Natural Language Processing (NLP) tasks. The project processes TED Talk transcripts using various NLP preprocessing methods, word embedding models, and visualization techniques.

## System and Environment Setup

- **Operating System**: The project was developed using a Linux distribution running on Windows Subsystem for Linux (WSL).
- **Virtual Environment**: The project dependencies were managed using a Conda virtual environment named `DeepL3`.

### Setting Up Conda Environment

If you want to replicate the environment used for this project, you can do so by creating a new Conda environment using the provided requirements.yml file.

To create the environment, use the following command:

```sh
conda env create -f requirements.yml -n new_env_name
```

This will install all necessary packages and dependencies in a new virtual environment.

### Activating the Environment

Once you have created the environment, activate it using:

```sh
conda activate new_env_name
```

## Dependencies

The main dependencies used in this project include:

- **Python 3.x**
- **NLTK** for Natural Language Toolkit functions
- **Gensim** for word embeddings
- **Matplotlib** for plotting
- **Scikit-Learn** for t-SNE visualization
- **Pickle** for saving and loading processed data
- **Inflect** for expanding word contractions

To install any missing dependencies manually:

```sh
conda install <package-name>
```

or use `pip` for specific libraries such as gensim:

```sh
pip install gensim
```

## Project Structure

- `ted_talk_preprocessing.ipynb`: Main Jupyter Notebook containing all code for data preprocessing, embedding generation, and visualization.
- `requirements.yml`: YAML file to recreate the Conda environment used.
- `tokenized_data.pkl`: A Pickle file containing the tokenized TED Talks data.