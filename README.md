# LAmetroCrimesPredictor
The Safety Prediction Using LA Metro Crime Statistics

Created by Youjin Ahn, Jeonggon Lee, Sinyeong Bak, Chanill Park at USC


Data Provided by "Los Angeles Police Department"
1) https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z
2) https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8

Among the crime data, only metro data was selected.


How to use?
1) Enter the line you want to board
2) Enter the race of the passenger
3) Enter the passenger's gender

======================result======================

ex) You're a Asian female and riding RED|PURPLE line at 12:00-13:00
the probability of a crime : 0.1015 ‱
...
The worst three cases was:
1. ATTEMPTED ROBBERY
2. ASSAULT WITH DEADLY WEAPON, AGGRAVATED ASSAULT
3. THEFT-GRAND ($950.01 & OVER)EXCPT,GUNS,FOWL,LIVESTK,PROD



development in progress
-> Finding the minimum route and marking it on a map using the Dijkstra Algorithm
