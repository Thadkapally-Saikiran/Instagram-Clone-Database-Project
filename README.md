# Instagram-Clone-Database-Project

This repository contains the SQL database schema and queries for an Instagram clone project. It demonstrates how various tables and relationships are structured in a typical social media application like Instagram. The project includes tables for users, photos, comments, likes, tags, and follows, and provides queries to analyze data such as the most liked photo, the oldest users, and usage of hashtags.

## Project Features

- **Database Design**: The project includes an SQL schema with multiple tables, such as `users`, `photos`, `comments`, `likes`, `tags`, `follows`, and `photo_tags`, to simulate a social media platform.
  
- **SQL Queries**: Various SQL queries are provided to extract and analyze data from the database, such as:
  - Finding the oldest users
  - Identifying the most liked photos
  - Analyzing user activity based on registration day
  - Identifying users who have never posted a photo
  - Analyzing hashtag usage
  
## Tables and Relationships

1. **Users Table**: Stores user information such as ID, username, and registration date.
2. **Photos Table**: Contains photo details such as ID, image URL, and the user who posted the photo.
3. **Likes Table**: Represents users who liked a specific photo.
4. **Comments Table**: Stores comments made by users on photos.
5. **Tags Table**: Contains tags that can be associated with photos.
6. **Photo Tags Table**: A relationship table linking photos with tags.
7. **Follows Table**: Represents users following other users.

## Setup Instructions

To set up this database locally and run the queries in MySQL Workbench:

### Prerequisites

- MySQL or MariaDB installed on your local machine.
- MySQL Workbench (or any MySQL client) to interact with the database.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/instagram-clone-database.git

## Import the SQL file:
Open MySQL Workbench, connect to your MySQL server, and open the .sql file in the repository. Run the file to create the database schema and insert sample data.

## Run the Queries:
Once the database is set up, you can execute the SQL queries provided in the file to interact with the data, analyze user activity, and more.

## SQL Queries Included:
The following queries are included to analyze the data in different ways:
1. **Finding 5 oldest users**
2. **Identifying the days of the week with the most user registrations**
3. **Finding users who have never posted a photo**
4. **Identifying the most liked photo**
5. **Finding users who have liked every photo**
6. **Finding the top 5 most commonly used hashtags**

## Contributions
Feel free to fork the repository, submit issues, or create pull requests to improve the project. Contributions are welcome!
