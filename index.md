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
<img src="lineplot.png" alt="Line plot of average understanding by own_examples" width="500">
<img src="own_examples_histogram.png" alt="Histogram of own_examples responses" width="500">
<img src="understanding_histogram.png" alt="Histogram of understanding responses" width="500">

## Final Conclusions
In conclusion, my analysis of the data is somewhat inconclusive, though it somewhat supports my idea that the course should encourage students to create their own examples when learning new concepts, as this can improve students' understanding. The line plot shows that students who reported creating their own examples when they were uncertain about how concepts work tend to have a higher average understanding. There is a visualized positive relationship between the two variables. 

However, the difference in understanding scores is too small. For example, those who reported never creating examples had an average understanding score of around 3.6, whereas those who reported always creating examples scored around 4.5. The increase in understanding is not significant, given the range of creating one's own examples. Also, the trend is not very consistent. The average understanding score decreases from 2 to 3 for own_example, and from 6 to 7. The histograms also show that most students are clustered around the middle of the scale, while fewer students selected the extreme values. Because of this, the averages for some groups may be less reliable.

Additionally, correlation does not imply causation, meaning that creating one's own examples does not necessarily lead to a better understanding. Some confounding relationships, such as the fact that students who already understand the material may be more comfortable creating their own examples.

To build more confidence in assessing my idea, a small experiment could be done. For example, students are randomly assigned to a treatment and a control group. This random assignment ensures that no confounding variables, such as students' initial coding abilities, are present. The treatment condition is that students are required to generate their own example for a new course concept, which could be part of their LS assignment. The controlled condition is just our normal course condition. The measurable dependent variable could be people's quiz grades. An average grade can be calculated and compared across two groups to see whether this course concept example actually influences people's understanding.

Finally, regarding potential costs, trade-offs, or stakeholders who may be negatively affected by experimenting with my idea, one cost is that requiring students to create their own examples could increase the time they spend on LS assignments. Students who struggle with the course may feel overwhelmed if they are required to do more work. It is not fair for the treatment group to take this responsibility. Another trade-off is that the course staff need to spend extra time grading this example because it is not convenient to use Gradescope or AI to grade free-response questions, unlike multiple-choice questions. Course staff may also need to spend extra time designing prompts and giving feedback.