# Summary

The data visualization created displays the 2014 Major League Baseball (MLB) regular season cummulative attendance highlighting teams that made the playoffs.  It is an expectation as a team that when performing well you are more likely to draw a larger crowd than when your team is playing poorly. Since making the playoffs is a measure of success for MLB teams, a spot in the playoffs should result in more fans, measured by attendance. This chart shows the highlights this relationship with the majority of the playoff teams in the upper half of 2014 attendance, 8 of the top 15 teams for attendance, with two teams from small market who had a strong season, but still did not draw a larger number of fans to their games.


#Design

## Initial Visualization
Once deciding on the variables and relation I wanted to display, I chose to use a bar chart because I was looking to do a comparison on multiple items for a single variable (attendance). Usign the bar chart allowed me to colour by an additional variable, playoff picture, as an effective way to convey the relationship between success and attendance. The first visualization I created (index_1.html) mainly consisted of default settings from dimple. 

## After Feedback #1
As shown in the next section, my colleague provided me with some excellent feedback regarding my visualization. It was apparent that based on her comments she wasn't exactly sure what the colouring indicated, as at this stage the bars were only coloured by "Y" or "N" for playoff appearance. Noticing this I restructed the variable and legend to consist of three outcomes; "Missed Playoffs", "Wild Card", and "Division Winner". In addition, I also altered the title to make the reader aware that the chart is showing success for the 2014 season, not an individual game. She also made a comment about the axis titles not being clear enough, so I renamed them in more understandable terms. Finally, the last change I made based on the feedback was to centre the chart title to the SVG, as opposed to the page, since this was cause the title to be more right aligned with the visualization than the desired centre alignment.

## After Feedback #2
Again, I receieved some excellent feedback from another individual who doesn't have a deep understanding of baseball and needed further clarification added to the chart. He was uncertain of whether a "Wild Card" team made the playoff or not, so I added a subtitle to the top of the chart to clarify that both "Division Winners" and "Wild Card" teams make up the playoff picture. He also commented on the legend being too small, which I hadn't originally noticed, and I restructed this to take into consideration his feedback, while also applying it to the axis titles.

##After Feedback #3
This feedback was probably the most influential to the visualization as it identified that my colours were too vibrant and took away attention from the more important colours. By introducing a more muted colour (grey) for the teams that missed playoffs it highlights the teams that did make playoffs. He also made a comment on the title, that it could be better worded to convey the data of the chart. Further, I applied his input to the visualization by making the axis titles bold, in an effort distinguish them from the measure the labels. The final impact to my visualization was to add a link to the data source used to create the chart.

## Final- Submission 1
The last thing I noticed was the labels on the x-axis for teams were database keys, and not the typical MLB short forms the average fan would be used to. I managed to find another column in the dataset to use that fixed this issue.

## Final- Submission 2
My reviewer had pointed out that they weren't baseball fans so had a hard time understanding the playoff picture, to which he suggested to add an explanation below the chart. I added this right below the source for clarification.

## Final- Submission 3
Another stong point form my second reviewer who suggested to alter my approach and let the data speak for itself, rather than stating correlation as a hard fact. I altered my readme to account for this which now states the chart is simply showing each teams overall attendance, while highlighted the playoff teams for the reader to identify that the majority of teams that make playoffs finish in the top half of cummulative attendance. He also made a good suggestion to add more to the tooltip hover which now shows more information for each team from my dataset such as their league, team city, games played, in addition to the already displayed metrics of attendance and playoff outcome.

## Final- Submission 4
Great suggestion made to add a description below the chart with a couple sentences to drive home the point of the visualization. Also increased the size fo the source below the chart by a font point for added visibility.


#Feedback

## Reviewer 1- Joanne (Colleague)
What do you notice in the visualization?
* The title is not centered
* Some are pink and some are blue
* The x axis title says teamID but this is clearly the team name, better yet the team name abbreviated
 
What questions do you have about the data?
* Isn’t the abbreviation for Million MM? 
* What is the time frame being represented?
 
What relationships do you notice?
* The lower the attendance the more likely the team will lose a division game
 
What do you think is the main takeaway from this visualization?
* A lot of people watch baseball
* The more people watch the more likely the team is going to win a division game
 
Is there something you don’t understand in the graphic?
* The y axis title is abbreviated, leaving me to guess it is the attendance
* What is the blue dotted line?
* I don’t understand the title, it says “MLB Attendance by Team and Division Winners” but the data is not showing just winners, it also shows teams who have lost the division game
* The legend says Y & N, assuming this means Y = Division game won & N = Division game lost

## Reviewer 2- Kevin (Colleague)
What do you notice in the visualization?
* Teams are represented by 3 colors
* The teams are sorted by attendance numbers from high to low in the X axis
* I find the legends on the top right corner a bit small for me (I am an old man)

What questions do you have about the data?
* Are all 4 wild card teams made it to playoffs?

What relationships do you notice?
* The lower the attendance, the lower chances of making it into the playoffs. But there are always exceptions (this applies to the Maple Leaf hockey team I think)

What do you think is the main takeaway from this visualization?
* Baseball is still a very popular game
* Some teams’ attendances double the numbers of some others in the lower end

Is there something you don’t understand in the graphic?
* No.

## Reviewer 3- Ross (Colleague)
What do you notice in the visualization?
* Colours are too bright and contrasty - less clarity in the message due to this axis labels need to be larger font
* Is it better labelled as attendance by playoff picture, or playoff picture by attendance?
* Don’t need the "(millions)" after the attendance on the y-axis label- you already have the measurement on axis


What questions do you have about the data?
* Where did the attendance data come from?
* How does this correlate to market size?


What relationships do you notice?
* Seems to be a correlation between attendance and appearance in the playoffs, with a couple of outliers


What do you think is the main takeaway from this visualization?
* See above 


Is there something you don’t understand in the graphic?
* No


# Resources

* Sean Lahman Database
* Udacity Forums