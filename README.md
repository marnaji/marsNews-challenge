# MarsNews-challenge
This Challenge inclued two section one is to scrape titles and previews and the other one is for scrapping weather data in Mars and do some Analysis on those data. 

### Part1
In this part of the challenge I scraped Titles and Previewes Text from Mars News. I used automated browsing to visit <a href="https://static.bc-edx.com/data/web/mars_news/index.html" target="_blank">Mars news site</a> 

I used Beautiful soup object to extract text elements for titles an previews then I stored the scraping results in a Python data structure. 

    1. Stored each title and preview pair in one dictionary and gave each dictionary keys : title and preview
    2. Stored all the dictinarie ina Python list 

<img src="/Images/dictionariesOutput.png" width="500" > 


### Part2

In this section I visited <a href ="https://static.bc-edx.com/data/web/mars_facts/temperature.html" target = "_blank">Mars Temperature Data Site</a> to scrape and analyze Mars Weather Data. 

I used Beautiful soup objecr and used it to scrape the data in the HTML table, Then assembled the scraped data into a Pandas DataFrame. There are six coulmns as the same as the website in the DataFrame. The data type has been examine and changed to the proper data type based on the values so, the new data types are datetime, int , and float. 

The later steps data has been analyzed to answers few questions such as :

    1. How many months exist on Mars?
    2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
    4. Which months have the lowest and the highest atmospheric pressure on Mars? 
    5. About how many terrestrial (Earth) days exist in a Martian year? 

Some of these question has been answered based on the plots that has been implemented and at the end the DataFrame has been exported to the csv format file. 

<img src="/Images/monthsTemp.png" width="300" > 
<img src="/Images/pressureMonths.png" width="300" >
<img src="/Images/terrestorialdaysTemp.png" width="300" > 
 


### References
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.