


# Data Visualization: Titanic Data Visualization

By Sargam Shah 

## Summary

This project depicts a visualization story created in tableu using different graphs. It shows number of survivals based on classes, age groups & sex. It draws conclusion that female of first class had higher chances of survival and males of third class had least chances of survival. In general, females had higher chances of survival than males.

## Design

Exploratory Data Analysis 

I downloaded the data from Kaggle - Machine Learning from Disaster, selecting a train data set which already had basic finding & doesn't need extensive data wrangling or transformation.I briefly use course techniques from Exploratory Data Analysis with Tableau and came up with few initial hypothesis. While exploring the data, I believed female passengers will have a better survival rate than male (according to what I've seen from Titanic movie). According to the course content, I decided to use bar charts to visualize those assumption, which would be displayed further down below.
 
I considered using multiple chart types (line chart, bubble chart, bar chart, etc.), make use of color, markers and filters to visualize my data. I re-evaluated different chart type by trial and error and confirm my initial assumption, a bar chart is already sufficient to dislay data characteristic. Then, I also created new data-type which involved breaking continuous age data into bins of width 2. 

SURVIVAL BY GENDER GRAPH
Why did you choose a specific chart type over the other types? or What makes that chart, legend, layout, etc a good choice to represent the data?

I chose bar chart to represent the passengers accross gender because bar charts provide great comparison view between entities. I chose to filter the bars using passenger survival status and color because this way we will come to know whether female passengers had higher level of survival or the male out of the total passengers on board. I chose age as a filter because viewer might be interested in knowing the results by age groups.

SURVIVAL BY AGE GRAPH
Why did you choose a specific chart type over the other types? or What makes that chart, legend, layout, etc a good choice to represent the data?


Here, we want to answer whether older people have higher chances of survival or vice versa. Age is a continuous datatype ranging from 0 to 74. I decided that histogram would be a nice representation of the distribution of the data and the nature of the distribution as well. If the distribution turns out to be normal, I can say that people of older age group or younder age group did not have high chance of survival. 
I converted age into discrete bins of age 2. I plot the histogram using bars in order to represent my visualization in a more appealing manner. I put filter color as survived or died as we are interested in knowing whether a passenger of certain age group had higher chances of survival or chances of dying. 
I also put filter as class as the viewer might be interested in knowing whether a certain age group of first class survived more as compared to third class. 

FINAL SURVIVAL GRAPH
Why did you choose a specific chart type over the other types? or What makes that chart, legend, layout, etc a good choice to represent the data?
I chose bubble graph to represent which gender had highest chances of survival belonging to which class as well. The beauty of bubble graph is that the most prominent group would bubble up and have the largest size. Thus, the viewer can instantly come to know the conclusions. I created a set named "most likely to survive" for female and put it as a filter to show which bubble belonged to this set. This bubble represents the passengers most likely to survive. I also put filters in case the viewer is only interested in knowing a certian class such as first class only.


**First version is as follows:**
https://public.tableau.com/profile/sargam6270#!/vizhome/Titanic_Tableau/Titanic?publish=yes

## Feedback
I gathered feedback from a person and tried to follow Udacity questions guideline and here is the abridged responses.
### Interview #1
![alt text](https://github.com/Sargam5360/Tableau-Story/blob/master/ii.png)
 
## Post-feedback Design

Following the feedback from the interview, I implemented the following changes:
I resized all the dashboards to make them visually appealing.

Following her feedback, "it opened on 'a reminder of..'", which was my last dashboard of the story, 
I realized the problem and fixed it so that my story opens at the first dashboard and the user can navigate along. 

From her second feedback regarding lots of babies aged 0, 
I decided to apply filters and remove all invalid entried from the age column. 

From her third feedback, 
I realized that I need to tell a story and not just create charts. Thus, I created my story first using blank cards.
Then I reverse engineered to create the dashboards and then the sheets. This really helped me.

Following her fourth feedback "What's survived 0/1?", 
I added careful chart title & clearly labeled axis title.
I corrected labeling errors found in many charts.
I also used consistent color theme to make the visualization more aesthetic.
She was not clear what Embarkment was. When I revisited the dashboard, I realized that the graph on which passenger boarded from which area served no purpose to my story. Hence, I decided to remove that graph altogether. Gold plating in terms of excessive data is unnecessary.

**Final rendition of the data visualization is shown below:**
https://public.tableau.com/profile/sargam6270#!/vizhome/Tableau_Titanic_Sargam_Final/Story1?publish=yeshttps://review.udacity.com/#!/reviews/577559/shared

## Project Review 
You can find what the reviewer thought about the project in the below link:
https://review.udacity.com/#!/reviews/577559/shared

## Resources
Udacity course on Tableau 
Tableau Resources

 
 
 
