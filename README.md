# CarHub - Car Dealer Website

## Final Project - Introduction to Software Engineering - HCMUS

## Member Contributor Information
| Name              | ID       |
|-------------------|----------|
| Vo Nguyen Gia Bao  | 21127016 |
| Tran Nguyen Huan   | 21127050 |
| Le Huynh Phuc   | 21127392 |
| Nguyen Phu Trong   | 21127708 |

## Problem Statements:
- With improved living standard, demand buying used car has surged. For people with low income, buying a new car from a genuine company is still not feasible.
- Researching different types of car manually costs buyers a lot of time and effort
- Navigating the complexities of used car transactions pose challenges due to scattered information and limited transparent.

## Introduction:
**Carhub** aims to:
- Provide a user-friendly online platform that allowing customers find their desired car quickly and accurately.
- Our platform focuses on fostering transparent inquiry between customer and admin (dealership)
<p align="center">
  <img src="https://github.com/knightstark7/CarHub-Car-Dealer-Website/blob/main/images/home_page.jpg" >
</p>

## Solid Features
1. Search Function
    - Implement a search bar allowing users to search for cars by name, model, location, year, and price.
    - Use backend logic to filter and retrieve relevant search results from the database.
2. Pagination
    - Implement pagination to display a specified number of cars per page, allowing users to navigate through multiple pages of search results.
3. Send Message
    - Provide a messaging feature where customers can request more information about a specific car they are interested in.
    - Implement logic to restrict each login account to send only one message per car.
4. Login
    - Enable users to log in using their Facebook or Google accounts for seamless authentication.
5. Register
    - Implement a registration form for new users, ensuring unique usernames and valid email addresses.
    - Validate that the confirm password matches the password entered by the user.
6. Send Email
    - Integrate functionality to send emails when users request more information or use the `Contact Us` service.
    - Configure email notifications to be received by the admin for user inquiries.
7. Messages
    - Successful or unsuccessful login will both pop out messages to inform users
8. Admin
    - Develop an admin panel to manage users' personal information and car listings.
    - Ensure authentication and authorization mechanisms to secure admin functionalities.
    - Provide options for admins to add, edit, or remove car listings, including details such as featured status, name, city, color, VIN, and whether the car is used or new.


## Our Architecture
Image about Use Case Models
<p align="center">
  <img src="https://github.com/knightstark7/CarHub-Car-Dealer-Website/blob/main/images/use_case_model.png" >
</p>

In this project, our website follows `MVC` (Model - View - Client) architecture
<p align="center">
  <img src="https://github.com/knightstark7/CarHub-Car-Dealer-Website/blob/main/images/MVT-architecture.png" >
</p>

## Tech Stacks
- CarHub employs HTML, CSS, JavaScript, Bootstrap for a responsive Front end 
- Django as a powerful Back-end framework for efficient development
- PostgreSQL as a reliable database for seamless data management. 

==> This tech stack ensures a user-friendly design, robust functionality, and effective handling of data on the CarHub website.
<p align="center">
  <img src="https://github.com/knightstark7/CarHub-Car-Dealer-Website/blob/main/images/tech_stack.png" >
</p>

## Requirements:

run command 

```
pip install -r requirements.txt
```

## Execution:
-	Clone this repository using
```
git clone https://github.com/knightstark7/CarHub-Car-Dealer-Website.git](https://github.com/vngbao21/CarHup.git
```
**OR**
Zip Download the Repository and Extract it's contents.
-	Now run the [manage.py](https://github.com/knightstark7/CarHub-Car-Dealer-Website/blob/main/manage.py) file directly in your Terminal using
```
python manage.py runserver 
```
which automatically runs the django server in port 8000

Then, open your browser and type localhost:8000 or 127.0.0.1:8000

## Demo:
- Link demo: https://www.youtube.com/watch?v=hpllW2t5fSc

## Deployment:
Our website and database are deployed on a server on [Render](https://render.com/). However, unfortunately, we don't have sufficient funds to renew the package, resulting in the temporary suspension of our website. Please clone our repository to run the website locally. :-)
link old web deployment: https://carhub-app.onrender.com/

