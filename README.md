# Assignment: Architectural Decisions


Student Name: DONGYUN (DAVID) KIM


Student ID: 000737829
# Scenario3
## I chose **SCENARIO 3** for the assignment.
You are a mobile app development team tasked with creating a new app for a client. 


The app will allow users to order food from local restaurants for delivery or pickup. Users must be able to create an account and save their payment information for future orders. The app must have a user-friendly interface that is easy to navigate and allows for seamless ordering.
| Requirements  | Architecture |
| ------------- | ------------- |
| <ins>User Registration and Authentication:</ins> Users should be able to create an account and securely log in to access their profile and order history. | <ins>Front-end:</ins>The front-end of the app will be developed using a cross-platform framework like React Native to ensure compatibility with both iOS and Android. |
| <ins>Restaurant and Menu Information:</ins> The app should provide up to date often restaurant listings and menus, including detailed information on available dishes and prices so customers and restaurant have more choices and revenue.  | <ins>Back-end:</ins> The back-end of the app will be built using Node.js for its scalability and efficiency (connects with React Native). It will communicate with a database to handle user profiles, orders, and payment information.  |
| <ins>Order Placement and Customization:</ins> Users should be able to place food orders, customize their orders (e.g., special instructions or allergy notice), and select delivery or pickup options.  | <ins>Database:</ins> Data, including user profiles, restaurant information, menus, and orders, will be stored in a relational database management system (RDBMS) for data integrity and consistency. (or MongoDB can be an option too) |
| <ins>Payment Processing:</ins> The app must support various payment methods, including credit/debit cards, mobile wallets, and cash on delivery, while ensuring secure and seamless transactions. | <ins>Payment Gateway Integration:</ins> The app will integrate with one or more secure payment gateways, such as Stripe or PayPal, to facilitate payment processing.  |
| <ins>Order Tracking:</ins> Users should be able to track the status and delivery time of their orders in real-time. | <ins>Location Services:</ins> To provide accurate restaurant recommendations and order tracking, the app will utilize location-based services or GPS capabilities for drivers’ and customers’ convenience. |
| <ins>Payment Information Management:</ins> Users should have the option to manage their profiles and information, save multiple delivery addresses, and securely store payment information for future orders. | <ins>Review and Rating System:</ins> User-generated content, such as reviews and ratings, will be managed through a database and API for seamless display and moderation.|
| <ins>Reviews and Ratings:</ins> Users should be able to leave reviews and ratings for restaurants and food items to help other users make informed and better choices. | <ins>Notification Service:</ins> Push notifications will be handled through a reliable push notification service provider that supports both iOS and Android platforms.|
| <ins>Notifications/Real-time communications:</ins> The app should provide push notifications to inform users about order confirmations, delivery updates, and promotional offers.| <ins>Machine learning:</ins> Machine learning algorithms will be used to analyze user preferences and ordering history, providing personalized recommendations for food choices and promotions.|

**Decisions and Rational** have been confirmed <ins>BASED ON THE REQUIREMNTS & ARCHITECTURE FROM Business requirements and user needs.</ins>


# <Architectural Decisions>
**Title:** ADR 1: Mobile App Architecture for Food Ordering and Payment Processing ZERO to LAUNCH
## Native, Web, or Hybrid App:

<ins>Decision:</ins> The app will be developed as a native mobile application.

<ins>Rationale:</ins> Native apps provide the best user experience, as they are optimized for each platform (iOS and Android) and can take full advantage of device features and performance. Given the user-centric nature of food ordering, a native app is the most appropriate choice to deliver a seamless and responsive experience. Also, users/customers mostly use mobile to order their foods.

