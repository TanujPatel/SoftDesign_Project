# **Iteration 3:  Addressing Quality Attribute Scenario Driver (QA-3)**

## **Step 2: Establish Iteration Goal by Selecting Drivers**
For this iteration, the  architect  focuses  on  the  QA-3  quality  attribute  scenario: 
The system server will stay running for 10 minutes after a power outage using the UPS we install, for users to back up data. The system will be running 24/7 for users to access multiple hotels and book hotels at any time.

## **Step 3 : Choose One or More Elements of The System to Refine**
For  this  availability  scenario,  the  elements  that  will  be refined  are  the  physical 
nodes that were identified during the first iteration: 
- Application server 
- Database server 

## **Step 4 : Choose One or More Design Concepts That Satisfy the Selected Drivers**
Design concepts uesd in this iteration:
![This is an image](https://github.com/TanujPatel/SoftDesign_Project/blob/main/Iteration%203/Tables/Step4Table.PNG?raw=true)

## **Step 5: Instantiating Architectural Elements, Allocate Responsibilities, and Defining  Interfaces**
The table below summarizes the instantiation design decisions:
![This is an image](https://github.com/TanujPatel/SoftDesign_Project/blob/main/Iteration%203/Tables/Step5Table.PNG?raw=true)

## **Step 6:Sketch Views and Record Design Decisions**
![This is an image](https://github.com/TanujPatel/SoftDesign_Project/blob/main/Iteration%203/Diagrams%20or%20Views/Step6Diagram.PNG?raw=true)

Figure 3.1: Sequence Diagram showing the exchange of messages between the physical nodes to support UC-10 (Detect Faults)
## **Step 7: Perform Analysis of Current Design and Review Iteration Goal and Achievement of Design Purpose**
The table below summarizes the status of the different drivers and the decisions that were made for this iteration:
![This is an image](https://github.com/TanujPatel/SoftDesign_Project/blob/main/Iteration%203/Tables/Step7Table.PNG?raw=true)


