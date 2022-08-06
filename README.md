# Ford GoBikes Data Exploration

## Dataset

The data consists of 183,412 records of features such as duration, birth years, start stations, end stations, gender, and types of users.


## Summary of Findings

In the exploration, I found that there was a relationship between the
duration of the trips and their ages. The curve shows a negative relation when duration is plotted on a logarithmic scale.

Outside of the main features of interest, it was interesting to see how the stations played their role in the duration of the trip. Gender played a part in how long the trips were. Most suprising was the type of user which showed customers were clocking more time than subscribers.


## Key Insights for Presentation

For the presentation, I put emphasis the duration of each trip. Initially I made a histogram of the duration on a logarithmic scale which produced a curve close to a normal bell curve.

I introduced age by plotting a heat map against the log of duration.
This curve suggested that the active participants were the younger generation.

Lastly I made a visual representation of age against the duration through the microscope of the user type. The best plot for this relationship was the multivariate scatter plot provided by seaborn.

I did not focus on stations against duration and age, because from prior exploratory analysis, the scatter plots produced were almost similar for both start stations and end stations.

Gender was not given any focus on the data because of the similar visual representations that they displayed when plotted as a hue against duration and age.