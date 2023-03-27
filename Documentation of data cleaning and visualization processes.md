# FIFA-World-Cup-Award-Winner-1930-2022-Analysis

This is a dataset i pulled from Kaggle, Which i used to build a simple dashboard on Excel to showcase my skills.
Link: https://www.kaggle.com/datasets/jahaidulislam/fifa-world-cup-award-winner-1930-2022

Data cleaning process with Excel:

1. Used the remove duplicates tool to check for any duplicated record. (0 were found).
2. Applied filters to every column to check for any errors regarding data formatting.
3. Used TRIM() functions to remove any added spaces.
4. Replaced records 'Not Applicable' with null values found in the Give Name column.#
5. Added a new column named 'Full name' where i used the CONCAT() to add together the column 'Give Name' and column 'Family name' seperated with a space.
6. Noticed where some of player names had question marks in them, so i had to manually fix that. 

Data visualisation process:

1. Inserted two pivot tables into a new sheet 'Pivot tables', Showing the count of total awards by full player name on the first pivot table, and by country on the second one.
2. Created a new sheet named 'Dashboard' and inserted two charts from the pivot tables. First chart is a column chart showing top countries by number of awards, Second chart contained a bar chart showing top players by number of awards.
3. Added Slicers and connected them to both charts, in order to easily filter the data by tournament name and award name.
4. Changed chart styles to make them more aesthetic as well as the dashboard sheet background.
