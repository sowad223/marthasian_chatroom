
# SAINT MARTHA'S SSC Batch-2018 Chat Application

This is a chat application built using **Flask**, **Flask-SocketIO**, and basic web technologies such as HTML, CSS, and JavaScript. It includes both real-time messaging and a stylish user interface with custom logos, animations, and more.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
- [How to Run](#how-to-run)
- [File Structure](#file-structure)
- [Dependencies](#dependencies)
- [Customization](#customization)
- [License](#license)

## Features

- Real-time chat rooms powered by **Flask-SocketIO**.
- User can create or join chat rooms using a unique room code.
- A modern, lively user interface with animations and responsive design.
- Two custom logos are displayed, with hover effects and animated transitions.
- Smooth background animations to enhance the UI experience.
- Live message updates and smooth scrolling.
- Works on mobile and desktop devices.

## Setup

### Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.8+
- Pip (Python package manager)

### Installation

1. Clone this repository to your local machine:

   \`\`\`bash
   git clone https://github.com/sowad223/marthasian_chatroom.git
   cd saint-martha-chat-app
   \`\`\`

2. Create and activate a virtual environment (recommended):

   \`\`\`bash
   python -m venv venv
   source venv/bin/activate  # For Windows, use: venv\Scripts\activate
   \`\`\`

3. Install the required Python dependencies:

   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

4. Ensure you have **Flask**, **Flask-SocketIO**, and other dependencies installed.

### How to Run

1. Start the Flask development server:

   \`\`\`bash
   flask run
   \`\`\`

   Alternatively, if using **Flask-SocketIO**:

   \`\`\`bash
   python app.py
   \`\`\`

2. Open your browser and go to `http://127.0.0.1:5000`.

3. Enter a username, create or join a room, and start chatting!

### File Structure

\`\`\`plaintext
.
├── app.py                 # Main Flask application
├── static/                # Static files (CSS, Images, etc.)
│   ├── css/
│   │   └── style.css      # Stylesheet for the application
│   ├── images/
│   │   ├── school.jpg     # School logo
│   │   └── cartoon_logo.png  # Cartoon logo for Batch-2018
├── templates/             # HTML templates
│   ├── base.html          # Base template
│   ├── home.html          # Homepage (Room creation/join)
│   └── room.html          # Chat room page
├── requirements.txt       # List of Python dependencies
└── README.md              # This file
\`\`\`

### Dependencies

- Flask: A micro web framework for Python.
- Flask-SocketIO: Adds support for real-time messaging using WebSockets.
- Python-SocketIO: Client for WebSocket communication.
- Gunicorn (optional): Production-ready web server for Flask apps.

You can install all dependencies with:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

### Customization

- **Logos**: The app uses two logos. You can replace the logos in the `static/images` directory with your own.
- **Styles**: To customize the look and feel of the app, you can modify `static/css/style.css`.
- **Room Code**: The app generates a random 4-letter room code for each room. This behavior can be customized in `app.py`.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
