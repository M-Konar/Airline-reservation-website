#Zeyad Tyara air travel agecy website#

It's a website for Those who love travelling and adventure!
- As a user you can book you can view all the available flights with all the search filters that helps you find the flight that suits you the best.
- You can book the flight online, cancel it, ..etc (the user part is not implemented yet in sprint 1.)
 
- As an Admin, you can create new flights, view all the available flights using filters to search among them, edit available flights and delete them with ease simply by pressing on buttons that exist on the flight cards. 
- All changes done by the admin are reflected instantaneously on the backend and the DB.
 The website is implemeted using the MERN stack( Mern stands for MongoDB- Express- React- NodeJS) and the DB is hosted on the cloud using MongoDB free plan.   



Motivation: 
The project was created as instructed in the Advanced Computer Lap course. We, frankly speaking, did it for the grades :D, but also to have fun and test our self-learning and programming skills as future computer engineers. 

Build Status:The Project is working perfectly without any errors or bugs


Code Style:
The Project is split in to two parts Client side which represents the frontend, and the Server side which represents the backend.
The Model-View-Controller style was used in the project's backend side. Their is a folder dedicated for each category(Model-View-Controller) for each category of users(Admin-Guest-User).
The client side is split into components that each component is the front-end that maps to a functionality in the backend.



Screenshots:Search for your desired flight from the homepage directly.

Login Portal
![image](https://user-images.githubusercontent.com/82762206/147352812-873973a1-4410-4d75-b8d3-a9b8f04ecd2c.png)
Signup Portal
![image](https://user-images.githubusercontent.com/82762206/147352950-2617e407-b2cb-470e-998d-d539cbd8cb47.png)
Creating a new flight(exclusive for admins only)
![image](https://user-images.githubusercontent.com/82762206/147359496-9e3e9c15-27d1-4466-89a1-f46310f6c584.png)

Editing or deleting an existent flight(exclusive for admins only)
![image](https://user-images.githubusercontent.com/82762206/147359684-38b58c1d-3fd7-4a27-a633-f5a80afd00d4.png)
![image](https://user-images.githubusercontent.com/82762206/147359765-25bbcbc7-de76-401c-aaa6-446ead4ba5aa.png)

Reserving a Flight(Users)
![image](https://user-images.githubusercontent.com/82762206/147392593-569afc35-f22a-499c-b65f-39dc4eaca290.png)
![image](https://user-images.githubusercontent.com/82762206/147392602-c34bc662-7485-4679-8546-242260374664.png)
![image](https://user-images.githubusercontent.com/82762206/147392654-d3466269-5b30-4d79-942e-ddcf0d5f2d08.png)

Payment for Reservation(Users)
![image](https://user-images.githubusercontent.com/82762206/147392729-e1f89d0f-2dac-433a-9211-287b56ee26d4.png)
![image](https://user-images.githubusercontent.com/82762206/147392737-1816f229-cd4f-4a66-8fb7-83249b544a24.png)

Updating personal info(Users)

![image](https://user-images.githubusercontent.com/82762206/147392765-b9886719-a0fb-4d84-b9d4-0677f4a6b1d9.png)

View/Cancel/Edit my resrvations(Users)

![image](https://user-images.githubusercontent.com/82762206/147392795-5e25af80-0f06-4094-a399-91c10b4bdebc.png)

Edit reservation(Users)

![image](https://user-images.githubusercontent.com/82762206/147392896-2e6b061e-cf3e-47b0-838a-c054b99ec28f.png)









Tech/Framework used:MongoDB-Express Routing-React Js-Node Js (MERN Stack)

Features:1-Users can Login by Facebook without the need to signup
         2-Admin can create flights
         3-Admin can edit existent flights
         4-Admin can delete existent flights
         5-User can search flights
         6-User can reserve a flight
         7- it is a must for user to reserve departure and return flights at the time of reservation
         8-User must pay for a reserved flight at the time of reservation
         9-An email will be sent to the user once the payment for the reservation is complete
         10-User can cancel his flight
         11-An email will be sent automatically when the user cancels his reservation
         12-User can edit their personal information(passport number-password-first name-last name-telephone number)
         

```
######


 
Installation:1-install npm
```
npm install
```
2-install module express
```
npm i express
```
3-install module cors
```
npm i cors
```
4-install module bcrypt
```
npm i bcrypt
```
5-install stripe
```
npm i stripe
```


API reference:
https://nodemailer.com/about/

https://stripe.com/docs/api/authentication

https://unsplash.com/documentation

Tests:Use postman application in testing backend functions before integrating the functions with the frontend and use chrome developer tools

Postman download link:https://www.postman.com/downloads/




How to Use:The project is split to two parts frontend and backend.
Both parts must be run to see the full functionality of the flight reservation system.
################################################################
In order to run the backend part:
1-open the console.
2-change directory to Server
```
cd Server
```
3-run the backend by using
```
node index
```
################################################################

Now that we have run the back let's run the front end:
1-open a new terminal
2-change directory to Client
```
cd Client
```
3-start the front-end by writing this to the console
```
npm start
```
Your default browser will load the website and you can navigate through it normally.
If you want to login as an admin you will have to write the route yourself /adminLogin



Contribute:
You can contribute by sending your feedback on email airlineszeyad@gmail.com


Credits:

Mohamed Mahmoud Abdulatif Konar

Mahmoud Ahmed Abdelkhaleq

Ali Helmy Youssef

Zeyad Elsaed Elnagar

Omar Usama Mahmoud Elnagar

