<h1> UiPath Studio Project </h1>


***

### Problem Statement
Our project is aimed to help  professors of various colleges in making their course policies for their subject. In the current scenario teachers make word file for course policy from scratch for every subject they teach. A teacher normally teaches 3-4 different subjects every semester. This work every week can add up to be a daunting task for the professors.
***
### Proposed Solution
We prepared a RPA **(Robotic Process Automation)** tool that can be deployed on an orchestrator. Our bot opens up the template word file and then asks input from teacher such as Course name, facuulty name, co-faculty name, faculty details, no. of lecture hrs, practical hrs, credits, email-id, course start date and end date, no. of lectures per week (automatically creates lecture and practical slots table accordingly), make course description, make Course methodology (as per blooms taxonomy), course outcome,course importance etc from Chat GPT.
***
### Technologies Incorporated 
* UiPath StudioX
* Microsoft Word
* Microsoft Excel
* OpenAI Chat GPT API
***
### Input Required
Some basic parameters like Course name, faculty name, course start/end date etc need manual input and popup input dialog will be dispalyed whenever manual input is needed. 
***
### Output Obtained
1. A folder containing
  * Final Course Policy Word document
  * Execel File to keep a record of how and what all records did UiPath store inorder to make the Course Policy document.

***


### Limitations of the program
* Date has (wherever necessary) has to be entered in mm/dd/yy format. 
* The machine on which user is executing the program needs to have unrestricted access to internet.
* Can only work on a particular type of Course Policy document. We plan to add more styles later.

***
### Contributions
1. We made this project as a part of our Robotic Process Automation Course.
 
 | Name          | Link                                                                          |
 | ------------- |:-----------------------------------------------------------------------------:|
 | Shreyas       | https://github.com/Shreyas-Dongre                                             |     
 | Maitri        | https://github.com/maitri01                                                   |
 | Hansin        | https://github.com/hansin2901                                                 |
 
