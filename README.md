# Goibibo-
***Manual Testing of Goibibo – A Travel Booking Platform***

The Goibibo platform is a popular online travel and hotel booking website that allows users to search, compare, and book flights, hotels, and other travel-related services. As a crucial part of the online travel industry, Goibibo aims to deliver a seamless, efficient, and user-friendly experience for its customers.

## OVERVIEW
The goal of this project is to thoroughly test the Goibibo platform, ensuring that all key functionalities—such as flight and hotel bookings, payments, cancellations, and user authentication—are working seamlessly. By employing a range of testing techniques, including both structured and exploratory testing, the objective is to identify defects across functionality, performance, usability, and security.

## UNDERSTANDING AND EXPLOREING THE FUNTIONALITIES OF GOIBIBO
To perform effective testing, it’s important to break down and understand the core functionalities of the Goibibo platform. This will help in designing test cases that cover all the critical workflows, ensuring that the system works as expected from a user’s perspective. Here's an overview of the key features and functionalities of Goibibo that need to be explored.

### 1. User Authentication and Login 
Users should be able to register for a new account by providing necessary details (email, mobile number, password).
Login functionality should allow users to access their account using correct credentials (email/phone number and password).
Social media logins (e.g., Google, Facebook) should also work for easy account creation
### 2. Search and Filters
The search feature allows users to find flights, hotels, and other services based on input parameters.
Filters help users narrow down results based on price, duration, ratings, airlines, or amenities.
### 3. Flight Booking 
Users should be able to search flights by entering details like origin, destination, travel dates, number of passengers, and class (economy/business).
Filters should allow sorting based on price, duration, airlines, and timings.
Once the user selects a flight, they should be able to proceed to the booking screen, entering passenger details and payment info.
### 4. Hotel Booking
Similar to flights, users should be able to search for hotels based on location, check-in/check-out dates, number of rooms, and type of accommodation.
Hotel details should include room types, price, amenities, and guest ratings.
Users should be able to book rooms, providing guest information and making payments.
Search and filter functionality for hotel availability and pricing.
Room selection and booking process, including input validation and payment gateway.
Ensuring cancellation terms are clearly displayed and functional.
### 5.Cancellations and Refunds
Users should be able to cancel bookings (flight, hotel, etc.) and receive the applicable refund based on the cancellation policy.
Testing for correct processing of cancellations.
Ensuring refunds are handled properly (amount calculation, processing time).
Ensuring the system informs the user about cancellation policies upfront.
### 6. Notifications and Alerts
The platform should send timely notifications for booking confirmations, cancellations, payment receipts, and reminders.
Timeliness and accuracy of alerts.
### 7. System Performance
The platform should load quickly and handle multiple user requests simultaneously.
Stress testing and load testing will help identify any performance bottlenecks.
Page load time during peak usage.
Scalability for handling multiple concurrent bookings.
### 8. Multi-Currency and Multi-Language Support (Globalization Testing)
Goibibo should support different currencies based on the user’s region (INR, USD, etc.).
The platform should also support multiple languages for users from different countries.
Currency conversion and accuracy.
Language switching and text alignment for different languages.

# SCOPE OF TESTING
The platform will be tested for various features, including:

•	**User Authentication**: Sign up, login, and profile management.

•	**Search Functionality**: Flight and hotel search with filters.

•	**Flight Booking**: Search, filter, select, and book flights.

•	**Hotel Booking**: Search, filter, select, and book hotels.

•	**Payment Gateway**: Payment processing, transaction success/failure.

•	**Cancellations and Refunds**: Booking cancellations and refund handling.

•	**User Profile Management**: Profile details, Profile updates, View booking history.

•	**Notifications & Alerts**: Booking confirmation notifications (email, SMS), Cancellation or modification notifications, Payment failure alerts Special offer/discount notifications

# TESTING TYPES
- [Smoke Testing](#SmokeTesting)
- [Functional Testing](#FunctionalTesting)
- [Usability Testing](#UsabilityTesting)
- [Performance Testing](#PerformanceTesting)
- [Compatibility Testing](#CompatibilityTesting)
- [Exploratory Testing](#ExploratoryTesting)
- [Regression Testing](#RegressionTesting)
- [Globalization Testing](#GlobalizationTesting)

# Test Environment
- **Devices** :Desktop (Windows, macOS), Mobile (Android, iOS),Tablet (Android, iOS).
- **Browsers**:Chrome, Firefox, Safari, Edge.
- **Network Conditions***:Wi-Fi,3G, 4G.
- **Testing Tools Test Case Management**: Excel.
- **Bug Tracking**: Jira.

# Risk Management And Mitigation Plan
- **Frequent UI/UX changes during testing** :	Regular communication with the development team for updates.
- **Third-party service/API failures**: Develop backup test cases for scenarios without third-party dependencies.
- **Network issues during payment testing** : Simulate different network conditions (e.g., weak Wi-Fi, 4G) during tests.
- **Time limitations for testing all scenarios**: Prioritize high-impact features for testing and conduct smoke tests early.

# Test Execution Plan
The testing will be executed based on the test cases developed. Each feature will be tested using a combination of predefined test scenarios and exploratory tests. Bugs will be logged immediately and will be verified after fixes are implemented.

# Exit Criteria
Testing will be considered complete when:
- All critical test cases have been executed.
- All major bugs are fixed and verified.
- Test coverage is complete with no high-priority defects remaining.
  
The test summary report is delivered with detailed findings and recommendations.

# Conclusion
This test plan outlines a comprehensive approach to testing the Goibibo platform, ensuring its key features and functionality work as expected. By combining multiple testing types, including functional, performance, compatibility, exploratory, and regression testing, we aim to uncover defects that could impact user experience and platform reliability.













