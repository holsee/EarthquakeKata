

Kata: Earthquake monitoring
===========================

Background
----------

In order to help scientists understand earthquakes better, an international monitoring 
system is in place to record where earthquakes occur and how powerful they are. 

Earthquake strength is measured by the ‘magnitude moment’: 
- earthquakes of magnitude three or lower usually imperceptible 
- those with magnitude seven and over can cause serious damage over large areas. 

National seismological observatories record earthquakes that occur. 

Problem specification
---------------------

Define Data Structures and Functions to store and retrieve information about the magnitude, 
position (latitude and longitude) and year of the event.

### Define an `Observatory`

#### Should provide functions to store: 
  - the name of the observatory
  - the name of the country in which it is located 
  - the year in which earthquake observations started
  - the area covered by the observatory (in square kilometres) 
  - a list of Earthquake events that it has recorded 

#### Include functions to return:
  - The largest magnitude earthquake recorded by the observatory
  - The average earthquake magnitude recorded at the observatory
  - A list of all earthquakes recorded at the observatory with a magnitude greater than a given number

### Define `Monitoring` 

Provides access to information about all observatories

#### Include functions to return:
  - The observatory with the largest average earthquake magnitude
  - The largest magnitude earthquake ever recorded
  - A list of all earthquakes recorded with magnitude greater than a given number

### Define a Console UI `MonitoringIO`

Present the user with a menu (printed to the console) of features:
  - enter observatory data
  - enter earthquake data
  - provide monitoring statistics on: 
    - largest average earthquake
    - largest earthquake ever 
    - all earthquakes with magnitude greater than a given number
  - exit
