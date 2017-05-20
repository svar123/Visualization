Summary

The visualization explains the survival rate of the passengers based on different factors like their gender, age and the class in which they travelled. This information is presented in a stacked bar chart with a count showing the number of passengers who survived and those who did not survive.


Design

A normalized stacked-bar chart was created for three scenarios. I used a stacked bar chart since there was only two groups to compare (Survived or Not Survived) and x-axis was discrete.
1. 'Sex' and the 'count' of passengers
2. 'Age' and the 'count' of passengers
3. 'Pclass' and the 'count' of passengers

The graphs also show the count of the number of passengers who survived and who did not survive.By clicking on the buttons the reader can navigate through the three scenarios and get a good understanding of which factors likely helped in the survival and reach at their own conclusion. From the bar charts the reader can find that being female, young (child, youth or adult)  and travelling in 1st class were favorable factors for survival.

The code for this visualization is written using D3 and Dimple libraries. First I defined the chart dimensions, created three new columns called 'Status', 'AgeGroup' and 'Count'.The 'Status' column has two values - Survived and "Not Survived', the column 'AgeGroup' has four groups - child, youth, adult and senior and 'Count' is the number of passengers. The charts were plotted with the 'count' on the y-axis and 'Sex', 'AgeGroup' and 'Pclass' on x-axis for the three charts respectively. Then 3 buttons were created to help the reader navigate through the three charts. A legend is added that aids the understanding of the chart.

After receiving the feeback, I changed the following:
1. The default colors of the stacked bar chart from blue/orange to blue/gray.
2. Added the values of survived or not survived in the bar graph. 
3. Made the button size smaller.
4. Used percentage measure for y-axis so we can easily see the numbers.

Feedback

1. What do you notice in the visualization?
   I noticed the fact that more passengers perished than those that survived.

   What questions do you have about the data?
   I want to know the number of passengers.

   What relationships do you notice?
   I noticed a strong relationship between gender and survival.

   What do you think is the main takeaway from this visualization?
   Some factors really helped the survival.

   Is there something you don’t understand in the graphic?
   No.

2. What do you notice in the visualization?
   The default blue and orange colors are too bright. The buttons are too wide.

   What questions do you have about the data?
   None.

   What relationships do you notice?
   Being female and young likely helped survive.

   What do you think is the main takeaway from this visualization?
   Most passengers who survived were young,female and travelled in 1st class.

   Is there something you don’t understand in the graphic?
   The graph is very clear.

3. What do you notice in the visualization?
   Good choice of colors and good visualization.

   What questions do you have about the data?
   Was the data tidy and cleaned?

   What relationships do you notice?
   I can clearly understand that sex, age and class were important factors in survival 
   of the passengers.

   What do you think is the main takeaway from this visualization?
   Main takeaway is that a combination of factors helped in survival.
 
   Is there something you don’t understand in the graphic?
   No.

Resources

1. D3.js API documentation https://github.com/d3/d3-3.x-api-reference/blob/master/API-Reference.md
2. Dimple.js documentation http://dimplejs.org/ 
3. https://www.w3schools.com/js/js_htmldom.asp
4. udacity discussion forum
5. http://simondfletcher-blog.azurewebsites.net/add-a-title-to-a-dimple-js-chart/

