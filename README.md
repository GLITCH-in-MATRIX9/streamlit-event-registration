# Streamlit Event Registration System

## Overview

The **Streamlit Event Registration System** is a web application designed to help manage and track event registrations in real-time. Built with **Streamlit**, this app allows users to register for multiple events, manage participant details, and store registration information securely. The system leverages a **CSV file** for data storage, making it simple to track participants for up to 100+ events.

### Key Features:
- **Event Registration:** Users can register for events by entering their details (name, email, etc.).
- **Real-Time Registration:** New registrations are immediately saved and displayed in the system.
- **CSV Data Storage:** The participant data is stored in a CSV file, allowing easy export and backup.
- **Participant Management:** Admin users can view and filter the participants by event.
- **User-Friendly Interface:** Built using **Streamlit**, making it simple for anyone to use without requiring prior technical knowledge.

### Technologies Used:
- **Frontend:** Streamlit (for interactive web app)
- **Backend:** Python (handling app logic)
- **Data Storage:** CSV file (for storing participant data)
- **Libraries:** pandas, streamlit

## Project Structure

Here is a list of the project files and their respective purposes:


## Setup and Installation

### 1. Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/streamlit-event-registration.git
cd streamlit-event-registration
```

# Optional: Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install the necessary dependencies
pip install -r requirements.txt

# Run App Locally 
streamlit run app.py
## The app will automatically open in your default web browser at http://localhost:8501.


## Features

### Home Page
The Home Page welcomes users and explains the basic functionality of the event registration system. Users can navigate to the registration form or view the list of participants for different events.

### Event Registration
The Register Page allows participants to sign up for an event by providing details such as name, email, and event selection. The data is stored in a CSV file, and registrations are updated in real-time.

### Participant Management
Admins can view all registered participants. They can filter participants by event name, which helps in tracking registrations for individual events.

### Data Storage
The `registrations.csv` file stores all participant details. This simple and effective method ensures data is easily accessible, though future improvements could involve cloud-based storage solutions like AWS S3 for scalability.

## Future Enhancements
- **Cloud Storage Integration:** To scale the app and improve data security, consider integrating cloud storage solutions such as AWS S3.
- **Automated Notifications:** Use AWS Lambda or similar services to send confirmation emails or notifications to participants after registration.
- **Mobile Responsiveness:** Enhance the app to be fully responsive for mobile users, providing a seamless experience across devices.
- **Advanced Search and Filters:** Implement additional search features like date, event type, etc., for better event management.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Dependencies
Here’s a list of required Python dependencies for this project:
- `streamlit`: 1.0.0 or higher
- `pandas`: 1.0.0 or higher




