# Hotel Booking Dataset Analysis

## Overview

This dataset contains booking information for city hotels and resort hotels. It includes details such as booking dates, length of stay, number of guests, and more. The dataset can be used to analyze booking patterns, cancellation rates, and other factors related to hotel bookings.

## Dataset Description

- `hotel`: Type of hotel (city hotel or resort hotel)
- `is_cancelled`: Whether the booking was cancelled (1 for cancelled, 0 for not cancelled)
- `lead_time`: Number of days between booking and arrival
- `arrival_date_year`: Year of arrival date
- `arrival_date_month`: Month of arrival date
- `arrival_date_week_number`: Week number of arrival date
- `arrival_date_day_of_month`: Day of arrival date
- `stays_in_weekend_nights`: Number of weekend nights booked
- `stays_in_week_nights`: Number of week nights booked
- `adults`: Number of adults
- `children`: Number of children
- `babies`: Number of babies
- `meal`: Type of meal booked
- `country`: Country of origin
- `market_segment`: Market segment designation
- `distribution_channel`: Booking distribution channel
- `is_repeated_guest`: Whether the booking is from a repeated guest (1 for repeated guest, 0 for new guest)
- `previous_cancellations`: Number of previous booking cancellations
- `previous_bookings_not_canceled`: Number of previous bookings not canceled
- `reserved_room_type`: Code of room type reserved
- `assigned_room_type`: Code for the type of room assigned
- `booking_changes`: Number of changes made to the booking
- `deposit_type`: Type of deposit made
- `agent`: ID of the travel agency
- `company`: ID of the company/entity that made the booking
- `days_in_waiting_list`: Number of days the booking was in the waiting list
- `customer_type`: Type of booking
- `adr`: Average daily rate
- `required_car_parking_spaces`: Number of parking spaces required
- `total_of_special_requests`: Number of special requests made by the customer
- `reservation_status`: Reservation status (canceled, check-out, no-show)
- `reservation_status_date`: Date at which the last status was set

## Analysis Goals

- Explore booking patterns and trends
- Analyze cancellation rates and factors influencing cancellations
- Identify key factors affecting booking decisions
- Predict future bookings or cancellations

## Tools Used

- Python
- pandas
- matplotlib
- seaborn

## Author

Gunjan Joshi
gunjan.joshi513@gmail.com
