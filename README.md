# web-scrapper
Python Website Scrapper


Python Web Scrapper

Objective: Extracting and collecting information from the website

PURPOSE: Collecting Information from a websites

Whenever you want any information, you Google it and go to the webpage, which offers the most relevant answer to your query. You can view the data you needed, but what if you need to save it locally? What if you want to see the data of a hundred more pages?  Then Web Scrapping is your Solution !

Information Gathering icludes:

Collecting Tags
Collecting Images
Collecting Posts Links
Collecting Posts names
Collecting Emails
Collecting External Website Links (Reference Links)
Collecting Tables Informations
Collecting Tags Classses, Id's Names
Collecting PDFs, CSVs
Saving the Collected data in .csv or .xlsx file in a Orgainsed Manner

OBJECTIVE OF THE PROJECT : Create a Responsive Website then Extract the data from the corresponding Website. ( This website is designed using HTML , CSS and Javascript )

Programming Language used to build a Web Scrapper : Python3

Web Scrapping: web scraping simplifies the process of extracting data, speeds it up by automating it and creates easy access to the scrapped data by providing it in a CSV format.

Applications : Web scraping is an important skill for any data scientist to have in their toolbox. Web scraping can be used to collect data about products for sale, user posts, images, and pretty much anything else that is useful on the web.


Requirements: 
* Python3
* xampp server and control panel
* Code Editor (IDE) Recommended: Visual Studio Code

1. Download and Install the python from https://www.python.org/downloads/
2. Install the xampp from the https://www.apachefriends.org/download.html
3. Open the xampp Control Panel
4. Start the Apache service
5. Download the repository from github as .zip format or if you have git installed on computer then run command in git bash terminal: git clone https://github.com/cypherhz/web-scrapper.git
6. Then Extract the .zip file
7. Navigate to the directory where you have extracted the repository folder
8. copy the "spicyo" directory (which is the website directory) into the C:\xampp\htdocs\
9. Open the web browser and search the url: localhost/spicyo
10. Check whether website is running
11. Open the Command Prompt
12. Then Navigate to the directory where you have extracted the repository
13. run the command : dir
14. Install the pip
open the terminal and run : 
pip -V (Checking the version of pip)
python get-pip.py (installing the pip)
python -m pip install --upgrade pip (Upgrading the pip package)

15. Install the Required Libraries and Modules
command to install requests module:  python -m pip install requests

command to install bs4 module:           pip install beautifulsoup4

command to install html5lib:                  pip install html5lib

command to install pandas:                    pip install pandas (it also installs numpy module)
 
command to install xlsxwriter:                pip install XlsxWriter

Finally It's time to execute the web-scrapper:

Launch the scrapper by running the command in the terminal:
python cypherscrappy.py

Eg:     C:\Users\ibrahim\Desktop\Cypher Scrapy> python cypherscrappy.py

This will create result.xlsx, about.txt, home.txt, blog.txt, links.csv etc file in the following directories

The Csv files will be stored in the Csv_Files folder
The Excel Files will be stored in the Excel_Files folder
The Whole Text of Website will be stored in the Whole_Text folder

The result.xlsx (Excel file) itself contains many data that are enough for the developer
