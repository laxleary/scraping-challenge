# Scraping Challenge
## Module 11 Challenge

### Overview
The following repository uses splinter and Beautiful Soup to extract html from two different websites about Mars. In [Deliverable 1](part_1_mars_news.ipynb), I extract the text from a website to create a list of dictionaries for the news articles included on the site. I then export this list to a JSON file so that it is user-ready. In [Deliverable 2](part_2_mars_weather.ipynb), I extract data from a table using Beautiful Soup methods and iterating by rows to create a list of dictionaries for each data transmission from the Mars rover Curiousity. I then apply Pandas to convert this list into a data frame, and run various analyses including group_by, counting, and plotting methods. I use this analysis to answer various questions such as, "How many days are there in a year on Mars?". Finally, I export my data frame to a CSV. 

**A note on the application of splinter using ChromeDriver:** The entire class experienced issues with the ChromeDriver application download. After significant discussion with our instructor, we located a fix for this by specifying a path to chromedriver.exe within our code rather than putting the file in our PATH on our individual machines. This fix is used in the attached code, with the version 116.0.5845.96 of ChromeDriver meant for 64-bit Windows included in the [corresponding folder](ChromeDriver) of this repository.

### Outside Sources
The following code was developed solely by me, with no assistance from other students, instructors, tutors, or TAs, though the starter code provided was used and included many of the necessary results in advance.
