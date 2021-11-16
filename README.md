# Challenge10_Repo
Crypto Clustering - Combining financial Python programming with unsupervised learning

# User Story
Role: Advisor FinTech Consulting Firm

Goal: The project goal is combine financial Python programming with unsupervised learning create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods and also plot the results so that you can visually show the performance to the board

Reason: As competitors are fiece, I am proposing a novel approach to assembling investment portfolios that are based on cryptocurrencies. Instead of basing my proposal on only returns and volatility, I am including other factors that might impact the crypto market—leading to better performance for my portfolio. I am also creating a prototype for submitting my crypto portfolio proposal to the company board of directors.

# General information 
This project is closned in the GitHub repository and the command line is used to add the relevant file along with commit messages.
Each code line also has relevant notes that are easily understood commented out 

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