# Dev-Event# Dev Event Platform

## Introduction
This project is a web-based platform where users can explore and register for developer events.

An event platform is a system that helps users discover upcoming events, view event details, and participate by registering online. This project helped me understand how such platforms manage data, users, and interactions.

---

## Why this project
I built this project to understand how real-world platforms manage events and user participation.

Many modern platforms allow users to browse events, upload content, and interact with the system. This project helped me learn how backend logic, database, and frontend work together to handle such features.

---

## Core Features
- Displays a list of upcoming events on the homepage
- Each event has a detailed page with complete information
- Users can register for events
- Supports image upload for event content
- Allows creating, updating, and deleting events (CRUD operations)
- Suggests similar events to users
- Tracks user activity for better understanding of usage

---

## What is CRUD and why it is used
CRUD stands for Create, Read, Update, and Delete.

In this project:
- Create → Add new events
- Read → View events
- Update → Edit event details
- Delete → Remove events

This helps in managing event data efficiently.

---

## How image upload works
Images are handled using a cloud-based service.

- User uploads an image
- Image is sent to a cloud service (Cloudinary)
- Image is stored and optimized
- URL is returned and used in the application

This avoids storing large files directly in the database.

---

## How the system works
- Event data is stored in the database (MongoDB)
- User visits homepage and sees list of events
- User clicks on an event to view details
- User can register for the event
- Backend handles all requests through APIs
- Data is processed and stored properly

---

## Tech Stack
- Frontend: Next.js / React
- Backend: Node.js (API routes)
- Database: MongoDB
- Media Handling: Cloudinary
- Analytics: PostHog
- Styling: Tailwind CSS
- Language: TypeScript

---

## What I learned
- How event management systems work
- Handling CRUD operations in real applications
- Managing image uploads using cloud services
- Tracking user activity using analytics tools
- Building a scalable full stack application
A full stack event platform where users can explore, manage, and register for developer events with image uploads and analytics tracking.
