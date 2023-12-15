[CS-340 Week 7 Project 2 README.docx](https://github.com/TheLvableMrFish/CS-340/files/13680896/CS-340.Week.7.Project.2.README.docx)
^
Download link for images.


Christian Pagano
SNHU CS-340
12/10/2023

Week 7 Assignment

 
D



All:
 
Water Rescue:
 
Mountain or Wilderness Rescue: 
Disaster Rescue or Individual Tracking:
 


README:
About the Project/Project Title
Using CRUD file, we allow users to Create, Read, Update, Delete, and execute with ease. This will allow users to make modifications more easily and read through a database, so they don’t have to use it the old and boring way. This interacts with the GUI and database which can be interchangeable. 

Using lists at the moment, but plans to change this to allow separate data coming in to allow the user to make their own changes to the GUI and allow for adjustments for their own animal needs.


 








This continues our intent on this open source tool for others to use, we will allow users to use the type lists to create their own query to find the ideal pet for their training or owner needs. 
 

Motivation
We love animals and making a difference, so we are developing this for Grazioso Salvare and they have allowed us to make it open source.

Installation
For this application you will want to have:
-Python 3 or greater installed
https://www.python.org/
-MongoDB
https://www.mongodb.com/
-Jupyter
https://jupyter.org/
-Dash
https://pypi.org/project/jupyter-dash/

Getting Started
First you want to download our file index.py and then get into it and set the username, password, host, port, database, and the collection. This will allow you to use it in the command prompt. 
Then inside the command line type:
```python index.py``` 



Usage

Code Example
Adds
    data=crud.read({"breed" : "Domestic Shorthair Mix"})
 
    for i in range(3):
        print(data[i])
data=crud.read({“breed”: “Domestic Shorthair Mix”})
for i in range(2):
	print(data[i])
 {
“breed”:“Domestic Shorthair Mix”
},
{
“breed”:“Domestic Shorthair Mix”

}

Tests
(pretend this works)
 

Getting Started 2:

After testing the index.py file and making sure it works, you should open Jupyter and go to the latest .ipynb file and make sure that the .py file is correctly being imported with class CRUD. 

You can then press the run on the top of the Jupyter application and click the link run by Dash. This will allow you to see the GUI.
 



Roadmap/Features (Optional)
As an open-source project, we would like to make this available to many users out there and allow contributors to create a UI for this so that users can use databases with even more ease. 


Challenges:
We are still in the early stages of creating this project and have bugs to work though, one of the bugs we are currently working on is having the GUI work with the database. We started by creating our index.py file, we learned that the way it was created may have an impact on those trying to work with our product and have since added comments to make it easier for someone to make changes or learn to use after downloading it. We also have an issue with Juypter at the moment and have to do a side work around by using from dash import Dash and app = Dash('My Dash-App'). 

Contact
Your name:

Christian Pagano

Email:

fake_email@gmail.com

Github:

fake_github.com

Phone:

100-110-010

•	How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?
Writing programs that are maintainable, readable, and adaptable can be done by creating steps in a program and making it modular if possible. I think using my CRUD python module as an example, I was able to create each function I needed separate of each other inside the CRUD class. This allowed each to be readable and making changes to one shouldn’t affect the rest. I think another way I could create a CRUD Python module in the future is making it more flexible, in this one I created it based on using my current host and hardcoding parts into it. 

•	How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?
I think the best approach is first finding out the requirements and creating steps to accomplish this, in this case that may be different from some other classes was using a virtual machine that made it difficult to work on some things and seemed to be a bit bugged in the sense of following the directions, similar to CS-465 which we needed to use some older versions of some programs for it to work properly. I think some of them would be like CS-360 where I am calling them with specific intentions based on the need of the application. I am calling and identifier to verify another part, but I have another for verifying the password. This is hardcoded, but specific. 

•	What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?
Computer Scientists solve problems in my opinion. I think they matter because it allows things to continue to progress. I think in a company setting this allows for solutions to things such as automation or creating ways to help keep track of inventory. In the sense of Grazioso Salvare it allows them to automate the task of filtering out the right dog to for training which could save them time looking for the correct qualifications. 



