Hotel Booking Demand
Project Proposal | Dataset: Hotel Booking Demand (Kaggle) | Tools: Python, Pandas, Matplotlib
Submitted by: Ayush Sheldia(IU2441230475) and Mahit Khant(IU2441230539) | Date: 09  October 2026 | Course/Program: B.Tech – CSE-F
1. Project Definition
This project cleans and analyses hotel booking data to find out who books, when they book, and why bookings get cancelled. It delivers a cleaned dataset, at least six charts, and a short insights report.
2. Dataset and Use Case
Dataset: Hotel Booking Demand on Kaggle: about 119,390 bookings and 32 columns from a City Hotel and a Resort Hotel in Portugal (2015 to 2017). The key column is is_canceled.
Use case: hotel managers can use the results to reduce cancellations, set seasonal prices, and target the best customer segments.
Data cleaning steps
•	Missing values: fill agent and children with 0, fill country with "Unknown", drop company.
•	Duplicates: find and remove repeated rows.
•	Data types: convert dates to datetime and ID columns to categories.
•	Outliers: remove negative or extreme adr values and bookings with zero guests, using the IQR rule.
3. Visualizations and Outcomes
Only line charts and bar charts will be used. Line charts show change over time, and bar charts compare categories. Each chart gets a title, labelled axes and a one-line takeaway.
#	Chart type	What it shows
1	Bar	Bookings by hotel, split into cancelled and not cancelled
2	Line	Number of bookings per month for each hotel
3	Line	Average daily rate (ADR) per month
4	Bar	Cancellation rate by lead time group (0-30, 31-90, 91-180, 180+ days)
5	Bar	Cancellation rate by market segment
6	Bar	Top 10 guest countries by number of bookings
7	Bar	Cancellation rate by customer type
4. Python Libraries and Tools
•	Pandas and NumPy: data cleaning and calculations
•	Matplotlib : charts
•	Google Colab: running the code
•	Git and GitHub: hosting code and documentation
5. GitHub Link and Documentation
Repository: https://github.com/ayushsheladia/Hotel-Booking-Demand-Project.git
The repository will contain the raw and cleaned data, the cleaning and visualization notebooks, exported charts, the insights report, requirements.txt, and a README explaining the project and how to run it.
6. Short Insights Report
After the charts are made, a short report will cover four points:
1.	Data quality: what was wrong with the raw data and how it was fixed, with row counts before and after cleaning.
2.	Key findings: the 4 to 5 most important patterns, each linked to one chart.
3.	Recommendations: for example, ask for deposits on long lead time bookings, run summer price campaigns, and focus on segments with fewer cancellations.
4.	Limitations: the data covers only two hotels in Portugal over two years, and the analysis describes patterns without proving causes.
7. Conclusion
This project covers the full analysis workflow on a real hotel dataset. The result will be a clean dataset, seven line and bar charts, a short insights report, and a GitHub repository that anyone can reproduce.

