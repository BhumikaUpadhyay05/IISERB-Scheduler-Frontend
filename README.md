# IISERB Timetable Scheduler

## Overview
The **IISERB Timetable Scheduler** is a web-based application that allows users to create and view academic timetables efficiently. Users can sign up, log in, and generate conflict-free timetables.

## File Structure

### `index.html`
- The main entry point of the application.
- Landing page with information regarding the website and options to **Sign Up** or **Log In** which on clicking takes the user to login page.
- Buttons to navigate to **Create Timetable** and **View Schedule** pages.

![Landing Page](images/index-html.png)

### `login.html`
- Users enter their email and password to log in.
- Provides authentication before accessing other features.

![Login Page](images/127.0.0.1_5500_login.html.png)

### `create-timetable.html`
- Interface to add and modify courses.
- Inputs for course code(that contains information like department and semester), instructor, and maximum student capacity per department.

| Add Course | Edit Course |
|------------|------------|
| ![Add Course](images/create-timetable.html(1).png) | ![View Course](images/create-timetable.html(2).png) |


### `view-schedule.html`
- Displays a sample weekly timetable.
- Showcases how weekly class schedules appear.
![Login Page](images/127.0.0.1_5500_view-shcedule.html.png)

## Languages Used
- HTML
- CSS (internal)
  
## How to Run the Project
### 1. Clone the Repository
```bash
git clone https://github.com/BhumikaUpadhyay05/IISERB-Scheduler-Frontend.git
```

### 2. Navigate to the Project Folder
```bash
cd IISERB-Scheduler-Frontend
```

### 3. Open `index.html`
- Right-click on `index.html`.
- Select **"Open with Live Server"**.

### 4. If Live Server is Not Installed
- Open **VS Code**.
- Go to **Extensions** (Ctrl+Shift+X).
- Search for **"Live Server"** and install it.
- Right-click `index.html` and select **"Open with Live Server"**.



