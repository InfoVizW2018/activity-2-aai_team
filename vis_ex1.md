# Exercise 1

Team:
Adeshina Alani,
Alison Ziesel,
Ivan Perez

## What-Why-How framework

## What?
**Data Types:**
- Items as ships with attributes like location at a specific time, occupancy, destination.

**Attribute Types:**
- Ships are categorical, but have quantitative occupancy. We’re also showing time which is cyclic in a weekly manner. Also we have ships moving in a sequential manner.

**Dataset Types:**
- Getting the data as a table, but visualizing it as a type of networks with fields for the edges because it’s using a continuous location variable(Position of the ship).

**Dataset Availability:**
- Static in a weekly time frame since we got the schedule data for the whole week since the beginning.

## Why?
### Actions
**Analyze:**
- Visualization can be used to present data to the ferry company(client)
- Also as a discovery tool for the company to discover schedule patterns and congestion problems, etc.

**Search:**
- We can locate a ship in its trajectory from port to port.
- Lookup the detailed information of the ship in a popup. (Extra in case it is needed)

**Query:**
- Compare schedules with occupancy to see if it gets better or worse
- Summarize by giving a comprehensive view of the week in a specific timeframe.
### Targets
**All Data:**
- We can identify a congestion trend and outliers for times that are very busy.

**Network Data:**
- We have a linear topology for the path the ships will be taking in their journeys through the ports.

## How?
**Map:**
- Showing motion (direction of ships)

**Manipulate:**
- Navigation through time with the slider

**Reduce:**
- Filtering data through time slices

## Design study methodology
*Learn* stage is what we are doing currently in class.
We Skipped *winnow* and *cast* as it’s not relevant for this exercise.
We did *discover* and *design* as we iterated through multiple visualization ideas we had and found the one we think best for our abstraction with the *What-Why-How framework*.
No *implement* and *deploy* was done in this exercise.
*Reflect* stage will hopefully be done next class with the professor to guide us.
The *write* stage is in part this document, but we know it’s not even close to completion.

## Pitfalls
- PF-1 as we might have skipped over methodology stages because of time restraints
- PF-2 because we are just starting this course
- PF-4 since we have no real data available
- PF-7 as we aren’t ferry scheduling experts
- PF-25 since one might say it’s not a real world task
- PF-28 Very little writing time

## Description of the visualization we made
The visualization can be made dynamic by moving the slider to different times over the week . This date and time can be seen above the slider. Each port has a number of berths and we indicate occupancy with the red color. Empty berths are left blank. In this example we can see the ship V5 in one of the three berths in Surrey. The ports are connected by their routes where you’ll be able to see the ships progression and direction by their arrows. In case speed gets to be important in the future, we could add or remove arrows to indicate this. You can also see the passenger occupancy of a ship by its red color. It’s meant to be a percentage of the total capacity of the vessel. The routes distance could also be shown by making them longer or shorter in case this is also needed by the company.

![visualization mockup](https://github.com/InfoVizW2018/activity-2-aai_team/raw/master/vis1_small.jpg)
