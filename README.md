Project Summary
This is a simple web application designed to capture employee photos as part of the attendance process or data collection for a face recognition project. The application connects a user-friendly web interface (frontend) with a robust backend using Google Apps Script, Google Drive, and Google Sheets.

How It Works
User Input:
Users can select their name from a list (or enter their NRP) and take a photo using a webcam.

Automatic Storage:
The captured photo is automatically saved in a specified Google Drive folder.

Record Keeping:
The photo information is recorded in a Google Sheet for record keeping.

Key Features
Google Workspace Integration:
Directly connected to Google Sheets for employee data and Google Drive for photo storage.

Modern Web Interface:
Built with HTML and Tailwind CSS, providing a clean and responsive design.

Camera Selection:
Automatically detects and provides options if there is more than one connected camera.

Dynamic File Naming:
Photo file names are automatically generated in the format:
NRP_Name_Timestamp.jpg for easy identification.

Logging:
Every successful photo submission is recorded in a separate Google Sheet, complete with a timestamp and a direct link to the photo on Google Drive.

Verification Modes
Dropdown Name:
Displays all employee names in a selection list (initial version).

NRP Input:
Users must first enter their NRP for verification (a more secure version).

Technologies Used
Frontend:
HTML, Tailwind CSS, Vanilla JavaScript

Backend:
Google Apps Script

Storage & Database:
Google Drive & Google Sheets

This layout uses headings, bold text, and bullet points to make the content more engaging and easier to read.