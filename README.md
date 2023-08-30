# ClientSculpt: Mastering Customer Segmentation


<img src="clustering clients.webp" alt="clustering clients" width="600">


- [Context](#context)
- [Introduction](#introduction)
   + [Data exploring](big_query.ipynb)


# Context


Utilizing *Google's BigQuery* as a Robust Data Source, this notebook delves into the dynamic consumer behavior within the United States. 

By scrutinizing distinct days, it endeavors to extract valuable insights, leading to a comprehensive customer segmentation. The ultimate goal is to refine our **pricing strategy** through a profound understanding of their behaviors.


# Introduction


After conducting an extensive analysis of countries by visitor count, it is evident that the United States stands out as the leading contender. 

To delve into the intricacies of refining pricing strategies, our focus narrows down exclusively to the United States. Within this scope, we meticulously cherry-pick relevant attributes such as quantity, **price, revenue**, action channel, and more, strategically aligning with our specific goal. While additional variables exist within the dataset, our current investigation intentionally centers around these chosen aspects.


<img src="visits_country.png" alt="visits country" width="150">


To facilitate our analysis, we introduce the incorporation of day numbers along with the inclusion of a weekend flag, effectively identifying Fridays and Saturdays. 

It's important to note that as part of the data preprocessing, we'll undertake a **price** adjustment by dividing the price by 1e6 to ensure optimal accuracy and scale.


<img src="overview_data.png" alt="overview data" width="450">

```python

```
