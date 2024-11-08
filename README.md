# Archery Club Database

![ERD Diagram](./ERD%20FINAL.pdf)

## Project Overview
This database project was developed to streamline scoring and record-keeping processes for an archery club. The goal is to provide a user-friendly, efficient system for managing archers’ scores, competition data, and championship results while minimizing manual entry and reducing errors.

## Team
Project by **Banh Paté Chaud Associates**

**Team Members:**
- Joshua Burns (Team Leader)
- Anh Khoa Nguyen (Stress Tester)
- Phuong Bao Minh Nguyen (Database Developer)
- Sukeyna Ali (Technical Writer)

## Project Structure
The project structure includes:
1. **Entity-Relationship Diagram (ERD)**: A visual representation of the database structure, detailing table relationships and key entities.
2. **SQL Scripts**: Scripts to create tables, relationships, and implement required indexes.
3. **Database Queries**: SQL commands for data interaction, such as inserting new records, updating scores, and retrieving data for reports.

## Key Tables and Relationships
- **Archer Information**: Stores archer details, including their scores and equipment.
- **Competition Information**: Manages data related to each competition.
- **Score Records**: Tracks each archer’s scores in individual rounds and competitions.
- **Round Types and Scores**: Provides structure for rounds, including parameters like distances, target face sizes, and scoring methods.

## Features
- **Score Lookup**: Retrieve individual and competition scores by date, archer, or round type.
- **Data Validation**: Ensures valid entries for competitions and rounds.
- **User Management**: Allows recorders to add and manage archer information.
- **Historical Data Access**: Keeps a comprehensive history of scores and competition results.

## Setup and Requirements
1. Ensure you have **MariaDB 5.5.68** or later installed.
2. Import the SQL scripts to create the database tables and relationships.
3. Use the database interaction queries to test functionality and perform initial data entry.

## Documentation
Detailed documentation for database management, user interaction, and setup procedures is available in the final project report.
