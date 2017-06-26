

# Data Visualization: Titanic Data Visualization

By Sargam Shah 

## Summary

This project depicts a visualization story created in tableu using different graphs. It shows number of survivals based on classes, age groups & sex. It draws conclusion that female of first class had higher chances of survival and males of third class had least chances of survival. In general, females had higher chances of survival than males.

## Design

Exploratory Data Analysis 
I downloaded the data from Kaggle - Machine Learning from Disaster, selecting a train data set which already had basic finding & doesn't need extensive data wrangling or transformation.I briefly use course techniques from Exploratory Data Analysis with Tableau and came up with few initial hypothesis. While exploring the data, I believed female passengers will have a better survival rate than male (according to what I've seen from Titanic movie). According to the course content, I decided to use bar charts to visualize those assumption, which would be displayed further down below.
 
I considered using multiple chart types (line chart, bubble chart, bar chart, etc.), make use of color, markers and filters to visualize my data. I re-evaluated different chart type by trial and error and confirm my initial assumption, a bar chart is already sufficient to dislay data characteristic. Then, I also created new data-type which involved breaking continuous age data into bins of width 5. The first version is as follows:

https://public.tableau.com/profile/sargam6270#!/vizhome/Titanic_Tableau/Titanic?publish=yes

Feedback
I gathered feedback from a person and tried to follow Udacity questions guideline and here is the abridged responses.
### Interview #1

Your chart was a bit messy & no consistent headlines & legend. I am not sure what S, C etc. stand for in the next chart. It will be better if you show percentage instead of age at the survival graph. Overall, it is a nice attempt and conclusion is clear.  
 
Post-feedback Design
Following the feedback from the 3 interviews, I implemented the following changes:
I resized all the dashboards to make them visually appealing.
I added careful chart title & clearly labeled axis title.
I corrected labeling errors found in many charts.
I also used consistent color theme to make the visualization more aesthetic.
Final rendition of the data visualization is shown below: 

## Resources
 

 
## Data

train.csv: original downloaded dataset with minor cleaning for dimple.js implementation.
