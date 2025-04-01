# Bike Rental Shop

## Overview
This project is an interactive Bash program that manages bike rentals using PostgreSQL. It allows customers to rent bikes, return them, and view rental history. This was developed as part of the freeCodeCamp "Bike Rental Shop" certification project.

## Features
- Customers can rent bikes from the shop.
- Customers can return rented bikes.
- Rental details are stored and managed in a PostgreSQL database.
- Customers can view their rental history.

## Technologies Used
- **Bash**: Used for scripting and user interaction.
- **PostgreSQL**: Database for storing rental records and customer details.
- **Gitpod**: Virtual development environment for project implementation.

## Usage
- The script prompts users to rent or return a bike.
- If the customer is new, they will be asked to provide their details.
- The system records the transaction and updates availability.
- Customers can check their rental history.

## Database Schema
The database consists of the following tables:
- `customers`: Stores customer information (ID, name, phone number).
- `bikes`: Lists available bikes for rent.
- `rentals`: Tracks bike rentals and returns.

## Files in the Repository
- **`bike_rental.sh`**: Main script handling user interactions and database operations.
- **`bike_rental.sql`**: PostgreSQL script to set up the database schema.

## How to Submit
After completing the project, submit the repository URL containing the required files (`bike_rental.sh` and `bike_rental.sql`).


