# Challenge10_Repo
Crypto Clustering - Combining financial Python programming with unsupervised learning

# User Story
Role: Advisor FinTech Consulting Firm

Goal: The project goal is to combine financial Python programming with unsupervised learning to create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods and also plot the results and visually show the performance to the board

Reason: As competitors are fiece, a novel approach is being proposed to assemble investment portfolios that are based on cryptocurrencies. Instead of basing the proposal on only returns and volatility, other factors that might impact the crypto market—leading to better performance of the portfolio are included. Also included in this package is the creation of a prototype for submitting crypto portfolio proposal to the company board of directors.

# General information 
This project is cloned in the GitHub repository using the command line to add the relevant codes along with commit messages.
Each code line also has relevant commented out notes that are easily understood  

# Technology
Jupyter notebook that contains data preparation, analysis, and visualizations 
%matplotlib inline
Python

# Libraries used in the analysis
The following libraries were imported and used in the project.
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler

# Analysis and Visualisation
The following key requirements were achieved in the project:
Import the Data (provided in the starter code)
Prepare the Data (provided in the starter code)
Find the Best Value for k Using the Original Data
Cluster Cryptocurrencies with K-means Using the Original Data
Optimize Clusters with Principal Component Analysis 
Find the Best Value for k Using the PCA Data
Cluster Cryptocurrencies with K-means Using the PCA Data 
Visualize and Compare the Results by creating a composite plot using hvPlot and the plus (+) operator 