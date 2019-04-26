# LoginCrud
This is Login Form project built with SpringMVC and SpringJDBC. This project is able to perform user login and also able to 
list the number of users ,change password in case if forgotten, add new user etc. (All CRUD operations performed in this project)

Databse used MySql.
I have used Pooled Connection(DriverMangerDataSource) for better performance of the project

I have used little part of Spring Security to encrypt the password of the users instead of storing the password as plaintext.
This increases the security of the project.

Initially I have used MD5 encryption technique(not recommended as it is depricated), but as this basic project we can use it.
Recommended Encryption technique Bcrypt or SHA-1. (You will se this in updated version of this project).


