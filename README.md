# Viz_with_dimple

# Summary

Here we have a bar chart of the handedness (right handed, left handed, or both handed) of 1,157 baseball players. In this chart we are comparing the average of all the home runs that those player have hit and we are grouping them by their handedness. Here we see that left handed player have more home runs on average than right handed or both handed players

# Design

In the first sketch I originally plotted, it was a scatter plot of batting average and home runs coloured by handedness. After the feedback I received, I changed it to a bar plot of average home runs hit by handedness. This plot conveys the difference between handedness of baseball player. I choose a bar chart because they are really good at showing differences between categories. For color I decided to use a strong looking color to draw attention to the left handed category and a pale or more greyish looking color to the other categories. By doing this, I make the left handed bar stand out more because of the difference in colors. 

For the x-axis I used the category handednes, my reasons were because the graph is a bar chart and the message that it conveys it a comparison, so using a categorical variable as handedness it is easy to make comparisons because there are three categories. Take for example, we could have used height, but it's very variable and to really make something usefull of it, it should be grouped and by grouping there is some loss of information. For the y axis the variable was home runs by player, but I choosed to used the average. The reason was that the average convey more information than a simple sum of home runs by handedness. While looking at the average we can compare almost equally all the categories but, if it was a sum making comparisons would be much harder; just because there are more right handed players it would be almost certain that they would have more home runs. For the order of the y-axis, I changed the order so that the left handed bar was at the left, the right handed at the right and both handed in the middle. It mimicks hand positions. (thanks to the reviwer.)

# Feedback

The first person that gave me feedback was my girlfriend. With the first sketch, that was the scatter plot, the feedback that she gave me is that there was relation between batting average and home runs, but it was not so clear and that the plot was too clutered up, it has to many points. There was no clear distinction betwwen points and that obscured that relation. After that I made a bar plot of handedness and home runs, the feeedback she gave was that is showed sum of home runs and it's not something that is informative at all and even suggested to use average of home runs by handedness. And so, the last one was instead of sum of home runs it was average of home runs by handednes. After playing with the colours she told me to higlight the left handed bar so that the findings were the first thing people see when they look at the chart.

The second person was my brother. The feedback he gave for the first sketch was that there were to many points, but he told that he clearly saw a trend in the points, the greater the average batting the more home runs that player gave. He told me it looked exponential. With the second sketch, he didn't like it. To him that chart didn't make any sense, hen said that the sums of home runs by handedness were boring. But he suggested that I should try something else instead of sum. And I did, when I showed him the final graph, average home run by handedness, his feedback was mostly positive. The only things that he pointed me were to change label names and play a little with the colours.

The third person was a coworker. He only gave me feedback for the second and final graph. With the second te first his feedback was that I should change label names to something more explicit and that sum of home runs is not informative at all. When I showed him the final graph, the first he said was to change colours so that the left handed bar was more prominent. He insisted with changing the labels and even the tooltip information, so that they were more explicit.

# Resources 

https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.series

http://dimplejs.org/advanced_examples_viewer.html?id=advanced_custom_styling

https://stackoverflow.com/questions/32618638/override-dimple-tooltip-text-only

https://stackoverflow.com/questions/25774821/dimple-js-axis-labels

https://stackoverflow.com/questions/25127527/how-to-change-color-of-line-in-line-chart-using-dimple-js

https://stackoverflow.com/questions/25015266/ordering-columns-in-a-stacked-bar-chart-dimple
