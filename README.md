# Instructions and template for Assignment 1

The purpose of this assignment is to ensure that you are becoming more comfortable working with Python scripting. Additionally, this assignment will demonstrate that you are comfortable with the Github Classroom workflow that we'll be using this semester.

## Task

In the Advanced Scientific Computing workshop, we wrote a short piece of code which loaded a CSV file, created a scatter plot with a regression line plotted over the top, and saved the results.

In this assignment, you should write a script which reads the CSV file in the data folder and produces the same kind of output - a scatter plot with a regression line over the top.

In particular, your should:

- Make sure to use a ```main()``` function
- Use ```argparse()```
- Include a requirements file
- Include a detailed README indicating what a user needs to do to get it to work (set up virtual environment, install requirements, etc)

## Additional task

If you have completed the above, try and modify your code to split the data into *male* and *female* and create a scatter plot with regression line for both.

You could perhaps include a specific flag using ```argparse()```, so that users can decide if they want a visualisation for all data points, only female, only male, or both separately.