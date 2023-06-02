# rutgers23-project-one
Rutgers23 Data Science PROJECT ONE Module 7 Group 7


**TABLE OF CONTENTS**
1. Project Description
2. Installation
3. Contributing
4. Acknowledgements


**1-PROJECT DESCRIPTION**

We were divided into random groups and tasked with creating and presenting a professional-looking research mini-project with the following criteria:

    •	Use Pandas to clean and format the datset(s).
    •	Create a Jupyter notebook describing the data exploration and cleanup process.
    •	Create a Jupyter notebook illustrating the final data analysis.
    •	Use matplotlib to create six to eight visualizations (ideally: two per question) of the data.
    •	Save .png images of the visualizations to distribute to the class and instructional team, and for inclusion in the presentation.
    •	Create a write-up summarizing the major findings. This is to include a heading for each question asked from the data as well as a short description of the findings and any relevant plots.
    •	As a bonus, we were to use at least one API with data pertinent to the primary research questions


As discovered by a preliminary exploration of recent New York Police Department (NYPD) traffic data made public by the City of New York, most significant vehicular crashes in New York City during the period of study (4/2016 to 7/2022) were caused by *inattentive driving*. We discussed the observable implications of this discovery and asked related questions:

    •	What is the relative percentage of significant crashes caused by inattentive/distracted driving vs. other causes? In other words, is distracted / inattentive driving a little more common than other phenomena as a correlate of vehicular crashes or is it much more common plurality, or even ubiquitous?
    •	Does this relationship hold over time of day: e.g., does the same general percentage of crashes caused by inattentive driving hold during the entire day, and/or the weekday rush hours?.
    •	Does this relationship hold over time of year: e.g., in the summer as well as the typically icy winter season?
    •	Do crashes caused by inattentive driving also result in the most injuries to all classes of persons involved: motorist, pedestrian, and cyclist?
    •	Are vehicular collisions more common for particular kinds of vehicles
    •	Are vehicular collisions more prevalent in particular boroughs of the city?


The importance of this study is as follows:

    •	It is uncontroversial and in everyone’s interest to understand when and why vehicular crashes happen in the hope of eliminating them.
    •	The role of handheld cellphones as a distraction leading to vehicular accidents is an issue of topical concern.
    •	Analysis like this may be used as a resource for deciding on the introduction of self-driving vehicles in the future.
    •	New York City has particular relevance as the largest city in the United States with the largest potential population of cases, and can serve as a model for similar studies in other cities.
    •	New York City is the closest major city to the historical main campus of Rutgers University, where this study is being carried out.


**2-INSTALLATION**

    •	This project is coded in Python 3.10.9.
    •	Reviewers should use the code in the "main" branch of the GitHub repositority only.
    •	The project files have an .ipynb extension, so they are meant to be viewed in Jupyter Notebook.
    •	The project requires the dependencies listed below. Pip installs should precede imports where necessary.
    •	The project assumes there is a folder called "plots" one level below the code file that contains the file "map_crashes.png"

  
*Dependencies -*

    •	json,
    •	matplotlib.pyplot,
    •	numpy,
    •	os,
    •	pandas,
    •	requests,
    •	scipy.stats.linregress,
    •	sodapy.Socrata,
    •	time,
    •	warnings

*Resources - The City of New York provides a JSON of NYPD-recorded vehicular accidents that result in an injury, death, or at least $1,000 in damage here: https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95. It can also be downloaded as a csv file. At this writing, the data covers the period 2016-04-16 to 2022-07-12.

**3-CONTRIBUTING**

Group 7 consisists of the following participants:

    •	Abraham, Susan J.,
    •	Glantz, Adam,
    •	Kabir, Debbie,
    •	Mysllinj, Andi


**4-ACKNOWLEDGEMENTS**

Code and other information related to this project were shared by the group participants

    Author: NYC Open Data - New York, NY USA = https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95b
