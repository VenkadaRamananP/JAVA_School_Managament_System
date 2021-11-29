# JAVA_School_Managament_System
2nd Year (3rd sem) Java Project

user login : 
id: user 
password: user

admin:
id: admin
password: admin

To create database: xampp phpMyAdmin
open database.....create a new database with name "student"
and write this sql code to create table
CREATE TABLE `infotable` (
  `form_id` int(50) DEFAULT NULL,
  `batch_no` int(50) DEFAULT NULL,
  `student_id` int(50) DEFAULT NULL,
  `first_name` varchar(50) DEFAULT NULL,
  `middle_name` varchar(50) DEFAULT NULL,
  `last_name` varchar(50) DEFAULT NULL,
  `email` varchar(50) DEFAULT NULL,
  `contact` varchar(50) DEFAULT NULL,
  `dob` varchar(50) DEFAULT NULL,
  `father_name` varchar(50) DEFAULT NULL,
  `mother_name` varchar(50) DEFAULT NULL,
  `permanent_add` varchar(50) DEFAULT NULL,
  `temporary_add` varchar(50) DEFAULT NULL,
  `particular_school` varchar(50) DEFAULT NULL,
  `particular_higherschool` varchar(50) DEFAULT NULL,
  `name_of_school` varchar(50) DEFAULT NULL,
  `name_of_higherschool` varchar(50) DEFAULT NULL,
  `percentage_school` varchar(50) DEFAULT NULL,
  `percentage_higherschool` varchar(50) DEFAULT NULL,
  `passed_year_school` varchar(50) DEFAULT NULL,
  `passed_year_higherschool` varchar(50) DEFAULT NULL,
  `image` longblob
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
