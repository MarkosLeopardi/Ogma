# Ogma – Project Requirements

## Overview

Ogma was developed as a university team project with the goal of creating a **web-based educational platform** for browsing, searching, filtering, and interacting with academic modules and related information.

The project followed a more structured workflow, including:

- UI planning
- database design
- backend implementation
- front-end development
- search and filtering functionality
- deployment

---

## Functional Goals

The application was designed to allow end users to:

- Browse available **modules / courses**
- Search for modules using a **search bar**
- Filter modules using **faceted search**
- View **module details**
- View **lecturer information**
- Enroll in modules
- Receive email confirmation after enrollment
- View academic **events**
- Leave **reviews**
- Organize enrolled modules through a **calendar interface**

---

## Main Functional Areas

### 1. UI / UX Design
- Initial application design and screen planning in **Figma**
- Discussion of each screen’s purpose and functionality
- Shared visual reference for the team during development

### 2. Branding
- Brainstorming for the project name (**Ogma**)
- Design of the project logo

### 3. Database Design
- Design of the database schema
- Creation of tables and relationships in **MySQL**
- Use of foreign keys and default values
- Testing and validation through SQL queries
- Data preparation and insertion for:
  - modules
  - lecturers
  - events
  - reviews
  - categories
  - dates and related metadata

### 4. Authentication
- User **login / register** functionality
- Backend methods for handling authentication logic
- UI integration for login and registration flows

### 5. Home / User Experience
- Home page implementation
- Personalized **MyCalendar** for enrolled modules

### 6. Modules & Browsing
- View all available modules
- Browse module details and related events
- Use **Enroll / Buy** actions
- Leave reviews on modules or events

### 7. Search & Filtering
- Search bar implementation using **Lucene.Net**
- Faceted search/filtering by:
  - category
  - lecturer
  - event date
  - module duration

### 8. Lecturer Information
- Lecturer information pages
- Filtering and browsing lecturers by teaching-related criteria

### 9. Calendar Functionality
- Fetching events from the database
- Displaying events in a user calendar
- Integration with **Google Calendar API**
- Support for combining events from selected enrolled modules

### 10. Deployment
- Deployment of the application to an **Azure server**
- Database hosting and server-side troubleshooting

---

## Technical Requirements

The project was implemented using:

- **ASP.NET MVC**
- **C#**
- **MySQL**
- **JavaScript**
- **HTML / CSS**
- **Lucene.Net**
- **Google Calendar API**
- **Azure**

---

## Team Context

Ogma was developed as a **team-based academic software project**, with work distributed across design, front-end, backend, database, and deployment responsibilities.

The project was intended both as a functional educational platform and as a hands-on experience in collaborative software development.

---

## Note

This document is a cleaned and summarized version of the original project requirements, which were initially written in Greek during the planning and development phases of the project.
