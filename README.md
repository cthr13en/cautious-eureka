# cautious-eureka
Data 115


#Motivating Question:
I thought it would be fun to look at something that wasn't very serious and lighthearted. UFO sightings seemed to be the answer. I think it is fun to think that aliens exist, and I want to believe as a previous watcher of the X Files. However, I am skeptical when it comes to the sightings of UFOs and the people reporting them. I am not sure what to believe in these situations, but I thought it would be interesting to see what the data says on the situation. 

I used a data set that was found on Kaggle, and the dataset contains over 80,000 records of UFO sightings over the past century (between 1910 and 2014). The UFO sightings were reported to the National UFO Reporting Center, and the report contains the city, state, time, description, and duration of each sighting.

Some of the questions that came to my mind were the following.
Where are UFO sightings mostly likely to occur? 
What time do UFO sightings generally fall in?
What is the most common shape reported by witnesses of UFOs?

#Data Process:

After downloading the data, I looked at the CSV file and was overwhelmed with the number of inconsistencies I saw. These were the changes I made to the data.

Corrected City to Proper
Corrected spelling for city names
Corrected State  to Upper
Corrected Country to Upper
Added Country for missing values
Separated Date from Time into their own columns
Added missing values when available for shape based on description
Deleted Rows with a duration of UFO sightings elapsing 3 hours (10,800 seconds)
Deleted rows for other countries that were not United States, Canada, Mexico, Great Briton, and Germany. I removed these smaller countries because I thought it lesson the noise
This left me with 70,000 rows

#Visualization:

![UFO_Sightings_By_Country](https://user-images.githubusercontent.com/91361493/145460736-c25a5251-903c-4b16-96d6-e10eda701a89.png)
![UFO_Sightings_By_Time](https://user-images.githubusercontent.com/91361493/145460976-d84c3912-e07d-4ae7-9854-d0d9bc9efde1.png)
![UFO_Sightings_by_Shape](https://user-images.githubusercontent.com/91361493/145461131-d2944aa1-1d30-467a-98ab-640911c9ff47.png)

#Analytical Technique:
The questions that I asked weren't too complicated, so I constructed bar charts to depict the answers to my questions.  The first visualization shows that the US far exceeds the other countries for UFO sightings with 70 thousand. Even being on the same continent, Canada is the second-highest in the number of people seeing UFOs with 3,500, but Mexico only reported 223 cases. As for the shape people most see, light was the predominant visual. Not surprisingly, the sweet spots for seeing a UFO were between the hours of 9 and 10 in the evening. 


