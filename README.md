# AUC_TMCI_2019
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Giovanni1085/AUC_TMCI_2019/master)

Amsterdam University College -- Text Mining and Collective Intelligence -- Fall 2019.

## Contents

* [Hello World](notebooks/0_HelloWorld.ipynb): a first notebooks to check everything is working.
* [Lab 1: Fundamentals](notebooks/1_Fundamentals.ipynb): variables, built-in data types and structures, syntax, flow control.
* [Lab 2: Fundamentals](notebooks/2_MoreFundamentals.ipynb): functions, exceptions, classes, I/O.
* [Lab 3: More fundamentals](notebooks/3_EvenMoreFundamentals.ipynb): modules, packages, standard library.
* [Lab 4_1: Scientific programming](notebooks/4_ScientificProgramming.ipynb): NumPy, matplotlib.
* [Lab 4_2: Regular expressions](notebooks/4_RegularExpressions.ipynb) (only for reference).
* [Lab 5: NLP pipelines](notebooks/5_NLP_pipelines.ipynb): sentence splitting, tokenizing, stemming and lemmatizing, part-of-speech tagging.
* [Lab 6: Web scraping and APIs](notebooks/6_WebScraping_APIs.ipynb).
* [Lab 7_1: Distributions in texts](notebooks/7_Distributions_in_text.ipynb).
* [Lab 7_2: WordNet](notebooks/7_WordNet.ipynb) (only for reference).
* [Lab 8: Vector Semantics](notebooks/8_Vector_Semantics.ipynb).
* [Lab 9: Intro to ML](notebooks/9_ML.ipynb): linear regression, logistic regression, SGD, Sklearn.
* [Lab 10: Word Embeddings](notebooks/10_WordEmbeddings.ipynb): Word2Vec using Gensim.
* [Lab 11: Sentiment Analysis](notebooks/11_Sentiment_Analysis.ipynb).
* [Lab 12: Recommender Systems](notebooks/12_Recommender_Systems.ipynb).
* [Lab 13: Clustering and Topic Modelling](notebooks/13_Clustering_TopicModelling.ipynb).

## Projects

See the [projects folder](/projects) for info.

2019/20 project outcomes:
* Jaël Kortekaas, António Mendes, Ludovica Schaerf, [Topic Modelling of Song Lyrics](https://github.com/ludovicaschaerf/TMCI_Project).
* Joyce den Hertog, Barbara van Eeghen, Eva Schoonings, [Fake News Detection](https://github.com/joycedh/TMCI_project).
* Vera Neplenbroek, Kamiel Fokkink, Baran Işcanli, [Machine Translation with Recurrent Neural Networks](https://github.com/Veranep/TMCI_Kamiel_Baran_Vera).
* Rajiv Manichand, Hanabi Ono, Eva Gmelich Meijling, [Topic Modeling on Bills of the US Congress](https://github.com/Raj1v/TMCI_Final_Project).
* Andrew Nelson, Tomas Kehus, Lela Roos, [Common Threads among Last Statements from Death Row Offenders](https://github.com/lelaroos/tmci_project6).
* Jan Koetsier, Lily Voge, Caoimhe Martin, [A Textual Analysis of UK Parliament Debates -- Gaining a Better Understanding of Brexit Processes](https://github.com/TjalieWS/TMCI-Project-Nov-2019).
* Jasmijn Bleijlevens, Lanie Preston, Floor Kouwenberg, [Fantastic Food Finder : Rating Prediction & Sentiment Analysis on Amazon Food Reviews](https://github.com/floorkouwenberg/TMCI_project).

## Set-up

1. Clone the repository locally: `git clone https://github.com/Giovanni1085/AUC_TMCI_2019.git`
2. Get updates (from time to time): `git pull`
3. Create a conda environemnt: `conda create -n myenv python=3.7 anaconda` (where `myenv` is the envirnoment name)
4. Activate it: `conda activate myenv`
5. Install packages (see the `requirements.txt` file), e.g. `conda install pandas`
6. Launch a Jupyter notebook: `jupyter notebook`

* [More on conda enviroments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
* [Conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
* [Getting started with Jupyter notebooks](https://medium.com/codingthesmartway-com-blog/getting-started-with-jupyter-notebook-for-python-4e7082bd5d46)
* [On using git and GitHub for version control](https://alan-turing-institute.github.io/rsd-engineeringcourse/ch02git)

Alternatively, use [Binder](https://mybinder.org) (link above).

**A more detailed [guide to setup your environment](setup.md), with multiple options.**

## Credits

* Michael Repplinger, who ran the 2018/19 edition and Gianluca Lebani, who ran the 2017/18 edition.
* Giovanni Colavizza and Matteo Romanello, Applied Data Analysis course for the Oxford Digitial Humanities Summer School [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3352830.svg)](https://doi.org/10.5281/zenodo.3352830)
* James Hetherington and Giovanni Colavizza, [Research Software Engineering with Python](https://alan-turing-institute.github.io/rsd-engineeringcourse/)
