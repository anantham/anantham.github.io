## My Projects

---

### DS 200 - Visualizing data from https://data.gov.in/

## Scatter Plot

When we have two paired numeric data. This sort of plot helps us confirm if there are any correlations. I turned to the [Railway Statistics Summary from 2002 to 2015](https://data.gov.in/resources/railway-statistics-summary-2002-03-2014-15). There were many items that was included in this data set but I thought that overall gross earning was a good metric for both how many trains ran that year, as well as the number of people. So the hypothesis was that if more people and more train ran then there must be more accidents. This was neglecting the fact that we get better at preventing accidents with time. But if look at the plot below you will note the points are close to the trend line until 2015.

![scatterplot](https://i.imgur.com/ydby0A8.png)

We see the deaths spikes around 2005 as the railway had to scale quickly with both deaths and earnings growing quickly. After that the deaths have stabilized even as earnings continued to grow rapidly over the years. 


## Box Plot

This type of plot is useful to see the shape of a distribution. Most of the data in https://data.gov.in/ seemed to be too small in number to really showcase the power of this plot. I finally decided to pick the [Weekly retail price of Milk from 2003 to 2012](https://data.gov.in/resources/weekly-retail-price-milk-upto-2012) dataset. After cleaning the data (removing NA), the box is shown below.

![boxplot](https://i.imgur.com/7mOkP5C.png)

From this plot we can observe that over the 9 year period milk price has varied considerably from as less as 7 Rs to 40 Rs (Min to Max). Even with an inflation of 15%, we can only explain upto 25 Rs. So this plot tells the story of the increasing middle class and consumption growth. The market determines the price. We see the median lies around the 20 Rs Mark and the first and third quartiles are quite close together at around 15 Rs and 24 Rs. The Interquartile range (IQR) is 9 that means the bulk of the prices was around 20 Rs with only 6 Rs movement in either direction.


## Bar Plot

This type of plot can help us see the trend of how values change over time. Since I always read about the fiscal deficit in the news and how it affects how foriegn investment flows into our country and also how governments try to keep it under control. I took the [State wise fiscal deficit data from 2007 to 2014](https://data.gov.in/resources/fiscal-deficit-surplus-percentage-gsdp-2007-08-2013-14-0). I plotted data from my home state - Kerala as shown below.

![bargraph](https://i.imgur.com/mgEWa1t.png)

This data shows us how the fiscal deficit peaked on 2012. It was just after the 2011 Kerala Legislative Assembly election where congress won the state elections. We see [increased funding](https://kerala.gov.in/documents/10180/c02a7d8e-18c2-4f72-8cfe-e0c176e851c6) from the central govt which partly explains how the deficit got unde control.


---

### Stats202 - Comparison of Binary classifiers

This project was done as part of the course stats202 taken by Professor Rajan Patel during the Stanford Summer Session 2016 which I attended.

Find more details over at the [project page](https://anantham.github.io/Stats202/).



---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
