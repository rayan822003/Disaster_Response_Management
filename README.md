# Disaster Response and Management System

A scalable, real-time disaster prediction and response platform that leverages machine learning, geospatial analytics, and API integration to enhance the speed and accuracy of disaster relief coordination.

## 📌 Project Overview

This project aims to bridge the gap between disaster occurrence and relief operations by:
- Classifying disaster-related messages in real-time
- Identifying geolocation of affected areas
- Mapping them to the nearest NGOs
- Providing a web-based interface with real-time data visualizations

## 🧠 Key Features

- **Disaster Classification**: Uses TF-IDF + Random Forest Classifier for high-accuracy message categorization.
- **Geolocation Identification**: Extracts location coordinates using Geopy + Nominatim.
- **NGO Mapping**: Matches disaster-hit locations to nearby NGOs using the Haversine formula.
- **Interactive Dashboard**: Built using Folium and Django, with map-based NGO visualization.
- **CLI and Web Interface**: Offers both command-line and web-based user inputs.

## 🔧 Tech Stack

**Frontend**:
- HTML, CSS, JavaScript
- Bootstrap, React (Optional)

**Backend**:
- Python 3.8+
- Django & Django REST Framework
- FastAPI (optional for async support)

**Database**:
- MongoDB (primary)
- PostgreSQL / SQLite (optional)

**ML Libraries**:
- scikit-learn, NumPy, pandas

## 🛠️ Installation & Setup

```bash
# Clone the repo
git clone https://github.com/rayan822003/disaster-response-system.git
cd disaster-response-system

# Set up virtual environment
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run Django server
python manage.py runserver
