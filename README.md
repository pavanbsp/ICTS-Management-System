# ICTS Management System
JAVA swings application for ICTS Management system

### Project Abstract

ICTS department provides various type of hardware, software, network, multimedia services to the people of our college. It has various service staff for this purpose. Each person (student or staff) can place the request for the service such as installation of a particular software, keyboard repair, network not available etc. after approval from the HoD of the respective department. However certain people do not require the approval. Based on the type of service requested, the ICTS staff is allotted the job. The personal details of the requester as well as the ICTS staff is maintained such as id, name,phone no. and department to know which person reqeusted the service and who addressed the issue. A person can place one or more requests at a time.
![Image](https://github.com/pavanbsp/ICTS-Management-System/blob/main/img.png)

#### Use Case Diagram
![Use Case Diagram](https://raw.githubusercontent.com/pavanbsp/ICTS-Management-System/main/Use%20case.jpg)

#### Class Diagram
![Class Diagram](https://raw.githubusercontent.com/pavanbsp/ICTS-Management-System/main/Class%20diagram.jpg)

#### User Manual 
**Stages :**
**WA** – waiting for approval<br/>
when a request is placed by a student then the request will move to this stage.<br/>
**AD** – access denied<br/>
when a request is denied by the HOD then the request will move to this stage.<br/>
**P** – Processing<br/> 
A request will move to this stage when
1. A request is placed by a staff/ICTS staff.
2. A request is approved by HOD.<br/>

In this stage request will be automatically(by algorithm) alloted to ICTS staff.<br/>
**C** – completed<br/> 
A request moves to completed stage when processing is completed by ICTS staff.<br/>
![User manuel](https://github.com/pavanbsp/ICTS-Management-System/blob/main/User%20manual.png)

