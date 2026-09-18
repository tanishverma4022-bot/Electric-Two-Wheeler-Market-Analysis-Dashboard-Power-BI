# Electric-Two-Wheeler-Market-Analysis-Dashboard-Power-BI
Power BI dashboard analyzing India's electric two-wheeler market — 15 models, 4 brands, sales, range, ratings &amp; state-wise adoption.
A Power BI capstone project analyzing India's electric two-wheeler (EV) market, covering 15 models across 4 brands (Ola, TVS, Bajaj, Ather), ~2M monthly sales units, an average real-world range of 122.42 km, and an average customer rating of 4.24/5.

📌 Problem Statement

EV companies had scattered data on sales, range, speed, and ratings, making it hard to:

Identify which states are adopting EVs fastest
Compare brands fairly on range, charging speed, and price
Determine which price segment (budget/mid/premium) performs best
Spot which models offer the best value for money

🧹 Data Cleaning
Removed duplicate model entries
Handled missing rating/speed values without dropping rows
Standardized inconsistent naming (e.g. "iQube ST" vs "iqubest", "UP" vs "Uttar Pradesh")
Converted text-stored numeric columns (battery, range, price) to proper number formats
Corrected unrealistic range/battery outliers
Unified inconsistent sales figure formats (e.g. "0.6M" vs raw numbers)

📊 Key Insights
Ola holds the largest market share (53.84%) and leads on overall value-for-money
TVS leads on customer ratings and charging speed
Maharashtra & Karnataka are adopting EVs fastest
Mid-range vehicles dominate sales over budget/premium segments
Real-world range increases steadily with battery capacity (75 km @ 2kWh → 180+ km @ 4.5kWh)
S1 Pro — fastest model | iQube ST — longest real-world range
🛠️ Tools Used

Power BI · Power Query · DAX

📁 Dashboard Pages
Overview (KPIs + State Map)
Range vs Battery Capacity
Charging & Range by Brand
Sales & Ratings by Brand
Value for Money Score
Price Segment Analysis
Top Speed & Range by Model
Market Share
