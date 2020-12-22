# Matplotlib Challenge

This is an assignment I completed for the [UCSD Extension Data Science Bootcamp](https://bootcamp.extension.ucsd.edu/).

## The Assignment

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Tools Used

Python

MatPlotLib.PyPlot

Pandas

SciPy

NumPy

## How I Did It

After importing dependencies, loading and mercing the two csv files my datapath was setup. I cleaned up the data with pandas, removing duplicate mouse IDs. I then found the statistics of the tumor volumes of the mice in the dataset, and the statistics of the drug regimen used to treat the mice.

Bar charts were then made using pandas and matplotlib.pyplot, as well as pie charts, to show the total number of treatments of each drug reginmen as well as a break up of gender of mice.

I generated box plots of four of the drug regimen and the total volume of the tumor. Isolating a single drug regimen and using a line plot shows how the drug regimen affected the volume of the tumor on mice over time. Which fortunately decreased the size of the tumor!

A scatter plot shows the average weight of the mouse against the average tumor size, and then with linear regression we can clarify that the weight of the mouse goes up with the size of the tumor.

## Thank You for Reading My ReadMe!

Thank you for reading my readme! Feel free to message me on GitHub or LinkedIn if you would like to connect.

[GitHub](https://github.com/mrryanlittle) - [LinkedIn](https://www.linkedin.com/in/ryanlittle01/)

