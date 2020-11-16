# Data Analysis and Visualization of SpaceX Data

### Project Inspiration
In the 1960's, the scientists, engineers, math 'computers', and astronauts at NASA proved to the country and to the world that space exploration was the next big adventure for humankind. The culmination of thousands of training hours, hundreds of errors, and out-of-the-box problem-solving paved the way to arguably one of the greatest feats of humankind - a moon landing. Never before had the human race stepped foot on another celestial body. But, in 1969 they found the right combination of intellect, determination, passion, grit, ingenuity, and persistence to get it done. 

Though there were only 6 successful missions, spanning only three years, that would carry out a mission to and from the moon, the lessons learned during the apollo era were indisputably a 'giant leap' for science, technology, and frankly - imagination. What was once impossible, became possible and the flood gates were opened to minds everywhere of what else could be accomplished.

Fast forward past the shuttle era, the creation of the ISS, and the deployment of Hubble, and we find ourselves in a new age of space exploration. Now, alongside the government-funded NASA, we have private companies joining in on the future of the space industry. One company in particular is leading the way in this new venture and has captured the hearts and minds of a new generation of space enthusiasts.

### Project Information
SpaceX is a private company paving the way in commercial space flight in collaboration with NASA's Commercial Crew Program. The purpose of this project, by way of jupyter notebook, is to gather, analyze, and visualization SpaceX data using an open source REST API through r/SpaceX. Specifically this project highlights past launch and upcoming launch data. The data of interest that you will find here are as follows:

***Past Launch Data:***
- First SpaceX launch & most recent launch date and mission details
- Rocket usage breakdown
- Payload breakdown

***Upcoming Launch Data:***
- Scheduled date and time for upcoming flights
- Time remaining until upcoming flights as of time of application execution
- Upcoming rocket usage breakdown
- Upcoming payload breakdown

### Features included:
1. Create a dictionary or list, populate it with several values, retrieve at least one value, and use it in your program
2. Connect to an external/3rd party API and read data into your app
3. Calculate and display data based on an external factor (ex: get the current date, and display how many days remaining until some event)
4. Visualize data in a graph, chart, or other visual representation of data
5. Use pandas, matplotlib, and/or numpy to perform a data analysis project. Ingest 2 or more pieces of data, analyze that data in some manner, and display a new result to a graph, chart, or other display

### How to run notebook:
*Note: this project was written in python 3. Ensure you have most updated python version downloaded on your machine.*
*Check python version using terminal: ```python --version```*
*If an upgrade is needed, consult the [download guide](https://wiki.python.org/moin/BeginnersGuide/Download) in the Python docs.*

#### 1. Import necessary libraries/modules to local machine: 
*Installation instructions use pip. To use anaconda, replace 'pip' with 'conda'.*
- jupyter notebook: ```pip install notebook```
- requests: ```pip install requests```
- pandas: ```pip install pandas```
- dateutil: ```pip install python-dateutil```
- matplotlib: ```pip install matplotlib```
- numpy: ```pip install numpy```
#### 2. Clone repo to machine
#### 3. Using terminal/command line, navigate to repo and open notebook by providing this command to the shell:
```jupyter notebook```
#### 4. Find spacex.ipynb file and open
#### 5. Inside of notebook, run shells with one of the following:
- Click 'Run' for each code cell
- On the keyboard, press 'shift' + 'enter' to run each cell

### Sources
1. API used was supplied by [r/SpaceX](https://github.com/r-spacex) open-source REST API. View API docs [here](https://docs.spacexdata.com/#intro).












