---
# Do not edit the text between these lines!
layout: default
---

# Kaiyuan's Website

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="custom_path/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## Basic Information

This is a website created for the EX09 assignment for comp110.

## Summary of the Analysis
For my analysis, I explored whether the course should encourage students to create their own examples when learning new concepts, as this may help improve students’ understanding of the material. I focused on two variables from the survey data: own_examples and understanding. The own_examples variable measures how often students try to come up with their own examples in code when they are uncertain about a concept, and the understanding variable measures how well students feel they understand the course material. I began by reading the CSV data into Python and converting it into a column-based table. I checked the first three values in each row to ensure the data loaded correctly using the head function. Then I selected only the columns needed for my analysis: own_examples and understanding. Since the data were originally stored as strings, I converted them to integers for calculations and visualizations. I also used the count function to examine the frequency of responses of each value in own_examples. To analyze the relationship between the two variables, I calculated the average understanding score for each value of own_examples. Then, I can compare whether students who reported creating their own examples more often also report higher understanding. I then created three visualizations: a line plot showing average understanding by own_examples,a histogram of own_examples, and a histogram of understanding. The histograms showed how the responses were distributed, while the line plot showed whether there was a possible relationship between creating one’s own examples and course understanding.

## Visualizations
