MySQL Database
You need to create a MySQL database with a table for storing notes.


CREATE DATABASE notes_db;

USE notes_db;

CREATE TABLE notes (
    id INT(11) AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    content TEXT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
