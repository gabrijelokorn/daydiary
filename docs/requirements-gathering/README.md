# REQUIREMENT GATHERING
## 1. Summary
This document serves as an overview of what the requirements are for the final project *DayDiary*. 
In second section a clue is given about what we want of the end product to be. Here functional and non-functional requirements are seperatly presented. They are well described and explained later on in sixth and seventh section of this document respectively. User roles that are involved in the program are defined and desciribed in the third section. Terms concerning this document and DayDiary application are defined and described next in fourth seciton. Functional and non-functonal requirements are graphically represented on *use case diagram*. Penultimate section gives us a sense about how the application will look like. These are images *screen wireframes* which represent the user graphicall interface of application. *Interfaces to External Systems* which define and describe relations between DayDiary and external systems will be presented last in this docmuent.

## 2. Introduction
DayDiary will offer a solution for a well trusted **confidential** digital diary. It will serve as a comftrable environment with a calendar view of diaries.

Representation of functional requirements:
Simple searching with a keyword on all text will be included. Editing already entered text will be enabled as well as deleting the diary input. User will be expected to save input manually. In case the user forgets to save the unsaved changes, the program should inform user about the potential data loss. 
Individual diary inputs will have an option of appending an image to it. `Pinning` specific diary will offer a quick access to it in case user wants to see that specific diary entry later on. DayDiary will offer a functionality to mark the text and add a graphical effect to it, in case text was shown to someone. Marking the text can be style (color) specific based on who it was shown to. 
Exporting text as pdf document in span of custom date will be supported in order to print a diary.
Every user authentication will be logged and visible to authorized owner. User input will be mathematically analyzed and visible to user in graphical form with charts. Text will be processed and analyzed and will offer user a linguistic analysis in a way to improve their expression and vocabulary.

Representation of non-functional requirements:
Program will support only one diary entry for each calendar day.
As the program is stored locally it will be available offline and whenever the computer will be acessible. In case there will be more than one user of DayDiary on same computer, program will offer multiuser option.
DayDiary will be reiliable: diary entries will be saved in a retrievable way without loss or corruption of data. Application will be installable on all operating systems (Linux, Windows, MacOS). Only english language will be supported for use of this program.
Optionally individual user will be able to customize stylish settings such as application background, fonts, etc.
The final package of the program should be easy to install and use. Users should be supported with well documented functionalities.

## 3. User Roles
Since DayDiary will be made for offline private purposes, it's user roles and relations between them will be quiet simple.
- **Diaree** - an authorized user of diary: can log in and out of program, use all functionalities of DayDiary and is authorized to edit, delete and change user data
- **Visitor** - unauthorized user that can only view list of already existing user profiles and choose one of them to become *diaree*.

*Visitor* has a potential to become *Diaree*.
## 4. Glossary of Terms
In filed of writing a diary there are not many technical terms. However, there will be some additional due to DayDiary program and project specifics.

**Diary** - a personal record or journal where individuals can document their thoughts, experiences, and events\
**Dayrec** - a unique and individual record within a diary or journal that captures the events, thoughts, or experiences usually of a specific day\
**Diaree** - user of *DayDiary* and author of *Dayrec*s\
**Dayrec metadata** - information associated with each entry, such as date, location and heading\
**Heading** - a word or phrase best describing the *dayrec*\
**Export** - saving diary in a specific format (e.g., PDF, plain text etc.) for external use or archivning\
**Screen Wireframe** - a visual representation of a UI design, often in the form of a static image of a website page or app screen

