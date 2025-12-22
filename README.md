# Hotel-Booking-Analysis

This project applies data science techniques to analyse booking behaviour in the hospitality industry using a real-world dataset of hotel reservations. The analysis compares City Hotels and Resort Hotels to uncover trends in cancellations, revenue generation, customer retention, and booking channels.



### Dataset

The dataset (hotel_bookings.csv) contains detailed booking records, including:

* Hotel type (City / Resort)

* Arrival dates and lead time

* Booking cancellations

* Average Daily Rate (ADR)

* Customer type and repeat guest indicator

* Distribution channel information

A full feature description is provided in Data Description.pdf.

### Methods & Tools

* Pandas – data cleaning and aggregation

* NumPy – numerical operations

* Matplotlib – exploratory data visualisation

* Jupyter Notebook – exploratory data analysis 

### Analytical Approach
1. Exploratory Data Analysis (EDA)

* Cleaned and aggregated booking data by hotel type and time period

* Identified missing values and structured categorical variables

* Grouped monthly booking behaviour for temporal analysis

2. Cancellation Behaviour Analysis

* Analysed monthly cancellation trends for City and Resort Hotels

* City Hotels show consistently higher cancellation volumes

* Seasonal patterns suggest demand-driven volatility in urban bookings

3. Revenue Analysis (ADR)

* Aggregated Average Daily Rate (ADR) to estimate revenue contribution

* City Hotels generate substantially higher total ADR than Resort Hotels

* Indicates stronger pricing power and occupancy in city-based hotels


### Visual Outputs

The project includes:

* Time series line plots for cancellations and repeated guests

* Bar chart comparing total ADR by hotel type

* Pie charts showing distribution channel breakdowns

### Final Conclusion/Insights
* Urban hotels face higher demand volatility but stronger revenue

* Resort hotels benefit from higher customer retention

* Distribution channels heavily influence booking patterns

* Data-driven segmentation can inform pricing and marketing strategy