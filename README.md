# Kickstarting with Excel

## Overview of Project
 Objective of the project was to reveal certain algorithims, within campaing stratigies. 
 Provide two technical analysis deliverables, organize and filter subcatagories within "plays" threshold. Be able to provide visual outcomes within based on launch date and Outcomes based on goals. 
### Purpose
To be able to provide a breakdown and proper analysis where Lousie can make proper decisions on starting her campaign. 
Client provied an estimate and budget, I was to proivde her with neccesary data to no only diplay where the campaign funding would be neccissary but also to what requirements where needed for her to reach her goal. I was able to todo so with kickstarter data.  
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
launch date outcomes were accomplished by using the "YEAR()" Function. In order to provide louise with compareable funding goals apposed to different campains, we filtered catagories using pivot tables based on the "parent Category" and "YEARS". Then by filtering the desired outcomes i was able to to provide louise with proper data that then showed the number of Cancels, successful, ect. 
Once Proper data was double checked i was able to generate a graph that shows a visual representation of the data. This graph then  show's us what months are best for launching, what values to expect when canceled within the time frame and what outcomes failed. The graph shows us a visual representation of what to expect with values at a certain time of month within the year to then refrece her launch date analysis. 
![Theater_outcomes_vs_Launch](https://user-images.githubusercontent.com/105321686/175853061-45fcf9d0-5c8e-49f4-96a5-9043fa3e03bf.png)


### Analysis of Outcomes Based on Goals
For outcomes based on goals we created a new sheet to allow a new set of ranges within the desired data. Using the COUNTIFS, function i was able to populate the numbered value by filtering them from my kickstarter data. Being able to filter certain values within the kick starter data, i was able to accept all criteria that is desired to then create and display my results, like percentage, and years, values, that fit within that percentage. Breaking down and orginizing the 12 ranges allows you to then create the line graph That then allows you to see visually what ranges, go up in percentage and go down. BY comparing the funding goals you can then use these refrence values to see what exactly what louise can expect on these outcomes for her overall goal.
![Outcomes_vs_goals](https://user-images.githubusercontent.com/105321686/175853332-e9d24541-bb7d-4daf-9f85-787a1edd5f1f.png)


### Challenges and Difficulties Encountered
For me my biggest challange was trying to properly use the COUNTIFS, formula as i was trying to spell it out everytime. Eventually through trial and error i was able to spell out the function and know exaclty what criteria to select. My line graph also suffered i found a mistake in my data pivot table. It took me a couple hours to realize the function was "successful" within the failed colum. Something so simple nearly brought me to my knees, but with more practice this should be more fluid with time.  

## Results
### Outcomes Based on Launch Date Conclusion
- The bar graph clearly displays when the best time to launch a play. As shown months of May and June. 
On the flip side it diplay's the worst profitable margin to beign during the winter months, And at that time the goal would not be met.  
### Outcomes Based on Goals Conclusion 
- The graph tell's us that goals that are more realistc within the set time frame are more successful, Range goal begins to increase and you see it fall toward the bottom of the graph. 
### limitations of the dataset 
- Alot of limitations would be that we only had a fixed set of values to base our goals and expectations. I belive there should have been much more data like demographicly, propabilites, income based on area, reaserch, investments.  
### Possible tables and graphs to potentially create 
- It would have been good to create a graph that allows us to see what types of income in the certain area, so we could then target that group on donators, investors ect. 
