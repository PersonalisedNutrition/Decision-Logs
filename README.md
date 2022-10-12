## Decision Record

---
##### Time: 2022.10.02【011】Logs database design change

> **Decision members:** All group members
>
> **Decision-making situations:** All agreed.
>
> **Decision topic:** Change the logs' database design
>
> **Decision material:** Before we store the logs's data in seperate tables according to different types of logs.As the client and nutritionist's need, we store all the logs' data of one client in a table.
>
> **Decision results:** We changed our logs' database in firebase.
>
> **Decision Risks:** As we store all the logs' data in one table, the amount of data stored at once is large, resulting in a slow response of the web page to the display of the database
>
> **Decision process and decision analysis:** First have a meeting with client and nutritionist and get their needs.Then the whole team have a meeting together to discuss this decision and finally the data group carry out the corresponding work.

##### Time: 2022.9.16【010】Data-side framework determination

> **Decision members:** All group members
>
> **Decision-making situations:** All agreed.
>
> **Decision topic:** Change date base from storage to real-time model.
>
> **Decision material:** When we tried to connect firestore with web backend, we cannot find enough learning meterial. However, we found the real-time mode can suit our project, and meet our design. Also we connect the real-time with website back end successfully.
>
> **Decision results:** We changed our database into firebase real-time mode.
>
> **Decision Risks:** The storage maybe light weighted. If the client want to use our product for business, it maybe not enough for all the data. So for the extra data, it may be charged.
>
> **Decision process and decision analysis:** Real-time can meet our demand, eventhrough it is light weighted, but it is enough for this stage. 

##### Time: 2022.8.28【009】Web-side framework determination

