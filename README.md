# rutgers23-project-one
Rutgers23 Data Science PROJECT ONE Module 7 Group 7

**PLEASE ALSO REFERENCE THE CONCOMITANT .ipynb FILE AND PRESEMTATIOM SLIDE DECK FOR RELATED INFORMATIOM**

**TABLE OF CONTENTS**
1. Project Description
    a. Task description
    b. Relevance of the Study
    c. Research Questions and Findings
    d. Ideas for Future Studies
2. Installation
    a. Prerequisites
    b. Dependencies
    c. Resources
3. Contributing
4. Acknowledgements


**1-PROJECT DESCRIPTION**

*Task -*

We were divided into random groups and tasked with creating and presenting a professional-looking research mini-project with the following criteria:

    •	Use Pandas to clean and format the datset(s).
    •	Create a Jupyter notebook describing the data exploration and cleanup process, and illustrating the final data analysis.
    •	Use matplotlib to create six to eight visualizations (ideally: two per question) of the data.
    •	Save .png images of the visualizations to distribute to the class and instructional team, and for inclusion in the presentation.
    •	Create a write-up summarizing the major findings. This is to include a heading for each question asked from the data as well as a short description of the findings and any relevant plots.
    •	As a bonus, we were to use at least one API with data pertinent to the primary research questions

*Relevance of the Study -*

    •	It is uncontroversial and in everyone’s interest to understand when and why vehicular crashes happen in the hope of eliminating them.
    •	The role of handheld cellphones as a distraction leading to vehicular accidents is an issue of topical concern.
    •	Analysis like this may be used as a resource for deciding on the introduction of self-driving vehicles in the future.
    •	New York City has particular relevance as the largest city in the United States with the largest potential population of cases, and can serve as a model for similar studies in other cities.
    •	New York City is the closest major city to the historical main campus of Rutgers University, where this study is being carried out.

*Research Questions and Findings -*

As discovered by a preliminary exploration of recent New York Police Department (NYPD) traffic data made public by the City of New York, most significant vehicular crashes in New York City during the period of study (4/2016 to 7/2022) were associated with *inattentive driving*. We discussed the observable implications of this discovery and asked related questions:

    •	What is the relative percentage of significant crashes associated with inattentive/distracted driving vs. other factors? In other words, is distracted / inattentive driving a little more common than other phenomena as a correlate of vehicular crashes or is it much more common, or even ubiquitous?
        - FINDING: Distracted or inattentive driving (we use the terms synonomously) is by far the overall predominant contributing factor (r value = 0.53) for the primary vehicle in accidents in New York City between April 2016 and July 2022, according to the New York Police Department (NYPD) employing a standardized list of 69 categories. Nearly a full third of all cases for which we have full data can be so characterized. It must be borne in mind for this and the rest of the findings that the API site doesn't provide defintitions for each category, the subjective views of the attending NYPD personnel are no doubt involved, it's unclear if the variables are related to each other, we excluded a significant number of cases for lack of complete data, and correlation is not necessarily causation.
    •	Does this relationship hold over time of day: e.g., does the same general percentage of crashes contributed to by inattentive driving hold during the entire day, and/or the weekday rush hours, on average? Also, does this relationship hold over time of year: e.g., in the summer as well as the typically icy Northeastern US winter season?
        - FINDING: Crashes increase in volume over the course of any particular day. We weren't surprised that the evening rush hour has a larger volume of vehicular incidents, since there are usually more cars in the city than at earlier times. But we didn't expect a significant number of crashes to begin so early in the morning nor to be so prominent during the lunch hour when, presumably, fewer commuters are driving than during the morning weekday rush period. We were amazed that so many accidents happen in April, as opposed to the icier winter months.
    •	Do crashes also result in the most injuries to all classes of persons involved: i.e., the motorist only, or pedestrians and cyclists?
        - FINDING: This relationship of distracted driving as the main correlate of accidents holds whether only the motorist is injured or killed, or if pedestrians and/or cyclists are involved, though precipitating conditions after distracted driving vary in volume. For example, failure to yield the right of way is almost as salient as distracted driving when pedestrians are involved (i.e., 10 incidents vs. 12). As a related and surprising finding: the NYPD reports only four fatalities from road collisions over the period of the study, and only one for which full data are available. We are frankly skeptical of this report.
    •	Are vehicular collisions by distracted drivers more common for particular kinds of vehicles? Are they more prevalent in particular boroughs of the city?
        - FINDING: The general vehicular class of *Sedans* have the largest volume of accidents in the study, which is interesting. As one consideration: Taxis (which are presumably exclusive of Sedans) are on the road for long periods, and presumably the longer one is driving, the more chance of an accident, but relatively few collisions involve taxis. Moreover, the volume of crashes tracks with the population of each borough, with Brooklyn (the most populous) suffering the most accidents, Queens (the second most populous) witnessing the second largest volume of crashes, etc. This is not necessarily intuitive because one might expect Manhattan, a small island where a large number of vehicles transit each day, could host the largest number of accidents

*Ideas for Future Studies -*

    •	Acquire more data on New York City accidents from different sources if available, or from different cities close to New York City, to obtain a greater number of cases and to perhaps mitigate the potential impact of subjective police assessments, the lack of variable definitions, and the likely overlap between variables.
    •	Find data on the correlates of distracted driving, such as cellphone usage, applying cosmetics, eating, etc., since it's important to further investigate the roots of such a clearly widespread phenomenon.
    •	Drill down the analysis geographically to particular streets, highways, neighborhoods, etc., to fine-tune the interrogation of spatial patterns associated with vehicular accidents, which then lend themselves to amelioration through actions like traffic light or stop sign placements.


**2-INSTALLATION**

*Prerequisites -*

    •	This project is coded in Python 3.10.9.
    •	Reviewers should use the code in the "main" branch of the GitHub repositority only.
    •	The project files have an .ipynb extension, so they are meant to be viewed in Jupyter Notebook.
    •	The project requires the dependencies listed below. Pip installs should precede imports where necessary.
    •	The project assumes there is a folder called "plots" one level below the code file that contains the file "map_crashes.png"
    •	The project is associated with an app key file, currently untracked, which is necessary to access the data
  
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

*Resources -* 

   •	The City of New York provides a JSON of NYPD-recorded vehicular accidents that result in an injury, death, or at least $1,000 in damage here: https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95. It can also be downloaded as a csv file. At this writing, the data covers the period 2016-04-16 to 2022-07-12. Definitions for the categories associated with accidents are not readily available. Requests for this information to the site administrator were directed by them to the NYPD, and the NYPD did not respond to our entreaty.


**3-CONTRIBUTING**

Group 7 consisists of the following participants:

    •	Abraham, Susan J.,
    •	Glantz, Adam,
    •	Kabir, Debbie,
    •	Mysllinj, Andi


**4-ACKNOWLEDGEMENTS**

Code and other information related to this project were shared by all of the group participants.

    Author: NYC Open Data - New York, NY USA = https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95b