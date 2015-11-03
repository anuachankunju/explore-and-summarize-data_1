#Data Visualization: Baseball players Performance

##Summary
This plot ranks the top 50 home run hitters from a list of over 1100 MLB players. The axes indicate the Home runs and BMI of the players and the size of each bubble represent the batting average of the player. The bubbles are colored by player’s handedness and the legend can be used to toggle between them. The plot also highlights the players who are in ideal BMI range to show how BMI relates to the performance of a player.

Design
I downloaded the Baseball Data from Udacity’s dataset options that included performance and physical aspects like height, weight and handedness of 1157 players. I have analyzed the data and looking at the height and weight of players first thing stroke was to calculate the BMI. The body mass index, or BMI, is a calculation used to determine level of body fat. It helps to determine the overall fitness of a person.  I have been hearing a lot about the importance of BMI   and thought of verifying if the BMI of a player has any effect on their performance. Added a new calculated column in the dataset “BMI” by calculating using the formula:
**BM I= Weight in Kilograms/(Height in Meters) x (Height in Meters)**

Next I attempted to plot a scatter plot of Home Runs Vs BMI. I selected scatter plot primarily because I wanted to see the distribution of players. Another advantage of using scatter plot is the ability to allow the reader to get further information about specific player with tool tip. My final plot used this idea but changed slightly to bubble chart when I realized the need to map multiple dimensions.
