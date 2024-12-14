# Canteen Ordering Platform

## Overview

The Canteen Ordering Platform is a web-based application that allows users to browse menu items, add them to a cart, place orders, and manage their account. The platform provides features like user authentication, menu browsing, cart management, order history, and a loyalty points system.

## Live Demo

👉 [Access the Live Website](https://larry-has.github.io/canteen-ordering-system)

## Features

### User Authentication
- User registration with email and password
- Login functionality
- Secure authentication using Firebase
- Dietary preference selection during registration

### Menu Management
- Dynamic menu item display
- Items categorized by type (Main, Sides, Drinks)
- Real-time menu fetched from Firestore

### Cart Functionality
- Add items to cart
- Remove items from cart
- Persistent cart storage using localStorage
- Real-time cart total calculation

### Order Management
- Place orders with a single click
- Order history tracking
- Order status display

### Loyalty Points System
- Automatic loyalty point tracking
- Points earned based on order total
- Points displayed in user profile
- Discount per 100 loyalty points

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Firebase Authentication
- **Database**: Firebase Firestore
- **Key Libraries**: 
  - Firebase SDK
  - Papaparse (CSV parsing)

## Screenshots

### Screenshot of database
![Database Screenshot](https://raw.githubusercontent.com/Larry-has/canteen-ordering-system/main/database_screenshot.png)

###Screenshot of website
![Website Screenshot](https://github.com/Larry-has/canteen-ordering-system/blob/main/website_screenshot.png)

## Technical Architecture

### Authentication Flow
1. User registers or logs in
2. Firebase Authentication verifies credentials
3. User profile data stored in Firestore
4. Authentication state changes trigger UI updates

### Data Management
- **Users Collection**: Stores user profiles, preferences, and loyalty points
- **Products Collection**: Stores menu items
- **Orders Collection**: Tracks user order history

## Setup and Installation

### Prerequisites
- Web browser
- Firebase account
- Internet connection

### Local Development
1. Clone the repository
2. Open `index.html` in a web browser
3. Ensure Firebase configuration is correctly set up

## Security Features
- Password validation during registration
- Secure Firebase authentication
- User-specific data access
- Loading overlay for async operations

## Mobile Responsiveness
- Responsive design
- Adapts to various screen sizes
- Touch-friendly interface

## Roadmap and Future Improvements
- [ ] Add more detailed dietary information
- [ ] Implement advanced search and filter for menu items
- [ ] Create admin dashboard for menu management
- [ ] Add more payment integration options
- [ ] Implement more advanced loyalty program features

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is open source. Please check the repository for specific licensing details.

## Contact
For any queries or support, please open an issue in the GitHub repository.

## Acknowledgments
- Firebase for authentication and database services
- Open-source community for various resources and inspiration
