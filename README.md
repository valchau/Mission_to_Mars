# Mission_to_Mars
## Introduction 
Robin was recently hired as a data analyst at SpaceForward. SpaceForward is an ambitious aerospace company that’s doing research about resource extraction from nearby planets. Robin has been asked to gather information about the climate of Mars. She’s also been asked to collect news items about Mars missions.  To scrape data from the websites that she’s identified, Robin needs to be able to find where the website code stores the data. That is, she must search beyond the text and images that users observe when they open a website—and find the code that organizes the information. This project is to help her succeed.

Robin has become familiar with the foundations of HTML. She can now identify several building blocks of a webpage, like headings and paragraphs. This knowledge will help her identify where to find the data that she wants on a particular webpage. But as Robin encounters references to using CSS selectors in web scraping, she realizes that she needs to learn about CSS. Robin feels excited to learn how to use CSS to style webpages. She’ll be able to use this knowledge to choose HTML elements from which to extract data when web scraping. Having learned about the CSS id selector, Robin now wonders how she can simultaneously target multiple elements for styling. She’ll learn how to do so with the CSS class selector. 

Having learned how to use CSS selectors to style HTML elements, Robin now feels ready to apply this knowledge to scraping a webpage by using Python. Now that she knows basic HTML and CSS, Robin wants to find specific data. But on a webpage with lots of content, finding the HTML element that contains the data she wants can be overwhelming. So, she’ll use Chrome Developer Tools (DevTools). With DevTools, developers can review the structure of any webpage. And not only that, but it also has a search function. This will help make sense of the tags and elements holding the data that Robin is seeking. 

Specifically, Robin needs to identify elements of a webpage so that she can extract data from the News – NASA Mars Exploration. Robin knows that she wants to extract the title and summary sentence from the first article. So, she needs a way to refer to the HTML elements that contain them. To do so, she can use their CSS selectors. 

Robin now feels more familiar with HTML tags and how they fit together to create a webpage. She also has the necessary tools installed to get started with her web scraping. So, she feels eager to dive in.
The next step is to use Splinter to automate a browser. We help Robin get Splinter set up,and now she can scrape data by using Beautiful Soup. This is where practice with HTML tags will come into play. To scrape the data that we want, code will tell Beautiful Soup which HTML tag is being used and if it has a specific class or id attribute.

Robin has now successfully scraped data from a single webpage. But to complete her task of scraping planetary climate data from the NASA website, she needs to use automated web scraping to collect data that spans multiple pages. Next, Robin wants to try scraping a collection of Mars facts. This information exists in a table. Even though that format differs from what she’s encountered before, she can still use DevTools to pinpoint the tag locations. She can then extract the table based on its tag-and-attribute pairing in the HTML code. Robin has chosen to collect her data from Mars Facts. Next, Robin will  scrape the Mars news site. After collecting the data, she’ll have the option to store it and later to analyze it.
 
Robin, with our help, is now ready to perform full web-scraping and data analysis project for the mission to Mars. She’s learned to identify HTML elements on a page, identify their id and class attributes, and to use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. She’s also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

## Results
# Questions 
* How many months exist on Mars?   
      There are 12 months on Mars.
  
* How many Martian (and not Earth) days worth of data exist in the scraped dataset?
     There are  1867  Martian days worth of data here

* What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
* Find the average the minimum daily temperature for all of the months.
    [Average Minimum Daily temperature on Mars](avg_daily_min_temp.PNG)

* Plot the results as a bar chart.
     [Average Minimum Daily temperature on Mars Bar Chart](avg_daily_min_temp_barchart.PNG)

Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average the daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
