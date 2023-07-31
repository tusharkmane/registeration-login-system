How to create a Registration and Login System with PHP and MySQL
Here are Seven pretty simple steps you have to follow to create a login system.

1.Create a Database and Database Table
2.Connect to the Database
3.Session Create for Logged in User
4.Create a Registration and Login Form
5.Make a Dashboard Page
6.Create a Logout (Destroy session)
7.CSS File Create



********************************************

##create database ##

CREATE TABLE IF NOT EXISTS `users` (
 `id` int(11) NOT NULL AUTO_INCREMENT,
 `username` varchar(50) NOT NULL,
 `email` varchar(50) NOT NULL,
 `password` varchar(50) NOT NULL,
 `create_datetime` datetime NOT NULL,
 PRIMARY KEY (`id`)
);
********************************************