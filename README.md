# PSGL
 development solution and code for the PSGL field trip report

# Equipment Monitoring System

This is an **Equipment Monitoring System** designed for a mining company that monitors equipment's temperature and vibration levels in real-time. The system includes a web interface to manage and display equipment data, along with real-time updates powered by WebSockets.

## Features

- **Real-Time Equipment Monitoring:** Equipment temperature and vibration levels are displayed in real-time.
- **Add New Equipment:** Users can add new equipment with details like name, temperature, and vibration level.
- **Data Display:** The system dynamically displays the list of equipment along with their temperature and vibration levels.
- **WebSocket Integration:** Real-time updates are displayed immediately when new equipment is added to the system.

## Technologies Used

- **Frontend:**
  - HTML5
  - CSS3 (Blue-Black Theme)
  - JavaScript (Fetch API, WebSocket)

- **Backend:**
  - Python
  - Flask (Web framework)
  - Flask-SQLAlchemy (Database integration)
  - SQLite (Database)

## Installation

Follow the steps below to set up and run the project locally:

### 1. Clone the repository

bash
git clone https://github.com/yourusername/equipment-monitoring-system.git

File Structure

equipment-monitoring-system/
│
├── app.py                # Main Flask application file
├── requirements.txt      # Python dependencies
├── templates/
│   └── index.html        # Frontend HTML template
├── static/
│   └── style.css         # CSS file for styling
└── README.md             # This README file
