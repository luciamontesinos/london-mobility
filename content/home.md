---
title: "Impact of Covid-19 into London Mobility"
description: "Final project for 02806 - Social Data Analysis and Visualization Spring 21"
draft: false
---

## How to navigate the notebook
Welcome to the main narrative of our findings. Throughout this page, you will find some highlighted sections that will lead you to a deeper analysis. Although they don't need to be read, they help contextualize the overall narrative. These sections can also be found through the upper right menu.  You can find the **[source code](https://github.com/luciamontesinos/london-mobility/blob/master/London.ipynb)** and the **[datasets](https://github.com/luciamontesinos/london-mobility/tree/master/datasets)** used for the plots.


### The impact of COVID-19 in mobility
COVID-19 has become an unprecedented change in our lives.  In order to mitigate the rapid spread of the virus,  governments from all around the globe implemented a range of social distancing policies. For Londoners, these legislations started at the end of March 2020, and currently, some are still in force. All of these distancing policies resulted in reduced mobility across the different London Boroughs. Throughout this interactive storyboard we will analyze the impact of COVID-19 on London mobility---and likely, the impact of London mobility on the spread of COVID-19.  

### The timeline
Although the virus was first identified in December 2019 in Wuhan, China, the first confirmed case in London appeared on 12 February 2020. By mid-March, there were already more than 500 cases in the city, and since then the **[number of confirmed cases has barely stopped growing](https://luciamontesinos.github.io/london-mobility/covid/#total-cases)**. This triggered a series of social distancing policies that were applied and lifted as the number of cases fluctuated. Below there is a timeline of the restrictions imposed in Greater London:


{{<include-html "/data/timeline_restrictions.html">}}


### The mobility
Most of these restrictions had a direct effect on the mobility of the Londoners. To analyze this, we used the Google Mobility Report of the Greater London Area. This report uses Google Location Services to estimate the places that the smartphone users visited and compares them to a baseline take in January 2020.


{{<include-html "/data/ChangeBaseline.html">}}

If we keep in mind the restriction timeline, we can see a clear correspondence between some of the restrictions and the decline of visits to these places.

For example, during the period in which pubs, shops, and eating places were closed, there is up to an 89% decrease with respect to the baseline. Another example is with the visits to the parks, which increases whenever the "stay at home" restriction is lifted.


We could extrapolate from this that the Londoners followed the social distance measurements. However, as some of the restrictions were lifted and then imposed again, it's interesting to study if the citizens followed the restrictions as strictly compared to the previous waves. 


If we take a look into how the daily covid cases, although there are more 


As London boroughs present very various **[socioeconomic circumstances](https://luciamontesinos.github.io/london-mobility/london/#socioeconomical-status)**, it is necessary to study them separately.

## Differences between restriction obidience during the first and the second lockdown

When people were initially forced to stay at home and reduce the amount of time they spend among other people, most took it very seriously and avoided going out of their homes at all costs. The public opinion about what is acceptable or safe to do, has been gradually getting broader during the pandemic, whether this change comes from better understanding of COVID-19, or the fact that the population is losing it's patience with the lockdowns, we'll leave this up for the reader.

We have picked the start date of the first lockdown, to be 24/03/2020, when the majority of the restrictions were put into place, similarly, we have decided on 05/11/2020 as the start of the second lockdown. We have taken the mobility data available for the week after the introduction of a restrictions and averaged them. With this we are able to visualize the change in people's tendency, to follow restrictions related to movement.

### Areas of negative change

As we have foreshadowed above, people seem to care less about the restrictions as we move forward in time, changes in Grocery and Pharmacy, Retail and Recreation, Transit Stations, and Workplaces, show a significant drop, from the baseline, both in the first and second lockdown.

Mobility trends for places like grocery markets, food warehouses, farmers markets, specialty food shops, drug stores, and pharmacies.
![grocery_1st_wave]({{< baseurl >}}images/mobility_1_grocery.png)
![grocery_2nd_wave]({{< baseurl >}}images/mobility_2_grocery.png)

Mobility trends for places like restaurants, cafes, shopping centers, theme parks, museums, libraries, and movie theaters.
![retail_1st_wave]({{< baseurl >}}images/mobility_1_retail.png)
![retail_2nd_wave]({{< baseurl >}}images/mobility_2_retail.png)

Mobility trends for places like public transport hubs such as subway, bus, and train stations.
![transit_1st_wave]({{< baseurl >}}images/mobility_1_transit.png)
![transit_2nd_wave]({{< baseurl >}}images/mobility_2_transit.png)

Mobility trends for places of work.
![work_1st_wave]({{< baseurl >}}images/mobility_1_work.png)
![work_2nd_wave]({{< baseurl >}}images/mobility_2_work.png)

### Areas of psoitive change

Unsurprisingly Residential movement has increased during both lockdowns, since if people want to meet up, their only option is someone's home or some public area.

Mobility trends for places of residence.
![residential_1st_wave]({{< baseurl >}}images/mobility_1_residential.png)
![residential_2nd_wave]({{< baseurl >}}images/mobility_2_residential.png)

Speaking of, Parks have seen a mild increase during the first lockdown, but has skyrocketed during the second lockdown. The reason? People initially didn't know how contagious COVID-19 was in an outdoors setting, but the public opinion has shifted in this regard. What is also interesting to note is the change that we can see during the 2nd lockdown, occured in the month of November, either it was a very sunny November, or people took every opportunity to get out of their homes for some environment change.

Mobility trends for places like local parks, national parks, public beaches, marinas, dog parks, plazas, and public gardens.
![parks_1st_wave]({{< baseurl >}}images/mobility_1_parks.png)
![parks_2nd_wave]({{< baseurl >}}images/mobility_2_parks.png)

