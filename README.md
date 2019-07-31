# About

This repository accompanies the dissertation for the **MSc Business Analytics (with specialisation in Management Science) Consultancy Project/Dissertation 2018-19**. This repository contains the code used in the **social network analysis** and **topic modelling** of the projects funded by Innovate UK from 2004 up to 3 July 2019. 

Most of the code is in Python and a few lines of code are in javascript to aid in creating rooted network tree graphs with Vega, which uses D3.js as a backend. 

# Files
The main files in this repository are:
-  Dissertation.ipynb
	> Contains all the code for the network analysis and topic modelling.
	
- Interactive_visualisations.ipynb
	> Calls all the interactive visualisations for the network analysis, topic modelling as well as the geospatial visualisations. These visualisations were not included in the dissertation because it was a plain document in PDF. However, the interactive visualisations are included here.

The content folder contains:
- Interactive visualisations in HTML 
 	> These are the interactive visualisations called and loaded within the jupyter notebook of Interactive_visualisations.ipynb
- Pickle files (.p)
  	> Saved pre-processed dataframes and layouts that can be loaded back in the jupyter notebook of Dissertation.ipynb.
- Image files (.png)
  	> Created network graphs, statistical graphs and charts.
 - JSON files (.json)
 	> Files created to use as input to Vega and ipysankeywidget. Both use D3.js as the backend to render the input into network graphs or sankey diagrams.
