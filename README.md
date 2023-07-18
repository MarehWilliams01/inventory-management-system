# Inventory Management System

## Overview

The Inventory Management System is a Java-based project designed to assist stores and warehouses in efficiently managing their product inventory and tracking sales. The system utilizes a MySQL database for data persistence, and different categories of products are stored using various data structures.

### Product Categories

The system organizes products into the following categories:

**1. Stack Categories:**

- Beverages: Includes coffee/tea, juice, and soda.
- Bread/Bakery: Includes sandwich loaves, dinner rolls, tortillas, and bagels.
- Canned/Jarred Goods: Includes vegetables, spaghetti sauce, and ketchup.
- Dairy: Includes cheeses, eggs, milk, yogurt, and butter.

**2. Queue Categories:**

- Dry/Baking Goods: Includes cereals, flour, sugar, pasta, and mixes.
- Frozen Foods: Includes waffles, vegetables, individual meals, and ice cream.
- Meat: Includes lunch meat, poultry, beef, and pork.

**3. List Categories:**

- Produce: Includes fruits and vegetables.
- Cleaners: Includes all-purpose cleaners, laundry detergent, and dishwashing liquid/detergent.
- Paper Goods: Includes paper towels, toilet paper, aluminum foil, and sandwich bags.
- Personal Care: Includes shampoo, soap, hand soap, and shaving cream.

## Features

The Super Store Inventory Management System provides the following features:

- Adding products: Allows users to add new products to the inventory.
- Editing product details: Enables users to modify product information such as name, price, quantity, etc.
- Removing products: Allows users to remove products from the inventory.
- Adding vendors: Allows users to add information about vendors supplying the products.
- Editing vendor details: Enables users to modify vendor information such as name, contact details, etc.
- Removing vendors: Allows users to remove vendors from the system.
- Creating orders/sales: Enables users to create orders and record sales transactions.
- Viewing orders/sales: Allows users to view and track orders and sales made.
- Efficient management of products based on their corresponding data structures.

## Project Setup

### Requirements

To set up the project, you'll need the following:

- MySQL Server
- Eclipse Java IDE with E(fx)clipse plugin
- JDK 18
- JavaFX 18 SDK

### Installation

Follow these steps to install and configure the project:

1. Download and install MySQL Server and ensure it is running. You can refer to the [Getting Started with MySQL](https://dev.mysql.com/doc/mysql-getting-started/en/) guide for assistance.
2. Open the `.env` file located in the project's root directory and provide the necessary database configuration variables based on your local setup.
3. Import the project into Eclipse as a Java project using the provided `.project` file.
4. Install the E(fx)clipse plugin from the Eclipse Marketplace to support JavaFX development.
5. Configure your Eclipse project for JavaFX by following the instructions outlined in the [Getting Started with JavaFX](https://openjfx.io/openjfx-docs/#IDE-Eclipse) documentation. If you are using a different IDE, you can refer to the relevant instructions for setting up JavaFX.
   - Note: The project was primarily developed using Eclipse, so the setup instructions are tailored to Eclipse.

### Running the Project

Launch the project using the predefined run configurations created during the setup process (Step 5 in the Installation section).

This setup guide provides a brief overview of the Super Store Inventory Management System and instructions for installing and running the project. Feel free to customize and adapt the system as per your specific requirements.
