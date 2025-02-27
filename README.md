# Occupant-centric grid interactive buildings 
#### Spring 2024, UT Austin
This course is a graduate-level course in civil, architectural and environmental engineering at the intersection of building energy systems, occupant comfort, and grid interaction. The course focuses on harnessing machine learning techniques to optimize building operations and energy efficiency while considering occupant comfort and preferences.


Key aspects of the course include:

1. **Introduction to Machine Learning:** The course begins with an exploration of fundamental machine learning concepts, distinguishing between supervised and unsupervised learning, and examining various algorithms like linear regression, logistic regression, k-nearest neighbors, decision trees, and support vector machines.
2.  **Data Handling and Analysis:** Students learn about different data types, such as ordinal, categorical, binary, and numeric data, and the importance of understanding and preparing data for machine learning models.
3. **Machine Learning in Practice:** The course covers practical aspects of machine learning, including the bias-variance tradeoff, cross-validation techniques, and model evaluation methods to ensure accuracy and prevent overfitting or underfitting.
4. **Python Programming for Machine Learning:** A significant part of the course involves practical Python programming activities, using libraries such as scikit-learn, and working with datasets relevant to building energy systems.
5. **Grid-Interactive Building Systems:** The course specifically focuses on applying machine learning to occupant-centric, grid-interactive building systems, addressing the challenges of integrating renewable energy sources, demand-response strategies, and real-time data analytics.
6. **Real-World Applications:** Through assignments, students engage with real-world datasets and scenarios, such as smart meter data and relational database management, to apply their learning in practical contexts.

The course is designed for graduate students with an interest in building energy, machine learning, and sustainable design. It aims to provide them with the skills and knowledge to contribute effectively to the evolving field of smart building technologies.

This repository contains lecture notes and jupyter notebooks for the course. Notebooks can be easily opened in Google Colab.


## Notes for General Public ##
_Note 1_: The course assumes no programming knowledge, but relies on heavy programming components with a steep learning curve. There is a ChatGPT trained with access to the same course materials to support the learning experience. Here is the public access (requires ChatGPT Plus subscription): https://chat.openai.com/g/g-OFAttq2Or-gpta

If you can, please [provide anonymous feedback](https://forms.gle/DYwHeBhVKpinuiyE9) on your interaction, so we can improve it.


_Note 2_: Some of the homework content requires access to non-public AMI data (eg HW2), you can replace those with other AMI data, e.g., from the [Building Data Genome 2 Project](https://github.com/buds-lab/building-data-genome-project-2).

_Note 3_: The class features a public guest lecture webinar with industry experts. You can sign up for it here: https://www.eventbrite.com/e/grid-interactive-buildings-webinar-series-tickets-781139989737


## Overview ##
The class is organized in three main modules: Machine Learning (W1-W4), Occupant Behavior and Building Energy (W5-W8), and Grid-Interactive Buildings (W9-11). The class concludes with a project using [CityLearn](http://www.citylearn.net) (W12-W15).

- Instructor: [Zoltan Nagy](https://www.ie-lab.org/author/zoltan-nagy/)
- TA (Jupyter notebooks): [Kingsley Nweye](https://kingsleynweye.com/)
- TA (GPT TA): Ting-Yu Dai

### Week 1 - 20240117 ###
#### Introduction / Overview ####
- [Lecture notes](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/CE397_OCCGEB_Sp24_01.pdf)
- [Tutorial: Introduction to Python](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/tutorials/introduction_to_python.ipynb)
- [Activity 1](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/activity/A1-Getting-Started-with-Python.ipynb)
- [Homework 1](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/homework/Homework_1.ipynb)

### Week 2 - 20241224 ###
#### Machine Learning I ####
- [Lecture notes](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/CE397_OCCGEB_Sp24_02.pdf)
- [Activity 2](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/activity/A2-scikit-learn.ipynb) and [energyData.csv](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/activity/energyData.csv)


### Week 3 - 20240131 ###
#### Machine Learning II ####
- [Lecture notes](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/CE397_OCCGEB_Sp24_03.pdf)
- [Tutorial: sqlite relational databases](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/tutorials/sqlite_relational_database.ipynb)
- [Homework 2](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/homework/homework_2.ipynb)

### Week 4 - 20240207 ###
#### Machine Learning III ####
- [Lecture notes](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/CE397_OCCGEB_Sp24_04.pdf)
- [Tutorial Part 1: SAX for motif/discord detection](https://nbviewer.org/github/buds-lab/day-filter/blob/master/DayFilter%20Process%20-%20Part%201%20-%20SAX.ipynb)
- [Tutorial Part 2: Clustering of motif candidates](https://nbviewer.org/github/buds-lab/day-filter/blob/master/DayFilter%20Process%20-%20Part%202%20-%20Clustering%20Motif%20Candidates.ipynb)
- [Homework 3](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/homework/Homework_3.ipynb)
- Guest Lecture: Just Hill, Southern Company, [[Slides](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/UT-Austin_JMH_2.2024.pdf)], [[Recording](https://youtu.be/zlUe_h8m2K8?feature=shared)]


### Week 5 - 20240214 ###
#### Occupant Behavior and Building Energy ####
- [Lecture notes](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/CE397_OCCGEB_Sp24_05.pdf)
- [Tutorial: Introduction to EnergyPlus](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/tutorials/introduction_to_energy_plus.ipynb)


### Week 6 - 20240221 ###
#### Occupant Behavior and Building Energy  ####
- [Lecture notes](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/CE397_OCCGEB_Sp24_06.pdf)
- Guest Lecture: Tanya Barham, Community Energy Labs, [[Slides](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/20240221_GEBsTalk.pdf)], [[Recording](https://youtu.be/aKEUyQCbWuY)]

### Week 7 - 20240228 ###
#### Occupant Behavior and Building Energy  ####
- [Lecture notes](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/CE397_OCCGEB_Sp24_07.pdf) 
- [Activity: Modeling occupancy in single person offices](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/wang05.pdf)
- [Homework 4: Create stochastic occupancy profiles](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/homework/Homework_4.ipynb) 
- Guest Lecture: Jessica Granderson, LBNL, [[Slides](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/ScalingGEBLectureFeb2024.pdf)], [[Recording](https://youtu.be/ixnUXH4lqDY)]

### Week 8 - 20240306 ###
#### Occupant Behavior and Building Energy  ####
- [Lecture notes](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/lectures/CE397_OCCGEB_Sp24_08.pdf)
- [Homework 5: Impact of Occupancy on Energy Use](https://github.com/intelligent-environments-lab/occupant_centric_grid_interactive_buildings_course/blob/main/src/notebooks/homework/homework_5.ipynb) 
- Guest Lecture: Hussain Kazmi, KU Leuven

### Week 9 - 20240313 ###
#### Spring Break ####


### Week 10 - 20240320 ###
#### Grid-Interactive Buildings ####
- Lecture notes
- Guest Lecture: Ankush Chakrabarty (MERL)

### Week 11 - 20240327 ###
#### Grid-Interactive Buildings ####
- Lecture notes
- Guest Lecture: Donghun Kim (LBNL)

### Week 12 - 20240403 ###
#### Grid-Interactive Buildings ####
- Lecture notes

### Week 13 - 20240410 ###
#### Grid-Interactive Buildings ####
- Project work in CityLearn
- Guest Lecture: Siva Sankaranarayanan (EPRI)


### Week 14—15  ###
#### Grid-Interactive Buildings ####
- Project work in CityLearn
 
