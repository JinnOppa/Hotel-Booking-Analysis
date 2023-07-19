# Hotel Booking Data Analysis

This project aims to perform an exploratory data analysis (EDA) on a hotel booking dataset to gain insights into various aspects of the bookings, cancellations, customer behavior, pricing, and room types.

## Dataset Source

The dataset used for this analysis is obtained from Kaggle. You can find the dataset on the Kaggle website at the following link: [Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand).

## What's in the Dataset?

The dataset contains information about hotel bookings and includes the following details:
- `hotel`: Hotel type (Resort Hotel or City Hotel)
- `is_canceled`: Binary variable indicating if the booking was canceled (1) or not (0)
- `lead_time`: Number of days between booking date and arrival date
- `arrival_date_year`: Year of arrival date
- `arrival_date_month`: Month of arrival date
- `arrival_date_week_number`: Week number of the year for the arrival date
- `arrival_date_day_of_month`: Day of the month for the arrival date
- `stays_in_weekend_nights`: Number of weekend nights (Saturday or Sunday) the guest stayed
- `stays_in_week_nights`: Number of weeknights (Monday to Friday) the guest stayed
- `adults`: Number of adults
- `children`: Number of children
- `babies`: Number of babies
- `meal`: Type of meal booked (e.g., Bed & Breakfast, Full board, etc.)
- `country`: Country of origin of the guest
- `market_segment`: Market segment designation (e.g., Online TA, Offline TA/TO, etc.)
- `distribution_channel`: Booking distribution channel (e.g., Direct, Corporate, etc.)
- `is_repeated_guest`: Binary variable indicating if the guest is a repeated guest (1) or not (0)
- `previous_cancellations`: Number of previous booking cancellations by the guest
- `previous_bookings_not_canceled`: Number of previous bookings not canceled by the guest
- `reserved_room_type`: Code for the type of room reserved
- `assigned_room_type`: Code for the type of room assigned
- `booking_changes`: Number of changes made to the booking
- `deposit_type`: Type of deposit made for the booking (Non-refundable, Refundable, No Deposit)
- `days_in_waiting_list`: Number of days the booking was in the waiting list
- `customer_type`: Type of booking (Transient, Contract, Group, Transient-Party)
- `adr`: Average Daily Rate (Price per room, not per person)
- `required_car_parking_spaces`: Number of car parking spaces required by the guest
- `total_of_special_requests`: Number of special requests made by the guest
- `reservation_status`: Current status of the reservation (e.g., Check-Out, Canceled, No-Show)
- `reservation_status_date`: Date of the last reservation status update

## What We'll Do

In this project, I'll perform data analysis and visualization to gain insights into different aspects of hotel bookings. Here's what I'll cover:

1. **Data Exploration**: Load the dataset, examine its size, and check for missing values.
2. **Data Preprocessing**: Handle missing values and perform feature engineering.
3. **Correlation Analysis**: Visualize the correlation between numerical features.
4. **Cancelation Analysis**: Analyze the cancelation rate by hotel and market segment.
5. **Customer Analysis**: Explore customer types, number of adults, children, and babies, and customer behavior based on market segment and hotel type.
6. **Pricing Analysis**: Examine the average daily rate (ADR) by hotel and the distribution of average total price per booking.
7. **Room Analysis**: Analyze the room type distribution and the relationship between reserved and assigned room types.
8. **Behavior Analysis**: Investigate the distribution of bookings with different deposit types, the number of special requests, and the car parking spaces requirement.
9. **Predictive Model**: Build time series forecasting models for cancelations and future bookings.

## Requirements

- Python 3
- Libraries: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn

## How to Use

To explore the analysis and visualizations in this project, follow these steps:

1. Clone the repository to your local machine using `git clone https://github.com/yourusername/hotel-booking-analysis.git`
2. Install the required libraries by running `pip install -r requirements.txt`.
3. Open the Jupyter Notebook `hotel_booking_analysis.ipynb`.
4. Run the notebook cell by cell to perform the data analysis and visualize the results.

Feel free to explore the notebook, and if you have any questions or suggestions, don't hesitate to reach out. Happy analyzing!