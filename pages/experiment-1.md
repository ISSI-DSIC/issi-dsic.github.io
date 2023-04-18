---
layout: default
---

# Comparing Preference of Adaptive User Interfaces with Performance: An Empirical Study using EEG

Paper can be found (anonymised for double-blind review) here: [https://figshare.com/s/4bd999f17ca46bb3d0d8](https://figshare.com/s/4bd999f17ca46bb3d0d8){:target="_blank"}

Menus are a primary form of end-user interaction with any interactive applications and the selection of menuitems has been studied for years to make graphical menus adaptive to the context of use in which the enduser is carrying out an interactive task. While the subjective preference of these graphical adaptive menushas been already studied, no consensus exists on which of these menus is performant enough to warrant anadaptation of the graphical user interface that should be for the ultimate benefit of the user. Some preferredmenus are not performant and some performant menus are not preferred. To investigate the relationshipbetween the preference of graphical adaptive menus and their performance, this paper reports the results of anexperiment where𝑁=40participants were instructed to manipulate twenty graphical adaptive menus whiletheir brain activity was captured by an electroencephalogram. Based on four measures computed from theseraw signals,i.e.cognitive load, engagement, attraction, and memorisation, we perform a statistical analysisand a computation of various distances, e.g., dynamic time warping, to determine the performance variancebetween participants. From these results we suggest some implications for software developers which want tochoose the most suitable graphical adaptive menu for their applications to increase the user experience.

# Instrumentation

## Device

We used [Bitbrain's Diadem headset](https://www.bitbrain.com/neurotechnology-products/dry-eeg/diadem). The following image illustrates the headset and its electrode placement.
 ![Diadem and electrode placement](/assets/images/Diadem.pdf)

## Slides

We represented the different graphical adaptive menus using an interactive slide presentation. Our menu representationswere based on two different domains: a mail manager software and a web browser.

 ![Menu and its domains: Mail manager](/assets/images/menus.png)
 ![Menu and its domains: Web browser](/assets/images/menus_2.png)


## Downloadable material

For this experiment we used PowerPoint slides. We used a template and then generaded more pptx for each participants using a different menu order of use. This template can be downloaded [here](downloads/instrumentation/slides.ppsx)



# Data

We obtained the metrics from [SennsCloud](https://www.bitbrain.com/neurotechnology-products/software/sennsmetrics#) for each participant. Then we computed the DTW distance. The results can be downloaded [here](downloads/data/Experiment1/Data_all.csv)



# Results

The results of the descriptive analysis performed over the emotion-based variables can be found [here](downloads/results/Experiment1/menuResults)


[back](../)
