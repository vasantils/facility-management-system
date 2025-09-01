
Built by https://www.blackbox.ai

---

# Facility Management System

## Project Overview
The Facility Management System is a comprehensive web application designed to streamline the management of facilities. The system encompasses various modules including Visitor Management, Room Bookings, Asset Tracking, Parking Management, Purchase Orders, Gate Pass Tracking, and a Helpdesk system. The application uses Tailwind CSS for styling and has a responsive design that ensures usability across multiple devices.

## Installation

To set up the Facility Management System locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/facility-management-system.git
   cd facility-management-system
   ```

2. **Open the project in your preferred browser**:
   - You can simply open `index.html` or serve the application using a local server if you have one set up.

3. **Dependencies**:
   - The project leverages external stylesheets and scripts:
     - [Tailwind CSS](https://tailwindcss.com/)
     - Font Awesome for icons

## Usage

1. **Login**:
   - Use the demo credentials to access the system:
     - Admin: `admin` / `admin123`
     - User: `user` / `user123`
     - Security: `security` / `sec123`
     - Technician: `tech` / `tech123`

2. **Navigate through the modules** from the sidebar where you can access different functionalities:
   - **Visitor Management**: Register and manage visitors.
   - **Room Bookings**: Check available rooms and manage bookings.
   - **Asset Tracking**: Keep track of assets within the facilities.
   - **Parking Management**: Manage parking slots.
   - **Purchase Orders**: Create and view purchase orders.
   - **Gate Pass Tracker**: Monitor the issuance of gate passes.
   - **Helpdesk**: Handle support tickets.

## Features

- **Role-Based Access Control**: Different roles have access to specific modules, enhancing security.
- **Dynamic Dashboard**: Users get an overview of various statistics.
- **Filter and Search**: Easily search for visitors, tickets, and assets.
- **Responsive Design**: The application is mobile-friendly.
- **Interactive Modals**: For registering visitors and managing other actions.

## Dependencies

The project relies on the following dependencies:

- **Tailwind CSS**: For utility-first CSS styling.
- **Font Awesome**: For iconography.
  
There is no `package.json` provided; however, you can create one if you plan to incorporate a build system or package management.

## Project Structure

```plaintext
facility-management-system/
├── index.html                 # Main entry point of the application
├── VMs.html                   # Visitor Management System page
├── facility-management-system.html # Overview and other functionalities
└── styles/                    # Directory containing custom styles (if any)
```

- **index.html**: Contains the login screen and dashboard layout.
- **VMs.html**: Implements functionality specific to visitor management.
- **facility-management-system.html**: Hosts the main content for the overall management system.
- **styles/**: Folder for additional CSS files if you decide to create custom styles.

## Conclusion

The Facility Management System aims to simplify the complexities of managing various aspects of facilities effectively and efficiently. It can be expanded further with user feedback and additional features to enhance user experience. Enjoy using the system!