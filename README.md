CREATE DATABASE multi_user_login;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL,
    role ENUM('admin', 'user') NOT NULL
);

![image](https://github.com/Nandhini-php-Developer/add/assets/164607559/343271ac-f71d-4e6e-b9bf-7cd6f11c8054)

![image](https://github.com/Nandhini-php-Developer/add/assets/164607559/78143fae-180a-47e9-943c-a58b82e7a2a6)


