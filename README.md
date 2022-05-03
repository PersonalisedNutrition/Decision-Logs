## Document Description

---

The document consists of two parts:

1.  The first is an overview of the project.
2.  The second part is the decision process in chronological order. And below each decision, there are some links to the document about the process that how to make it.

## Project Overview

---

### Project Introduction：

- Develop a personalized, user-friendly health APP using Android

### Project Landing Page: [Link to Landing Page](https://personalisednutrition.github.io/)

### Project design:

> source: [Statement Of Work v1.3](https://anu365-my.sharepoint.com/:w:/g/personal/u7175274_anu_edu_au/Efm1kUvjZ2BLjSEMPjtS4Y8BiMSoTsCM4RXhh1Vd0LV8-g?e=CPvAb9)

```mermaid
 gantt 
        dateFormat  YYYY-MM-DD
        title Gantt (unfinished)
        section design
        needs analysis                 :done,des1, 2022-03-06,2022-03-08
        beta version design            :active,des2, 2022-03-09, 3d
        UI design                      :des3, after des2, 5d
   	    tasks review                   :des4, after des3, 5d
        section develop
        preparing                      :crit, done, 2022-03-06,5d
        skeleton design                :crit, done, after des2, 3d
        android develop                :crit, active, 3d
        tasks arrange                  :crit, 3d
        final report                   :2d
 
        section test
        function                       :active, a1, after des3, 3d
        stress                         :after a1  , 20h
        test report                    : 48h
```

| Task | **Work**  MILESTONES                                         | Completion date |
| :--: | :----------------------------------------------------------- | :-------------: |
|  1   | Complete user system functions.                              |     Week 5      |
|  2   | Complete basic data input system.                            |     Week 7      |
|  3   | Complete algorithm development for report generation module and image recognition algorithm. |     Week 8      |
|  4   | Complete the build of the nutritionist side of the function. Export data available. |     Week 10     |
|  5   | Complete the building of the communication interface.        |     Week 11     |
|  6   | Complete the app testing.                                    |     Week 12     |

### Members:

| Name        | title           | Email               |
| ----------- | --------------- | ------------------- |
| Bowen Zhang | Scrum Master    | u7274475@anu.edu.au |
| Yuhao Zhai  | Spokesperson    | u7152566@anu.edu.au |
| Shuyi Chen  | Spokesperson    | u7175274@anu.edu.au |
| Tianqi Tang | Techinical Lead | u7192230@anu.edu.au |
| Shiyun Zhu  | ALGO Manager    | u7041419@anu.edu.au |
| Xinyue Hu   | UI Manager      | u7151386@anu.edu.au |

### Communication Plan:

| Stakeholder | **Method**   | **Frequency**                                     |
| :---------: | ------------ | ------------------------------------------------- |
|   Client    | Email & Zoom | Tuesdays every two weeks 13:30-14:30 &as required |
|    Tutor    | Email & Zoom | Weekly tutorial Thursday 13-15 PM & as required   |
| Shadow Team | Wechat       | Weekly Tutorial & as required                     |
|    Team     | Wechat       | Weekly on Sunday 19-21 pm & as required           |

## Decision Record

---

##### Time: 2022.5.02 Which database are suitable for the project?

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
![image](https://user-images.githubusercontent.com/100653606/166412239-4040682d-329b-4ef0-8a0e-f49f77a0731d.png)
> 
> **Decision Risks:**
>
> 1. Charges may be paid when exceed the free use limit.
> 2. The speed of uploading and downloading data can be affected by network condition.
> 
> **Decision process and decision analysis:**[link to the document](https://docs.google.com/spreadsheets/d/1RkY096tJSgi-kvxhQjRj9ckXJtfF_9kK/edit#gid=827619485)
> 
##### Time: 2022.4.12 How to avoid possible mistakes?

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
> 
##### Time: 2022.4.12 How many nutritionists are best for a client?

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
##### Time: 2022.3.21 What we still need to do for the Landing Page.

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



##### Time: 2022.3.21 Create Google Drive by ANU email and migrate files from Onedrive to Google Drive. 

> **Decision members:** All members
>
> **Decision-making situations**： Vote: 3 agreed, 2 disagreed and 1 abstained.-pass
>
> **Decision topic:** Create Google Drive by ANU email and migrate files from Onedrive to Google Drive. 
>
> **Decision material:** 
>
> ​	NA
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



##### Time: 2022.3.17 Conduct Feedback meetings to discuss possible suggestions. Set next goals. 

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



##### Time: 2022.3.15 Make use of the feedback of ‘Many Eyes’ evaluations.

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
> **Decision Risks:** NA
>
> **Decision process and decision analysis:** [link to the document]()



