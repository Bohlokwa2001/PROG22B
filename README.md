🧾 Contract Monthly Claim System

Developer: Bohlokwa Letsoso
Student Number: ST10096006
Project Type: Web Application (Single-Page HTML, CSS, JavaScript)
Version: Developer Edition

📘 Overview

The Contract Monthly Claim System is a browser-based web application designed to help lecturers easily submit, track, and manage their monthly payment claims.
It also allows coordinators to review, verify, approve, or reject claims — all within a simple, modern dashboard interface.

The application uses localStorage for data persistence, meaning all submitted and verified claims are stored locally on your browser (no external database required).

⚙️ Features
👩‍🏫 Lecturer Features

Submit new monthly claims with details like:

Contract/course code

Month

Hours worked

Notes and uploaded supporting documents

Save draft claims locally

View claim history and statuses

Download claim summaries as PDFs

🧑‍💼 Coordinator Features

Switch to Coordinator mode using the “Switch to Coordinator” button

View all lecturer submissions

Approve or reject pending claims

Filter and review claims by status

📊 Dashboard Highlights

Real-time statistics:

Total Claims

Pending, Approved, and Monthly Totals

Recent activity feed

Dynamic updates every time a claim is submitted or verified

🖥️ Technologies Used
Layer	Technology
Frontend	HTML5, CSS3, JavaScript (ES6)
Storage	Local Storage API
UI Styling	Custom CSS variables, responsive layout
PDF Export	JavaScript window print/export function
🚀 Installation & Usage

Download or clone this repository:

git clone https://github.com/<your-username>/contract-claim-system.git


Open the file:

contract_claim_system.html


Run the system directly in any modern browser (e.g. Chrome, Edge, Firefox).

Use the default demo data automatically loaded when first opened.

🧩 How It Works
Action	Description
Submit Claim	Fills out a claim form, uploads supporting documents, and submits to localStorage
Save Draft	Temporarily stores incomplete claim data
Switch Role	Toggles between Lecturer and Coordinator views
Approve/Reject	Coordinator can change claim status
Download PDF	Exports claim summary for record-keeping
🔒 Data Storage

All data (claims, drafts, approvals) are stored in your browser’s localStorage.
To reset or clear the system, open your browser’s Developer Tools → Application → Local Storage → Clear All.

🧑‍💻 Developer Notes

Designed for educational and demonstration purposes.

No backend or server database is required.

Uses sample data on first launch (seedSampleData() in script).

Each claim entry includes:

Auto-generated ID (CL-1001, CL-1002, etc.)

Lecturer name

Hours, contract, and status

Submitted date/time

📄 Example Claim Structure
{
  "id": "CL-1001",
  "lecturer": "Bohlokwa Letsoso",
  "contract": "PROG101",
  "month": "2025-06",
  "hours": 20,
  "amount": 7000,
  "status": "pending",
  "submittedDate": "2025-06-05 09:12",
  "notes": "June sessions - Weekday labs"
}

📱 Responsiveness

The layout automatically adjusts to smaller screens:

Two-column grid for tablets

Single-column stacked layout for mobile screens

🧾 License

This project is for academic and demonstration use.
All rights reserved © 2025 Bohlokwa Letsoso (ST10096006).
