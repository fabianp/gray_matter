# Gray Matter: Science Hack Day SF 2017 Project

*Participants*: [Valentina Borghesani](https://twitter.com/vborghesani), [Fabian Pedregosa](https://twitter.com/fpedregosa), Ines Bahri

There is a rare kind of dementia that affects language more than memory, i.e., patients don't forget things, they lose knowledge of the meaning of words.

# The data

We have data on ~100 of these patients: brain atrophy maps and behavioral scores from a series of neuropsychological testing.

We know clinicians tend to cluster the patients in two sub-groups: primarily left vs primarily right atrophy.

These are the two classes identified by the Neurologist at time=0
![](https://github.com/fabianp/gray_matter/raw/master/img/ClassificationNeurologist_time0.png)

These are the two classes identified by the Neurologist at time=1
![](https://github.com/fabianp/gray_matter/raw/master/img/ClassificationNeurologist_time1.png)

# Our project

We want to cluster the patients in a data-driven way by looking at the atrophy in specific regions of interest of the brain. Then we compared:
* our clustering with the one made by neurologists
* our clustering at time=0 with the resuls of the same process at time=1 (second visit for each patient)
* the behavioral performance across the 3 clusters we obtained

# Our Results

Data-driven clustering suggests actually 3 clusters at time=0: 
![](https://github.com/fabianp/gray_matter/raw/master/img/ClassificationUS_time0.png)

Patients in blue have the most advanced stage of dementia. 

Patients in green are really bad at naming things.

Patients in red are really bad with social skills.

And it's all confirmed (of course atrophy advanced!) at time=1
![](https://github.com/fabianp/gray_matter/raw/master/img/ClassificationUS_time1.png)