> **Decision members:** Web group members
>
> **Decision-making situations:** All agreed.
>
> **Decision topic:** What framework will be used for the development phase.
>
> **Decision material:** After carefully studying the development cycle, we realized that if we were to develop the web-side architecture all by ourselves, we would waste a lot of time on writing the basic architecture. Instead, we wanted to focus on the implementation of user requirements and optimization of user experience.
>
> And framework development, should take into account the development costs, learning costs.
>
> **Decision results:** Decided to use Django for full-end development with a more established base open source architecture.
>
> **Decision Risks:** Group members need to learn Django, and try to connect it to firebase, which may delay development.. 
>
> **Decision process and decision analysis:** After a detailed understanding of each group member's technology stack and an analysis of the advantages and disadvantages of each framework, the group made that choice based on the development plan.
>
> The minutes of the meeting are attached here： [Minutes](https://docs.google.com/document/d/1FjWj_0I9ZUBXTRLtCvJfEXIWWfAC-c6gnNwrWpiWs1Q/edit?usp=sharing)

##### Time: 2022.8.25【008】 Self-built back-end framework

> **Decision members:** Web group members
>
> **Decision-making situations:** All agreed.
>
> **Decision topic:** What framework to use for website development.
>
> **Decision material:** As the development into the next phase, we need to decide as soon as possible what framework to use for web development, the framework should meet the following requirements: 
>
> - Database can use firebase.
> - Can be highly customizable front-end and back-end
> - Use the technology as much as possible in the scope of everyone's technical reserves. 
> - Safe and reliable.
>
> **Decision results:** designs our own development framework.
>
> **Decision Risks:** Designing your own development framework may lead to longer development cycles, bugs in the system, and other risks. 
>
> **Decision process and decision analysis:** Since most frameworks are not compatible with the firebase database, and we have to use firebase in order to ensure that we can provide real-time interactive features to users and nutritionists, we need to develop our own framework.

##### Time: 2022.8.22 【007】 Manual document
> **Decision members:** All members
>
> **Decision-making situations:** All agreed.
>
> **Decision topic:** We should add a user manual document for user. This will be a task in week 11.
>
> **Decision material:** We will write an instruction for nutritionists to learn how to use our website.
> 
> **Decision results:** We will finish this task at week 11. Because, at this time, we still at developing state.
>
> **Decision Risks:** 1, Maybe we will forget this task. 2 It add some workload on the original plan, maybe we don't have enough time to do that.
>
> **Decision process and decision analysis:** We developed an APP and Website for nutritionist, They need to know how to use it. So an manual document is necessary.
> 
##### Time: 2022.8.20 【006】 Web-side user experience optimisation

> **Decision members:** Members from Web group
>
> **Decision-making situations:** All agreed
>
> **Decision topic:**  Secondary design of the web end, with controls optimised for user experience.
>
> **Decision material:**  [Web Preview](https://js.design/f/AFy6ra?p=exj8lED8oB)
>
> **Decision results:** 
>
> - Make changes to the number and location of controls; 
> - Add a user settings page; Remove the number of follower and user data completion statistics display controls from the board page; 
> - Decide to add up to three user alerts on the settings page.
>
> **Decision Risks:** 
>
> - The optimization of the control experience was designed by members of the web group without stakeholder involvement, which may have led to negative feedback from some users about the optimization.
> - A new user reminder feature on the user settings page will allow nutritionists to send reminders to users at regular intervals, which may be perceived by users as an intrusion.
>
> **Decision process and decision analysis:**
>
> - Regarding the modification of controls: overly complex page design may make users feel inconvenient to use, so we decided to keep only the frequently used key functions and key information entry on the first level page as much as possible, hide the necessary controls on the next level, and remove unnecessary controls.
> - About the new settings page: After consultation between the dietitian and the client, a plan will be provided by the dietitian, which may include a timed reminder to the user to eat. Therefore, we have provided the function of the dietitian to push notifications to the user at regular intervals on the user settings page.

##### Time: 2022.8.20 【005】 Determine log module database tables

> **Decision members:** Members from Web group and Data group
>
> **Decision-making situations:** All agreed
>
> **Decision topic:**  How to design a log table so that it can quickly query the content of the type of tables required.
>
> **Reasons:**  To simplify the searching process and make speed up the searching efficiency.
> 
> **Decision material:**  https://drive.google.com/drive/folders/1EBECsdKqL4or9WGRNPUXVfJb5RiwICmo
>
> **Decision results:** Add type column and table_id column to quickly query the required table information.
><img width="501" alt="image" src="https://user-images.githubusercontent.com/100653606/185786833-b6971bbd-6e02-40fb-b044-2953ea961e77.png">
>
> **Decision Risks:**
> 1. Increasing the number of table columns may increasing the amount of data and thus increasing the storage space cost of the database.
> 2. Increase the cost of database maintenance and management.
>
> **Decision process and decision analysis:** Also update the links in landing page.

##### Time: 2022.8.1 【004】Made a survey to collect the information and logs.
> **Decision members:** All members with Ric
>
> **Decision-making situations:** All agreed
>
> **Decision topic:** Made a survey to collect the information and logs.
>
> **Decision material:** The survey.doc and the clearance.doc.
>
> **Decision results:** Use the survey to collect two kind of informations: users' basic information, user's daily logs.
> the survey will be modified by nutritionists and need a clearance to tutorial
>
> **Decision Risks:** So many items will be collect, and the nutritionists' opinions maybe delay the process
>
> **Decision process and decision analysis:** Because the app can not use for collecting data.

##### Time: 2022.8.1 【003】 Add a web site for nutritionist. 
> **Decision members:** All members
>
> **Decision-making situations:** All agreed
>
> **Decision topic:** Add a web site for nutritionist. 
>
> **Decision material:** In the contract, we write this inside it. It's about the tasks.
>
> **Decision results:** Make new plan for this semester. Ric and nutritionists will give us help during this sesmester.
> For the web, it should have these functions: 
> 1 nutritionists can login to the system
> 2 nutritionists can add comment on the logs
> 3 nutritionists can look throught the logs which belongs to him
> 4 other functions that client want or nutritionist want.
>
> **Decision Risks:** Team members need some time to learn the knolodge about deploy the web site.
>
> **Decision process and decision analysis:** 
> Have a meeting with Ric. And need more meeting with nutritionists.

##### Time: 2022.7.25【002】 Add two new members for S2.
> **Decision members:** All members
>
> **Decision-making situations:** All agreed
>
> **Decision topic:** Add two new members for S2.
>
> **Decision material:** Contract.
>
> **Decision results:** Team add Siyuan He and Hengtong Wu
>
> **Decision Risks:** The two numbers don't know the skills what we need.
>
> **Decision process and decision analysis:** Because we need more labor for our project. More people means more out put.

##### Time: 2022.5.02 【001】Which database are suitable for the project?

> **Decision members:** All members
>
> **Decision-making situations**： All agreed
>
> **Decision topic:** Which database are suitable for the project?
>
> **Decision material:** 
>
> 1. Group discussion
> 2. Firebase google documents
>
> **Decision results:**
> 
>  We compared all the database listed on Firebase and finally select the cloud storage for our project.
>  
> ![image](https://user-images.githubusercontent.com/100653606/166412239-4040682d-329b-4ef0-8a0e-f49f77a0731d.png)
> 
> **Decision Risks:**
>
> 1. Charges may be paid when exceed the free use limit.
> 2. The speed of uploading and downloading data can be affected by network condition.
> 
> **Decision process and decision analysis:**[link to the document](https://docs.google.com/spreadsheets/d/1RkY096tJSgi-kvxhQjRj9ckXJtfF_9kK/edit#gid=827619485)
> 

##### TEMPLATE!

##### Time: 2022.3.15 【XXX】 Decision log templates(It should be concise)
> **Decision members:** All members
>
> **Decision-making situations:** All agreed, Some people may raise up different solutions.
>
> **Decision topic:** Topics in one sentence
>
> **Decision material:** The content of the decision, what have been decided? Details about the decision topic.
>
> **Decision results:** The result of the decision.
>
> **Decision Risks:** Some potential risks.And how to over come it.
>
> **Decision process and decision analysis:** The reason why we need to decide this.And maybe some comments from the future. Whether this decision is good or not.

