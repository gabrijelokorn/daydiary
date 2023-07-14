# Project Proposition

## 1. Project Summary
Daydiary is a program for storing user's diary - what has happened over the course of the day or other period of time.\
Program comes with a graphical interface - calendar view of the stored diaries. Every diary, which is bound to specific unique date has an option of inserting an image, leaving a note and pinning the content. Latter is used for faster access of specific content when searching and is in other applications often denoted as _favorites_.\
The data the program stores is only on user's personal computer and is not accessible to anyone else. Password protection is optional, but recommended.\
Optionaly, the author of the diary will have an opportunity to export the diary as _pdf document_.\
Advanced user intput analysis such as number of words, diversity of words and others will be availible to end users and will be shown on charts.
## 2. Project Idea
- ### Background
    Writing a diary is not a common activty and there are not many programs supporting it. People writing a diary digitaly often encounter a problem of programs not offering confidentiality. It is however among the most important concepts of writing a diary and should not be ignored.
    
    A few applications offering similar service are availible for free. Among them are best known [Day One](https://dayoneapp.com/) (Unix), [RedNotebook](https://rednotebook.app/) (Linux) and [Diarium](https://diariumapp.com/) (Windows).

    The other solutions do not offer everything one might desire, such as expotring to pdf, pining the diary input etc. DayDiary will offer specifics that other apps might have missed. Daydiary will support marking the part of diary that was shown to somebody to keep the track of it.
- ### Area and Motivation
    We got asipiration when we searched the World Web for an appropiate *diary* program for Linux OS. We did not find any great solution that could satisfiy our safty needs.

    Before writing to ordinary text files, diaries were written on paper. Doing it in a digital form speeds up the process of writing and comes with other features such as erasing, embellishing text, etc.

    Unlike most common applications, Daydiary will be platform (OS) independent and will provide safe diary encryption. Daydiary has a unique feature of professional data analysis and it's graphical presentation. DayDiary will offer a unique functionality for labeling a diary and adding a graphical effect to it if someone was shown the diary.

    End audience of this project is everyone intenting to write a confidential digital diary. Confidentiality and simplicity of this program will convince our audince to use our solution to get their job done.
- ### Purpose
    Solution serves as an accessory for an individual personal growth. Program does not have any use in scientific and reaserch space or business. This project's main goal is to make **confidential** digital diary for users of Linux operating system. Since there are no free solutions to assure confidential and user friendly use of digital diary, DayDiary will make this contribution to free market. End users will be able to analyze their diary input and improve their expression of thoughs.
- ### Objective
    Solution will be presented as a standalone application. The program will **not** use any communication with internet. User's diary will only be accessible to an individual with their own computer and password. 
- ### Solution Guidelines
    The most prioritized guideline on DayDiary will be high level of data security, straight-forward usage and simple installation of program.
- ### End Users
    Everyone willing to write a digital diary will be a potential customer. Since there is no clinet-server involved, the number of customers does not affect our service. Expected number of customers is one, but the project will be built as there were millions of which most do not have knowledge of software engineering. Only end users will benefit from this program, since there are no inderctly connected people to this project.

## 3. Project Plan
- ### Summary of project activity breakdown,
The first 6 acitivites to A6 (Interfaces to external systems) are part of requirements gathering. The following regarding project plan are  from A7 (Interfaces to external systems) to A10 (Program basic workflow). The rest describe activities to implement and publicate the program.
- ### Plan of individual activities
  |Activity Label|A1|
  |-|-|
  |Estimated Start Date of Activity|06.07.2023|
  |Estimated Completion Date of Activity|06.07.2023|
  |Duration|1|
  |Name of activity|**Determining user roles**|
  |List of Activity Objectives|Specify user roles. To divide users in groups based ond the functionalities they use|
  |Description of Activity|Analyze user needs and different types of functionalities they use.|
  |Possible Dependencies and Constraints|None|
  |Expected Results of Activity|All the different user roles will be defined.|

  |Activity Label|A2|
  |-|-|
  |Estimated Start Date of Activity|06.07.2023|
  |Estimated Completion Date of Activity|06.07.2023|
  |Duration|1|
  |Name of activity|**Dictionary of terms**|
  |List of Activity Objectives|Define terminology of the project|
  |Description of Activity|Find different words and in fields of computer security, project planning, digital diary and text encryption.|
  |Possible Dependencies and Constraints|None|
  |Expected Results of Activity|List of words and it's meanings concerning this project.|

  |Activity Label|A3|
  |-|-|
  |Estimated Start Date of Activity|07.07.2023|
  |Estimated Completion Date of Activity|08.07.2023|
  |Duration|2|
  |Name of activity|**Make use case diagram**|
  |List of Activity Objectives|Specify which type of user uses which functionality.|
  |Description of Activity|Searching for different ways of how diffenet users can use the application.|
  |Possible Dependencies and Constraints|Uses A1 (Determining user roles)'s user roles|
  |Expected Results of Activity|Use case diagram|

  |Activity Label|A4|
  |-|-|
  |Estimated Start Date of Activity|10.07.2023|
  |Estimated Completion Date of Activity|12.07.2023|
  |Duration|3|
  |Name of activity|**Functional requirements**|
  |List of Activity Objectives|Find what functionalities the program should support|
  |Description of Activity|Go through all the usecases and get all the functions that the program should offer the user.|
  |Possible Dependencies and Constraints|A3 (Make use case diagram) has to be finished|
  |Expected Results of Activity|List of all the functional operations the program will offer.|

  |Activity Label|A5|
  |-|-|
  |Estimated Start Date of Activity|10.07.2023|
  |Estimated Completion Date of Activity|12.07.2023|
  |Duration|3|
  |Name of activity|**Non-functional requirements**|
  |List of Activity Objectives|Expose the environmental requirements that should support the program and vice versa|
  |Description of Activity|Think about use-cases and what do functional requirements need to operate. Search for platform specific constraints.|
  |Possible Dependencies and Constraints|Depends on A4 (Functional requirements)|
  |Expected Results of Activity|List of non-functional requirements|

  |Activity Label|A6|
  |-|-|
  |Estimated Start Date of Activity|06.07.2023|
  |Estimated Completion Date of Activity|12.07.2023|
  |Duration|6|
  |Name of activity|**Create screen wireframes**|
  |List of Activity Objectives|Define the use case user interfaces|
  |Description of Activity|Draw or design prototyps of (preferably all) different user interface screen masks.|
  |Possible Dependencies and Constraints|None|
  |Expected Results of Activity|Pictures of all user interface variants|

  |Activity Label|A7|
  |-|-|
  |Estimated Start Date of Activity|06.07.2023|
  |Estimated Completion Date of Activity|12.07.2023|
  |Duration|6|
  |Name of activity|**Interfaces to external systems**|
  |List of Activity Objectives|Define how the end-users will update the application to a newer version.|
  |Description of Activity|Think about updating the program version.|
  |Possible Dependencies and Constraints|None|
  |Expected Results of Activity|Defined process of using interfaces to external systems when updating application|
  
  |Activity Label|A8|
  |-|-|
  |Estimated Start Date of Activity|13.07.2023|
  |Estimated Completion Date of Activity|27.07.2023|
  |Duration|14|
  |Name of activity|**Architectural design**|
  |List of Activity Objectives|Develop a view of architecture to show how the components of system and outside of system interact|
  |Description of Activity|Design an UML diagram of project architecture for logical, physical, process and development perspective. Use *Design Patterns*|
  |Possible Dependencies and Constraints|Every Activity up to A7 has to be done|
  |Expected Results of Activity|Architectural design|

  |Activity Label|A9|
  |-|-|
  |Estimated Start Date of Activity|13.07.2023|
  |Estimated Completion Date of Activity|27.07.2023|
  |Duration|14|
  |Name of activity|**Structural design**|
  |List of Activity Objectives|<ul><li>Define and name all structrues in program</li><li>Relation and mulitplication between classes</li></ul>|
  |Description of Activity|Design UML class diagram of project, their basic functions and relations between them. Use *Design Patterns*|
  |Possible Dependencies and Constraints|Every Activity up to A7 (Interfaces to external systems) has to be done|
  |Expected Results of Activity|Class diagram of program|

  |Activity Label|A10|
  |-|-|
  |Estimated Start Date of Activity|13.07.2023|
  |Estimated Completion Date of Activity|27.07.2023|
  |Duration|14|
  |Name of activity|**Behaviour design**|
  |List of Activity Objectives|Design sequence diagram, state diagam or activity diagram based on basic and alternative flows|
  |Description of Activity|Decide which of the diagrams (sequence diagram, state diagam and activity diagram) should be included and implement them with UML. Use *Design Patterns*|
  |Possible Dependencies and Constraints|Every Activity up to A7 has to be done|
  |Expected Results of Activity|sequence diagram, state diagam or activity diagram|

  |Activity Label|A11|
  |-|-|
  |Estimated Start Date of Activity|28.07.2023|
  |Estimated Completion Date of Activity|09.09.2023|
  |Duration|28|
  |Name of activity|**Program basic workflow**|
  |List of Activity Objectives|Working basic input and output of the program without security and user interface|
  |Description of Activity|Program basic functionalities of the program. |
  |Possible Dependencies and Constraints|All the projcet architectures should be well defined|
  |Expected Results of Activity|Program skeleton|

  |Activity Label|A12|
  |-|-|
  |Estimated Start Date of Activity|13.09.2023|
  |Estimated Completion Date of Activity|26.09.2023|
  |Duration|14|
  |Name of activity|**Implement data Protection**|
  |List of Activity Objectives|To secure data of the user input|
  |Description of Activity|Program or use existing algorithnm for data encryption|
  |Possible Dependencies and Constraints|Basic workflow of the program|
  |Expected Results of Activity|A piece of program assuring data confidentiality|

  |Activity Label|A13|
  |-|-|
  |Estimated Start Date of Activity|27.09.2023|
  |Estimated Completion Date of Activity|07.10.2023|
  |Duration|10|
  |Name of activity|**Implement logging and analsys**|
  |List of Activity Objectives|<ul><li>Storing user data</li><li>Analyzing user data</li></ul>|
  |Description of Activity|Build algorithms to analyze different scopes of user input|
  |Possible Dependencies and Constraints|Basic workflow of the program|
  |Expected Results of Activity|A piece of program for analyzing user input data|

  |Activity Label|A14|
  |-|-|
  |Estimated Start Date of Activity|09.10.2023|
  |Estimated Completion Date of Activity|01.11.2023|
  |Duration|21|
  |Name of activity|**Create user interface**|
  |List of Activity Objectives|<ul><li>working user interface, platform independent</li><li>plotting graphs of user input</li></ul>|
  |Description of Activity|Decide for best library and implement the program to a standalone application|
  |Possible Dependencies and Constraints|Working program|
  |Expected Results of Activity|A user interface program using program|

  |Activity Label|A15|
  |-|-|
  |Estimated Start Date of Activity|02.11.2023|
  |Estimated Completion Date of Activity|09.11.2023|
  |Duration|7|
  |Name of activity|**Testing**|
  |List of Activity Objectives|Test the application|
  |Description of Activity|Final test of the program|
  |Possible Dependencies and Constraints|Has to be done after A14 (Create user interface)|
  |Expected Results of Activity|Eliminated potential errors|

  |Activity Label|A16|
  |-|-|
  |Estimated Start Date of Activity|10.11.2023|
  |Estimated Completion Date of Activity|25.11.2023|
  |Duration|14|
  |Name of activity|**Software release**|
  |List of Activity Objectives|<ul><li>Make program accessible to end users</li></ul>|
  |Description of Activity|Create a program to install an app for different platforms.|
  |Possible Dependencies and Constraints|The program has to be finished and tested|
  |Expected Results of Activity|Installable version of the application|

  |Activity Label|A17|
  |-|-|
  |Estimated Start Date of Activity|26.11.2023|
  |Estimated Completion Date of Activity|29.11.2023|
  |Duration|3|
  |Name of activity|**Instruction**|
  |List of Activity Objectives|<ul><li>Help end users using the application</li></ul>|
  |Description of Activity|Write user manual and instructions|
  |Possible Dependencies and Constraints|Sofware realease has to be ready|
  |Expected Results of Activity|User Manual|

- ### List of deliverables
|Product Label|P1|
|-|-|
|Name of product|**Requirement capture document**|
|Activity to produce the product|A10 (Behaviour design)| 

|Product Label|P2|
|-|-|
|Name of product|**Project plan document**|
|Activity to produce the product|A7 (Interfaces to external systems)|

|Product Label|P3|
|-|-|
|Name of product|**DayDiary application**|
|Activity to produce the product|A16 (Software release)|

|Product Label|P4|
|-|-|
|Name of product|**User Manual**|
|Activity to produce the product|A17 (Instruction)|


- ### Gantt chart
![Link name](https://cdn-0.plantuml.com/plantuml/png/nPPDRzf048Rl_XLpwyaIaAeXjuI6LkGZGO1wACfXQe_jRTQxT6TSoh-lxSJfeetJebRfZMMMztddOqUSig2J78r8n9L9SSU0ZY3HbYcDviv-fKIWlSKm6eoEui5nF7WNFNmSnwCnY7qCdDInzjS6IqfXlLfCLnTJc7sUprOtjt0xER-TN4pl04tgGNuThRQkFYi3ZBgq9kfumvCEqfn6Gn-odDvSdKtWyknwVe1o5CUme6-LSbII4OQFA0KvPNAO5yW4SHojprKYoXfqEx0P2BcIxy9Ij1GoQV2TOXzyMU2zgZMfqL6c8LLC3fpLzFUortXFZHuaZVbKOUwmV595WJxm6suWpy36_R0FbNaeZ0RdrT37zHZgemr7_RGRQ-BiLOdl7Q4GSEA836nhMbPBaO_pcdAOzim8kGmJucQawKTzQhBY7GkL_uGmhGCsswiJvDrqtq61cmsPbl2ocMusshVIBOAvHkEza3EN54hgGELGGqgiSkFdyB8PlpaQkGuD1z2ke32vAvKNiXGYFT4LHUkbkEe_O2TKu7TbA_UQr4vuyzY4ZKQpryZ0rdEjcvKRtPf2KTPlOdsXUIhm1LabiBNkFjDs6sQsRo3CPpJkosUEcZufgqaMb4Rh9oUGec1ZKAXztZwpprPOnhS7OxNDysOFOYk4cdVie_iD7jB4VNgtLDhLgxft5r9x_ONb7luHEPWUvS_1_XprcFI6QKKii7aQdUPO6_NJU1aNfd5yM1OTqRVTsV2DBaWJCdbUbpQJBJe2zn0AJ7lg1mpPml9kukpMDBkTnLNjeB2l7g83_QFVoqUdPDBsdzfF)

<!-- - ### PERT Graph -->
<!-- ![](http://www.plantuml.com/plantuml/png/ZPHFZzCm4CNl_XIZ7f4gKMZvSq7BV-q1jDfoGnnCCadDEdOPJoWLuhip7gVT95I8G-Lg_9lnqvkdN2Msn7tdpSxL2DZj-GWrfehSdbqCvlE3Bx1Sle1R_DuxmWu3f_UMTqWkjCPZmy0HoBKxXbg0IhkCZ6Myt0I_36prMg4Ls0IBDquRBHqXDi18NLgO2VUeS9ZlNCXp-eG453qAEYOVA_d1tc56eB89HPfjoNPJSAtWkpwKjptGIEyKtIZwCOPbyp_u4yLV4sgb8iG01q4RqJ2N-rJPwy18ZQqmPJ_n9oFb9z8nCNQpZcVQyJRKujL41BGdaxDvWssol6AB6SvpPVrNPMD-6tDvQuBSKFo65Tzu6upYuugiTIJnkKfyITNEiG0zMPzZvTgm66EhXyfjcVf_G2k5Nk7E_d2nfpCZMaS2HWglkxrN_PPTd6gTtirKhqh8XCnXWQyskGeEaUuQ7mzJJILavs5GMxRv2KPDnnHUps0VspPxQaCjF-jbozE6pJW_cdDtoeTijZ33PbMC6SxxqjeCvtr9btlP1M4-OUBIetzdnfH0vmlHhSuh97tRsF314jwYHvkmZ9XNPzDAv4yC392EdJVA2_89CbSOwhxpVm00) -->

## 4. Risk managment plan
The project of creating an application can be faced with some of the Risks, which are described in the table under.
| Risk Label | What is impacted *(technology, people, organization, tools, requirements, assessment)* | Description of Risk | Type of Risk *(product, project, business)* | Probability of Risk occurrence *(very high, high, moderate, low, very low)* | Consequences of Risk *(fatal, serious, acceptable, negligible)*|
|-|-|-|-|-|-|
|Skill gaps|Project|Developer does not have a skill to implement a functionality|Project|High|Acceptable|
|Loss of key personnel|Project|Risk of the developer putting the project on hold or leaving the project.|Product|Very low|Fatal
|Compatibility issues|Product|The final program would not work on other operating system or might not work on different computers with same operating system|Product|Moderate|Serious|
|Incomplete or changing requirements|Project|A change of end program request|Product and Project|High|Acceptable|

In risk planning, we ask "what if" questions that consider individual risks, combinations of risks, and external factors that can influence the risks. The risk management plan is depicted using the following table:
|Risk Label|Strategy|
|-|-|
|Loss of key personnel|Put the project on hold and wait until the developer comes back or gets substituted.|
|Compatibility issues|Develpoer searches for help at senior developer. Study the platform documentation.|
|Incomplete or changing requirements|Accept the change. Fix the project plan (Gannt and PERT graphs, architecture of program) and implement the alternation.|
|Skill gaps|Educate a developer by attending a course. If the problem is of acceptable nature than "Googling" the solution might resovle the problem. An expensive but fast way to get over skill gaps is to pay an external developer or instructor for help.|

## 5. Project Managment
Since there is only one individual working on the whole project, he will manage the project and do all the work. The individual has connections and acquaintances who are skillful on this field and might help him with program implementation and data encryption. The individual will stick to the project plan. So communication might be only from outside the group and not inside.
## 6. Presentation of the Project Group
The group working on this project consists of only one software developer. A student of Faculty of Computer Science in Ljubljana. He is a diligent student who aims to perfect his programming skills and wills to get good experiments in fields of project managment and security protocols. He is known for his examplary work ethics. He has done several similar projects where he got the courage to take all the responsiblity of this project alone.