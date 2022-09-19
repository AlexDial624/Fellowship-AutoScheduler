# Fellowship-AutoScheduler
Generate fellowship cohort times based on when2meet data

A recurring challenge that Effective Altruism University groups face is scheduling their fellowship cohorts. For a given number of facilitators and participants, we'd like to pick times for our cohorts such that everybody can get assigned to one and each cohort has at least 5 people. This can become a very difficult puzzle when you have many fellows and several facilitators - for our use case of 3 facilitators and 20 fellows, there we over 90,000 different possible sets of cohort times we could pick, and after running this program we able to select one of the only 30 that meets the above critera.

We also had a unique challenge of needing to rework our first week, since 2 of our 3 facilitators would be out of town thurs-Sun. This program allowed us to fully explore our different options, and settle on one that had our 3rd facilitator to pick up one of the groups while rescheduling the other to the Monday of the next week in such a way that all but one can attend - minimizing the inconvinence to our group as a whole.

![screencapture-localhost-8888-notebooks-Documents-Learning-Coding-Py-DS-ML-Bootcamp-master-Fellowship-Scheduler-Scheduler-ipynb-2022-09-19-18_05_47](https://user-images.githubusercontent.com/29134239/191135389-7ca67813-6e21-4e01-87ab-c7e6df9f24a7.png)
