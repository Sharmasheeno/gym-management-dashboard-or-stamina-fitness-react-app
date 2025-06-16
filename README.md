Stamina Fitness - Gym Management System

A complete, feature-rich gym management dashboard built with React and Tailwind CSS. This application provides a comprehensive interface for managing members, coaches, inventory, payments, and viewing sales reports, with distinct user roles for administrators and coaches.
Key Features

    Role-Based Authentication: Secure login system with separate views and permissions for Admins and Coaches.

    Admin Dashboard: A comprehensive overview of gym statistics, including total revenue, active members, and coach listings.

    Full CRUD Functionality: Easily Create, Read, Update, and Delete records for:

        Members

        Coaches

        Membership Plans

        Equipment Inventory

    Point of Sale (POS): A dedicated interface for recording new member payments against their chosen plans.

    Dynamic Sales Reporting: View payment history and filter sales reports by date to track revenue over specific periods.

    Search and Filter: Instantly find information in all management tables with live search functionality.

    Modern UI/UX: Built with Tailwind CSS for a clean, responsive design, and includes a non-intrusive notification system for user feedback.

    Profile Management: Admins and coaches can view and manage their profile information.

Technologies Used

    Frontend: React.js

    Styling: Tailwind CSS

    Icons: Lucide React

    State Management: React Hooks (useState, useContext, useMemo, useCallback)

    Database: The current version uses a simulated, in-memory database via React Context for demonstration purposes.

Local Setup and Installation

To run this project on your local machine, please follow these steps:

    Prerequisites: Make sure you have Node.js and npm installed.

    Clone the Repository (or Create a New React App):
    If you've cloned this repository, just run npm install. Otherwise, create a new project:

    npx create-react-app gym-management-app
    cd gym-management-app

    Install Dependencies:

    npm install lucide-react

    Add Tailwind CSS:
    Open the public/index.html file and add this script tag to the <head> section:

    <script src="https://cdn.tailwindcss.com"></script>

    Add the Source Code:
    Copy the code from this project's App.js file and replace the contents of your src/App.js.

    Start the Server:

    npm start

    The application will be available at http://localhost:3000.

Login Credentials

Use the following credentials to access the application:

    Admin Account:

        Email: admin@stamina.fit

        Password: password

    Coach Account:

        Email: coach@stamina.fit

        Password: password123
