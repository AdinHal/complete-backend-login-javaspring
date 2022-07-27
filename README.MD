# Register System with Java Spring
![](https://i.imgur.com/VqUmOtb.jpg)

- Create a database with PosgreSQL and connect it over the application.yml file
- The App also erases all the data after each run, in case you want to change it all You have to do is edit the ddl-auto in application.yml
- I used Postman and Maildev for the POST/GET and to test the verification emails
- I also used Docker to work with Maildev since it was easier for me, it also works fine with normal maildev run
- The app also generates a unique token for each user which we have to verify in order to be able to Login
- The app has password encryption too

## Initialized with Spring Initializr
![](https://i.imgur.com/Q7zktR5.png)

### Used Dependencies
```
- Lombok
- Spring Web
- Spring Security
- PosgreSQL Driver
- Spring Data JPA
- Java Mail Sender
```
## PostgreSQL as Database
![](https://i.imgur.com/r4JT2ln.png)

## Registering a User
### Token as response
![](https://i.imgur.com/AobytGm.png)
### Mail we get inside Maildev
![](https://i.imgur.com/qHbVt05.png)
### After verification
![](https://i.imgur.com/reQQ3hr.png)
### Mail configuration is located inside application.yml
![](https://i.imgur.com/sG37wmJ.png)
### You get the default Sign In page from Spring Security
![](https://i.imgur.com/JtP48qi.png)
### PostgreSQL Previewing the Tokens
![](https://i.imgur.com/TWiDXW9.png)

