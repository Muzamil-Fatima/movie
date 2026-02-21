# 🎬 Movie Ticket Booking App (MERN Stack)

A modern and responsive full-stack web application where users can explore movies, check showtimes, view details, book seats, and manage their bookings — built using the **MERN Stack (MongoDB, Express, React, Node.js)**.

---

## 🚀 Project Overview

This project is a **full-featured movie ticket booking platform** designed to provide an intuitive and seamless user experience. It includes both **user** and **admin** sides.
Users can browse movies, select theaters, book seats, and mark favorites, while the admin can manage movies, shows, and bookings.

---

## 🧠 Frontend Overview

### 🔹 Navbar Component

* Built using **React.js** and styled with **Tailwind CSS**.
* Displays navigation links such as Home, Movies, Theaters, Releases, and Favorites.
* Fully **responsive** — collapses into a hamburger menu on mobile devices.
* Includes a **Login button** and a **search icon** for quick access.
* Uses **Lucide React** icons (`MenuIcon`, `XIcon`, `SearchIcon`) for a modern and minimal look.
* The mobile menu uses a blur background effect and smooth open/close transitions.

### 🔹 App Component

* Defines all the **application routes** using **React Router DOM**.
* Renders components like Home, Movie Details, Seat Layout, My Bookings, and Favorites.
* Uses **React Hot Toast** for showing real-time notifications.
* Automatically hides Navbar and Footer on admin-related routes for a cleaner dashboard view.

---

## 🧩 Libraries and Dependencies Used

### 🧱 Core Libraries

* **React.js** – For building the user interface.
* **React Router DOM** – For managing page navigation without reloads.
* **Lucide React** – For adding sleek and scalable icons.
* **React Hot Toast** – For displaying stylish success and error notifications.
* **Tailwind CSS** – For fast, utility-first styling.

### 🖼️ Assets

* The logo and other images are imported from a central **assets folder** for easy management.

---

## 🧭 Application Flow

1. **User visits the website** and navigates via the Navbar.
2. **Movies and Theaters** are displayed on different pages.
3. Clicking a movie opens its **details page**.
4. Selecting a showtime leads to the **seat layout**, where users can choose and book seats.
5. Booked tickets appear in **My Bookings**, and users can save their favorites.
6. **Admin** can manage movies, showtimes, and bookings in separate routes (hidden from regular users).

---

## 🧰 Technologies Used

| Category          | Technology                                          |
| ----------------- | --------------------------------------------------- |
| Frontend          | React.js, Tailwind CSS, Lucide React                |
| Routing           | React Router DOM                                    |
| Notifications     | React Hot Toast                                     |
| Authentication    | Clerk                                               |
| Backend (planned) | Node.js, Express.js, MongoDB                        |
| Deployment        | Vercel / Render (Frontend), MongoDB Atlas (Backend) |

---

## 💡 Key Features

* Dynamic routing between pages
* Responsive UI for all devices
* Seat selection and ticket booking system
* Toast-based notifications
* User-friendly navigation
* Admin dashboard ready for backend integration
* **Secure authentication via Clerk** for user signup, login, and profile management

---

## ⚙️ Future Enhancements

* Connect to **MongoDB database** for dynamic movie and booking data
* Enable **online payments**
* Add **admin analytics dashboard**
* Support for **real-time seat availability updates**
* Expand **user profile features** with Clerk (favorites, booking history, preferences)

---

## ✨ Credits

Developed as part of the **“Build and Deploy a Full Stack Movie Ticket Booking App using React JS | MERN Stack Project”** learning series.

