# surfs_up
Practice with SQLite

## Overview of the statistical analysis:
My dream is to open a Surf & Shake Shop on Oahu, so I can spend the rest of my life surfing and, well, sipping shakes (sometimes even slurping them). A key investor named W. Avy has come on board, but he wants more than the business analysis I have prepared: he wants a weather analysis of Oahu. He's worried that too much rain will chase away surfers along with their thirst for milkshakes.

I want to create a program that analyses data from a SQLite database that Mr. Avy has set up. I will use dependencies from SQLAlchemy to help python interact with the code. Then I will set up a web site using Flask to let Mr. Avy interact with the data and find answers to his questions about rain.

## Results:
The weather in Hawaii is remarkably consistent when we compare the first month of summer with the first month of winter. Still there are differences, especially if we consider that selling milkshakes will be a part of our business revenue at Surf & Shake Shop:
* Average temperature in June is 75 degrees; in December it is 71. Temperatures in December can drop as low as 56. That's not milkshake weather, and only the hardiest surfers will be on the waves in temperatures between 56 and 71.
* A look at average temperatures throughout the year, reveal that temperatures drop off significantly in October and begin rising again in March.
  * ![Hawaii yearly temperatures](https://github.com/JDittes/surfs_up/blob/main/avg_temps_hawaii.png)
* Rainfall numbers have an even greater difference. December is far wetter than June is. In fact, December and March are the rainiest months of the year. These will be rough days for surfing and terrible days for customers to enjoy even the creamiest milkshakes. On the other hand, April through October are relatively dry, perfect for surfing *and* sipping.
  * ![Hawaii avg monthly rainfall](https://github.com/JDittes/surfs_up/blob/main/avg_precip_hawaii.png)

## Summary:
Hawaiian weather is variable, and while the combination of sipping milkshakes and surfing monster waves would seem like a profitable pursuit, we should keep a few things in mind:
* We should take care of when we open the business. I would open when the sun shines and the rains end in April, giving the shop seven profitable months before the temperatures drop in November and the rains arrive in December. Demand for shakes will tail off at that time, especially.
* We should adapt the business for the winter months. Consider offering coffee for sale from November through March instead of milkshakes, for example. Consider selling more wet suits in winter, more sunscreen in summer.
* This data is from all locations on the island of Oahu. Considering that rain may be variable, as well as waves. We could dig deeper into this data to find which location has the least rainfall, which has the most. 
* We could also look at data to find which station's temperature will be the highest, and therefore the best for selling milkshakes..
