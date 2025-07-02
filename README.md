# ✈️ Airline Data Management and Analysis Using Power BI

## 📌 Project Title
**Airline-Performance-Analysis**

## 🧩 Problem Statement
The airline industry operates with numerous complexities, requiring robust **data management** and **insightful analytics** to enhance **flight operations**, **passenger management**, and **ticketing systems**. This project leverages Power BI to analyze operational trends and improve decision-making efficiency in the airline sector.

---

## 📊 Objective
To analyze and visualize airline data using **Microsoft Power BI**, delivering actionable insights into:
- Airline operations
- Passenger management
- Ticket booking trends

---

## 📁 Datasets Used

1. **Flight_Information**
   - Columns: `FlightID`, `FlightNumber`, `Airline`, `Destination`, `Status`

2. **Passenger_Information**
   - Columns: `PassengerID`, `FlightID`, `SeatNumber`

3. **Ticket_Information**
   - Columns: `TicketID`, `FlightID`, `BookingStatus`

These datasets were integrated, cleaned, and modeled in Power BI to extract insights and build interactive dashboards.

---

## ✅ Tasks and Deliverables

### 1. 🧹 Data Preparation and Cleaning *(10 Marks)*
- Used **Power Query** to:
  - Remove duplicates
  - Handle missing/null values
  - Format columns consistently
- **Deliverable:** Screenshot of Power Query Editor showing cleaned datasets

---

### 2. 🔗 Data Modeling *(10 Marks)*
- Created relationships using `FlightID` as the primary key
- Configured cardinality and cross-filter direction
- **Deliverable:** Screenshot of the Data Model view with defined relationships

---

### 3. 📌 Enhanced Data Insights *(10 Marks)*
- Added a **conditional column** to classify flights:
  - `"Best"` or `"To Be Improved"` based on flight status
- Used **"Column from Examples"** to extract flight numbers
- **Deliverable:** Screenshot of transformed data in Power Query

---

### 4. 📐 Calculations Using DAX *(10 Marks)*
- Created custom DAX measures to calculate:
  - Total passengers per flight
  - Total tickets booked
  - Filtered table showing only `"Best"` flights
- **Deliverable:** Screenshot of DAX calculations and visual output

---

### 5. 📈 Visualization and Interactive Features *(20 Marks)*
- Built visuals including:
  - Passenger count by airline
  - Ticket booking statuses
  - Flights by airline and destination
- Implemented **interactive filters**:
  - By destination and airline
  - Quick view filters
  - Airline-specific pages
- **Deliverable:** Screenshots of visuals and interactive report pages

---

### 6. 🖥️ Final Dashboard & Power BI Service *(20 Marks)*
- Designed a **comprehensive dashboard** showcasing all key metrics
- Configured:
  - **Row-Level Security (RLS)** for Airline A data
  - **Scheduled refresh** at 5 PM daily
- **Deliverables:** Screenshot of published dashboard and RLS configuration

---

## 🧠 Tools & Technologies
- **Microsoft Power BI**
  - Power Query
  - DAX Calculations
  - Data Modeling
  - Report & Dashboard Design
  - Row-Level Security
- **Excel** (initial review and prep)
- **Power BI Service** (for publishing and scheduling)

---

