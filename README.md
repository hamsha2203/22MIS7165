# CampusHub — Campus Notifications Platform

## Overview

CampusHub is a modern responsive campus notifications platform built using React + Vite + Material UI.
The application helps students track important campus updates related to:

* Placements
* Results
* Events

The platform prioritizes important notifications using a Priority Inbox system and provides a premium dashboard experience with responsive layouts, filtering, search, pagination, and real-time notification visualization.

---

# Features

## Priority Inbox

* Displays top high-priority notifications
* Priority based on:

  * Placement > Result > Event
  * Recency of notification

## Notification Categories

* Placement Updates
* Academic Results
* Campus Events

## Smart UI Features

* Glassmorphism-inspired premium UI
* Responsive desktop and mobile layouts
* Dynamic notification cards
* Real-time filtering
* Search functionality
* Pagination support
* Unread/read indicators

## API Integration

Integrated with provided evaluation API:

```txt
http://4.224.186.213/evaluation-service/notifications
```

Supports:

* limit
* page
* notification_type

---

# Tech Stack

## Frontend

* React
* Vite
* Material UI (MUI)
* JavaScript

## Middleware

* Custom Logging Middleware

## Version Control

* Git & GitHub

---

# Folder Structure

```txt
campus-notification-system/
│
├── logging_middleware/
├── notification_app_fe/
├── notification_app_be/
├── notification_system_design.md
├── screenshots/
├── demo-video/
└── .gitignore
```

---

# Logging Middleware

A reusable logging middleware utility was implemented to provide application observability and debugging support.

### Log API

```txt
http://4.224.186.213/evaluation-service/logs
```

### Logger Function

```js
Log(stack, level, packageName, message)
```

### Supported Levels

* debug
* info
* warn
* error
* fatal

### Logging Events

* API fetch success/failure
* Search actions
* Filter changes
* Pagination updates
* Notification interactions
* Error handling

---

# Installation

## Clone Repository

```bash
git clone <repo-link>
```

## Navigate to Frontend

```bash
cd notification_app_fe
```

## Install Dependencies

```bash
npm install
```

## Run Development Server

```bash
npm run dev
```

Application runs on:

```txt
http://localhost:3000
```

---

# Responsive Design

The UI is fully responsive and optimized for:

* Desktop
* Tablet
* Mobile devices

---

# Design Goals

The application was designed with focus on:

* Clean premium user experience
* Minimal clutter
* High readability
* Modern glassmorphism aesthetics
* Efficient notification management

---

# Future Improvements

* Real-time WebSocket notifications
* Push notification support
* Authentication system
* Dark/Light mode switching
* AI-based priority prediction
* Backend integration
* Notification bookmarking

---

# Author

Hamsha Vardhini
