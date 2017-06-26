# Data Visualization: Titanic Data Visualization

By Sargam Shah 

## Summary

This project charts 3 different graphs. It shows number of survivals based on classes, age groups & Parents with Children.

## Design

Exploratory Data Analysis and Cleaning (R)
I downloaded the data from Kaggle - Machine Learning from Disaster, selecting a train data set which already had basic finding & doesn't need extensive data wrangling or transformation.I briefly use course techniques from Exploratory Data Analysis with Tableau and came up with few initial hypothesis. While exploring the data, I believed female passengers will have a better survival rate than male (according to what I've seen from Titanic movie). According to the course content, I decided to use bar charts to visualize those assumption, which would be displayed further down below.
 
I considered using multiple chart types (scatter, line chart, bubble chart, bar chart, etc.), color each line separately to test if this is a good way to visualize & stress on important point. I re-evaluated different chart type by tweaking few line of code and confirm my initial assumption, a bar chart is already sufficient to dislay data characteristic. Then, I also use Excel to do basic data munging (mute the blank age by inputing N/A), created new column called age group and divided into "15 age" bracket. The first versio is drawn from index-initial.html or image below:
This initial iteration can be viewed at index-initial.html, or below:
![First Chart](https://raw.githubusercontent.com/tommyly2010/Udacity-Data-Analyst-Nanodegree/master/p6 - Data Visualization/img/image-initial.png)
Feedback
I gathered feedback from 3 different people people and tried to follow Udacity questions guideline and here is the abridged responses.
### Interview #1

Your chart was a bit messy & no clear headlines & legend. If there is some explanation like a bold headline then these charts would make sense. The insights is not so much of a surprise and if you just create a small tweak in the legend, x-axis & y-axis then this would looks good. The data clearly favors your initial hypothesis, women children & elders are prioritized to board the baot first.
### Interview #2

The chart is interactive, that's nice. But why the second chart is revert and not in-line with the other chart. Switch x-axis & y-axis with each other and I think the chart will looks much better. By the way, the first chart to split between classes is cool but I think you can make it even better by combining gender & classes to see if there's different behavior in different classes. Broadly speaking, the chart looks intuitive & only needs a few small tweak.
### Interview #3

The second chart looks a bit weird and too much junk information, there's no need to include different age in different age bracket like that. There's not much information to show. And for the first chart, split the column into two, a stacked-bar wouldn't be necessary. Also, you also needs to clean up the headline & make clear of the axis, what is PClass? Can you makes it a bit clearer. Overall, this chart is straightforward.
Post-feedback Design
Following the feedback from the 3 interviews, I implemented the following changes:
I separate man & women from the first chart.
I added careful chart title & clearly labeled axis title.
I flipped the chart from horizontal bar chart to vertical bart chart.
I remove the individual age & only shows aggergrate age group.
I intended to add few special effect (highlight a chart when mouseover) but this would not be necessary.
I switched from Number of Survival to Survival Rates since the amount of passengers in each class/ages group is not similar.
Final rendition of the data visualization is shown below:
![Final Chart](https://raw.githubusercontent.com/tommyly2010/Udacity-Data-Analyst-Nanodegree/master/p6 - Data Visualization/img/image-final.png)

## Resources
 

 
## Data

train.csv: original downloaded dataset with minor cleaning for dimple.js implementation.
