# Airline Analytics

SQL-driven analysis of an airline ticketing database using SQLite and Python.

## Overview
This project explores airline booking and flight data stored in an SQLite database. It uses SQL queries from Python to analyse aircraft capacity, ticket bookings, revenue, fares and seat occupancy.

## Dataset
The notebook uses an SQLite database with 8 tables: `aircrafts_data`, `airports_data`, `boarding_passes`, `bookings`, `flights`, `seats`, `ticket_flights` and `tickets`.

Data scale used in the notebook:
- `ticket_flights`: **1,045,726 rows**
- `tickets`: **366,733 rows**
- `seats`: **1,339 rows**

> The database file is **not included** in this repository because of its size.

## Analysis
- Aircraft models and seat capacity
- Ticket bookings over time
- Total booking revenue over time
- Average fare by aircraft and fare class
- Revenue and average revenue per ticket by aircraft
- Aircraft occupancy rates

## Tech stack
Python, SQL, SQLite, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## How to run
1. Get the SQLite airline database and place it at `airline/travel.sqlite` (or change the path in the first connection cell of the notebook).
2. Install the dependencies:
```bash
   pip install -r requirements.txt
```
3. Open `airline_analytics.ipynb` in Jupyter and run all cells.
