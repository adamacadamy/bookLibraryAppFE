# 📚 Book Library Management
The Book Library Management App is a user-friendly application that helps individuals and organizations keep track of their book collections. Users can easily search for books, borrow or return them, and manage due dates. Admins can add new titles, update inventory, and monitor borrowing activity—all from a simple interface. This app makes managing books convenient, efficient, and accessible on the go.


## Pages
## Book Related Pages
### 1. View Books Anauthenticated Page `/au_books.html`
 
 <img src="/screens/books/Books Pape [Not Authenticated ]/Books View 1.png" width="400"/>
 
 
### 2. View Books Authenticated Page `/books.html`
 
 <img src="/screens/books/Books Page [Authenticated] View Book/Books View 8.png" width="400"/>


### 3. View Books Ditailed Page  `/au_books.html?book_id=1.html&action=view`
   <img src="/screens/books/Books Pape [Not Authenticated ]/Books View 6.png" width="400"/>  

### 4. View Book Ditailed Page  `/books.html?book_id=1.htmll&action=view`
   <img src="/screens/books/Books Page [Authenticated] View Book/Books View 6.png" width="400"/>  

### 5. Add Books Authenticated Page `add_book.html`

   <img src="/screens/books/Books Page [Authenticated] Add Book/Books View 2.png" width="400"/>  

### 6. Edit Books Authenticated Page `/edit_books.html?book_id=1.html`

   <img src="/screens/books/Books Page [Authenticated] Edit Book/Books View 2.png" width="400"/>  


### 7. Delete Books Authenticated Page `/books.html?book_id=1.html&action=delete`
 <img src="/screens/books/Books Page [Authenticated] Delete Book/Books View 6.png" width="400"/>  

 
## User Related Pages

### 1. View Users Anauthenticated Page `/users.html`
 <img src="/screens/users/User Page [Authenticated] Edit User/User View 1.png" width="400"/>  


 
### 2. Edit User Detaile Anauthenticated Page `/edit_users.html?user_id=1`
 <img src="/screens/users/User Page [Authenticated] Edit User/User View 2.png" width="400"/>  

 ### 3. Dlete User Detaile Anauthenticated Page `/users.html?user_id=1&action=delete`
 <img src="/screens/users/User Page [Authenticated] Edit User/User View 2.png" width="400"/>

 
 ### 4. View User Me Anauthenticated Page `/users.html?user_id=1&action=view`
 <img src="/screens/users/User Me Page [Authenticated]/User View 2.png" width="400"/>
 
 ### 5. Add User Me Anauthenticated Page `/add_users.html`
 <img src="/screens/users/User Me Page [Authenticated]/User View 2.png" width="400"/>
 

 
## Auth Related Pages

### 1. Login Page `/login.html`
 <img src="/screens/auth/Home Page [NOTE AUTHENTICATED] Login Page/Headers Selected.png/" width="400"/>  


### 2. Registeration Page `/registraton.html`
 <img src="/screens/auth/RegisterationPape [Not Authenticated]/Register View 1.png" width="400"/>  

 
## Navigation Rules

<img src="/screens/navigation.png" width="500">

# Rule 1 | [start] => not authenticated [`login.html`, `registration.htm`]

1. if anauthenticated user reaches home page is redirected or landed to `loging.html`
2. an anauthenticated can navigate to registration page and register with default `ROLE` user

.... CONTINUE