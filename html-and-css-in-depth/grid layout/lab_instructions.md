# Create a grid layout


 ##### **Tips: Before you Begin**
> - To view this file in Preview mode, right click on this LabInstructions.md file and `Open Preview`

<br>

## Introduction

In this lab you will be creating a Grid layout commonly called the Holy Grail layout.&#x20;

## Goal
* To create a grid layout implemented using the grid template area
## Objectives
* Add styling to the CSS page with the help of grid template area
* Configure rules for different properties inside the grid template area

## Instructions

Initial code for the HTML is already provided. The rules for different areas within the grid template area are already provided in the CSS code. You will add the rules for the container class in the **gridtemparea.css** file.&#x20;

The two set of rules to be added for the container class will have one set for regular ‘container’ class and another using media query for a different size. Follow the instructions below:&#x20;

It is helpful to check the output of your code at every step.&#x20;
```
```
First, write rules by adding properties for the ‘container’ class as below:

&#x20;
**Step 1:**  Add a display property that will create a grid.
&#x20;
```
```
&#x20;
**Step 2:**  It will have a maximum width of 900 pixels.
&#x20;
```
```
&#x20;
**Step 3:**  The minimum height for it will be the length of 50 viewport height
&#x20;
```
```
&#x20;
**Step 4:**  Now you will first add rule for grid template columns that will span 100 % of the width.&#x20;
&#x20;
```
```
&#x20;
**Step 5:**  You will then add rule for grid template values for five rows, of which the middle one will have value of 1 fractional area and the rest will be set to auto.&#x20;
&#x20;
```
```
&#x20;
**Step 6:**  Finally, you will create a grid template area that will contain five values viz. ‘header’, ‘left’, ‘main’, ‘right’ and ‘footer’
&#x20;
```
```
&#x20;
&#x20;
Similar to the rules you have defined above, you will again add different set of rules inside the media query when the minimum width of the viewport is 440 pixels.&#x20;
&#x20;
The rules to be added for the container ‘class’ will be as below:&#x20;
&#x20;
&#x20;
```
```
&#x20;
**Step 7:**  The three grid template columns will have respective values of 150 pixels, 1 fractional area and again 150 pixels.&#x20;
&#x20;
```
```
&#x20;
**Step 8:**  The three grid template rows will have the middle value of 1 fractional are, while the two others will be set to auto
&#x20;
```
```
&#x20;
**Step 9:**  Finally this time, you will be creating a 3 x 3 grid template area that will have only header in the first row. It will have  ‘left’, ‘main’ and ‘right’ in the second row and finally have only ‘footer’ in the last row.&#x20;
&#x20;
```
```
&#x20;
&#x20;

Now when you preview your code you should see a layout similar to the screenshots provided.  

After completing all the steps you can compare you code with the code provided in the **solutionfile.css**.