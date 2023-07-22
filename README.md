# Bikeshopdashboard
 This Project consisted of the client wanting to create a dashboard to figure out who will buy more bikes.
The client has given us the data that we have in our Excel program.
We start to clean our data by getting rid of our duplicates as well as making sure they are spaced.
Then start to select all of our columns by "ctr + A" and then select our filter options just in case we have to filter.
Now we select column B which contains the marital status of M and S.

 I thought that the M and S would be confusing so I wanted to change it.
So how we would do it is by going to that column, we hit "ctr + H" to change the M to Married and S to Single.
I would also repeat this in column C which is are gender column in the above sentence.
Now I want to start to make a new column M and call that our "Age Bracket" which will make it simple as we go farther into our data.
Now I'm going to put in a sequence for this to have Adolescence, Middle Age, and Old.

The sequence goes as this =IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolecent","Invalide"))) this will determine what age group is grouped by.
I know later on that the 10+ Miles will cause problems so we then change it earlier to more than 10 miles.
Now we start to make our three pivot tables which will show certain relationships.
Pivot one will have Gender as rows, Columns as purchased bikes, values will be the average of income.
Pivot two will have commute distance as rows, purchased bikes as columns, and the count of purchased bikes as values.

And finally, Pivot three will have age brackets as rows, purchased bikes as columns, and count of purchased bikes as values.
we want to make our charts so for our pivot table one we make a bar graph, pivot tables two and three will both be line charts with dots at certain points
Now we want to copy and paste all the graphs over to our sheet that is marked Bike Sale Dashboard.
You clear out the gridlines by going to the page layout and deselecting gridlines to clear it all out and make it clean.
Now you want to select a certain amount of rows to columns to make a header, by selecting home, then merge to center then write your header.

Change the size and color of your font to whatever you feel like, as well as fill in the header area to whatever color you choose.
Now the three graphs that we have we are going to neatly put them under the header in such a way that we leave some space on our left side.
we are going to insert three slicers that will fill in our left side empty spaces.
the first slicer will consist of Married and single, the second will consist of the regions, and the third will consist of education.
You are wanting to connect these slicers to all the pivot tables that will be able to interact with the graphs on our dashboard.

With this, we can conclude that we have a clear dashboard on Excel that will show multiple relationships to those who own or don't own a bike.
We now can present this to our client in showing which age group will buy bikes, as well as who is willing to travel farther distances with a bike.
