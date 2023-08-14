# **UCB FinTech Bootcamp Module 7 Challenge**
# *Managing Pasive Income : SQL Financial Databases in Python*
## **Introduction**
### The Bootcamp Module 7 Challenge - Managing Pasive Income : SQL Financial Databases in Python aims to create a web application that analyzes the performance of a hypothetical fintech ETF. The application utilizes SQL, Python, and the Voilà library to provide insights into the daily and cumulative returns of the ETF's constituent stocks.
---
## **Goals and Objectives**
### The primary goals of this project are as follows:
### - Analyze the daily and cumulative returns of individual stocks within the ETF.
### - Optimize data access using advanced SQL queries.
### - Evaluate the performance of the entire ETF portfolio.
### - Deploy the analysis as an interactive web application using the Voilà library.
---
## **Technologies and Tools**
### The following list includes the main technologies and tools using during the preparation and deployment of the solution:
### 1. *Python* - Programming language used to code the solution. Version 3.7.13 was used. Required libraries and frames listed in the Installation section below
### 2. *GitHub* - Reposotory for code deployment, version management and documentation of the presented solution
### 3. *Jupyter Labs* - IDE tool for coding, code testing/debugging and solution documentation. Version V3.4.4 was used
### 4. *Git Bash console* - Local console used to test the coded solution and sync wiht GitHub Version 2.40.0.windows.1 was utilized
### 5. *Slack* - Collaboration tool to communicate and brainstorm with other FinTech Bootcamp participants
### 6. *Operative System* - This solution was prepared in a PC running Windows 11 v H22
### 7. *[pandas](https://pandas.pydata.org/docs/)* - Pandas is a popular Python library for data manipulation and analysis. It provides data structures like DataFrames for handling and analyzing structured data effectively. In the code, Pandas is used to display the PyChain ledger as a DataFrame. Indysllation details below.
### 8. *[hvPlot](https://github.com/holoviz/hvplot)* - hvPlot is a high-level plotting library that provides an interface to generate interactive visualizations using the HoloViews library. It allows you to create visualizations with just a few lines of code and is especially well-suited for data analysis in Jupyter notebooks.
### 9. *[Voilà](https://github.com/voila-dashboards/voila)* - Voilà is a library that helps you turn Jupyter notebooks into interactive web applications. It allows you to deploy your Jupyter notebooks as standalone web applications without the need for any additional coding.
#### For additional details, please refer to the watermark output at the bottom of the `etf_analyzer.ipynb` Jupyter Notebook
---
## **Installation Guide**

### 1. *pandas*: To install Pandas follow the below instructions:
#### 1.1. Open the GitBash terminal
#### 1.2 Type the following command and press Enter:
```python 
pip install pandas
```
### 2. *hvPlot*: To Install hvPlot follow these steps:
#### 2.1. Open the GitBash terminal
#### 2.2 Type the following command and press Enter:
```python 
pip install hvplot
```
##### **Note** Keep in mind that hvPlot is built on top of HoloViews and other libraries. Depending on your needs, you might need to install additional libraries. For example, if you want to use the interactive features, you might also need to install Bokeh:
```python 
pip install bokeh
```
### 3. *Voilà*: To Install Voilà follow these steps:
#### 3.1. Open the GitBash terminal
#### 3.2 Type the following command and press Enter:
```python 
pip install voila
```
---
## **Solution Structure**

### The **[7.PasiveInvesting](https://github.com/LUTOV001/7.PasiveInvesting)** repository in GitHub contains the solution components. The repository consists of the following folders and contents as described below:
###   *1. gitignore :* Instructions for which files/file types to exclude from the sync process between GitHub and the local environment.
###   *2. README.md :* The present file containing this outline of the challenge and its components and results.
###   *3. etf.db:* SQLite database containing stock data tables..
###   *4. etf_analyzer.ipynb:* This is the Jupyter Notebook containing the Python code for the challenge solution.
---
## **User Instructions**
### 1. Run the Jupyter Notebook `etf_analyzer.ipynb` to execute the analysis code.
### 2. Follow the instructions within the notebook to complete each section.
### 3. Once the analysis is complete, you can deploy the notebook as a web application using Voilà:
```python 
voila etf_analyzer.ipynb
```
### 4. Access the web application through the provided link
---
### **Credits**
#### Prepared by Luis Torres 
#### [LUTOV001](https://github.com/LUTOV001)
#### August 2023