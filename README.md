# Lab Equipment Management System

## 🧪 Project Overview

This project is a comprehensive **Lab Equipment Management website** designed to streamline the inventory, tracking, and reservation of laboratory equipment. Built using the **Laravel PHP Framework**, it provides a robust and scalable platform for educational institutions or research facilities to efficiently manage their valuable assets.

<hr>

## ✨ Key Features (Assumed)

This application aims to provide the following functionalities:

* **Equipment Inventory:** A centralized database to list, categorize, and track all lab equipment.
* **Detailed Equipment Profiles:** Store essential information for each item, including model number, serial number, purchase date, maintenance history, and current status.
* **Reservation System:** Users (e.g., students or researchers) can view equipment availability and submit requests to reserve equipment for a specific time slot.
* **User Role Management:** Differentiate access levels for **Administrators**, **Lab Technicians**, and **General Users** (e.g., students).
* **Maintenance Logging:** Record and track maintenance schedules, repairs, and calibration logs to ensure equipment remains in optimal condition.
* **Reporting:** Generate reports on equipment usage, reservation frequency, and inventory status.

<hr>

## 🛠️ Technology Stack

The project is built on the following technologies:

* **Backend Framework:** **Laravel** (PHP)
* **Language:** **PHP**
* **Database:** **MySQL**
* **Frontend:** **HTML**, **CSS**, **JavaScript**

<hr>

## 🚀 Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

Ensure you have the following software installed on your system:

* **PHP** (v7.4 or higher recommended)
* **Composer**
* **Node.js** and **npm** (for front-end asset compilation)
* **MySQL Server**

### Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/sayhan39/Lab-Equipment-Management.git](https://github.com/sayhan39/Lab-Equipment-Management.git)
    cd Lab-Equipment-Management
    ```

2.  **Install PHP Dependencies:**
    ```bash
    composer install
    ```

3.  **Install Node Dependencies and Compile Assets:**
    ```bash
    npm install
    npm run dev
    # or npm run production for minified assets
    ```

4.  **Configure Environment Variables:**
    * Copy the example environment file:
        ```bash
        cp .env.example .env
        ```
    * Generate an application key:
        ```bash
        php artisan key:generate
        ```
    * Edit the `.env` file and update the **Database** connection settings (`DB_DATABASE`, `DB_USERNAME`, `DB_PASSWORD`).

5.  **Run Migrations and Seed the Database:**
    * Create the database specified in your `.env` file.
    * Run the database migrations (and optional seeders to populate initial data):
        ```bash
        php artisan migrate --seed
        ```

### Running the Application

Start the local development server:

```bash
php artisan serve
