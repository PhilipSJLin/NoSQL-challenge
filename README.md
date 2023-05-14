# NoSQL-challenge
 
As a future analyst, I setup, updated, explored, and anlyzed simulated food data for the purpose of learning through the use of MongoDB.

## **Introduction**<br/>
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. I have been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## **How to Run** <br/>
* Import the data provided into your terminal <br/>
  * mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json <br/>
* Setup and update the establishment database <br/>
  * NoSQL_setup_starter.ipynb <br/>
* Explore and analyze the data to find which restaurants should be **visited** and which should be **avoided** <br/>
  *NoSQL_analysis_starter.ipynb  <br/>

## **Data**
For our analysis, I have utilized simulated data available in the Resources folder <br/>
   * establishments.json <br/>

## **Technology/Tools used**
* Python <br/>
* Pandas <br/>
* MongoDB <br/>

In this assignment, I receieved assistance through looking at previous activities, stackoverflow, and received some support through my partner who works in the data analyst field
