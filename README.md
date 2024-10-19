
# WiFi File Transfer App

This is a simple Flask-based web application that enables file transfer between two devices connected to the same WiFi network. Users can upload files to a server, which can then be accessed and downloaded by other devices on the network.

## Features

- Upload files to the server from any device connected to the same WiFi.
- Access and download uploaded files from other devices.
- Simple and user-friendly interface.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.x
- Flask (`pip install flask`)

## Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vinay-vk-kumar/WiFiShare
   cd WiFiShare
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Linux/Mac
   venv\Scripts\activate         # On Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   python app.py
   ```

5. **Access the application:**
   Open a web browser and navigate to:
   ```
   http://<server-ip>:5000
   ```
   Replace `<server-ip>` with the IP address of the machine running the app.

## Usage

1. Visit the application URL on the browser.
2. Use the "Upload File" button to choose and upload files.
3. Access uploaded files from other devices connected to the same network.

## Directory Structure

```
repository-name/
│
├── app.py               # Main application file
├── templates/
│   └── index.html
├── static/
│   └── styles.css        # Css file for the web interface
├── uploads/             # Directory where uploaded files are stored
├── requirements.txt     # List of required Python packages
└── README.md            # This README file
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements.

