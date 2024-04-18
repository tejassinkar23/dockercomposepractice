# python-mysql-crud-webapplication

For this, Python Web Application CRUD Example using Flask and MySQL, you need modules, such as, table, flask, mysql. 


# Table Module Installation
pip install flask_table

# MySQL Module Installation
pip install flask-mysql


# Create database and table
CREATE TABLE `tbl_user` (
  `user_id` bigint NOT NULL AUTO_INCREMENT,
  `user_name` varchar(45) DEFAULT NULL,
  `user_email` varchar(45) DEFAULT NULL,
  `user_password` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`user_id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;

# insert data to the table
insert  into `tbl_user`(`user_id`,`user_name`,`user_email`,`user_password`) values 
(1,'vishnu','contact@vishnu.com','pbkdf2:sha256:50000$obX7AAZv$61ba4f743eff5113433a3fd249896deed4120e9a83deaf166477ca5fb74fcd49');
