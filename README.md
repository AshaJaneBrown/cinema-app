![Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQp-UyGkZark_FdFkunNt7ntA68ijgim5LsOg&usqp=CAU)

# Cinema App

This app is a simulator of a cinema booking system

## :purple_circle: Features

- User registration and authentication (user/admin roles)
- Adding movies and cinema halls
- Searching for available movie sessions
- Adding tickets to shopping cart and making orders

## :purple_circle: Project Structure

The project has N-Tier Architecture with the following tiers:

- DAO. Storing and retrieving data from a database
- Service. Logical part of the application
- Controller. Interaction with a user

## :purple_circle: Technologies

Java 17, Maven, MySQL, Hibernate, Tomcat, Spring MVC, Spring Security

## :purple_circle: Quickstart 

To launch the project:

- Fork this repository
- Clone the repository to PC
- Configure "db.properties" file
```
db.driver=YOUR_DRIVER
db.url=YOUR_URL
db.user=YOUR_USERNAME
db.password=YOUR_PASSWORD
```
- Install and configure Tomcat (9.0.50)
- Run the project
