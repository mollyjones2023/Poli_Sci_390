# Visualization Blog 2: Adding Uncertainty

## Plotting Uncertainty

### Plot 1
![Uncertainty of Brexit Plot](images/uncertainty_plot1.png)

I chose to use geom_ribbon to visualize uncertainty because the line is continuous, and I wanted something to wrap around the lines. I tried using two line to represent the uncertainty, but it looked cluttered and didn't visualixe the range of values that the correct number could be. I made it transparent because the ribbons overlap, and I wanted to make sure you can see all of them.



### Plot 2
![Uncertainty of Police Shootings Plot](images/uncertainty_plot2.png)

I created a new plot based off of my old bar plot because it was made up primarily qualitative vales, and I didn't understand how to make an error bar for any other form that would work with that section of the data besides a bar plot. I used an error bar to display the error because there are individual points in this plot so the error bar capture the uncertainty of each individual point. I made the bar red to distinguish it from the point and made the ends wider to better see them. I also made the image wider so that it didn't look so cluttered. 

### Attempt to create a visual for both age and number of shootings
![Uncertainty of Police Shootings Plot 2](images/uncertainty_plot2_1.png)

I also made this plot to include the uncertainty with age, but I thought it was confusing to look at. However, I think it capture the uncertainty more accurately since the uncertain values are somewhere in between the axes that the error bar creates.

