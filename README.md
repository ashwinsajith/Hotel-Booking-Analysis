# Hotel Cancellation Predictive Analysis

This project applies data science and machine learning techniques to analyse and predict cancellation behaviour in the hospitality industry using a real-world dataset of hotel reservations. The analysis compares City Hotels and Resort Hotels to reveal trends in cancellations, revenue generation, customer retention, and booking channels. It uses a Random Forest Classifier to tackle business risks with overbooking.

### Project Highlights

* Predictive Power: Developed a model achieving 86.24% Accuracy and an 80.1% F1-Score.

* Business View: Optimised for 86.5% Precision over Recall (74.6%) to specifically minimise "False Positives", reducing the risk of overbooking scenarios.

* Scale: Processed and analysed a comprehensive dataset of over 115,000 hotel reservations.


### Dataset

The dataset (hotel_bookings.csv) contains detailed booking records, including:

* Hotel type (City / Resort)

* Arrival dates and lead time

* Booking cancellations

* Average Daily Rate (ADR)

* Customer type and repeat guest indicator

* Distribution channel information

A full feature description is provided in DataDescription.pdf.

### Methods & Tools

* Pandas - Data cleaning and Aggregation

* NumPy - Numerical operations

* Matplotlib - Exploratory data visualisation
* Scikit-learn - Machine learning implementation (Random Forest)

* Jupyter Notebook - Exploratory Data Analysis 


### Analytical Approach
1. Exploratory Data Analysis (EDA):

    * Cleaned and aggregated booking data by hotel type (City vs. Resort).

    * Identified seasonal patterns suggesting demand-driven volatility in urban bookings.

    * Analysed revenue through Average Daily Rate (ADR) to estimate total revenue contributions.

2. Predictive Modelling (Machine Learning):

    * Model Selection: Implemented a Random Forest Classifier to handle complex, non-linear relationships in booking data.

    * Feature Engineering: Utilised one-hot encoding and structured categorical variables to prepare the 115k+ record dataset for training.

    * Optimisation Strategy: Tuned the model to prioritise Precision (86.5%), ensuring that predictions of "No Cancellation" were highly reliable to protect the guest experience and hotel reputation.


### Visual Outputs

The project includes:

* Performance Metrics: Confusion matrices and classification reports documenting the 80.1% F1-Score.

* Trend Analysis: Time series line plots for cancellations and bar charts comparing total ADR by hotel type.

* Retention Insights: Identified that while City Hotels face higher demand volatility, Resort Hotels benefit from higher customer retention rates.


### Final Conclusion

The integration of predictive modeling allows for data-driven insights that can directly inform pricing and marketing strategies. Hotels can better manage occupancy levels and revenue generation while significantly reducing the operational costs of overbooking. The ability to maintain an 80.1% F1-Score across a massive 115,000+ record dataset proves the model is robust enough for real-world deployment. Ultimately, this project demonstrates how Scikit-learn and Random Forest architectures can be tuned not just for the highest number, but for the safest business outcome.

