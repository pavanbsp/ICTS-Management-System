# ICTS Management System
JAVA swings application for ICTS Management system

### Project Abstract

ICTS department provides various type of hardware, software, network, multimedia services to the people of our college. It has various service staff for this purpose. Each person (student or staff) can place the request for the service such as installation of a particular software, keyboard repair, network not available etc. after approval from the HoD of the respective department. However certain people do not require the approval. Based on the type of service requested, the ICTS staff is allotted the job. The personal details of the requester as well as the ICTS staff is maintained such as id, name,phone no. and department to know which person reqeusted the service and who addressed the issue. A person can place one or more requests at a time.
![Image](https://amritauniv.sharepoint.com/sites/ObjectOrientedProgrammingJune-Dec2020/_layouts/15/getpreview.ashx?resolution=2&guidSite=9901b62baa6a4662b7799e1fa389dfb4&guidWeb=9567aaa1b213476ba6a6c3103584fa24&guidFile=0c64ab8874564c8aaf0e7c1b0049a26e&clientType=modernWebPart)

#### Use Case Diagram
![Use Case Diagram](https://raw.githubusercontent.com/pavanbsp/ICTS-Management-System/main/Use%20case.jpg)

#### Class Diagram
![Class Diagram](https://raw.githubusercontent.com/pavanbsp/ICTS-Management-System/main/Class%20diagram.jpg)

#### User Manual 
**Stages :**
**WA** – waiting for approval 
when a request is placed by a student then the request will move to this stage.
**AD** – access denied
when a request is denied by the HOD then the request will move to this stage.
**P** – Processing 
A request will move to this stage when
	1. A request is placed by a staff/ICTS staff.
	2. A request is approved by HOD.
in this stage request will be automatically(by algorithm) alloted to ICTS staff.
**C** – completed 
A request moves to completed stage when processing is completed by ICTS staff.
![User manuel](https://github.com/pavanbsp/ICTS-Management-System/blob/main/User%20manual.png)

#### Screen Shots

###### Main page
![Home Page](https://github.com/pavanbsp/ICTS-Management-System/blob/main/Page%20screenshots/Main%20page.png)
###### Place request page
![Home Page](https://github.com/pavanbsp/ICTS-Management-System/blob/main/Page%20screenshots/Place%20request%20page.png)
###### Place request page
![Home Page](https://github.com/pavanbsp/ICTS-Management-System/blob/main/Page%20screenshots/View%20request%20details%20page.png)
###### Icts staff login page
![Home Page](https://github.com/pavanbsp/ICTS-Management-System/blob/main/Page%20screenshots/Icts%20staff%20login%20page.png)
###### Hod login page
![Home Page](https://github.com/pavanbsp/ICTS-Management-System/blob/main/Page%20screenshots/Hod%20login%20page.png)
###### Admin page
![Home Page](https://github.com/pavanbsp/ICTS-Management-System/blob/main/Page%20screenshots/Admin%20login%20page.png)
###### Admin Details
![Home Page](https://github.com/pavanbsp/ICTS-Management-System/blob/main/Page%20screenshots/Admin%20data.png)
This page contains all the details of staff,Hod's,Icts staff,student and about all request placed.
Requests contains requested by,date,status,completed date,approval required,proccesed by,department.