## 5. Use Case Diagram
![](http://www.plantuml.com/plantuml/png/PPBFQiCm3CRlVWgHdlS0Wr9QserTDiQoFvTUr4HDJHqdsCxQCFRkcwmK13dbqwSVKYHv7HE6DBJEE3ecI1q4svmIr3PGbMpdJJnRtsF05h1ANIZJw0ZmGh5hoPZimSvY88BbycbeqQzMi0ZTYExW1e89-RJHybSnZZinOmmtGzyuWXsEN6s41TL7FDx3Zm4O8bKO2I9Xg4w04OfIv0ql55K5maJ_cK1LPhVPW1UwxBtO6gVQfemzi9ZdQtAKA1CxaNCcuhSG9Ojv7lkUV9s9ZSX7wsZUXLtLQKO5GgdonaBwnC8eehS-0w_ydVy9j1ZE6NXcyKxN1ALSMfS1klPTcDOYCgzPiJVoWi5RtsJqQzARGpUalV_ml9SQjYVq3SN2_9hffS3T2lIPjC_tqB5iHZjSLSVoB9J3Mz0X3wrZcKuxSY3bg8DebmzWff4vbfGnQ_BrqBe_)
![](http://www.plantuml.com/plantuml/png/NP2zJiGm381tFuNLcta0f5DrY1iOs4wmczPDBL879OvGXNXtcj8hEPOs_lmb_ZabesXvyk1vCBI0KTnes4lapYGef7VH3ueq8NKMuiLcpqYVdCB402l3ir1ankFnAK-aROk766RoRpupRigh92d_ol6bKd40IZ5IvndFD9VNPZnmFz1mZr-0c1Dtb1Yxo6JyaZWY9MmUzx2ffJ64L4bxM4i-ED4r_nmSYlxBXMnxSZdVFa_g-C9ceYvj9Gh2AwjjoZQkpiDoO3NfoBY1Ru3hGkxQQgoTBhWQ1BO55_hRNKrkEmBukxVveh1-IrWQWXDhdoV_0m00)
![](http://www.plantuml.com/plantuml/png/RO-zJWD138HxFuMLr3m0KdGAqXNq0IgQuTONLkmFMdi92-BTOHC1YNJbZByPsrir5AinK93Ps38NltysThx8P3udqXUVNb4G6PFbihCMX74GpL68ZXwF7aM4DvlR6f66WTSbDuIdK8Me5o7jW_28rid6Qt4pvcl-9EQgCa65txmSTWPJXlBguKTnbrxDJxew0v4GseVSoRiTqPkJxkskjp-c4OQ5nBrAkKXquvUcBwB_4ww6ypMBWnucEdtUxJ-6Q2l9rHY-0G00)

## 6. Functional Requirements
|Functionality label|Create Diaree|
|-|-|
|Description|Visitor can create a new `Diaree`, which can be given a name and other specific Diaree information and password|
|Main flow|1.) Visitor chooses `Create Diaree` functionality<br/>2.) System gives a form to fill Diaree information<br/>3.) Visitor fills the form with personal data.<br/>4.) Visitor clicks on `create` button.<br/>5.) System shows message about successfully made Diaree and logs `Visitor` in as a `Diaree`|
|Alternative flow||
|Execptional flow||
|Dependencies|Nobody should be logged in (user should be in `Visitor` mode)|
|Aftermath|`Diaree` profile is made and system logs the user in as a new `Diaree`|
|Extra||
|Priority|**Must have** / Should have / Could have / Would have|
|Acceptance test|<ul><li>Create new `Diaree`, log out, log in.</li><li>Create new `Diaree`, exit application, choose newly created Diaree and log in.</li></ul>|

|Functionality label||
|-|-|
|Description||
|Main flow||
|Alternative flow||
|Execptional flow||
|Dependencies||
|Aftermath||
|Extra||
|Priority|Must have / Should have / Could have / Would have|
|Acceptance test||

|Functionality label||
|-|-|
|Description||
|Main flow||
|Alternative flow||
|Execptional flow||
|Dependencies||
|Aftermath||
|Extra||
|Priority|Must have / Should have / Could have / Would have|
|Acceptance test||

## 7. Non-functional Requirements

## 8. Screen Wireframes

## 9. Interfaces to External Systems