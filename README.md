## Decision Record

---
##### Time: 2022.8.20 【016】 Web-side user experience optimisation

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

##### Time: 2022.8.20 【015】 Determine log module database tables

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

##### Time: 2022.8.15 【014】 Add "set reminder" function for nutritionists side or clients side.
> **Decision members:** All members
>
> **Decision-making situations:** All agreed
>
> **Decision topic:**  Add "set reminder" function for nutritionists side or clients side.
>
> **Reasons:** 
> 1.The nutritionists should monitor the client's daily nutritional tasks.
> 2.Clients have the right to choose to set alerts or not to set alerts
>
> **Decision material:**  https://docs.google.com/spreadsheets/d/1PLmOsQnCVrAAO0LpaOhfZcuOYHoYTo4h/edit#gid=827619485
> <img width="501" alt="image" src="https://user-images.githubusercontent.com/100653606/185787530-94166760-06a7-4ebe-b34e-13c9981083e2.png">
>
> **Decision results:** Add "set reminder" function for both nutritionists side and clients side.
>
> **Decision Risks:** It may annoy the clients when frequent reminder were sent.
>
> **Decision process and decision analysis:** Also update the links in landing page.

##### Time: 2022.8.7 【013】 Use Git-Hub to track the decisions
> **Decision members:** All members
>
> **Decision-making situations:** All agreed
>
> **Decision topic:**  Give up the excle file which record the decisions.
>
> **Decision material:**  https://github.com/PersonalisedNutrition/COMP8715-Nutrition-Project/edit/main/README.md
>
> **Decision results:** Update the decision logs in this page
>
> **Decision Risks:** People who first read this record may feel uncovienet to go through all the decisions. 
>
> **Decision process and decision analysis:** Also update the links in landing page.

##### Time: 2022.8.7 【012】 Use newsletter to record tasks, give up devops
> **Decision members:** All members
>
> **Decision-making situations:** All agreed
>
> **Decision topic:**  Use newsletter to record tasks, give up devops
>
> **Decision material:**  https://drive.google.com/drive/folders/1HIpgdxuxjfJruCtvwNC3l2SuTSx6FTpc?usp=sharing
>
> **Decision results:** Give up devops. But restart it if it is needed.
>
> **Decision Risks:** Not so clear compared to Devops. Teammembers may forget their tasks.
>
> **Decision process and decision analysis:** Because the devops need to add the items in it, and the news letter can clear show what tasks we have. So the devops are useless.

##### Time: 2022.8.7 【011】 Working field
> **Decision members:** All members
>
> **Decision-making situations:** All agreed
>
> **Decision topic:** Working areas are divided.
>
> **Decision material:** Who is responsable for the centein area of works. 
>
> **Decision results:** 
> Speak person: Shuyi, Yuhao
> Holding the meeting(Meeting aganda, news letter), and design the tasks.
> Connect with client and nutritionists: Shuyi
> Paper works: Yuhao (Decision log, Risk, Reflection, Meeting minutes, Checking Ring and so on)
> Web site: Tianqi, Shiyun, Siyuan, Shuyi.
> Data base: Xinyue, Hengtong, Yuhao.
> Audit: All group members, ppt:Shuyi. 
> Landing page: Shiyun, Yuhao, Shuyi, Tianqi. 
> **Decision Risks:** May left some part of work not assigned to people. And in the future need to change according to the need. 
>
> **Decision process and decision analysis:** NA
##### Time: 2022.8.1 【010】Made a survey to collect the information and logs.
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

##### Time: 2022.8.1 【009】 Add a web site for nutritionist. 
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

##### Time: 2022.7.25【008】 Add two new members for S2.
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

##### Time: 2022.5.02 【007】Which database are suitable for the project?

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
##### Time: 2022.4.12 【006】How to avoid possible mistakes?

