# oCEO-flask-webapp
A flask webapp for performing INSERT, UPDATE, DELETE, RENAME, WHERE operations in oCEO database
Assignments 1 to 4 documentation: https://drive.google.com/drive/folders/1ltRDRza7WN9xpJzQtzhMOig613UMhG6j?usp=sharing

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

https://user-images.githubusercontent.com/74257754/229287002-89b92f89-0e6b-4692-9d5d-d0ddfbbdf944.png

install python packages(flask, pyyaml, flask-mysqldb) using command: pip install flask pyyaml flask-mysqldb (enter)

Finally type command to run the flask-webapp: python .\app.py (press enter)

Fig: Server got started[running on PORT shown] image

https://user-images.githubusercontent.com/74257754/229287434-1d1e95c6-d9a5-4a42-b937-77b3e1587e25.png


If you are getting an error, like this!!!
sometime while activating python virtual env. we get an error as shown image

https://user-images.githubusercontent.com/74257754/241738032-2c0c0587-51f1-4cbd-85e6-b9b370e3c098.png


to remove this, open windows powershell as admin and do as shown in Screenshot image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/27c8c213-10bc-44bf-91a8-3c2314691e1a)


Other way(if above steps not working) :-
install Flask(python web framework) using the commands as shown :
py -m pip install flask
Now, check their versions using command as shown :-
py -m flask --version
SS for the output :-
image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/6d13bb9a-9f53-4eb6-9fe6-7e5a17e3c1a4)

Then install following pip packages :-
pip3 install flask-mysqldb
pip3 install pyyaml
Open the oCEO-flask-webApp
command: python app.py (press enter)
then in terminal we get the ouput as shown in screenshot below
image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/927c6467-84bc-42d6-a2c5-3bf02f94627f)

On clicking the default PORT(shown with arrow mark)[on clicking the link] : we will our app running and displays the homepage
Home Page view:-
image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/37ec131f-fecf-48d6-8064-e99c53919df6)


On clicking the IITGN-logo, we get 3 options as follows:-
Login As Student
Login As Professor
Login As Admin
On clicking "Login As Student" we get the UI as shown :- image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/ddd17fda-a075-4685-b35e-3180476fe889)

Login details of student(for registered student) i.e emailID and Password image
On clicking "Login As Professor" we get the UI as shown :- image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/37e9ce97-9f8d-4d40-a36d-ce202b774231)

On clicking "Login As Admin" we get the UI as shown :- Screenshot (726)

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/094fa368-b8a8-4214-8fff-bb47caf3c41c)

In MySQL, created database named "oceo" and tables as shown :-
image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/e1a7ec58-86c8-48e6-8b01-f28d919f93af)


These are the following commnads used for creating tables :-
Creating Student table image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/69fc5a1d-0e9e-413a-9fdc-ec72043fa13f)


Creating Professor table image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/8107482f-a5ce-400f-a748-a86ab9ee7252)


Creating total_jobs table image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/502cf7da-b188-4d4a-9606-7ad006a2b555)


Creating application table image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/1c9c065d-ad6c-42da-bbbe-c9ccf58a9df6)


Creating ongoing_jobs table image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/4db49465-d975-4622-bdf0-712f3f582ec2)


Creating concluded_jobs table image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/3c47b437-487f-438e-bd9d-a345d2607e20)


Creating bank_details table image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/c088c27e-ee6b-4380-ab7b-1739876cb277)


Working of all Operations shown below(with SS attached) :-
RENAME Operation :-
image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/169186eb-8eb8-43bf-afa6-df441253f1e0)


Same rename operation working on MySQL Workbench :- image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/84912f6e-00f8-4e7b-b8d3-74ad60961c80)

RENAME queries
SELECT with WHERE operation :-


Professor login page image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/c3e17051-f6a9-4078-bb3e-4805b7091a0c)

Operation performed in MySQL workbench image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/0229693b-5296-4da5-a5a6-2c6acb405dd8)

Updated date get reflected in table shown image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/6bef10c5-bbeb-409b-836f-75b09e9fbade)

UPDATE operation :-
image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/684851cb-121c-4201-9bfd-dd0f48d56bb2)


before update image
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/e9c368e7-ae06-4da7-af85-3c7287e9c7b0)

before update in schema image
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/9bb66bb6-4b43-4de1-adad-5a0503eb37fc)

updated data in schema image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/eb55bb38-c040-494b-89fb-a85fe9a1c6ce)

Alert dialog box to confirm the update operation image Dynamic execution in the frontEnd

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/2f7d3b18-ca8c-46c1-8af6-ae5354d11abe)

DELETE operation :-
image
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/7202ca9e-90f6-4f40-ac61-65e2fd13c161)


Before delete operation image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/c369a2dd-ec65-48e6-bcc9-e5d89a854eed)

Before delete in schema(i.e MySQL workbench) image
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/d9d63640-3d3b-4f39-ad9a-53d6bff183d9)

Alert Box for confirming deletion operation image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/05f17b6c-f2c9-430e-96b9-bc372dd9ae46)

After delete operation from Schema(from MySQL workbench) image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/4f16abbb-a593-4703-93c0-6aea14453af0)

deletion operation on table showing Dynamic Execution
INSERT operation (for student Registration):-
image
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/4306937b-86fb-4994-b845-df90d5b1ca79)


These data of student will be stored in student table in oceo database image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/78a8ebb1-ed28-4ef9-9104-e352d25ecf85)

Student will be prompted with "Student Login" page as shown below image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/efe00f19-d775-4480-94c1-6ee0496e34b7)

The updated data can be viewed from mySQL Workbench
Here are some of the dummy data used for testing our webApps shown below :-
image image image image
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/711b2e1c-2528-42fc-83c6-a3f800d6de60)
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/c8b52feb-bd70-41d2-be7e-362662f9dc41)
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/7773eb42-58b2-41dd-bbd0-776f2236b4e3)
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/4aefce46-3a90-439f-8cef-a6fcda6019fc)


If login details is wrong :-
image

![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/b202f927-47f6-4d9a-91db-f4c2eae706b5)


About-Us page of oCEO database :-
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/f81865fa-77d1-42fa-be63-2b435159b088)


## NavBar and Selection process in oCEO database :-
![image](https://github.com/ishanichogle/oCEO-flask-webapp/assets/76484181/a6d6d6f3-4883-45e4-9602-b4f90d0e4461)



