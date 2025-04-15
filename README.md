# G Attendance

**G Attendance** is a modern, web-based attendance management system designed to simplify the process of recording attendance. The system integrates seamlessly with **Google Sheets** through **Google Apps Script**, ensuring efficient and accurate attendance tracking.

## Features
- **LDAP Name Selection**: Users can easily select their LDAP (e.g., `savbindu`, `hindol`, etc.).
- **Status Selection**: Allows users to mark their status as **Present** or **Absent**.
- **Google Sheets Integration**: Automatically records attendance data into a Google Sheet for centralized tracking.
- **Confirmation Modal**: Displays a success modal with the details of the submitted attendance entry.
- **Responsive Design**: Fully responsive design for accessibility across both desktop and mobile devices.

## Technology Stack
- **Frontend**: HTML, CSS, JavaScript, [Bootstrap 5](https://getbootstrap.com/), [Font Awesome](https://fontawesome.com/)
- **Backend**: [Google Apps Script](https://developers.google.com/apps-script) (Handles form submissions and data entry into Google Sheets)
- **Hosting**: Deployable on any web server or platforms like [GitHub Pages](https://pages.github.com/), [Netlify](https://www.netlify.com/), or [Vercel](https://vercel.com/).

## Prerequisites

To get started with the G Attendance system, ensure you have the following:

1. **Google Sheets**: A Google Sheet for storing attendance data.
2. **Google Apps Script**: Set up Google Apps Script to process and log form submissions.
3. A web server or hosting platform for deploying the frontend (optional for local testing).

## Setup Instructions

### 1. **Set Up Google Sheets**
- Create a new Google Sheet to record the attendance.
- Ensure the first row contains the column headers: **Date**, **Name**, and **Status**.

### 2. **Set Up Google Apps Script**
- Open your Google Sheet, navigate to **Extensions > Apps Script**.
- Paste the provided Google Apps Script code, which will handle the form submissions and append the data to the Google Sheet.

### 3. **Update the Google Apps Script URL**
- After deploying the Google Apps Script as a web app, update the `scriptUrl` in the HTML file with your own generated URL.

### 4. **Deploy the Web Application**
- Host the HTML file on your preferred platform (e.g., GitHub Pages, Netlify, Vercel).

## Usage

1. **Access the Webpage**: Open the attendance page in a web browser.
2. **Select Your LDAP**: Choose your name from the LDAP dropdown.
3. **Select Your Status**: Choose your status—either **Present** or **Absent**.
4. **Submit the Form**: Click **Submit** to record your attendance.
5. **Confirmation Modal**: A modal will appear confirming that your attendance has been successfully marked.

## Customization

- You can easily add additional names to the LDAP dropdown in the HTML file.
- Modify the Google Apps Script to handle specific data processing or backend operations according to your needs.
- Update the front-end styles to align with your organization’s branding or visual preferences.

We hope this system streamlines the attendance management process for your organization.
