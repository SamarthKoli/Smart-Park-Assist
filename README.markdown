# Smart Park Assist

## Overview

Smart Park Assist is a backend application built with Spring Boot, designed to simplify parking management through a RESTful API. It enables users to book parking spots, manage vehicles, add optional services (e.g., EV charging, car wash), and process payments. The system supports both vehicle owners and parking spot owners, providing a seamless way to reserve and manage parking spaces based on location, vehicle type, and availability.

Notice

Due to policy restrictions from Infosys Springboard, the source code for this project cannot be shared publicly in this repository. For inquiries, discussions, or further details about the project, please contact me at samarth.s.koli@gmail.com.


**Screenshot**: *Application Dashboard*  
![Application Dashboard](screenshots/application-dashboard.png)  
*Caption*: Dashboard view summarizing user bookings and available parking spots.

---

## Features

### 1. User Management
- Register new users with details like name, email, contact number, and user type (VehicleOwner or SpotOwner).
- View and update user profiles by ID.

**Screenshot**: *User Profile View*  
![User Profile View](screenshots/user-profile-view.png)  
*Caption*: Displaying user details, including name, contact, and user type.

### 2. Vehicle Management
- Add vehicles with registration number and type (e.g., Sedan, SUV).
- Retrieve vehicle details by ID or filter by vehicle type.

**Screenshot**: *Vehicle List*  
![Vehicle List](screenshots/vehicle-list.png)  
*Caption*: List of registered vehicles with their types and registration numbers.

### 3. Parking Spot Management
- Create and manage parking spots with details like name, type (e.g., Compact, Large), and EV charging availability.
- Deactivate or update spots.
- View all spots, owner-specific spots, or available spots by city and vehicle type.
- Filter booked spots by date range or EV charging availability.

**Screenshot**: *Spot Availability*  
![Spot Availability](screenshots/spot-availability.png)  
*Caption*: Displaying available parking spots in a selected city with EV charging options.

### 4. Booking Management
- Book a parking spot for a specific vehicle, including start/end dates and times.
- View bookings by ID, vehicle ID, user contact, spot ID, or date and location.
- Cancel or update existing bookings.


**Screenshot**: *Booking Dashboard*  
![Booking Dashboard](screenshots/booking-management.png)  
*Caption*: Navigation dashboard for booking service.


**Screenshot**: *Booking Confirmation*  
![Booking Confirmation](screenshots/booking-confirmation.png)  
*Caption*: Confirmation screen after successfully booking a parking spot.


### 5. Payment Processing
- Record payment details, including parking charges, add-on fees, discounts, and EV recharge amounts.
- (Planned) View payment history for users or bookings.


**Screenshot**: *Payment Summary*  
![Payment Summary](screenshots/payment-gateway.png)  
*Caption*: Payment gateway to proceed with payment of booking.



**Screenshot**: *Payment Summary*  
![Payment Summary](screenshots/payment-summary.png)  
*Caption*: Summary of charges, including parking and add-on fees.


