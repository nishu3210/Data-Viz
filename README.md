# A visual journey of how our world has changed in data

This project was part of my masters in data science at IU for the data visualization course. The purpose is to **use visualization tools and techniques in python** to explore the World Development Indicator data by the World Bank.

## Abstract

This project is about getting insights from the World Development Indicator dataset provided by the World Bank and explore other related datasets, and in the process validating the results presented in the book “Factfulness” by Hans Rosling. And finally, being able to at least explore if not answer the question: is world a better place than we think?

All of the work is done in python. A html copy of Jupyter Notebook is uploaded for reference as "plotly" charts won't load in Github in the .ipynb file.

## Python Packages used
- Plotly
- Pandas
- Matplotlib
- Cufflinks
- Seaborn

### What is iplot?
Instead of using *pandas.plot*, here I used *pandas.iplot* to make interactive plots using plotly as backend. 

### Color Scale
The aim was to use the *"viridis"* color scale as it is color blind friendly and hence great for visualization which can be shared with anyone. But cufflinks didn't had inbuilt support for viridis at that time hence, a close match which is *'ylgnbu'* is used everywhere in this project.