# Pseudocode for Project:

my_file = open("pbdb_data\(Elasmobranchii\).csv")  
xx = Get user input (In Geological Time Period)  
yy = Correlate xx to corresponding species  
Order geological time period  
	Print how many times yy shows up in each input of geological time period

Graph corresponding data and species along geological time era axis with computer program R. 

More-Detailed Explanation:

Since we have yet to go over R, here is a thought out explanation of my project idea. First I will find the number of unique geological time periods that Elasmobranchii species have existed in. From there, I will determind how many unique species showed up during the geological era. From there, I will track each species through the different geolocial time scales and see if they decrease in number over time or disappear from the timeline. 

Alternatively:

Use shell commands to filter through the data: cut, sort, uniq, grep, and head/tail
This is used to find the species name and how many times it shows up in each geological era. As we proceed towards the present, we will see if they increase or decrease in diversity. 
