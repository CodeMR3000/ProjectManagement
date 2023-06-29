# ProjectManagement
# (Micro Project Work Assigned by Login2Xplore)
## By Manish Raj
This work involves designing a project management form that will store data in the "PROJECT-TABLE" relation of the "COLLEGE-DB" database. The form will have several input fields to capture relevant information about a project.

## The UI of the project:
<img width="939" alt="image" src="https://github.com/CodeMR3000/ProjectManagement/assets/53638010/c01ebd35-dd81-48c7-8aa4-08027d354c19">
UI is fully responsive as shown below,
<img width="186" alt="image" src="https://github.com/CodeMR3000/ProjectManagement/assets/53638010/d6b2d25e-780e-4e44-84fc-3c1f4683c7bc">


## Functions of the project

There are three control buttons [Save], [Update], and [Reset] at the bottom of the form. When the page loads or any control button is clicked, an empty form is displayed, and the cursor remains at the first input field in the form, which has the primary key in the relation. At this time, all other fields and buttons are disabled.
as shown below:
<img width="819" alt="image" src="https://github.com/CodeMR3000/ProjectManagement/assets/53638010/238aaf63-cc63-4280-bb1d-392345a2b37e">


### If the primary key value does NOT exist in the database, the [Save] and [Reset] buttons are enabled, and the cursor is moved to the next field, allowing the user to enter data in the form.

<img width="539" alt="image" src="https://github.com/CodeMR3000/ProjectManagement/assets/53638010/7e7d2a1d-1ed6-4f9a-9bfd-2938cb7fb1bb">

as shown in the above image project-ID: 00002 is not present in the database

<img width="968" alt="image" src="https://github.com/CodeMR3000/ProjectManagement/assets/53638010/d64ffa84-9c71-49f3-a634-ba904216a9a8">

after saving the form, the data gets saved into the database


### If the primary key value is present in the database, the data associated with that key is displayed in the form. The [Update] and [Reset] buttons are enabled, and the cursor is moved to the next field in the form. The primary key field remains disabled, allowing users to change other form fields.

<img width="529" alt="image" src="https://github.com/CodeMR3000/ProjectManagement/assets/53638010/561e11d5-8be6-45c8-b43b-de5630c853ce">


Before Updating:



<img width="779" alt="image" src="https://github.com/CodeMR3000/ProjectManagement/assets/53638010/0a75c222-ed46-49bd-b8f3-66b44f0de807">



After Updating:



<img width="783" alt="image" src="https://github.com/CodeMR3000/ProjectManagement/assets/53638010/8b6d0eed-2255-4afe-a1b2-b14757479039">




as we can see  that the Project name and deadline got updated.














