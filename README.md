# Movie Database Application

A MVC web application for users to keep a list of their favorite movies.

## Business Problem:

Streaming providers such as Netflix all have a User List feature where users can maintain a list of movies that they would like to watch. The problem is that between these streaming services there is way to share your favorite movies.

## Solution:

My web app allows users to share their favorite movies by adding movies to the database. It is currently a master list that all users collaborate and append to. In a future release I would like the users to ownership of their own movie tables.

## Technology:

    - ASP.NET web framework.

    - ASP.NET MVC.

    - SQLite Database Backend.

    - Bootstrap page styling.

## Functionality:

### Welcome Page:
    - Upon entering the site Users are first presented with only the Navigation bar.
    - The Movies link will bring users to a view of the Movie database.
![Welcome Page](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/welcome-screen.png)

---

##### Login Page:
    - Users are not required to be registered to view the movies, but they are unable to Add, Edit, Delete.
    - Registered users can all make changes to the Movie database.
    - Users register with an email address.
    - The password must have atleast 1 Uppercase character and Non-Alpha-Numeric character.
![Login Page](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/login-screen.png)

---

### Movies Page:
    - Clicking Movies on the Navbar brings the users to the Movie Table.
    - Unregistered users are allowed to view the items but are prohibited from Creating, Editing, and Deleting movies.
    - Clicking on any of these functionalities will route unregistered users to a login/registration page.
![Movies Page](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/movies-screen.png)

---

### Genre Filtering:
    - Any user can use the dropdown menu to filter movies by genre.
![Genre Filter View](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/genre-filter.png)

---

### Title Filtering:
    - Any user can also use the text input form to filter movies by Title or Genre.
    - This can filter by Genres as well.
![Filter View](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/filter.png)

---

### Add Movie Page:
    - Registered users can add movies to the list.
    - All fields are required for submission.
![Add Movie Page](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/add-movie-screen.png)

---

### Details Page
    - Any user can view the details of a movie by clicking on the Details button.
    - If they wish to Edit from here they must be a registered user.
![Details Page](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/details-screen.png)

---

### Edit Page:
    - Registered Users can edit the fields of each movie.
![Edit Page](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/edit-screen.png)

---

### Delete Page:
    - Registered Users can delete.
![Delete Page](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/delete-screen.png)

---

### Manage Account Page:
    - If a user is signed in they can click on Account in the Navigation bar to view their account settings.
        - Change Email.
        - Change Password.
        - Enabling Two-Factor Authentication.
        - Delete Account.         
![Account Management Page](https://github.com/SamEakin/Movie-MVC/blob/AuthVersion/Documentation/Screenshots/manage-screen.png)
