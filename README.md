# Final-Assignment-Parking-Summer-Analytics-2025-
Urban Parking Summer Analytics 2025 


Urban parking spaces are a limited and highly demanded resource. Prices that remain static
 throughout the day can lead to inefficiencies — either overcrowding or underutilization.
 To improve utilization, dynamic pricing based on demand, competition, and real-time
 conditions is crucial.
 This project simulates such a system: participants will create an intelligent, data-driven
 pricing engine for 14 parking spaces using real-time data streams, basic economic theory,
 and ML models built from scratch, using only numpy, pandas libraries


 Data Description
 You are given data collected from 14 urban parking spaces over 73 days, sampled at
 18 time points per day with 30 minutes of time difference (from 8:00 AM to 4:30
 PMthe same day).


Resources for Real Time Applications
 1. Pathway. From Jupyter to Deploy. Retrieved from: https://pathway.com/developers/
 user-guide/deployment/from-jupyter-to-deploy/
 2. Pathway. First Real-Time App with Pathway. Retrieved from: https://pathway.com/
 developers/user-guide/introduction/first_realtime_app_with_pathway/


Goal :-

Build a dynamic pricing engine for 14 parking lots based on real-time factors using only NumPy, Pandas, and Pathway. The solution involves 3 models:

Model 1 (Baseline Linear): Price increases linearly with occupancy.

Model 2 (Demand-Based): Price based on a demand function using occupancy, queue, traffic, special days, and vehicle type.

Model 3 (Optional - Competitive): Includes geographic proximity and competitor price comparison.
