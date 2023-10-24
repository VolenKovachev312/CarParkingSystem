# CarPark Solutions
Website for renting a parking space.

<h2>Main Page</h2>
For testing purposes there are "Demo Admin" and "Demo User" buttons for quick login.<br>
"Who are we?" description generated by AI.<br>
The satisfied customers, cities and continents statistics are placeholder and just used for the design.<br>
<br>

![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/2d533860-92f2-4a46-bc90-5ba554a11f75)
![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/95fa1ddb-ada5-4950-9d11-98c884d38b82)

<h2>Reserve Page</h2>
In this page google api is used to show the map, put corresponding markers on all parking locations,<br>
generate search autofill and request your location to find nearby parking locations.<br><br>
Clicking on the "find parking near me" button asks for permission to use your location<br>
and fills the location list beneath if there are nearby parking lots.<br>
Using the search bar also fills the list depending on the search result.<br>
Clicking on the map markers pops up a info menu with details about the clicked location.<br>
<br>

![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/64e7953e-f562-45d7-823e-44e7dba597b6)
![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/cdd3c96f-75d3-4b7a-ac1b-0dd25988588b)

<h2>Confirming Reservation</h2>
This page can be used as a logged user and as a non-logged user.<br><br>
If a logged user makes a reservation, their info is autofilled and the reservation gets stored in their reservation history,<br>
but if a non-logged user makes a reservation they can't access the reservation history page and need to manually fill out their information.<br><br>
The payment info is not required.<br>
For the date and time selection i use the daterangepicker library.<br>
<br>

![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/cf665b66-4cb7-4d35-8e60-cbd361fb3d03)
![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/505aa559-c308-4a88-bec2-c723a39cc7e8)

<h2>Admin Page</h2>
In the Admin Page the admins can create new locations, search for locations by name and also look at every parking location, edit them if necessary and check all the reservations made for them.<br>
What is more, the admins can search up information about users, such as their name, their reservations, and other stats.<br>
<br>

![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/2d65f2bb-80b8-4266-9292-e31120adacc8)

<h2>Creating a new parking lot</h2>
In this page the admin fills out a form to create a new location.<br>
The address and coordinates are fetched with the google maps api depending on where the admin clicks on the map.<br>
The admin has the option the make the parking lot 24/7 Open which disables the working hours selection.<br><br>
The Edit Parking page looks almost identical, but has the ability to soft delete the parking lot.<br>
<br>

![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/b2253716-a6ff-409d-9069-a4efc6219fe3)

<h2>Checking User Info</h2>
This page is simillar to the user reservation history and parking lot reservations page so I'll not include them.<br><br>
In this page we can see general info about the user, their reservation info and whether the reservation is canceled, active or completed.<br>
The user who has made the reservations and the admin can both cancel them.<br>
<br>

![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/e6874fc9-ccba-4aaf-8312-9698216c4bc6)

<h2>Account Page</h2>
This is a basic page with the functionality to change info about your account and delete it if wanted.<br><br>
Zoomed out to fit in the image<br>
<br>

![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/388b6fb0-7738-4259-a717-efa991505a7b)

<h2>Login and Register</h2>

![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/14da60e3-1340-466e-a346-8817d08e48a2)
![image](https://github.com/VolenKovachev312/CarParkingSystem/assets/117029606/49e2059e-c39c-4be4-bc39-921f318c3614)
