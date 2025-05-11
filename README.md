# Employee Management Frontend

## Overview
This is the frontend of the Employee Management application, built with **Angular 19** using standalone components. It displays a list of employees fetched from a .NET Core Backend API or mock data if the Backend is unavailable.

## Features
- Displays a table of employees with columns: ID, First Name, Last Name, Email, and Position.
- Fetches data from the Backend API at `https://localhost:7047/api/Employees`.
- Uses mock data as a fallback if the Backend is not available (e.g., Mohamed, Ahmed).
- Responsive table styling with CSS.

## Prerequisites
- Node.js (v18 or higher)
- Angular CLI (v19 or higher)
- Backend API running at `https://localhost:7047/api/Employees` (optional for mock data)

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedEmad158/Employee-Management-Front.git
   cd Employee-Management-Front


Install dependencies:npm install


Run the application:ng serve


Open http://localhost:4200 in your browser to view the employee list.


Build
To build the project for production:
ng build

The build artifacts will be stored in the dist/ directory.
Notes

If the Backend API is unavailable, the application uses mock data.
Ensure CORS is enabled in the Backend for API integration (see Backend README: Employee Management Backend).
For additional features (e.g., employee form, pagination), please contact me.

Folder Structure

src/app/Shared/Interface/iemployee.ts: Defines TypeScript interfaces for API response.
src/app/Components/list: Contains list.component.ts, .html, and .css for the employee list.
src/app/Shared/Service/employee.service.ts: Handles API calls.

Contact
For any questions or feedback, reach out to Mohamed Emad at mohamedemadmb@gmail.com or me298016@gmail.com.```
