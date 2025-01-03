# Restaurant Table Booking System

A responsive and user-friendly application to book restaurant tables. Built using **Next.js** for the frontend and **Node.js** with **Express.js** for backend functionality.

## Objective

To design and develop a feature-rich restaurant table booking system that simplifies the reservation process for users and manages booking data effectively.

---

## Features

### 1. **Booking Form**
- Users can input:
  - Date and time for the reservation.
  - Number of guests.
  - Name and contact details.
- Input validation to ensure accurate data entry.

### 2. **Availability Display**
- Show available time slots for reservations based on user selection.
- Prevent double bookings for the same slot by checking backend data.

### 3. **Booking Summary**
- Display a confirmation message or page after a successful booking.
- Provide a summary of the reservation details for the user's reference.

### 4. **Responsive Design**
- The application is optimized for both desktop and mobile devices for a seamless user experience.

---

## Bonus Features
### **Calendar or Timeline View**
- Visualize available and booked slots through a calendar or timeline view.
- Users can select a date and time directly from the visual interface.

### **Backend API**
- Minimal APIs to handle bookings:
  - `POST /createBooking`: Create a new booking.
  - `GET /getBookings`: Retrieve booking details.
  - `DELETE /deleteBooking/:id`: Delete a specific booking.
- Backend implemented using **Node.js** and **Express.js**.

---

## Technology Stack

### **Frontend**
- **Framework**: Next.js
- **Styling**: CSS/SCSS or Tailwind CSS (optional)

### **Backend**
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: Any (e.g., MongoDB, PostgreSQL, or in-memory storage for demo purposes)

### **Deployment**
- Frontend: [Vercel](https://vercel.com/) (recommended)
- Backend: [Railway](https://railway.app/), [Heroku](https://www.heroku.com/), or any cloud service.

---

## Installation & Setup

### Prerequisites
- Node.js installed on your machine.
- A package manager (e.g., npm or yarn).

### 1. Clone the repository
```bash
git clone https://github.com/your-username/restaurant-table-booking-system.git
cd restaurant-table-booking-system
