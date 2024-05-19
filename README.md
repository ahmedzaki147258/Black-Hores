# Black-Horse

## Overview
The E-commerce Management System is a comprehensive platform designed to manage various aspects of an online marketplace. It comprises five applications, each tailored to different user roles and functionalities. This README provides an overview of the API endpoints and functionalities available within each application.

## Applications

### 1. Customer Application
The Customer Application is designed to enhance the shopping experience for users. It includes the following features:
- **Account Management**: Users can create accounts, log in, and reset passwords via email.
- **Product Browsing**: Customers can view products and offers.
- **Purchasing**: Customers can buy products and offers, choosing between delivery or pickup from the supplier’s location.
- **Order Tracking**: Users can track the status of their orders.
- **Customer Support**: Real-time chat with customer service using Socket.io.
- **Notification**: Firebase Cloud Messaging (FCM) is utilized to send notifications to customers about order updates and promotions.

### 2. Vendor Application
The Vendor Application allows suppliers to manage their product offerings and interactions. Key features include:
- **Admin-Added Suppliers**: Vendors are added by the admin.
- **Product Management**: Vendors can select products listed by the admin and create offers.
- **Customer Support Interaction**: Vendors can initiate chats with customer support.
- **Notification**: FCM is used to notify vendors about new orders, inquiries, and other relevant updates.

### 3. Delivery Application
The Delivery Application facilitates the assignment and tracking of orders in real-time. Features include:
- **Order Assignment**: Orders are assigned to delivery personnel by vendors via real-time updates using Socket.io.
- **Order Status Updates**: Delivery personnel can update the status of orders as they are processed and delivered.
- **Notification**: FCM is employed to send delivery personnel notifications about new orders, route changes, and delivery updates.

### 4. Admin Application
The Admin Application provides comprehensive control and monitoring capabilities over the entire system. Features include:
- **User Management**: Admins can create and manage products, suppliers, and delivery personnel.
- **Order Tracking**: Admins can track the status and total costs of orders.
- **System Monitoring**: Full visibility into system operations and user activities.

### 5. Warehouse Application
The Warehouse Application is designed to manage inventory and related operations. Features include:
- **Warehouse Management**: Create and manage warehouse locations.
- **Inventory Management**: Purchase and store products, record wastage and returns from purchases and sales.
- **Sales and Employee Management**: Manage sales, add employees, and maintain supplier accounts.
- **Expense Tracking**: Record fixed and variable expenses related to warehouses, such as rent and utility bills.

## Conclusion
The E-commerce Management System is a robust platform that provides end-to-end management of an online marketplace. From customer interactions and vendor management to delivery logistics and warehouse operations, each application is designed to optimize the efficiency and effectiveness of the e-commerce process, with the added benefit of Firebase Cloud Messaging for seamless communication and notification delivery.
