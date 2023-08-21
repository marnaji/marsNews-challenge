# MarsNews-challenge
This challenge comprises two distinct sections: the first involves scraping titles and previews, while the second pertains to extracting weather data from Mars and conducting subsequent analysis on the collected data.

### Part1
In this part of the challenge I scraped Titles and Previewes Text from Mars News. I used automated browsing to visit <a href="https://static.bc-edx.com/data/web/mars_news/index.html" target="_blank">Mars news site</a> 

I employed the Beautiful soup library to extract text elements for titles an previews. I stored the scraping results in a Python data structure. 

    1. Stored each title and preview pair in one dictionary and gave each dictionary keys : title and preview.
    2. Stored all the dictinaries in a Python list .

<img src="/Images/dictionariesOutput.png" width="500" > 


### Part2

In this section I visited <a href ="https://static.bc-edx.com/data/web/mars_facts/temperature.html" target = "_blank">Mars Temperature Data Site</a> to scrape and analyze Mars Weather Data. 

I utilized the Beautiful Soup library to create an object, which I then employed for data scraping from the HTML table. Subsequently, I compiled the scraped information into a Pandas DataFrame, mirroring the six columns found on the website. I meticulously evaluated and adjusted the data types in the DataFrame to align with the values—resulting in the utilization of datetime, integer, and floating-point data types as appropriate.


Subsequently, the data from the subsequent steps was subjected to analysis in order to address several questions, including:

    1. How many months exist on Mars?
    2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
    4. Which months have the lowest and the highest atmospheric pressure on Mars? 
    5. About how many terrestrial (Earth) days exist in a Martian year? 

Several of these questions were addressed through the implementation of various plots, and at the end the DataFrame has been exported to the csv file format. 

<img src="/Images/monthsTemp.png" width="300" > 
<img src="/Images/pressureMonths.png" width="300" >
<img src="/Images/terrestorialdaysTemp.png" width="300" > 
 


### References
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.