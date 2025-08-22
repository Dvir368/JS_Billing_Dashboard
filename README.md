D&J Personal Credit Card Manager
A responsive, client-side web application for managing personal financial information, including monthly charges, credit card status, and transaction history. This project was developed for the "Internet Systems Development" course and demonstrates Object-Oriented Programming (OOP) principles in JavaScript. 



📜 Overview
This application provides users with a modern interface to manage their personal finances. Users can register, log in, and view their credit card information and transaction history in a clear and intuitive way. The system uses 

LocalStorage for data persistence between sessions and is built with a modular, class-based architecture to ensure the code is readable and scalable. 



✨ Core Features
User Management:

Secure user registration with validation for email format, password strength, and age (minimum 16 years old). 



User data, including passwords, is securely managed in LocalStorage. 


Session management ensures that unauthorized users are redirected to the login page. 


Credit Card Management:

Safely stores credit card numbers, displaying only the last four digits for privacy. 



Includes validation for card numbers and expiry dates. 



Users have the ability to 

lock their card, which is visually represented with a "Blocked" stamp animation. 


Transaction Tracking & Visualization:

A dynamic table displays a detailed list of past transactions. 



Interactive 

pie and bar charts (using Chart.js) provide a visual summary of monthly expenses by category. 

Smooth animations are used when loading graphs to enhance user experience. 

Dynamic and Responsive UI:

The entire application is fully responsive for both desktop and mobile screens. 

The interface is built dynamically with JavaScript, loading tables, graphs, and other elements in real-time. 


Profile Customization:

Users can update their profile information, including email, password, and credit card details. 

A unique feature allows users to 

change their monthly billing date (1-28), and the dashboard updates dynamically to reflect the new billing cycle. 



🛠️ Technologies & Concepts
Frontend: HTML5, CSS3, JavaScript (ES6)


Core Concepts: Object-Oriented Programming (OOP), DOM Manipulation, Event Handling


Data Storage: Browser LocalStorage 



Libraries: Chart.js for data visualization 


Development Practices: Modular code organized into classes like User, CreditCard, and StorageHandler. 
