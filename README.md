# SchoolManagementSystem

School Management System Website built on **Node js** and **MySQL Database**.

## LANGUAGES USED:
1. **HBS**
2. **CSS**
3. **JAVASCRIPT**
## TECHNOLOGIES USED:
1. **NODE JS** (FOR DEVELOPMENT PURPOSE)
2. **MYSQL** (FOR DATABASE PURPOSE)
## DESCRIPTION
School management system consists of these folders
1.	**GetRequest**
2.	**PostRequest**
3.	**routes**
4.	**views**

And some js & .json files
5.	**pakage.json**
6.	**pakage-lock.json**
7.	**app.js**


# BACKEND

<img src="https://user-images.githubusercontent.com/64039135/135749839-6c65bb11-4295-41e7-a8d5-156dc204ce60.PNG" width="1000px" height="400px" />


## GetRequest:
The files in this folder contain codes and queries that’s bring data from database (MySQL) to our webpages.

## PostRequest:
The files in this folder contain codes and queries that’s send the data from webpages to database (MySQL).

## routes:
The file in this folder contain queries and program that render the webpages on websites.

## view:
This folder contains all the .hbs files and image folder, where **hbs** is the updated version of **html** that facilities **nodejs** for web development. 
hbs is an **express. Js** wrapper for the **handlebars. Js** JavaScript template engine. **Handlebars. Js** is a template engine to make writing html code easier.

## package.json:
It records important metadata about a project.

## package-lock.json:
The goal of package-lock. json file is to keep track of the exact version of every package that is installed.

## App.js:
 This file contains all the codes that is essential for the starting of program. It connects the database (MySQL) with our webpages. It also contains the path of all **.js files** and **.hbs files**

# FRONTEND:
It consists of three major Views:

1.	**Administrator View**
2.	**Teacher View**
3.	**Student View**
## Home Screen
It displays three buttons for admin, teacher and student to navigate to their login or signup page. There is also a carousel in the background.
<img src="https://user-images.githubusercontent.com/64039135/135750263-62826696-44a1-4bb2-af22-358778809229.PNG" width="800px" height="400px" />

## Administrator View
Administrator can sign up and login into his/her account using password (in case of login). 
<img src="https://user-images.githubusercontent.com/64039135/135750135-65dc603e-75ea-4cda-b4ad-7bb6748c76d0.PNG" width="800px" height="400px" />


After successfully login, he
1.	can see his information on a side navigation bar in an Admin portal.
<img src="https://user-images.githubusercontent.com/64039135/135750410-7a649326-b92e-4f1f-bc9b-8ef6f2a8471f.PNG" width="800px" height="400px" />


2.	He has the options of enter, edit, view and delete information of Student fees payment detail, Teacher salary payment detail, Student marks, Schedule, subject also he can enter and edit student's marks.

<img src="https://user-images.githubusercontent.com/64039135/135750842-c2b2d8c4-361a-40c3-8067-a96805d8ee59.PNG" width="800px" height="400px" />
<img src="https://user-images.githubusercontent.com/64039135/135750908-f2761b2b-e608-47ec-8389-dd451a9ca8d0.PNG" width="800px" height="400px" />
<img src="https://user-images.githubusercontent.com/64039135/135750842-c2b2d8c4-361a-40c3-8067-a96805d8ee59.PNG" width="800px" height="400px" />


## Teacher View:

Teacher can sign up and login into his/her account using password (in case of login). 
After successfully login, he can see
1.	his personal information on a side navigation bar in a Teacher portal.
2.	He can view his salary payment detail and schedule, also can enter and edit students’ marks.

## Student View:
Student can sign up and login into his/her account using password (in case of login). After successfully login, he can see
1.	his personal information on a side navigation bar in a Student portal.
2.	He can view his fees payment detail, examination result marks, subject and schedule

