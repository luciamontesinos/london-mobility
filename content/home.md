---
title: "Impact of Covid-19 into London Mobility"
description: "Final project for 02806 - Social Data Analysis and Visualization Spring 21"
draft: false
---

## How to navigate the notebook
Welcome to the main narrative of our findings. Throughout this page, you will find some highlited sections that will lead you to a deeper analysis. Although they don't need to be read, they help contextualize the overall narrative. These sections can also be found through the upper right menu.  You can find the **[source code](https://github.com/luciamontesinos/london-mobility/blob/master/London.ipynb)** and the **[datasets](https://github.com/luciamontesinos/london-mobility/tree/master/datasets)** used for the plots.


### The impact of COVID-19 in mobility
COVID-19 has become an unprecedented change in our lives.  In order to mitigate the rapid spread of the virus,  governments from all around the globe implemented a range of social distancing policies. For Londoners, these legislations started at the end of March 2020, and currently, some are still in force. All of these distancing policies resulted in reduced mobility across the different London Boroughs. Throughout this interactive storyboard we will analyze the impact of COVID-19 on London mobility---and likely, the impact of London mobility on the spread of COVID-19.  

### The timeline
Although the virus was first identified in December 2019 in Wuhan, China, the first confirmed case in London appeared on 12 February 2020. By mid-March, there were already more than 500 cases in the city, and since then the number of confirmed cases has barely stopped [growing](https://luciamontesinos.github.io/london-mobility/covid/). This triggered a series of social distancing policies that were applied and lifted as the number of cases fluctuated. Below there is a timeline of the restrictions imposed in Greater London:


{{<include-html "/data/timeline_restrictions.html">}}

Most of these restrictions had a direct effect on the mobility of the Londoners. To analyze this, we used the Google Mobility Report of the Greater London Area. This report uses Google Location Services to estimate the places that the smartphone users visited and compares them to a baseline take in January 2020.


{{<include-html "/data/ChangeBaseline.html">}}

If we keep in mind the restriction timeline, we can see a clear correspondence between some of the restrictions and the decline of visits to these places.

For example, during the period in which pubs, shops, and eating places were closed, there is up to an 89% decrease with respect to the baseline. Another example is with the visits to the parks, which increases whenever the "stay at home" restriction is lifted.

**todo: add a plot of the above explanations ??**

We could extrapolate from this the Londoners followed the social distance measurements. However, as some of the restrictions were lifted and then imposed again, it's interesting to study if the citizens followed the restrictions as strictly compared to the previous waves. 


If we take a look into how the daily covid cases, **todo: link to daily covid cases**, although there are more 


As London boroughs present very various socioeconomic circumstances **todo link here Max socioeconomical plots**, it is necessary to study them separately.

### The impact by boroughs
**todo: add Tamás google mobility plots**
