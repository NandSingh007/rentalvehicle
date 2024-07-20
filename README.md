# Vehicle Rental System

## Description

This project is a vehicle rental system designed to collect user information and data about the vehicle to rent and the dates on which the vehicle is rented. The backend is built with Node.js and uses a SQL-based database with an ORM of your choice, while the frontend is a React application utilizing Material UI and optionally Tailwind CSS.

## Features

- **Backend**: Node.js with any framework of your choice, SQL-based database, and ORM.
  - Seed initial values into the database for car and bike types with associated vehicles.
  - APIs to fetch vehicle types and vehicles.
  - API to submit rental bookings, ensuring no overlapping bookings.
- **Frontend**: React with Material UI and optionally Tailwind CSS.
  - Multi-step form interface displaying one question per screen.
  - Form validation with error handling.
  - Dynamic vehicle type and model selection based on user input.
  - Date range picker for selecting rental dates.

## Installation

### Prerequisites

- Node.js
- npm or yarn
- PostgreSQL or any SQL-based database

### Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/vehicle-rental-system.git
   cd vehicle-rental-system
   ```
