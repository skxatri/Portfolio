# ✈️ Flight Data Analysis (SQL Project)

This project focuses on analyzing flight and airline operations data using SQL. It includes queries that provide insights into flight delays, aircraft usage, booking trends, revenue, and passenger behavior.

---

## 📌 Project Goals

- Identify delayed flights and calculate average delays
- Analyze aircraft usage and flight durations
- Calculate revenue per flight and per passenger
- Explore passenger boarding patterns and seat occupancy
- Track booking and airport activity trends

---

## 🧰 Tools Used

- MySQL
- MySQL Workbench

---

## 🗃️ Dataset Overview

The database includes the following tables:

- `aircrafts` – Details about each aircraft (model, range)
- `airports` – Airport info including location and timezone
- `flights` – Scheduled and actual flight info
- `seats` – Seat layout and fare conditions per aircraft
- `bookings` – Booking references and total amount
- `tickets` – Ticket info linked to bookings
- `ticket_flights` – Tickets mapped to flights with fare and amount
- `boarding_passes` – Passenger boarding information

Download [Airlines Schema](https://github.com/skxatri/Portfolio/blob/main/sql-project/flight-data-analysis/docs/Airlines_schema_scripts.zip)

---

## 🗺 Database Schema (ER Diagram)

Here is the schema used in this project:

[ER Diagram](./docs/flight_schema_er_diagram.png)

---

## 📊 SQL Queries Included

The [flight_data_analysis.sql](https://github.com/skxatri/Portfolio/edit/main/sql-project/flight-data-analysis/flight_data_analysis.sql) file contains 15 queries that cover:

1. Departure delays
2. Aircraft usage frequency
3. Revenue per flight
4. Boarding patterns
5. Occupancy per aircraft and per flight
6. Top revenue-generating flights
7. Average flight durations
8. Airport traffic
9. Booking trends
10. Popular flight routes
11. Passenger activity and spending

---

## 🚀 How to Run

1. Import the dataset and schema into MySQL Workbench.
2. Run the queries from [flight_data_analysis.sql](https://github.com/skxatri/Portfolio/edit/main/sql-project/flight-data-analysis/flight_data_analysis.sql).
3. View results for each insight.

---
