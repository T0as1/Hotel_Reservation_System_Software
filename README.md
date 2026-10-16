# Hotel Reservation System

A web-based platform for browsing hotels, booking rooms, and managing stays and billing.

**Course:** CSE242 Advanced Software Engineering, Fall 2026
**Institution:** Ain Shams University, Faculty of Engineering, Computer Engineering and Software Systems Program

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [User Roles](#user-roles)
4. [Tech Stack](#tech-stack)
5. [Project Structure](#project-structure)
6. [Getting Started](#getting-started)
7. [Development Workflow](#development-workflow)
8. [Documentation](#documentation)
9. [Team](#team)

---

## Overview

The Hotel Reservation System lets guests search for available rooms, book, pay, and cancel online, while hotel staff manage rooms, prices, check-ins, check-outs, and reports. The system prevents overbooking, applies configurable cancellation policies, and generates invoices.

## Features

- **Account management:** registration, login, and role-based access
- **Room search:** filter by hotel, dates, price, and room type
- **Booking:** reserve rooms with overbooking prevention (no double-booking of the same room and dates)
- **Cancellation policies:** free cancellation until a deadline, fees afterward
- **Billing:** invoices covering room charges, extras, and taxes, with payment status
- **Reception tools:** check-in, check-out, walk-in bookings, and no-show handling
- **Management tools:** room and price management, reports, and user administration
- **Notifications:** booking confirmations and updates

## User Roles

| Role | Main capabilities |
|------|-------------------|
| Guest | Search, book, cancel, pay, view invoices |
| Receptionist | Check-in, check-out, walk-in bookings, no-shows |
| Hotel Manager | Manage rooms, prices, policies, and reports |
| Admin | Manage hotels and user accounts |

## Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | Java |
| Frontend | _To be decided_ |
| Database | _To be decided_ |
| Version control | Git and GitHub |

## Project Structure

```
.
├── backend/     Server-side code
├── frontend/    User interface
├── docs/        Diagrams, project document, and presentation
└── README.md
```

## Getting Started
_To be added_
### Prerequisites

- Git
- _Runtime and database required by the chosen stack_

### Installation

```bash
# 1. Clone the repository
git clone <repository-url>
cd hotel-reservation-system

# 2. Install dependencies (update for the chosen stack)
# backend:  ...
# frontend: ...

# 3. Configure the environment
# Copy the example config and fill in the values

# 4. Run the application
# ...
```

## Development Workflow

- The `main` branch is protected. No direct pushes.
- Create one branch per task, named `feature/<short-task-name>` (for example `feature/booking-search`).
- Open a pull request for every change and get at least one review before merging.
- Write clear commit messages, for example `Add overbooking check to booking service`.
- Merge into `main` at least weekly, and keep the project working at all times.

## Documentation

All design artifacts live in the [`docs/`](docs) folder:

- Use-case diagram and narratives
- Swimlane and interaction diagrams
- CRC cards, state diagram, and class diagram
- Architecture and component diagrams
- Cost estimation and time plan
- Prototype screens

## Team

| Name | Student ID | Role / Sub-team |
|------|------------|-----------------|
| Saeb AlRayyes | 24P0409 |  |
| Mohamed Khaled Abd Elmoanim | 25P0127 |  |
| Omar Khaled Mohamed Soliman Elsawy | 25P0110 |  |
| Ali Mohamed Hassan Tawfeek Abdelrazik | 25P0107 |  |
| Yousef Hesham Abdeltawab | 25P0118 |  |
| Abdelrahman Mohamed | 25P0252 |  |
| Omar Ali Sayed | 25P0282 |  |
| Omar Abdelaziz Abdelaty | 25P0458 |  |
| Eiad Sayed Tawfik | 25P0040 |  |
| Mario Soliman | 25P0226 |  |
| Mohamed Taha | 24P0136 |  |
| Mustafa Aed Mahmoud Yaghi | 2301076 |  |

---

_This project was developed for academic purposes as part of the CSE242 term project._
