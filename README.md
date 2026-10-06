# Airline Analytics

SQL-driven analysis of an airline ticketing database using SQLite and Python.

## Data scale used in the notebook
- `ticket_flights`: **1,045,726 rows**
- `tickets`: **366,733 rows**
- `seats`: **1,339 rows**

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
The notebook reads an SQLite airline-ticketing database that is **not included** in this repository (file size). It expects the file at `airline/travel.sqlite`. The queries use the tables `tickets`, `ticket_flights`, `seats`, `flights`, `aircrafts_data`, `bookings`, `boarding_passes` and `airports_data`.

1. Place the database at `airline/travel.sqlite`, or change the path in the first connection cell.
2. `pip install -r requirements.txt`
3. Open `airline_analytics.ipynb` in Jupyter and run all cells.