> **Decision members:** All members
>
> **Decision-making situations**： All agreed
>
> **Decision topic:** How to avoid possible mistakes?
>
> **Decision material:** 
>
> Group discussion
>
> **Decision results:**
> 
> 1. There are two types of checks, the first is self-checking and the second is having another group member to check.
> 2. Create a "check ring" to avoid possible mistakes
> 
> **Decision Risks:**
>
> 1. The workload of each team member will increase.
> 2. Work efficiency may be reduced.
> 
> **Decision process and decision analysis:**[link to the document](https://docs.google.com/spreadsheets/d/1zL6bBy1mA-BDMYINQeXaFdCgvZHBLW20/edit#gid=827619485)
##### Time: 2022.4.12 【005】 How many nutritionists are best for a client?

> **Decision members:** All members
>
> **Decision-making situations**： All agreed
>
> **Decision topic:** How many nutritionists are best for a client?
>
> **Decision material:** 
>
> Group discussion
>
> **Decision results:**
>
> 1. A client is better to have more than 1 nutritionist.
> 2. The number of matched nutritionist should be limited to 
>
> **Decision Risks:**
>
> 1. Increasing the difficulty of database design, as well as the complexity of user management.
> 2. Clients may lack the ability to judge the quality of the solutions provided by different nutritionists.
> 3. The certification of nutritionists needs to be strengthened.
>
> **Decision process and decision analysis:**[link to the document](https://docs.google.com/spreadsheets/d/1RkY096tJSgi-kvxhQjRj9ckXJtfF_9kK/edit#gid=827619485)
> 
##### Time: 2022.3.21 【004】 What we still need to do for the Landing Page.

> **Decision members:** Members responsible for producing Landing pages include:
>
> ​									Shuyi Chen, Tianqi Tang, Yuhao Zhai, Shiyun Zhu
>
> **Decision-making situations**： All agreed
>
> **Decision topic:** What we still need to do for the Landing Page.
>
> **Decision material:** 
>
> 1. Group discussion.
> 2. Problems with previous Landing Page: not user-friendly enough; Missing necessary documentation and links.
>
> **Decision results:**
>
> 1.  Upload the following content to LP, or make changes according to the latest version of the LP document:
>
>    a. Links of various documents: 
>    https://anu365-my.sharepoint.com/:x:/g/personal/u7175274_anu_edu_au/EYJEUEIDhUZMg3UgF5BODNYB2sKWuAdJabM-PqsderXsEA?e=lOuWMS
>
>    b. Project background
>
>    c. Introduction
>
>    d.Add other content that already exists in the document:https://anu365-my.sharepoint.com/:w:/g/personal/u7175274_anu_edu_au/EUo5x05kb7RLpUtM1CgNJgwBi-NUEcoBW3qA1HtTpfh5JQ?e=1oHixN
>
> 2. Landing Page style:
>    Instead of creating a new page for each TAB, we decided to go with a long page format.
>
> **Decision Risks:** 
>
> 1. In the process of making a web page, it is possible that everyone has different ideas, resulting in the finished product can not meet the expectations of some members.-More communication
> 2. As more content needs to be recorded on the Landing Page, pages can become too long in the later stages.
>
> **Decision process and decision analysis:** [link to the document](https://docs.google.com/spreadsheets/d/15EHaV_sALzCfbfEcNLhsnOZY213hzSDZ/edit?usp=sharing&ouid=110206985761702410237&rtpof=true&sd=true)



##### Time: 2022.3.21 【003】 Create Google Drive by ANU email and migrate files from Onedrive to Google Drive. 

> **Decision members:** All members
>
> **Decision-making situations**： Vote: 3 agreed, 2 disagreed and 1 abstained.-pass
>
> **Decision topic:** Create Google Drive by ANU email and migrate files from Onedrive to Google Drive. 
>
> **Decision material:** 
>
> Where to store our works.
>
> **Decision results:**
>
> - [x] **1.** Create Google Drive by ANU email and migrate files from Onedrive to Google Drive. 
> - [x] **2.** Fill this decision in the Decision Log.
>
> **Decision Risks:**
>
> 1. We don't have a Google Drive membership, so we can only store up to 15 gigabytes of files. - We thought that the number of documents we wanted to store would not exceed 15GB after discussion and analysis.
> 2. Storing data in Google Drive is not as secure as Onedrive.
> 3. Links shared through Onedrive often fail, and the exact cause can't be found.
>
> **Decision process and decision analysis:** [link to the document](https://docs.google.com/spreadsheets/d/15EHaV_sALzCfbfEcNLhsnOZY213hzSDZ/edit?usp=sharing&ouid=110206985761702410237&rtpof=true&sd=true)



##### Time: 2022.3.17 【002】 Conduct Feedback meetings to discuss possible suggestions. Set next goals. 

> **Decision members:** All members
>
> **Decision-making situations**： All agreed
>
> **Decision topic:** Conduct Feedback meetings to discuss possible suggestions. Set next goals. 
>
> **Decision material:** 
>
> 1. The feedback of ‘Many Eyes’ evaluations(self, shadows, tutor).
> 2. Analysis and summary by each group member.
> 3. We need to clarify the decision-making process and other details.
> 4. Some people cannot open **OneDrive**;
> 5. We need to supplement some documents, such as competitive product analysis, requirements analysis, functional analysis, etc.
> 6. We need to improve the way we record some documents, such as meeting minutes.
>
> **Decision results:**
>
> To Do：
>
> - [x] **1.** Conducted competitive product analysis for the four apps. 
>   a. Yuhao Zhai, Xinyue Hu, Tianqi Tang, and Shuyi Chen are each responsible for an APP. 
>   The distribution is as follows:
>        Yuhao Zhai - FodMap
>        Xinyue Hu -  薄荷健康（Bohe Health）
>        Tianqi Tang - Fat Secret
>        Shuyi Chen - Lose it!
>
>   b. Bowen Zhang and Shiyun Zhu each review and supplement the analysis reports of two competing products.
>
> - [x] **2.** Optimize the Landing Page by adding necessary text and necessary links.
>
>   - [x] a. text - Yuhao Zhai
>
>   - [x] b. Links - Shiyun Zhu
>
>   - [x] c. Web - Shuyi Chen & Tianqi Tang
>
> - [ ] **3.** We'll have a technical meeting before the end of Week 5： programming language, development environment, naming conventions.
>
> - [x] **4.** Improve the decision record page, including the new decision risk analysis, and decision situation (who participated in the decision, etc.) - Shiyun Zhu 
>
> - [x] **5.** Create a shared EXCEL sheet and fill it out according to the division of labor in the previous decision.  - Shuyi Chen & Xinyue Hu
>
> - [x] **6.** Clean and maintain OneDrive regularly.-Shuyi Chen 
>
> The follow-up to be done:
>
> 1. Create a  demand analysis.
> 2. Complete UML.
> 3. App Function analysis.
>
> **Decision Risks:**
>
> 1. It is difficult for members outside Australia to download the competing app.
> 2. Forgot to check the validity of links.
>
> **Decision process and decision analysis:** [link to the document](https://docs.google.com/spreadsheets/d/1o6777CFawbaqHM_j-eVpxjIEYmoStJSK/edit?usp=sharing&ouid=110206985761702410237&rtpof=true&sd=true)



##### Time: 2022.3.15 【001】 Make use of the feedback of ‘Many Eyes’ evaluations.

> **Decision members:** All members
>
> **Decision-making situations**： All agreed
>
> **Decision topic:** Make use of the feedback of ‘Many Eyes’ evaluations.
>
> **Decision material:** 
>
> 1. Project schedule.
> 2. The feedback of ‘Many Eyes’ evaluations(self, shadows, tutor).
>
> **Decision results:**
>
> 1. In order to explore the value of suggestions and use them to improve the project plan, we decide to analyze the feedback. Each member handles a part of it, and one person to summarize(Details below).
>    1. Yuhao Zhai - Project Output
>    2. Xinyue Hu - Decision Making
>    3. Tianqi Tang - Team Work
>    4. Shuyi Chen - Communication
>    5. Bowen Zhang - Reflection
>    6. Shiyun Zhu - Summarize
> 2. According to the advice, build a *Project log file* to record decisions witch are approved and will be implemented, helping us manage projects better and improve ourselves.
>
> **Decision Risks:** No people is responsible for the coding work. Some people need too change working scope in the future.
>
> **Decision process and decision analysis:** [link to the document]()

##### Time: 2022.3.15 【000】 Decision log templates(It should be concise)
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

