# behavior-pipeline

## *Background*

Self-administration may be the most popular pre-clinical model for substance abuse. Hundreds of labs around the world train animals (rats and mice, mostly) to self-administer addictive drugs in order to understand the relationship between environment, behavior, and neurochemistry. My lab is one of them.

To understand why self-administration experiments are important and how they have contributed to our understanding of substance abuse in humans, see this [review](https://www.sciencedirect.com/science/article/pii/S0149763410001764). But to learn more about my effort to streamline analysis of this data in our lab, read on.

The goal for this project was to generate a pipeline that would automatically transfer raw data from one network location to another, analyze it, and display it on a dashboard. This represents a significant improvement on our previous system, which required us to physically retrieve the data on a flashdrive each day, extract metrics from each file using basic Excel operations, and append these data to files which were maintained separately by each person in the lab. The old approach was slow, error-prone, and a nuisance.

The result is a system that, while not perfect, saves everyone in the lab 30+ minutes of time per day and limits human error.

## *In this repo...*
* **transfer.bat:** A windows batch file that transfers data from between drives. Saves us having to manually retrieve the data from computers on another floor of the building.
* **file_sort.py:** A simple python script to sort the files into folders that match the animal names. This makes it _much_ easier to find data.
* **extract_metrics.py:** Extracts the metrics of greatest interest: drug infusions, inter-press intervals, latency to first press, active and inactive presses, etc.
* **dashboard.py:** Build a dashboard from the metrics above, updated daily.
