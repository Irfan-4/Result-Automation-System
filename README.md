# Result-Automation-System
AIM:
The aim of this project is to obtain the results of all students from any college at once rather than one by one.
WHY THIS PROJECT?
Once the students' results have been published, they become accessible on the college's official website. Students can access their results by entering their respective roll numbers. However, if there is a desire to view the collective results of all students, it necessitates manually inputting the details of each student, one after another, to access individual results. This process is notably time-intensive.
To tackle this predicament, a project was developed to present all student results simultaneously. These results are presented in the format of an Excel spreadsheet.
WORKING:
Upon the initiation of my program, it directs itself to the website where the academic grades of college students are published. By gaining access to this website, the program systematically populates the students' particulars individually. Consequently, it extracts the corresponding grades from the presented results. Furthermore, these attained scores are accumulated and stored within an Excel file for record-keeping purposes.
TECHNOLOGY USED:
Programming Language: Python
Web scraping: By BeautifulSoup
Web Automation: By Selenium
Webdriver: Chrome
SOFTWARE REQUIREMENTS:
Python: The code is written in Python, so you need to have Python installed on your system. You can download Python from the official website: https://www.python.org/downloads/
Chrome WebDriver: Since Selenium is used to scrape data from a web page, you need to download the appropriate Chrome WebDriver for your Chrome browser version. You can get the Chrome WebDriver from here: https://sites.google.com/chromium.org/driver/

HARDWARE REQUIREMENTS:
The hardware requirements are minimal. You need a computer or laptop with the following:
Adequate RAM and CPU power to run Chrome browser and Python scripts smoothly.
Sufficient storage space to store the Python scripts, Chrome WebDriver, and any data files generated.
Installation Steps:
1.Install Python: Download and install Python from the official website. Make sure to add Python to your system's PATH during installation.

2.Install Required Libraries: Open a command prompt or terminal and run the following commands to install the required libraries:
pip install pandas
pip install selenium
3.Download Chrome WebDriver: Download the Chrome WebDriver that matches your Chrome browser version. Place the WebDriver executable in a directory that's in your system's PATH.
4.Update Chrome: Make sure your Chrome browser is up to date to avoid compatibility issues with the Chrome WebDriver.
5.Run the Script: Save the provided code in a ‘.py’ file and run it using the command prompt or terminal. Make sure the script file, Chrome WebDriver, and the Excel file are in the same directory.
