# Sentiment_Analysis_Youtube

**Overview**

This project is a part of a group effort to analyze the sentiment of YouTube comments comparing the United States and Great Britain. We aim to explore the differences in sentiment between these two regions, and consider the effect of the comments sentiment to the interaction on a video.

**Contents**

1. Introduction - Background and objectives of the analysis
2. Data Importing & Cleaning - Loading and preparing the YouTube comments dataset
3. Exploratory Data Analysis - Uncovering insights through detailed data exploration
4. Comment Volume Analysis - Comparing number of comments between US and UK
5. Comment Length Analysis - Distributions of comment character length
6. Sentiment Polarity Analysis - Using VADER model to score comment sentiment
7. Emoji Analysis - Extracting and analyzing use of emojis
8. Engagement Analysis - Statistical analysis of likes, dislikes, replies
9. Topic Modeling - Using NMF and LDA to extract discussion topics
10. Interactive Visualizations - Plots generated using Plotly Express and Dash
11. Model Development - Training sentiment classification and engagement prediction models

**Datasets**

1. USvideos.csv and UScomments.csv - Video metadata and comments from United States
2. GBvideos.csv and GBcomments.csv - Video metadata and comments from United Kingdom

These CSV files contain samples of YouTube data scraped and published on Kaggle.

**Technologies Used**

1. Python
2. Jupyter Notebook
3. Pandas
4. NLTK
5. Matplotlib
6. Seaborn

**Results**

The sentiment analysis revealed interesting patterns in the comments from both countries. Further details can be found in the Jupyter Notebook provided in this repository.

**Future Work**

Improve sentiment analysis accuracy by using more advanced natural language processing techniques.
Extend the analysis to include comments from other countries for a broader comparison.

**How to Run**

Clone the repository
Install dependencies like pandas, nltk, scikit-learn
Run jupyter notebook to start Jupyter
Open the youtube_comments_analysis.ipynb notebook
Run the cells in order to reproduce the analysis
Alternatively, view youtube_comments_analysis.html to see a static HTML export of the executed notebook.

**Contributors**

1. Aryan Jain
2. Devesh Talreja
3. Micah Billington
4. Rupesh Rangwani

**Credits**

Thanks to DataSnaek for curating and releasing the YouTube comments dataset on Kaggle.

**MIT License**

Copyright (c) [2024] [Aryan Jain, Devesh Talreja, Micah Billington, Rupesh Rangwani]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

