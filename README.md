Module 14 Homework

# Belly Button Biodiversity Dashboard

## Description

The Belly Button Biodiversity Dashboard ia an interactive web application that visualizes data from the Belly Button Biodiversity study. This dataset catalogs the microbial species (Operational Taxonmic Units, or OTUs) found in humnan navels and reveals intriguing insights about microbial diversity.

The dashboard allows users to explore individual data samples through interactive visulizations like horizontal bar charts, bubbles charts, and metadata panels. By dynamically updating charts and metadata based on user selections, the app provides a user-friendly interface to better understand microbial compositions.

## Background

The Belly Button Biodiversity study found that while a small number of microbial species were present in over 70% of participants, most species were relatively rare. This dashboard was built to explore this fascinating dataset interactively.

## Features
* Metadata Panle: Displays demographic information for each individual, such as age, gender, and location.
* Horizontal Bar Chart: Highlights the top 10 microbial OTUs, found in each individual.
* Bubble Chart: Provides a detailed view of all OTUs, showing relationships between OTU IDs, sample values, and labels.
* Dynamic Interactivity: Updates all visualizations when a new sample is selected from the dropdown menu.

## Files 
The project includes the following key files:
* index.html: The main HTML file that loads the dashboard.
* sampl.json: The dataset used for the visualizations (accessed via a static URL).
* app.js: Contains the JavaScript logic for building charts and metadata panels.
* styles.css: Custon styles for the dashboard layout.
* static/: Folder containing additional assets (like JavaScript and CSS).

## Technologies Used
* HTML and CSS: To structure and style the application.
* JavaScript: For dynamic interactivity and data manipulation.
* D3.js: For data-driven document manipilation.
* Plotty.js: For creating interactive charts.
* GitHub Pages: For deployment.

## Installation
To run the project locally, follow these steps:
1. Clone the repository:
`git clone https://github.com/jennibean-k/belly-button-challenge.git`
2. Navigate to the project directory:
`cd belly-button-challenge`
3. Open index.html in your browser to view the dashboard.

## Usage
1. Open the dashboard in your browser (either localley or via the deployed GitHub Pages link).
2. Use the dropdown menu to select an individual sample.
3. View:
    * The metadata panel for dempgraphic information.
    * The bar chart for top 10 OTUs.
    * The bubblw chart for all OTUs in the sample.

Explore how microbial diversity varies between individuals.


