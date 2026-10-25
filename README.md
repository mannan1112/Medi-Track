# MediTrack Hospital Management System

Plain HTML, CSS and JavaScript demo application. No React, Vite, or npm dependencies are required.

## Run in VS Code
1. Extract/open this folder in VS Code.
2. Open `index.html` with the Live Server extension, or run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Demo accounts
- Administrator: `admin` / `admin123`
- Doctor: `doctor` / `doctor123`
- Head Nurse: `nurse` / `nurse123`

## Features
- Patient directory and patient editing
- Appointment scheduling, rescheduling and cancellation
- Medical histories, prescriptions and laboratory reports
- Billing and print-to-PDF invoices
- Staff, departments, inventory, reports and alerts
- Discharge management with printable discharge summaries
- Light/dark theme and browser localStorage persistence

## Important
This is a demonstration application. Authentication and role-based navigation are client-side only, and records are stored in browser localStorage. Do not use it for real patient data or clinical decisions without a secure backend, access controls, and appropriate validation. Print actions use the browser print dialog; select “Save as PDF” to create a PDF file.
