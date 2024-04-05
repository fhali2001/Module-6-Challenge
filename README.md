# Python API Challenge

## Background
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

## Before You Begin
Create a new repository for this project called python-api-challenge. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Inside your local Git repository, create a directory for this assignment. Use a folder name that corresponds to the Challenges, such as WeatherPy.

Inside the folder you just created, add the files called api_keys.py, WeatherPy.ipynb, and VacationPy.ipynb that you will find in the starter code ZIP file provided. These will be the main scripts to run for each analysis.

Before you push your changes to GitHub, add a .gitignore file.

## Add a .gitignore File
For this assignment, you will need to add a .gitignore file to your repo. Doing so will prevent the api_keys.py file that contains your API key from being shared with the public. If you skip this step, anyone using GitHub could copy and use your API key, and you may incur charges as a result.

To get started, type git status in the command line to see a list of all the untracked files that you have created so far.

To add only the WeatherPy.ipynb file to GitHub, for example, type git add WeatherPy.ipynb. Keep in mind that you would have to add each file individually when adding or updating a file. A more efficient solution is to add all of the files that you don't want to track to the .gitignore file.

Before adding your files to GitHub, add api_keys.py to the .gitignore file by following these steps:

Open your python-api-challenge GitHub folder in VS Code.

Open the .gitignore file and type the following code on the first line:

# Adding config.py file.
api_keys.py
In the command line, type git status and press Enter. The output should indicate that the .gitignore file has been modified and the api_keys.py file is untracked.

Use git add, git commit, and git push to commit the modifications to the .gitignore, WeatherPy.ipynb and VacationPy.ipynb files to GitHub.

On GitHub, the only new python files you should find are WeatherPy.ipynb and VacationPy.ipynb.

## Files
Download the following files to help you get started:
- [Module 6 Challenge files](https://static.bc-edx.com/data/dl-1-2/m6/lms/starter/Starter_Code.zip)

## Instructions
This activity is broken down into two deliverables, WeatherPy and VacationPy.

**Part 1: WeatherPy**
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python library, the OpenWeatherMap API, and your problem-solving skills to create a representative model of weather across cities.

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.

**Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude**
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

**Requirement 2: Compute Linear Regression for Each Relationship**
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

**Part 2: VacationPy**
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

## Requirements
**Part 1: WeatherPy**
- Create Plots to Showcase the Relationship Between Weather Variables and Latitude (30 points)
- Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code (10 points)
- Create a scatter plot to showcase the relationship between Latitude vs. Temperature (5 points)
- Create a scatter plot to showcase the relationship between Latitude vs. Humidity (5 points)
- Create a scatter plot to showcase the relationship between Latitude vs. Cloudiness (5 points)
- Create a scatter plot to showcase the relationship between Latitude vs. Wind Speed (5 points)

- Compute Linear Regression for Each Relationship (40 points)
  - Linear regression scatter plot for Northern Hemisphere: Temperature (C) vs. Latitude (5 points)
  - Linear regression scatter plot for Southern Hemisphere: Temperature (C) vs. Latitude (5 points)
  - Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude (5 points)
  - Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude (5 points)
  - Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude (5 points)
  - Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude (5 points)
  - Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)
  - Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude (5 points)

**Part 2: VacationPy**
- Create a map that displays a point for every city in the city_data_df DataFrame (5 points)
- Narrow down the city_data_df DataFrame to find your ideal weather condition (5 points)
- For each city in the hotel_df DataFrame, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates (10 points)
- Add the hotel name and the country as additional information in the hover message for each city in the map. (10 points)

## Grading
This assignment will be evaluated against the requirements and assigned a grade according to the following table:

Grade	Points
A (+/-)	90+
B (+/-)	80–89
C (+/-)	70–79
D (+/-)	60–69
F (+/-)	< 60

## Submission
To submit your Challenge assignment, click Submit, and then provide the URL of your GitHub repository for grading.

**NOTE:** You are allowed to miss up to two Challenge assignments and still earn your certificate. If you complete all Challenge assignments, your lowest two grades will be dropped. If you wish to skip this assignment, click Next, and move on to the next module.

Comments are disabled for graded submissions in Bootcamp Spot. If you have questions about your feedback, please notify your instructional staff or your Student Success Advisor. If you would like to resubmit your work for an additional review, you can use the Resubmit Assignment button to upload new links. You may resubmit up to three times for a total of four submissions.

## IMPORTANT
It is your responsibility to include a note in the README section of your repo specifying code source and its location within your repo. This applies if you have worked with a peer on an assignment, used code in which you did not author or create sourced from a forum such as Stack Overflow, or you received code outside curriculum content from support staff such as an Instructor, TA, Tutor, or Learning Assistant. This will provide visibility to grading staff of your circumstance in order to avoid flagging your work as plagiarized.

If you are struggling with a challenge assignment or any aspect of the academic curriculum, please remember that there are student support services available for you:

- Ask the class Slack channel/peer support.
- AskBCS Learning Assistants exists in your class Slack application.
- Office hours facilitated by your instructional staff before and after each class session.
- Tutoring Guidelines - schedule a tutor session in the Tutor Sessions section of Bootcampspot - Canvas

If the above resources are not applicable and you have a need, please reach out to a member of your instructional team, your Student Success Advisor, or submit a support ticket in the Student Support section of your BCS application.
