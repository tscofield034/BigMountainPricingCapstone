<h1>Generate Pricing Model for Ski Resort Tickets</h1>

<h2>Languages and Libraries Used</h2>

- <b>Python</b> 
- <b>Scikit-learn</b>

<h2>Description</h2>
In this capstone project, I was tasked to generate a pricing model for Big Mountain Ski Resort lift tickets based on other resorts in its market. The project is broken up into four portions (notebooks): data wrangling, exploratory data analysis, preprocessing and training, and modeling.  


Following the data wrangling, EDA, and preprocessing, our final model uses a random decision tree classifier to predict what price Big Mountain should charge for their daily lift ticket. The features that were most important to the modeling (see fig below) were vertical drop, snow making acreage, total number of chairs, number of fast quads, number of runs, longest run, number of trams, and skiable amount of terrain. Based on these values, we could predict a lift ticket price and an expected mean absolute error to conclude that they are undercharging based on other resorts in their market. 

<p align="center">
Feature Importance: <br/>
<img src="https://i.imgur.com/JeYiOW2.png" height="80%" width="80%" alt="feature importance"/>
<br />
