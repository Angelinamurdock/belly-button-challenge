# JavaScript Belly Button Biodiversity App
**Creator**: Angelina Murdock  
**Date**: March 2025

## Description
A interactive project exploring the biodiversity of belly buttons using **JavaScript**. This app allows users to visualize different species of bacteria found in the belly buttons of various test subjects, displayed using data visualizations and interactive charts.

## Table of contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Deployment](#deployment)
- [Methodology](#methodology)
- [Resources](#resources)

## Features
**samples.json:** Contains demographic information and sample data for all of the test subjects, including bacteria culture data.

**app.js:**
- Implements a bar chart to visualize data of the top 10 bacteria cultures found in each test subject.
- Implements a bubble chart for visualizing data of the number of bacteria cultures per sample by OTU ID.
- Loop through metadata to get the demographic info for each imdividual and populates it into a panel.

**index.html:** The main HTML file that connects all components of the app.

## Installation
### Set up and  Usage instructions
1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser to view and interact with the app.
3. Use the dropdown menu to select a specific test subject ID. The visualizations and demographic panel will update based on the selected ID. 

## Deployment
This app is deployed on **GitHub Pages**, making it accessible from any web browser. To view the app live:
1. Go to the repository's GitHub page.
2. Click on the "Settings" tab.
3. Scroll down to the GitHub Pages section.
4. Select the branch you'd like to deploy (typically main or master).
5. After a few moments, your app will be available at https://<username>.github.io/<repository-name>/.

**Dashboard Example:**
![Dashboard Example](https://github.com/Angelinamurdock/belly-button-challenge/issues/1#issue-2961608621)

## Methodology
### Data Processing and Visualization
- **JavaScript Functions**: The app relies on JavaScript functions to handle data extraction, dynamic visualization updates and interactivity. Key functions include:
- Loading and parsing JSON data from `samples.json`.
- Uploading charts and panels based on user interaction.
- **Plotly Data Visualizations**: The app uses Plotly to create interactive bar and bubble charts. Plotly allows users to interact with the data points, making the visualizations both informative and engaging.

## Resources
* **Belly Button Biodiversity dataset:** https://robdunnlab.com/projects/belly-button-biodiversity/ 
* **Plotly Documentation:** https://plotly.com/javascript/ 
* **DU Bootcamp Module 14:** Utilized challenge files and class materials from the bootcamp.
* **ChatGPT:** Assisted with code explanations and debugging.
