[Blog homepage](https://1040mxg.github.io/blog/) || [View Report on Google Colab **RECOMMENDED**](https://colab.research.google.com/github/1040mxg/5334project/blob/main/projectReport.ipynb) || [View Report on Kaggle](https://www.kaggle.com/mxg1040/5334project) || [Github Repo](https://github.com/1040mxg/5334project)

This project seeks to create a classifier that could detect misinformation and propaganda, geared specifically towards older members of the Chinese diaspora. A prevalent issue among mainland Chinese diaspora is the spread of sensationalist “fake news” and propaganda through various websites and popular messaging apps. These news sources are essential parts of life and often the only source of news for older Chinese immigrants, but strict guidelines set forth by the ruling Chinese government (“CCP”) authority restricts what topics may be covered and how, so as to hide calls for reform or exposure of human rights abuses that may subvert government authority. For these reasons, there is a general distrust among Chinese diaspora of state-sanctioned media such as Xinhua or People’s Daily, but very rarely does this same caution extend to English-language sources. This creates the issue that I seek to address: English-language versions of major CCP media exist, both branded and unbranded. I seek to create a classifier that can detect possible state media influence on unbranded (ie. not connected to any large or known news source) English-language articles. In this way, the hope is that effects of CCP propaganda on overseas diaspora can be highlighted and reduced.

# Requirements
This project was written in Python 3 in Google Colab and requires the following to run:

- Natural Library Toolkit<br>pip3 install --user -U nltk
- random
- re
- numpy
- matplotlib

All datasets used are available in the data folder.

To run: python3 main.py

**To best view the project report** with graphs and images, please view/run all on Google Colab [here](https://colab.research.google.com/github/1040mxg/5334project/blob/main/projectReport.ipynb) or with outputs [here](https://github.com/1040mxg/5334project/blob/main/projectReport.ipynb).
