# oCEO-flask-webapp
A flask webapp for performing INSERT, UPDATE, DELETE, RENAME, WHERE operations in oCEO database
Assignment-4: here
Firstly download latest python version, its packages and flask framework shown below :-
Create a python virtual environment [Recommended]
Go to powershell(being in project directory) and follow the below steps :-
Command: pip install virtualenv (enter)

then type virtualenv env (enter)
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/f7119b56-01f7-49f8-bcc9-6b5b56704510)


Fig: a folder named "env" will be created[as shown]
Screenshot 2023-04-01 172523
Now, we have to activate this python virtual environment using command: .\env\Scripts\activate.ps1 (press enter)

Fig: It will show something like this Screenshot 2023-04-01 172048
install python packages(flask, pyyaml, flask-mysqldb) using command: pip install flask pyyaml flask-mysqldb (enter)

Finally type command to run the flask-webapp: python .\app.py (press enter)

Fig: Server got started[running on PORT shown] image
If you are getting an error, like this!!!
sometime while activating python virtual env. we get an error as shown image

to remove this, open windows powershell as admin and do as shown in Screenshot image

Other way(if above steps not working) :-
install Flask(python web framework) using the commands as shown :
py -m pip install flask
Now, check their versions using command as shown :-
py -m flask --version
SS for the output :-
image
Then install following pip packages :-
pip3 install flask-mysqldb
pip3 install pyyaml
Open the oCEO-flask-webApp
command: python app.py (press enter)
then in terminal we get the ouput as shown in screenshot below
image
On clicking the default PORT(shown with arrow mark)[on clicking the link] : we will our app running and displays the homepage
Home Page view:-
image

On clicking the IITGN-logo, we get 3 options as follows:-
Login As Student
Login As Professor
Login As Admin
On clicking "Login As Student" we get the UI as shown :- image
Login details of student(for registered student) i.e emailID and Password image
On clicking "Login As Professor" we get the UI as shown :- image
On clicking "Login As Admin" we get the UI as shown :- Screenshot (726)
In MySQL, created database named "oceo" and tables as shown :-
image

These are the following commnads used for creating tables :-
Creating Student table image

Creating Professor table image

Creating total_jobs table image

Creating application table image

Creating ongoing_jobs table image

Creating concluded_jobs table image

Creating bank_details table image

Working of all Operations shown below(with SS attached) :-
RENAME Operation :-
image

Same rename operation working on MySQL Workbench :- image
RENAME queries
SELECT with WHERE operation :-
Professor login page image
Operation performed in MySQL workbench image
Updated date get reflected in table shown image
UPDATE operation :-
image

before update image
before update in schema image
updated data in schema image
Alert dialog box to confirm the update operation image Dynamic execution in the frontEnd
DELETE operation :-
image

Before delete operation image
Before delete in schema(i.e MySQL workbench) image
Alert Box for confirming deletion operation image
After delete operation from Schema(from MySQL workbench) image
deletion operation on table showing Dynamic Execution
INSERT operation (for student Registration):-
image

These data of student will be stored in student table in oceo database image
Student will be prompted with "Student Login" page as shown below image
The updated data can be viewed from mySQL Workbench
Here are some of the dummy data used for testing our webApps shown below :-
image image image image

If login details is wrong :-
image

About-Us page of oCEO database :-
Screenshot 2023-03-20 at 21 14 40

## NavBar and Selection process in oCEO database :-
Screenshot 2023-03-20 at 21 15 30

Assignment - 3 | Contribution details : https://docs.google.com/document/d/1BiXMFtXF_6aI8bDtQSFaYC893RRDsi20zemd4p5jOqY/edit?usp=sharing
