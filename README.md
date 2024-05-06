## Overview
The Store Management System is a Java-based application designed to facilitate the management of a store's inventory, orders, and shipping operations. It employs various design patterns and adheres to solid principles to ensure flexibility, scalability, and maintainability.

This is my final project for Object Oriented Design course, in Afeka - the academic college of Engineering in Tel Aviv.

## Features
1. **Facade Design Pattern:** The core functionalities of the system are encapsulated within a StoreManagement class, serving as the facade for store operations.
2. **Command Design Pattern:** Operations such as adding orders to products, adding products to the store, and updating stock utilize the command pattern for encapsulating requests as objects.
3. **Factory Method Design Pattern:** Creation of different types of orders and products is facilitated through factory method patterns, allowing for flexible object creation.
4. **Observer Design Pattern:** Shipping company instances observe changes in supported countries and taxes, ensuring dynamic updates in shipping fee calculations.
5. **Singleton Design Pattern:** The ShippingManagement class is implemented as a singleton to ensure a single instance manages supported shipping countries and shipping company observers.

## Usage
1. Upon running the program, follow the on-screen prompts to interact with the store management system.
2. Use commands such as adding orders/products, updating stock, and managing shipping details to perform store operations.
3. Explore different functionalities and observe how design patterns and solid principles are implemented throughout the system.
