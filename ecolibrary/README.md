# Library_Management_System

This is a subscription based libarary Management Sysyem with the following features.
        
        1.User Registration & Login
        Members create accounts and log in securely 

        2.Monthly Subscription 
        One paid plan unlocks full access

        3.Browse & Search Books
        Search by title, author, genre 

        4.Borrow / Return Books
        Members borrow physical copies from the library

        5.Read Books Online
        Paid members can read e-books in the browser

        6.Peer Borrowing
        Members can lend their own books to other members 


# Responsebilities:

- **Guest** — Can browse book titles only
- **Free Member** — Registered but not subscribed (very limited access)
- **Subscribed Member** — Full access: borrow, read online, peer borrow
- **Admin** — Manages books, users, and borrowing records

# Systems Life Cycle:

 1. React sends HTTP requests to Spring Boot REST APIs
2. Spring Boot validates JWT tokens, processes business logic
3. Spring Boot reads/writes data to MySQL
4. Responses come back as JSON to React



# Tech Stack and Tools

| Tool | Purpose | Download |
|---|---|---|
| JDK 17+ | Run Java code | https://adoptium.net |
| Maven | Java build tool | https://maven.apache.org |
| MySQL 8 | Database | https://dev.mysql.com/downloads |
| Node.js 18+ | Run React | https://nodejs.org |
| VS Code | Code editor | https://code.visualstudio.com |
| Postman | Test APIs | https://postman.com |


# System architecture
> 1. Requests

     Broweser/PostMan
            |
       HTTP Request
            |
        Controller
            |
         Service
            |
        Respository
            |
         Database   

> Response flow

        Database
           |
        Respository
           |
        Contoller
           |
        JSON Response