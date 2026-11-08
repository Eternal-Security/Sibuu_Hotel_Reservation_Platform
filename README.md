# SIBUU HOTEL RESERVATION PLATFORM

## Hotel Reservation & Management System (HRMS)

A comprehensive web-based hotel management system built with HTML, CSS, and JavaScript for managing hotel operations including room management, guest registration, reservations, check-in/check-out, payments, and reporting.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Default Credentials](#default-credentials)
- [System Modules](#system-modules)
- [Screenshots](#screenshots)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)
- [License](#license)

---

## 🎯 Project Overview

The **SIBUU HOTEL RESERVATION PLATFORM** is designed to automate and simplify hotel operations. The system provides a centralized platform where authorized hotel administrators and receptionists can manage hotel information efficiently, reducing manual recordkeeping, preventing reservation conflicts, and improving information accuracy.

### Project Goals

- Automate hotel reservation processes
- Improve operational efficiency
- Reduce manual errors
- Provide centralized information management
- Generate comprehensive reports
- Enhance guest experience

---

## ✨ Features

### Core Features

- **User Authentication**
  - Role-based access control (Administrator, Receptionist)
  - Secure login system
  - Session management

- **Dashboard**
  - Real-time statistics
  - Total rooms, available rooms, occupied rooms
  - Total guests and active reservations
  - Revenue tracking
  - Recent reservations overview

- **Room Management**
  - Add, edit, delete rooms
  - Room types (Single, Double, Suite, Deluxe)
  - Room status management (Available, Occupied, Maintenance, Cleaning)
  - Room capacity tracking
  - Price management

- **Guest Management**
  - Register new guests
  - Update guest information
  - View guest reservation history
  - Search and filter guests
  - Guest identification tracking

- **Reservation Management**
  - Create new reservations
  - Modify existing reservations
  - Cancel reservations
  - Automatic conflict detection
  - Date validation
  - Automatic cost calculation
  - Real-time room availability checking

- **Payment Management**
  - Record payments
  - Multiple payment methods (Cash, Credit Card, Debit Card, Mobile Money, Bank Transfer)
  - Partial payment support
  - Outstanding balance tracking
  - Generate payment receipts

- **Reports & Analytics**
  - Room occupancy reports
  - Revenue reports
  - Guest statistics
  - Date-range filtering
  - Export functionality

---

## 🛠 Technologies Used

### Frontend Technologies

- **HTML5** - Structure and content
- **CSS3** - Styling and responsive design
- **JavaScript (ES6+)** - Application logic and interactivity

### Additional Technologies

- **Local Storage** - Browser-based data persistence
- **Font Awesome** - Icons
- **Responsive Design** - Mobile-friendly interface

---

## 📁 Project Structure

```
Hotel_Reservation_Management_System/
│
├── index.html                      # Login page
├── README.md                       # Project documentation
│
├── assets/
│   ├── css/
│   │   ├── style.css              # Main stylesheet
│   │   ├── dashboard.css          # Dashboard styles
│   │   └── responsive.css         # Responsive design styles
│   │
│   └── js/
│       ├── app.js                 # Main application functions
│       ├── auth.js                # Authentication module
│       ├── dashboard.js           # Dashboard functionality
│       ├── rooms.js               # Room management
│       ├── guests.js              # Guest management
│       ├── reservations.js        # Reservation management
│       ├── payments.js            # Payment management
│       ├── reports.js             # Reports and analytics
│       ├── storage.js             # Local storage management
│       └── validation.js          # Input validation
│
└── pages/
    ├── dashboard.html             # Dashboard page
    ├── rooms.html                 # Room management page
    ├── guests.html                # Guest management page
    ├── reservations.html          # Reservation management page
    ├── payments.html              # Payment management page
    ├── reports.html               # Reports page
    └── users.html                 # User management page (Admin only)
```

---

## 🚀 Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- A code editor (VS Code recommended)
- Basic understanding of HTML, CSS, and JavaScript

### Setup Steps

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/yourusername/sibuu-hotel-platform.git
   cd sibuu-hotel-platform
   ```

2. **No Installation Required**
   - This is a pure frontend application
   - No dependencies to install
   - No build process needed

3. **Open the Application**
   - Open `index.html` in your web browser
   - Or use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     ```

4. **Access the Application**
   - Navigate to `http://localhost:8000` in your browser
   - Login with default credentials

---

## 💻 Usage

### Getting Started

1. **Login**
   - Open the application in your browser
   - Select your role (Administrator or Receptionist)
   - Enter username and password
   - Click "Login"

2. **Dashboard**
   - View real-time statistics
   - Monitor room availability
   - Check recent reservations

3. **Managing Rooms**
   - Click "Rooms" in the sidebar
   - Click "Add Room" to create a new room
   - Fill in room details and save
   - Edit or delete rooms as needed

4. **Registering Guests**
   - Click "Guests" in the sidebar
   - Click "Register Guest"
   - Enter guest information
   - Save the guest record

5. **Creating Reservations**
   - Click "Reservations" in the sidebar
   - Click "New Reservation"
   - Select guest and room
   - Enter check-in and check-out dates
   - System automatically calculates total cost
   - Save the reservation

6. **Recording Payments**
   - Click "Payments" in the sidebar
   - Click "Record Payment"
   - Select reservation
   - View outstanding balance
   - Enter payment amount and method
   - Generate receipt

7. **Generating Reports**
   - Click "Reports" in the sidebar
   - Select date range
   - Click "Generate Report"
   - View occupancy, revenue, and guest statistics
   - Export report data

---

## 🔑 Default Credentials

### Administrator Account
- **Username:** `admin`
- **Password:** `admin123`
- **Role:** Administrator
- **Access:** Full system access including user management

### Receptionist Account
- **Username:** `receptionist`
- **Password:** `recept123`
- **Role:** Receptionist
- **Access:** Guest, room, reservation, and payment management

---

## 📦 System Modules

### 1. Authentication Module
- User login
- Session management
- Role-based access control

### 2. Dashboard Module
- Real-time statistics
- Summary cards
- Recent reservations table

### 3. Room Management Module
- CRUD operations for rooms
- Room status tracking
- Search and filter functionality

### 4. Guest Management Module
- Guest registration
- Guest information updates
- Reservation history viewing

### 5. Reservation Management Module
- Create and modify reservations
- Date conflict detection
- Automatic cost calculation
- Reservation status management

### 6. Payment Management Module
- Payment recording
- Multiple payment methods
- Outstanding balance tracking
- Receipt generation

### 7. Reports Module
- Occupancy reports
- Revenue analysis
- Guest statistics
- Date-range filtering

### 8. User Management Module (Admin Only)
- Add new users
- Modify user roles
- Activate/deactivate users

---

## 🎨 Screenshots

*Screenshots would be inserted here showing:*
- Login page
- Dashboard
- Room management
- Reservation creation
- Payment processing
- Reports

---

## 🔮 Future Enhancements

### Planned Features

1. **Backend Integration**
   - Node.js/Express backend
   - RESTful API
   - MySQL or PostgreSQL database

2. **Advanced Features**
   - Online booking system for guests
   - Email and SMS notifications
   - Payment gateway integration
   - Multi-branch support
   - Dynamic pricing
   - Housekeeping management

3. **Security Enhancements**
   - Server-side authentication
   - Password encryption
   - JWT tokens
   - Role-based API access

4. **Additional Modules**
   - Restaurant management
   - Room service
   - Staff management
   - Inventory management

5. **Mobile Application**
   - Native mobile app
   - Push notifications
   - Mobile-optimized booking

---

## 📄 Documentation

### Important Notes

**About Local Storage:**
- Data is stored in the browser's local storage
- Data persists across browser sessions
- Data is NOT shared between different browsers
- Clearing browser data will delete all records
- NOT suitable for production multi-user environment

**Security Notice:**
- This is a demonstration/educational project
- Client-side authentication is not secure for production
- Passwords are stored in plain text (for demo purposes only)
- Production systems require proper backend authentication

**Browser Compatibility:**
- Chrome (recommended)
- Firefox
- Edge
- Safari
- Modern mobile browsers

---

## 👥 Contributors

**Developer & System Architect:**  
**Debela Kebede**

**Features Developed:**
- Multi-language support (English, Amharic, Afaan Oromoo)
- Black/Dark theme implementation
- Complete hotel management system
- Real-time statistics and reporting
- Responsive design
- Role-based access control

**Institution:** [Your Institution]  
**Year:** 2024

---

## 📝 License

This project is developed for educational purposes.

---

## 🤝 Support

For questions or support:
- Email: support@sibuuhotel.com
- Documentation: See project documentation in `docs/` folder

---

## 🙏 Acknowledgments

- Font Awesome for icons
- All team members and contributors
- Instructors and advisors

---

**SIBUU HOTEL RESERVATION PLATFORM**  
*Simplifying Hotel Management, One Reservation at a Time*

---

## Development Notes

### Testing the Application

1. **Test Room Management**
   - Add multiple rooms
   - Edit room details
   - Change room status
   - Delete rooms

2. **Test Guest Registration**
   - Register guests with valid data
   - Test form validation
   - View guest history

3. **Test Reservation System**
   - Create reservations
   - Test date conflict detection
   - Test cost calculation
   - Cancel reservations

4. **Test Payment Processing**
   - Record payments
   - Test partial payments
   - Generate receipts
   - Verify balance calculations

5. **Test Reports**
   - Generate reports with different date ranges
   - Verify statistics accuracy
   - Test export functionality

### Known Limitations

- Data is browser-specific
- No real-time multi-user synchronization
- No server-side validation
- Limited to browser storage capacity
- No file upload functionality

### Troubleshooting

**Issue:** Cannot login  
**Solution:** Verify credentials, check browser console for errors

**Issue:** Data disappeared  
**Solution:** Check if browser data was cleared, restore from backup

**Issue:** Reservation conflict not detected  
**Solution:** Verify date formats, check reservation status

**Issue:** Payment not recording  
**Solution:** Verify reservation exists, check outstanding balance

---

*Last Updated: November 2024*
