---
id: zUTHtkQuKQWwnIiQhb9uJ
title: Jupyter Notebook and Alternatives
desc: ''
updated: 1649283171250
created: 1639628094199
---
# Jupyter notebook and alternatives

## Getting started with [Mito](https://trymito.io/)

### Installing Mito
ref: [Mito | Install Mito inside a virtual environment](https://docs.trymito.io/getting-started/installing-mito/installing-mito-inside-a-virtual-environment),

Preparation: [[Install virtualenvwrapper|notes.tutorial.python.virtual-environment#install]]

Step-by-step:

1. Create a new virtual environment named `mitoenv`
    ```shell
    mkvirtualenv mitoenv
    ```
2. install the Mito installer
    ```shell
    pip install mitoinstaller
    ```
3. run the installer
    ```shell
    python -m mitoinstaller install
    ```
    Done here. Jupyter Lab will be called to open in browser.
4. Next time, I can initiate Jupyter lab instance to start, using
    ```shell
    py -m jupyter lab
    ```

## Other alternatives

[Exploratory](https://exploratory.io/)
- [pricing](https://exploratory.io/pricing) starts at USD 49/month. 30-day free trial only
- Simple and Modern UI experience to access various Data Science functionalities including Data Wrangling, Visualization, Statistics, Machine Learning, Reporting, and Dashboard
- alternative of [Jupyter](https://jupyter.org/) notebook

[Google colab](https://colab.research.google.com/)
- [pricing](https://colab.research.google.com/signup) starts at EUR 9.25/month. Free plan available
- alternative of [Jupyter](https://jupyter.org/) notebook

[Deepnote](https://deepnote.com/)
- [pricing](https://deepnote.com/pricing) starts at USD 12/month. Free plan available
- alternative of [Google colab](https://colab.research.google.com/), [Jupyter](https://jupyter.org/)

[Kaggle](https://www.kaggle.com/)

[Ellx](https://ellx.io/)
- web-native spreadsheet where formulas and macros are both JavaScript instead of Excel formulas and VBA
- [review](https://news.ycombinator.com/item?id=30871606) on HackerNews
