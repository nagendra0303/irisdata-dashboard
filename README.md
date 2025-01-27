#Dashboard of Iris Dataset

This project is a Flexdashboard with interactive visualizations of the Iris dataset using R, flexdashboard, plotly, and shiny. The dashboard includes three main sections: Histogram, Boxplot, and Scatter Plot. Users can interactively select variables to explore the dataset's features and relationships.

Features

1. Histogram

Visualize the distribution of numeric variables.

Select the variable for the histogram using a dropdown menu in the sidebar.

Histogram is colored by species.

2. Boxplot

Display the summary statistics of numeric variables for each species.

Select the variable for the boxplot via the sidebar.

Boxplots are grouped and colored by species.

3. Scatter Plot

Examine relationships between two numeric variables.

Select variables for the X-axis and Y-axis from dropdown menus in the sidebar.

Scatter plot points are colored by species.

How to Run Locally

Prerequisites

Ensure you have the following R packages installed:

install.packages(c("flexdashboard", "ggplot2", "plotly", "shiny"))

Steps

Save the .Rmd file (e.g., iris_dashboard.Rmd) to your local machine.

Open the file in RStudio.

Click the Run Document button to launch the dashboard in your default web browser.
