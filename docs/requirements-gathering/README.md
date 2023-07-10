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
![](http://www.plantuml.com/plantuml/png/RP7FQiCm3CRlVWgHdlS0Wr9QrerT1cFTdyikQgAcfeuTR6Tj67ltJLOAWkpaJvz_iQ9FwvGnvg5pnj4XGmuGRNlCqDX8TRR1ctIoliU87M2TGzpbqH7WcLBeo9ZYmTPY98Bbyd7eqAzMi8XXHBTt0y64lDja-LICuqxC6CFDqBUEO8iZlpR2Wfe37cxXsm0CYMfC18amraV01DLEv1Ml54MDpOMv_nDCHAhrVKEECXLYAtBE9FmYwSDYVezzJxufn4RaWtKqxyAkwZIZ8g6yyi92-gJAAAAtlW3FVFxp9nt6Km6UMBpI9SDELgUV0Rhq8KwnY2ovAVPAdZ5wwzk2Vanwimz3_lHlddDfuEw8lgLKcHyphHvkLYLtNKi2sk6lTItxL0vFgqiUJjSoXNPa4SfHmMkNWpRJQ5pBbJ5hyitGkLy0)
![](http://www.plantuml.com/plantuml/png/RP71JiCm38RlVWfhE_C0IDCqn0uSk4rmDwsNMgG9IXoX2l7kp5NMPcYNnFxzoN_i7B9IqZ9wy7nMr8X9tA3OI-9E9GR8dnA-AD68r6bC9vqy8trpZYC3p1eUXH8pxdOlPQImt-CsnOdyXo-C5NcNB7OtZ3SdOm3CZ8BpZ4UQhDk4M-xFT7x47q0icJlAZ3rxLdxBd90oRevpMjqt3TSbfePxjlGkDyIO6yxIUvoFJiACl4Q74lxLOj6bU8bl7IWuFh6g19UhYqburLgQYWupytG9EAXqfBo1Nu3h-XxspN2BQl8w2zJlC7NT6AoX5Sog0UiOhNBxT83LeF8IO3wNTWSEVHdz7m00)
![](http://www.plantuml.com/plantuml/png/HOsxIi1044Nx-OfBKli1GWWfKjW7xCVD90xkGtPc3OluxneHBC_bSCzYpjLRYXJbS7X1rVFLiMkLu5eosPlcTwwSmC5BtRn70LzY9GdHxuPLkOfWcfvQuZpF66lf75zY4wBxYFCP1Ilts-mOPJ_uUCGd0Sqai0a-LAxDsGri69v_23UgkGORYBw8_Z8FyxzCY-IzfVWD)

## 6. Functional Requirements
|Functionality label|Create Diaree|
|-|-|
|Description|Visitor can create a new diaree, which can be given a name and other specific diaree information and password.|
|Main flow|<ol><li>Visitor chooses `Create Diaree` functionality</li><li>System gives a form to fill diaree information</li><li>Visitor fills the form with personal data</li><li>Visitor requests to create a new diaree (pressing `create` button)</li><li>System shows message about successfully made diaree and logs visitor in as a diaree</li></ol>|
|Alternative flow|*none*|
|Execptional flow|<ul><li>Diaree fills unvalid data (unvalid username / already in use) in form and system requires different diaree data.</li></ul>|
|Dependencies|Nobody should be logged in (user should be in visitor mode).|
|Aftermath|Diaree profile is made and system logs the user in as a new diaree.|
|Extra|*none*|
|Priority|**Must have** / Should have / Could have / Would have|
|Acceptance test|<ul><li>Create new diaree, log out, log in.</li><li>Create new diaree, exit application, choose newly created diaree and log in.</li></ul>|

|Functionality label|**Delete Diaree**|
|-|-|
|Description|Diaree can delete oneself. All data about the diaree is deleted. The action cannot be undone.|
|Main flow|<ol><li>Visitor logs into as a diaree</li><li>Diareel chooses `delete diaree` option in settings</li><li>System deletes all the `diaree's` data</li><li>System warns the diaree about a potential data loss and asks for a confirmation</li><li>Diaree confirms their action with password</li><li>System logs the diaree out</li></ol>|
|Alternative flow|*none*|
|Execptional flow|<ul><li>Diaree has wrong password. The deletetion of diaree is unauthenticated and does not get deleted.</li></ul>|
|Dependencies|Diaree has to exist and a diaree has to be logged in a profile to delete that profile.|
|Aftermath|All the diaree's data is removed from drive and diaree is logged out.|
|Extra|*none*|
|Priority|Must have / **Should have** / Could have / Would have|
|Acceptance test|<ul><li>Create new diaree. Log in and delete it. Deleted diaree should not be on list of diarees at login screen anymore.</li><li>Create new diaree. Log in and delete it with wrong password. Deleted diaree should be on list of diarees at login screen.</li><li>Create new diaree. Log in and delete it. Close and reopen the application. Deleted diaree should not be on list of diarees at login screen anymore.</li></ul>|

|Functionality label|**Log in**|
|-|-|
|Description|Visitor can access a chosen diaree's data.|
|Main flow|<ol><li>Visitor chooses an already existing diaree</li><li>Visitor authenticates himself with apporopriate password</li><li>System validates authetnication</li><li>Visitor becomes diaree</li></ol>|
|Alternative flow|<ol><li>Visitor uses a functionality `create Diaree`</li><li>System automatically logs visitor in as a newly created diaree.</li></ol>|
|Execptional flow|<ul><li>The passowrd is incorrect so the system returns a message and gives endless more opportunities.</li></ul>|
|Dependencies|*none*|
|Aftermath|User gets changes `user role` from visitor to diaree.|
|Extra|*none*|
|Priority|**Must have** / Should have / Could have / Would have|
|Acceptance test|<ul><li>Create new diaree and log in.</li><li>Create new diaree and log in with incorrect password. The system should not log one in and should return a corresponding message.</li></ul>|

|Functionality label|**Authenticate**|
|-|-|
|Description|Visitor or diaree can authenticate when another functionality requires authentication to be processed.|
|Main flow|<ol><li>Visitor or diaree inputs requested data for their authentication</li><li>System verifies authentiacation</li><li>Functionality is permitted</li></ol>|
|Alternative flow|*none*|
|Execptional flow|<ul><li>The entered password (diaree data) is incorrect and the request for functionality is rejected.</li></ul>|
|Dependencies|Diaree has to exist in order to authenticate|
|Aftermath|System allows diaree to use the dangerous functionalities|
|Extra|*none*|
|Priority|**Must have** / Should have / Could have / Would have|
|Acceptance test|<ul><li>Try to authenticate with correct password. The system should allow the functionality.</li><li>Try to authenticate with incorrect password . The system should not allow the functionality</li></ul>|

|Functionality label|**Log out**|
|-|-|
|Description|Diaree can log out of system. User role changes from diaree to visitor and user has no longer access to previously logged diaree.|
|Main flow|<ol><li>Diaree uses functionlity `log out`</li><li>System logs user out</li><li>New user role is visitor</li></ol>|
|Alternative flow|<ol><li>Diaree shuts the application down</li><li>System offers to save potentially unsaved work</li><li>System logs user out</li><li>Daydiary gets closed</li></ol>|
|Execptional flow|<ul><li>User ends the processes which runs the Daydiary forcefully and the app closes with no prompt.</li></ul>|
|Dependencies|Current user role has to be diaree.|
|Aftermath|New user role is visitor.|
|Extra|*none*|
|Priority|**Must have** / Should have / Could have / Would have|
|Acceptance test|<ul><li>Log into a system and log out. Log in again into same and different account.</li><li>Close the application and open it again and try to log in into the same account and once again into a different account.</ul>|

|Functionality label|**Change settings**|
|-|-|
|Description|Diaree can change their personal application settings under settings section. User input such as select button and colour picker are required. The functionality offers to set personal background colour, theme, fonts etc.|
|Main flow|<ol><li>Diaree navigates to settings section</li><li>Application offers a set of different options for each setting</li><li>Diaree chooses and sets all teh desired settings</li><li>Diaree saves changes</li><li>System stores the newly required settings</li><li>Application starts using the new settings</li></ol>|
|Alternative flow|*none*|
|Execptional flow|<ul><li>Invalid settings are handled as error and returned as an error message to user.</li></ul>|
|Dependencies|User should be logged into an account.|
|Aftermath|Graphical user interface of the application changes only for user and is changed until the same user changes it again.|
|Extra|*none*|
|Priority|Must have / **Should have** / Could have / Would have|
|Acceptance test|<ul><li>Log in and try to change every setting. Log out and see if the application is adjusted as required from previous session.</li><li>Fill the wrong input to form and test some other functionalities.</li></ul>|

|Functionality label|**Choose diaree**|
|-|-|
|Description|Visitor can choose which profile (diaree) to log in to.|
|Main flow|<ol><li>Visitor chooses to log in rather than to create a new account</li><li>System provides visitor with existing diarees</li><li>By clicking on one of the offeredd diarees, visitor chooses to use one of the profiles</li></ol>|
|Alternative flow|*none*|
|Execptional flow|*none*|
|Dependencies|At least one diaree has to exist on the system in order to choose one.|
|Aftermath|The system provides user with a form to authenticate oneself.|
|Extra|*none*|
|Priority|**Must have** / Should have / Could have / Would have|
|Acceptance test|<ul><li>Pick a profile when there are no profiles and when there is one and when there are more than one on system.</li></ul>|

|Functionality label|</li>**View statistics**|
|-|-|
|Description|Diaree can look up his activity via this functionality. They can view all the login activity. This functionality also provides linguistically analyzed data of diaree's dayrecs.|
|Main flow|<ol><li>Diaree opens personal statistics section</li><li>System provides diaree with a compact and visual representation of diaree's analyzed personal data</ol>|
|Alternative flow|*none*|
|Execptional flow|*none*|
|Dependencies|Diaree has to be loged in.|
|Aftermath|*none*|
|Extra|*none*|
|Priority|Must have / Should have / **Could have** / Would have|
|Acceptance test|<ul><li>Change input and check if the anaylzed data has updated.</li><li>View statistics when diaree has no input for every parameter of analyzed data.</li></ul>|

|Functionality label|Edit a Dayrec|
|-|-|
|Description|Diaree can edit the content of any dayrec.|
|Main flow|<ol><li>Diaree clicks functionality on calendar or other views to enter editor</li><li>Diaree is redirected to editor mode</li><li>On save, application deletes teh previous version of dayrec and creates a new dayrec with a corresponding date</li></ol>|
|Alternative flow|*none*|
|Execptional flow|*none*|
|Dependencies||
|Aftermath|Diaree has to be logged in.|
|Extra|*none*|
|Priority|**Must have** / Should have / Could have / Would have|
|Acceptance test|<ul><li>Start new dayrec. Save. Exit application and check for the new input.</li><li>Open existing dayrec and change it. Log out and log in againg and scheck for new input</li></ul>|

|Functionality label||
|-|-|
|Description||
|Main flow|<ol><li></li></ol>|
|Alternative flow|<ol><li></li></ol>|
|Execptional flow|<ul><li></li></ul>|
|Dependencies||
|Aftermath||
|Extra||
|Priority|Must have / Should have / Could have / Would have|
|Acceptance test|<ul><li></li></ul>|

|Functionality label||
|-|-|
|Description||
|Main flow|<ol><li></li></ol>|
|Alternative flow|<ol><li></li></ol>|
|Execptional flow|<ul><li></li></ul>|
|Dependencies||
|Aftermath||
|Extra||
|Priority|Must have / Should have / Could have / Would have|
|Acceptance test|<ul><li></li></ul>|

|Functionality label||
|-|-|
|Description||
|Main flow|<ol><li></li></ol>|
|Alternative flow|<ol><li></li></ol>|
|Execptional flow|<ul><li></li></ul>|
|Dependencies||
|Aftermath||
|Extra||
|Priority|Must have / Should have / Could have / Would have|
|Acceptance test|<ul><li></li></ul>|


## 7. Non-functional Requirements

## 8. Screen Wireframes

## 9. Interfaces to External Systems