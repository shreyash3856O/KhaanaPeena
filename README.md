# KhaanaPeena – Food Ordering Application (Frontend Assignment)

## Candidate Note

This project was developed as part of the LenDenClub frontend assignment.
While the original brief targets native Android (Kotlin) or iOS (Swift), I chose to implement the application as a web-based frontend using React, HTML, CSS, and JavaScript to demonstrate core product logic, UI/UX thinking, state management, and clean architecture concepts that are transferable across platforms.

All mandatory functional requirements outlined in the assignment have been implemented and mapped clearly below.

## Why LenDenClub

LenDenClub’s focus on building impactful fintech products and empowering the next generation strongly resonates with my career goals. I am particularly inspired by the company’s emphasis on ownership, innovation, and building technology that solves real-world problems at scale.

Through this assignment, I aimed to showcase not just technical implementation, but also attention to user experience, clean structure, and real product flow—qualities that align with LenDenClub’s engineering culture.

## Assignment Objective Alignment

Assignment Goal:
Develop a Food Ordering App with restaurant listing, menu viewing, cart management, and checkout flow.

Implementation Platform:
Web application using React (component-based architecture)

## Implemented Features (Mapped to Mandatory Tasks)

### 1. Home Screen – Restaurant Listing

Implemented features:

* Displays a list of restaurants with restaurant name, image, and cuisine type
* Search bar to dynamically filter restaurants by name
* Popular food items with quick add-to-cart functionality

This screen acts as the entry point to the application and allows users to discover restaurants easily.

### 2. Restaurant Menu Screen

Implemented features:

* Navigates to a dedicated menu page when a restaurant is selected
* Displays food items with name, description, price, and image
* Users can add menu items to the cart

Menu data is structured per restaurant to simulate a real-world food ordering flow.

### 3. Cart Screen

Implemented features:

* Displays all items added to the cart with item name, quantity, and individual price
* Shows total cart value
* Allows users to increase or decrease item quantity
* Allows removal of items from the cart
* “Proceed to Checkout” button for navigation

Cart state persists across pages using browser localStorage.

### 4. Checkout Screen

Implemented features:

* Input fields for name, email, and address
* Input validation for empty or invalid values
* “Place Order” button
* Success confirmation message after order placement
* Order details saved and visible in Order History

## Optional Tasks

* API integration was not implemented
* Static and mock data were used to focus on UI flow, state management, and core logic
* This decision was made to prioritize completion of all mandatory tasks within scope

## Architecture & Code Structure

* Component-based architecture using React
* Clear separation of concerns between UI rendering and business logic
* Persistent state handled using localStorage
* Modular and readable code structure

While not using MVVM or MVC explicitly due to the web platform, similar principles such as separation of logic and UI responsibility were followed.

## Technologies Used

* HTML
* CSS
* JavaScript
* React

## How to Build and Run

1. Clone or download the repository
2. Open `index.html` in a modern web browser
3. Navigate through the app using the UI

No additional setup or dependencies are required.

## Project Structure

```
KhaanaPeena/
├── index.html        Home screen
├── menu.html         Restaurant menu screen
├── cart.html         Cart management
├── checkout.html     Checkout screen
├── orders.html       Order history
└── README.md         Project documentation
```

## Error Handling & Edge Cases

* Empty cart handling
* Quantity limits to prevent invalid values
* Input validation on checkout fields
* Graceful UI behavior for missing data

## Assumptions & Limitations

* Implemented as a web application instead of native mobile
* Static or mock data used instead of APIs
* No authentication or payment gateway integration

These decisions were made to focus on core functional requirements and UI flow clarity.

## Future Improvements

* Backend and API integration
* Real-time order tracking
* Authentication and user profiles
* Payment gateway support
* Migration to native Android or iOS if required

## Submission Notes

* All mandatory tasks have been completed
* Project demonstrates an end-to-end food ordering flow
* Code is modular, readable, and well-structured
* Suitable for extension into a native or full-stack application
