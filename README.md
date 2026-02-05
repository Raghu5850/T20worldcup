# T20worldcup
🏏 T20 World Cup Database System (MySQL)
📌 Project Overview

This project is a relational database system designed to store, manage, and analyze match and player statistics for the T20 World Cup.
It supports match-level data, player performance metrics, and advanced SQL queries such as leaderboards and strike-rate analysis.

The system is built using MySQL, following database normalization principles and optimized with indexes and stored procedures.

## 🎯 Objectives

Design a normalized database schema for a cricket tournament

Store match details (teams, venue, result)

Track per-player, per-match performance

Perform analytical queries (top scorers, wicket takers, strike rates)

Practice real-world SQL concepts (joins, indexes, procedures, truncate)

### 🗂 Database Schema
Tables

Teams – Stores participating teams

Players – Stores player details mapped to teams

Venues – Stores match venues

Matches – Stores match-level information

PlayerMatchStats – Stores player performance per match

Relationships

One team has many players

One match is played between two teams

One match has one venue

One match has many player statistics

One player can have stats in many matches

### 🧱 Tables Structure


<img width="327" height="122" alt="image" src="https://github.com/user-attachments/assets/843ec295-36a4-45d9-80fd-657745835c08" />

#### 🛠 Technologies Used

Database: MySQL

Language: SQL

Concepts:

Normalization

Primary & Foreign Keys

Joins

Aggregate Functions

Indexes

Stored Procedures

#### ⚡ Key Features

Fully normalized relational database design

Match-wise and player-wise statistics tracking

Optimized leaderboard queries using indexes

Stored procedures for inserting match and player stats

Easy cleanup using TRUNCATE for testing new tournaments

##### 🚀 How to Run the Project

Clone the repository

Create the database using provided SQL scripts

Insert sample data (first 5 matches)

Execute analytical queries

Truncate tables to reset the data

###### 🧪 Testing Approach

Inserted sample data from previous T20 World Cup matches

Verified leaderboard queries

Validated foreign key relationships

Tested performance with indexed queries

###### 🔮 Future Enhancements

Points table & Net Run Rate calculation

Player career statistics

Views for dashboards

Triggers for automatic stats updates

Migration to PostgreSQL

Integration with visualization tools (Power BI / Tableau)

###### 📚 Learning Outcomes

Hands-on experience with relational database design

Improved understanding of real-world SQL analytics

Learned query optimization using indexes

Practical usage of stored procedures

Built an end-to-end database project

###### 👤 Author

Raghu B
📍 India, Bangalore
💡 SQL | MySQL | Database Design


