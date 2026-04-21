<p align="center"> <img src="https://github.com/user-attachments/assets/b9a8038f-b394-478e-b18a-2b3d038bc600" width="850" alt="Indian Airlines Dashboard" style="border-radius: 16px;"/> </p>

# ✈️ Indian Airlines Ticket Price Analysis

This project focuses on analyzing airline ticket pricing patterns in India using data analytics and visualization techniques. It explores how various factors like travel class, duration, airline, and booking timing influence ticket prices.

## 🎯 Objective
- Analyze airline ticket pricing trends
- Identify key factors affecting ticket prices
- Perform exploratory data analysis (EDA)
- Understand customer booking behavior
- Help optimize travel planning and pricing strategies

## 📊 Problem Statement

In this project, we analyze structured airline data using data analytics techniques. The goal is to identify relationships between different variables such as:

- Class of travel
- Flight duration
- Airline
- Booking time

These insights help in understanding ticket pricing behavior and making better travel decisions.

## 📂 Dataset Description
| Feature | Description |
|---------|-------------|
| Airline |	Name of airline company |
| Flight |	Flight code |
| Source City	| Departure city |
| Destination City	| Arrival city |
| Departure Time	| Time of departure |
| Arrival Time	| Time of arrival |
| Stops |	Number of stops |
| Class |	Economy / Business |
| Duration	| Total travel time (hours) |
| Days Left	| Days before departure when booked |
| Price	| Ticket price |

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

## 🧑‍💻 Project Workflow
### 🔹 1. Data Collection
- Imported dataset using Pandas
- Explored dataset structure and unique values
### 🔹 2. Data Understanding
- Identified categorical and numerical features
- Analyzed airline, cities, timings, and travel classes
### 🔹 3. Exploratory Data Analysis (EDA)
- Visualized trends using plots and graphs
- Identified patterns and correlations

## 📈 Key Insights
### 📌 Flights by Airline
- Vistara has the highest number of flights
- Air India is the second highest
- SpiceJet has the least flights

### 📌 Ticket Price by Class
- Economy Class: ₹2,500 – ₹22,500
- Business Class: ₹25,000 – ₹95,000

### 📌 Ticket Availability
- Economy tickets are nearly 2× more available than Business class
- Only Air India and Vistara offer Business class

### 📌 Price vs Flight Duration
- Ticket price generally increases with duration
- More data points for Vistara and Air India due to higher flight frequency

### 📌 Airline vs Price (Class-Based)
- AirAsia offers cheapest Economy tickets
- Indigo, GO_FIRST, SpiceJet have similar pricing
- Vistara & Air India are more expensive (Full-Service Carriers)
- Business class:
- Vistara is more expensive than Air India
- Likely due to better service and comfort

### 📌 Booking Timing Impact
- Prices rise gradually until ~20 days before departure
- Prices increase sharply closer to departure
- Prices drop 1 day before flight (to fill seats)

### 📌 Duration vs Price Trend
- Relationship is non-linear
- Prices increase up to ~20 hours duration, then stabilize or drop

### 📌 Time-Based Pricing
- Cheapest flights:
- Late night departures
- Early morning arrivals
- Afternoon flights are moderately priced

### 📌 Source & Destination Insights
- Flights from Delhi are generally cheaper
- Due to better connectivity and higher frequency
- Chennai–Bangalore route is most expensive
- Hyderabad is costly overall

### 📌 Stops vs Price
- Non-stop flights: Cheapest
  1- stop flights: Moderate 
  2+ stops: Most expensive

### Exception:
- AirAsia shows minimal variation across stops

## 📊 Dashboard Highlights

The Power BI dashboard provides insights into:

✈️ Number of flights by airline
💰 Average ticket prices
⏱️ Flight duration comparison
📊 Economy vs Business pricing
🧭 City-wise price variations

<p align="center"> <img src="https://github.com/user-attachments/assets/48466519-d7e1-476d-9111-b5b163b21dcd" width="650" alt="Indian Airlines Dashboard" style="border-radius: 16px;"/> </p>

## 🔌 Use Cases
- Smart travel planning
- Ticket price prediction
- Airline pricing strategy
- Customer behavior analysis
- Route optimization

## 📁 Project Structure
```
Indian-Airlines-Analysis/
├── data/
│   ├── Indian Airlines.csv
├── notebooks/
│   ├── analysis.ipynb
├── visuals/
│   ├── dashboard.png
├── README.md
└── ...
```
## 🧠 Future Improvements
- Add machine learning models for price prediction
- Build interactive dashboards (Streamlit / Power BI)
- Integrate real-time flight APIs
- Perform demand forecasting

## 👩‍💻 Author

Made with ❤️ by Rakhi Yadav

## ✨ Tagline

### Turning flight data into smarter travel decisions ✈️📊
