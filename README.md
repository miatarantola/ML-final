# Predicting Air Pollution with Census Data
 Bridget, Mia, and Kate's Final Project! 

## Abstract

Our project address the problems of disparities in pollution and air quality based on race, income, and other factors. Our overall approach will be to isolate factors to see how well we can predict pollution and see what factors influence the amount of pollution in an area. We will evaluate our success against our stated goals by using visual cues such as graphs, analysis, and the source code to demonstrate the experiments we have done with the data. 


## Motivation and Question

- We have a scientific data set 
- 3 data sets we are hoping to merge 
- Census, EPA, income data
- Interested in bias both in algorithms and in the real world through environmental issues 
- Could inform resource allocation, new building projects, choosing whether to invest in properties

The initial motivation for our project was coming across a data set of EPA air pollution from 2000-2020 that has records of different types of pollutants on a national, state, and county level. From there, we wanted to work on something related to that data set and all three of us had an interest in working on a project that considered bias as a key component. So we landed on the idea of working with the EPA data set in addition to census data about the demographics of different areas to explore what factors are most highly correlated with pollution. Additionally, this project is an opportunity to explore algorithmic bias once we complete our modelling process. 

## Planned Deliverables
If everything works outs exactly as we planned we will produce the following deliverables
- A combined data set: We currently have 3 different data sets - one with environmental data by county, one with racial demographic data by county and one with income data by county. We hope to clean these data sets and eventually merge the three of them into one large data set.
- A Python package containing all code used for algorithms and analysis. We hope to create a predictive model that predicts whether a given location is a high pollution or low pollution area. 
- A Jupyter Notebook with experimental graphics. We hope to do some experimentation to determine which factors have the heaviest contribution to the prediction.

If things don't go directly as planned we will produce the following deliverables:
- A combined data set
- A Python package containing our code and predictive model
- A Jupyter notebook. However, our experiments and analysis may not be flushed out to a deep level. We might not have as many visualizations or research on environmental racism or factor contributions.

## Resources Required
To complete our project will we need to utilize the following resources:
- Census Data https://www.census.gov/data/tables/time-series/demo/popest/2020s-counties-detail.html
- Income Data 
- Environmental Pollution Data https://www.kaggle.com/datasets/sogun3/uspollution
- Possibly meeting with Phil. None of us have completed heavy data cleaning and we are likely to need advice about the built in census packages. https://pypi.org/project/CensusData/

## What We Will Learn
Mia: In my initial goal setting, I wrote that I wanted to focus on experimentation and implementation. I think that this project will allow me to pursue both interests. I am excited to add the social responsibility portion of the project. Investigating environmental racism and the bias of our algorithm will allow for a wholistic picture of its impacts. I also wrote that I want to have a open line of communication with my group. I enjoyed working with my group today and think that working with my group members will be a fun and positive experience in the future. I also wrote that I wanted to design a creative visual representation of our project and I think our final jupyter notebook will help me achieve this goal.


Bridget: Our project aligns with my beginning-of-semester goals rather well. I stated that I wanted to study "a complex dataset in depth and how that affects algorithmic bias in a certain field," and our project includes putting together a complex dataset to determine whether disparities exists in urban air pollution. I am excited to learn how to clean data, and one of my goals was meeting with Phil if we get stuck and I think this is a good opportunity to practice that. I am happy to be working with my group and think meeting weekly will be possible and even enjoyable. 

Kate: In my initial reflective goal setting I wrote that I wanted to work on a project that interested me and ideally would be related to an environmental issue or algorithmic bias. I think that this project offers both and I am excited to move forward with it and hopefully achieve my process goals. I am excited to be working with my team so I think that achieving my goals of open communication and regular meetings will be very achievable, and even fun! I hope to learn more about some of the models we have implemented and specifically how to use our machine learning models on more complex data sets. 


## Risk Statement

- Data cleaning and joining taking too long 
- Patterns expected not happening would make analysis much more difficult

## Ethics Statement

The groups that stand to benefit from our project include people in highly polluted areas, as the outcome of this experiment could highlight the disparities between different groups of people and air quality and therefore spur lawmakers to allocate resources more liberally to those places. Government decision makers could also benefit from our project as it provides evidence to justify spending money in certain areas. 
The groups that stand to be excluded or harmed also include the people in highly polluted areas. We think that if our project is used in a biased way, it could be used to justify not buying, investing, or building in certain areas. If an area is known to be polluted, that area will not be desirable as a place to live or raise children. This could drive money away from these areas and be very harmful for the people already living there; it could increase already-existing disparities. 
However, we are hopeful that the world will become an overall better place because of our project. This comes along with the assumption that policy-makers and government actors are well-intentioned, and that they will allocate money in an equitable way to systemically oppressed areas. We also assume that environmental spending is increasing in the government and that government actors can create effective environmental policy that passes through both the House and Senate. 


## Tentative Timeline

Our tentative timeline is to have: by the three week check-in: the data cleaned and in one dataset, exploratory phase of playing around with the data and features done, a few features selected (with potential to drop or add features as we go on), and the beginning of the modelling process to determine which models we should use. By the six week check in: graphs, analysis, and code all in one Jupyter Notebook with a clear story being told (whether we find results we are expecting or not).

