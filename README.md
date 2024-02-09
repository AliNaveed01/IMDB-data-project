# IMDB Data Analysis Project

This project involves the analysis and visualization of IMDB data, including sentiment analysis and trends over the decades. The project is divided into multiple phases, encompassing data scraping, cleaning, analysis, natural language processing (NLP), and visualization using Plotly.

## Overview

The project is structured into five phases:

1. **Data Scraping:** Utilizing Beautiful Soup from the BS4 library, 1000 top-rated movies' data was scraped and organized into a dataframe.

2. **Data Cleaning:** The data underwent cleaning procedures, including the removal of missing values, redundant and irrelevant data. Two datasets were concatenated into a single, larger dataset.

3. **Data Analysis:** Analysis on the corpus provided insights into data trends. Changes over the decades were observed, and a movie suggestor was implemented to recommend the best movie based on user preferences.

4. **Sentiment Analysis:** Natural Language Processing (NLP) techniques, including Support Vector Machine (SVM) and Multinomial techniques, were applied to perform sentiment analysis on the data.

5. **Visualization:** Plotly was employed for data visualization to provide clear and interactive representations of the analyzed data.

# Installation

### Prerequisites

1. Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

2. Required Python libraries. Install them using the following commands:

```bash
pip install beautifulsoup4 pandas scikit-learn plotly
```

## Usage

### Data Scraping (Phase 1)

```python
# Importing necessary libraries
from bs4 import BeautifulSoup
import requests
import pandas as pd

# Your data scraping code here
```

### Data Cleaning (Phase 2)

```python
# Importing necessary libraries
import pandas as pd

# Your data cleaning code here
```

### Data Analysis (Phase 3)

```python
# Importing necessary libraries
import pandas as pd

# Your data analysis code here
```

### Sentiment Analysis (Phase 4)

```python
# Importing necessary libraries
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.model_selection import train_test_split
from sklearn.svm import SVC
from sklearn.metrics import accuracy_score

# Your sentiment analysis code here
```

### Visualization (Phase 5)

```python
# Importing necessary libraries
import plotly.express as px

# Your visualization code here
```

## Contributing

Contributions to this project are welcome. Feel free to open an issue or submit a pull request for improvements or bug fixes.

