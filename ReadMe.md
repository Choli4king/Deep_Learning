README for Word2Vec NLP Notebook

Overview

This notebook contains the complete process of text preprocessing, tokenization, word embedding creation, and visualization using a TED Talk dataset. The notebook walks through exercises that include cleaning the data, building a Word2Vec model, and visualizing word embeddings using t-SNE. Below are details on the environment setup and the steps required to replicate the experiments in this notebook.

System Information

Operating System: The notebook was developed on a Linux-based system. However, it should also run on Windows and MacOS with minimal adjustments.

Python Version: The code uses Python 3.12, though it should work with Python 3.7 and above with compatible versions of the dependencies.

Virtual Environment

A virtual environment was used to manage the necessary Python packages. Specifically, Conda was used to create and manage an isolated environment called DeepL3.

YAML File for Environment Setup

To recreate the virtual environment for this project, a .yml file has been provided. Follow these steps to download and recreate the environment:

Download the .yml file:

Ensure that the DeepL3_environment.yml file is available in the current directory.

Create the environment using Conda:

conda env create -f DeepL3_environment.yml

Activate the new environment:

conda activate DeepL3

The YAML file includes all the necessary libraries, including NLTK, NumPy, Gensim, scikit-learn, and Matplotlib.

Dependencies

The notebook uses the following libraries:

NLTK: For text preprocessing and tokenization (stopwords, punkt, etc.).

Gensim: For building the Word2Vec word embeddings.

Scikit-learn: For t-SNE visualization (sklearn.manifold).

Matplotlib: For plotting bar graphs and visualizations.

NumPy: For efficient numerical operations.

These libraries should be installed automatically with the provided .yml file.

Important Notes

Download Required NLTK Packages: The notebook downloads certain NLTK resources like punkt, stopwords, wordnet, and omw-1.4. Make sure that your environment has access to download these NLTK data packages.

t-SNE Visualization: Running the t-SNE visualization may take some time depending on the size of the dataset and the available computational resources.

Data File: You will need the TED Talk text data as the input. Make sure to place it in the appropriate path as specified in the notebook.

Reproducing the Experiments

Data Preprocessing: The notebook first removes unnecessary characters, such as speaker names, numeric values, and extra whitespaces. Additionally, stopwords are removed.

Tokenization and Embedding: The cleaned text is split into sentences and words. Word2Vec embeddings are generated from the tokenized text.

t-SNE Visualization: The high-dimensional vectors are visualized using t-SNE to show semantic relationships between words.

Running the Notebook

To run the notebook:

Clone the repository or download the files.

Activate the Conda environment as described above.

Start Jupyter Notebook:

jupyter notebook

Open the HW1_Alec_Traub.ipynb file and execute the cells sequentially.

License

This notebook and its contents are developed by the department of Cognative Science at Osnabrueck University.
