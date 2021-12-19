# behavior-pipeline
### *Streamlining analysis of self-administration behavior data*

Self-administration may be the most popular pre-clinical model for substance abuse. Hundreds of labs around the world train animals (rats and mice, mostly) to self-administer cocaine, heroin, alcohol, nicotine, and other drugs in order to understand the relationship between environment, behavior, and neurochemistry. My lab is one of them.

To understand why self-administration experiments are important and how they have contributed to our understanding of substance abuse in humans, see this [review](https://www.sciencedirect.com/science/article/pii/S0149763410001764). But to learn more about how we streamlined analysis of this data in our lab, read on.

The goal for this project was to generate an automated pipeline that would perform daily updates to transfer behavior data to a network drive, sort the data into folders, then generate a set of metrics from the data that would feed into a dashboard.  This represented a significant improvement on our previous system, which required us to go to a separate floor of the building, retrieve the data on a flashdrive, examine each file independently to extract metrics, and append these data to excel files, which were maintained separately by each person in the lab. The old approach was slow, error-prone, and generally a nuisance.

The result is a system that, while not perfect, saves everyone in the lab 30+ minutes of time per day. 

### *In this repo...*
* 


