# JPDB_Project
Project Management Form that will store data in PROJECT-TABLE relation of COLLEGE-DB database  Input Fields: {Project-ID, Project-Name, Assigned-To, Assignment-Date, Deadline}  Primary key: Project ID
## (Micro Project Work Assigned by Login2Xplore) 
## By Manish Raj
<br>

## UI of the project
<br>
<img width="853" alt="image" src="https://github.com/mani504/JPDB_Project/assets/84199658/f2739d6b-1fb4-41e5-926a-5514b4ca14c3">

## The Design is fully responsive
<br>
<img width="305" alt="image" src="https://github.com/mani504/JPDB_Project/assets/84199658/889cfb69-6c4a-4cfc-aac9-245b140c4970">


## Functions of the project
There are three control buttons [Save], [Update], and [Reset] at the bottom of the form. When the page loads or any control button is clicked, an empty form is displayed, and the cursor remains at the first input field in the form, which has the primary key in the relation. At this time, all other fields and buttons are disabled. as shown below:
<br>
<img width="482" alt="image" src="https://github.com/mani504/JPDB_Project/assets/84199658/82aba742-5924-4f54-81d9-a0fd0e11dce6">

## Create
<br>
If the primary key value does NOT exist in the database, the [Save] and [Reset] buttons are enabled, and the cursor is moved to the next field, allowing the user to enter data in the form.
<br>
<img width="481" alt="image" src="https://github.com/mani504/JPDB_Project/assets/84199658/5d1c9685-eb10-4459-a5bc-124e19554d73">
<br>
as shown in the above image project-ID: 00004 is not present in the database
<br>
<br>

<img width="950" alt="image" src="https://github.com/mani504/JPDB_Project/assets/84199658/3506a1a4-c7b4-41b8-834d-0eff7746c540">
<br>
after saving the form, the data gets saved into the database


## UPDATE
<br>
If the primary key value is present in the database, the data associated with that key is displayed in the form. The [Update] and [Reset] buttons are enabled, and the cursor is moved to the next field in the form. The primary key field remains disabled, allowing users to change other form fields.
<br>
Let us change the project name and deadline of the following entry
<br>
<img width="533" alt="image" src="https://github.com/mani504/JPDB_Project/assets/84199658/6ba0383f-8dd3-4b0c-8d64-38a5d3404336">
<br>
After changes
<br>
<img width="494" alt="image" src="https://github.com/mani504/JPDB_Project/assets/84199658/72e41e64-48a7-45de-b8d2-98a15d974267">
<br>

## The above changes are reflected in the database
<br>
<img width="740" alt="image" src="https://github.com/mani504/JPDB_Project/assets/84199658/80c93861-737e-43b0-92e3-3d24e6e402fc">
<br>
<img width="764" alt="image" src="https://github.com/mani504/JPDB_Project/assets/84199658/76280fcd-b39b-419b-91e9-9e3ab8b4f443">











