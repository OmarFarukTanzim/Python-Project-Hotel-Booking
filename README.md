Problem Statement:<br>
In the past few years, both the City Hotel and Resort Hotel have experienced significant increases in their cancellation rates. As a result, both hotels are currently facing a range of challenges, such as reduced revenue and underutilized hotel rooms.<br>Therefore, the top priority for both hotels is to reduce their cancellation rates, which will enhance their efficiency in generating revenue. This report focuses on the analysis of hotel booking cancellations and other factors that do not directly impact their business and annual revenue generation.<br>

Basic Description About Dataset:<br>
This dataset contains 119390 observations for a City Hotel and a Resort Hotel. Each observation represents a hotel booking between the 1st of July 2015 and 31st of August 2017, including booking that effectively arrived and booking that were canceled.<br>

Columns:<br>
-- hotel: One of the hotels is a resort hotel and the other is a city hotel.<br>
-- is_canceled lead_time: Value indicating if the booking was canceled (1) or not (0).<br>
-- arrival_date_year: Year of arrival date.<br>
-- arrival_date_month: Month of arrival date with 12 categories: “January” to “December”.<br>
-- arrival_date_week_number: Week number of the arrival date.<br>
-- arrival_date_day_of_month: Day of the month of the arrival date.<br>
-- stays_in_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.<br>
-- stays_in_week_nights: Number of week nights (Monday to Friday) the guest stayed.<br>
-- adults: Number of adults<br>
-- children: Number of Childern<br>
-- babies: Number of Babies<br>
-- meal: BB – Bed & Breakfast<br>
-- country: Country of origin.<br>
-- market_segment: Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”<br>
-- distribution_channel: Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”<br>
-- is_repeated_guest: Value indicating if the booking name was from a repeated guest (1) or not (0)<br>
-- previous_cancellations: Number of previous bookings that were cancelled by the customer prior to the current booking<br>
-- previous_bookings_not_canceled: Number of previous bookings not cancelled by the customer prior to the current booking<br>
-- reserved_room_type: Code of room type reserved. Code is presented instead of designation for anonymity reasons.<br>
-- assigned_room_type: Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request.<br> Code is presented instead of designation for nonymity reasons<br>
-- booking_changes: Number of changes/amendments made to the booking.<br>
-- deposit_type: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.<br>
-- agent: ID of the travel agency that made the booking<br>
-- company: ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons<br>
-- days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed to the customer<br>
-- customer_type: Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; <br>Transient-party – when the booking is transient, but is associated to at least other transient booking<br>
-- adr: Average Daily Rate (Calculated by dividing the sum of all lodging transactions by the total number of staying nights)<br>
-- required_car_parking_spaces: Number of car parking spaces required by the customer<br>
-- total_of_special_requests: Number of special requests made by the customer (e.g. twin bed or high floor)<br>
-- reservation_status: Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why<br>
-- reservation_status_date: Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel<br>
-- name: Name of the Guest (Not Real)<br>
-- email: Email (Not Real)<br>
-- phone-number: Phone number (not real)<br>

Research Questions:<br>
-- What are the variables that effect hotel reservation cancellations?<br>
-- How can we make hotel reservations cancellation better?<br>
-- How all hotels be assisted in making pricing and promotional decisions?<br>
