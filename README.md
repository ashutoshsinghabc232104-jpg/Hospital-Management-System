# MedCore — Hospital Management System

MedCore is a streamlined management solution designed for healthcare facilities to handle patient registration, appointment scheduling, and billing records. The system is available in two versions: a lightweight Python CLI for backend logic testing and a modern, responsive web interface for daily hospital operations.

## Features

### 1. Patient Management
* **Registration**: Securely add new patients with details including full name, age, and diagnosis.
* **Automated ID Assignment**: Each patient is automatically assigned a unique ID (e.g., P-0000) upon registration for easy tracking.
* **Registry View**: Access a comprehensive list of all registered patients to view their medical history and status.

### 2. Appointment Scheduling
* **Booking**: Schedule visits for registered patients by selecting their profile and a preferred date.
* **Status Tracking**: Automatically categorizes appointments as "Upcoming," "Today," or "Completed" based on the current date.

### 3. Billing System
* **Generation**: Issue billing records to patients for services rendered.
* **Financial Records**: Track all billing entries, including patient names and total amounts billed.

### 4. Real-time Dashboard (Web Version)
* **Quick Stats**: View total patients, scheduled appointments, and total revenue at a glance.
* **Activity Feed**: Monitor a live log of system actions, such as new registrations or issued bills.
* **Recent Patients**: A quick-access table showing the most recently registered individuals.

## Technical Stack

### Web Interface
* **Frontend**: HTML5, CSS3 (using CSS Variables for theming).
* **Typography**: IBM Plex Sans, IBM Plex Mono, and Playfair Display for a professional medical aesthetic.
* **Logic**: Vanilla JavaScript for state management and dynamic UI updates.
* **Responsiveness**: Fully optimized for mobile and desktop viewing using CSS Media Queries.

### CLI Version
* **Language**: Python.
* **Data Structure**: Utilizes list-based storage for quick, in-memory data management during sessions.

## How to Use

### Web Version
The web interface is hosted on **GitHub Pages**. 
1.  **Navigate** through the sidebar to access different modules (Dashboard, Patients, etc.).
2.  **Register a Patient** first to enable appointment booking and billing.
3.  **Use Quick Actions** on the Dashboard for the most common tasks.
4.  **User Link** https://ashutoshsinghabc232104-jpg.github.io/Hospital-Management-System/

### CLI Version
1.  Run the Python script.
2.  Follow the on-screen menu prompts (1–7) to manage data via the terminal.

***

*This system is designed for efficient hospital administration, ensuring that patient data and financial records are organized and easily accessible.*
