# Movie Database Application

A MVC web application for users to keep a list of their favorite movies.

https://seakin-movie.azurewebsites.net/

## Business Problem:

Streaming providers such as Netflix all have a User List feature where users can maintain a list of movies that they would like to watch. The problem is that between these streaming services there is way to share your favorite movies with your friends.

## Solution:

My web app allows users to share their favorite movies by adding movies to the database. It is currently a master list that all users collaborate and append to. In a future release I would like the users to create and share their own movie lists individually.

## Technologies:

    - ASP.NET web framework
    - ASP.NET MVC
    - Bootstrap page styling
    - SQLite Database Backend    
    - Azure Cloud Hosting

# User Interface:

[Welcome Page](#Welcome-Page)

[Creating an Account/Log in](#Login-Page)

[Movies Page](#Movies-Page)

[Filtering by Genre](#Genre-Filtering)

[Filtering by Title](#Title-Filtering)

[Adding Movies](#Add-Movie-Page)

[Viewing Movie Details](#Details-Page)

[Editing an Existing Movie](#Edit-Page)

[Deleting a Movie](#Delete-Page)

[Managing your Account](#Manage-Account-Page)

---

## Welcome Page:
    - Upon entering the site Users are first presented with only the Navigation bar.
    - The Movies link will bring users to a view of the Movie database.
![Welcome Page](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/welcome-screen.png)


[Back](#User-Interface)


---


## Login Page:
    - Users are not required to be registered to view the movies, but they are unable to Add, Edit, Delete.
    - Registered users can all make changes to the Movie database.
    - Users register with an email address.
    - The password must have atleast 1 Uppercase character and Non-Alpha-Numeric character.
![Login Page](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/login-screen.png)


[Back](#User-Interface)


---


## Movies Page:
    - Clicking Movies on the Navbar brings the users to the Movie Table.
    - Unregistered users are allowed to view the items but are prohibited from Creating, Editing, and Deleting movies.
    - Clicking on any of these functionalities will route unregistered users to a login/registration page.
![Movies Page](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/movies-screen.png)


[Back](#User-Interface)


---


## Genre Filtering:
    - Any user can use the dropdown menu to filter movies by genre.
![Genre Filter View](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/genre-filter.png)


[Back](#User-Interface)


---


## Title Filtering:
    - Any user can also use the text input form to filter movies by Title or Genre.
    - This can filter by Genres as well.
![Filter View](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/filter.png)


[Back](#User-Interface)


---


## Add Movie Page:
    - Registered users can add movies to the list.
    - All fields are required for submission.
![Add Movie Page](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/add-movie-screen.png)


[Back](#User-Interface)


---


## Details Page
    - Any user can view the details of a movie by clicking on the Details button.
    - If they wish to Edit from here they must be a registered user.
![Details Page](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/details-screen.png)


[Back](#User-Interface)


---


## Edit Page:
    - Registered Users can edit the fields of each movie.
![Edit Page](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/edit-screen.png)


[Back](#User-Interface)


---


## Delete Page:
    - Registered Users can delete.
![Delete Page](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/delete-screen.png)


[Back](#User-Interface)


---


## Manage Account Page:
    - If a user is signed in they can click on Account in the Navigation bar to view their account settings.
        - Change Email.
        - Change Password.
        - Enabling Two-Factor Authentication.
        - Delete Account.         
![Account Management Page](https://github.com/SamEakin/Movie-MVC/blob/master/Documentation/Screenshots/manage-screen.png)


[Back](#User-Interface)


---
