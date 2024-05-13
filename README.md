# KSG-App
This repository is the home for all development on the Kingston Springs Gazette Mobile App.

## Features
- **User Authentication:** Secure login and signup options.
- **News Feed:** Browse the latest articles and news.
- **Interactive Content:** Engage with the news through comments and reactions.
- **Offline Access:** Save articles to read offline.
- **Notifications:** Stay updated with real-time notifications for new posts and important updates.

## Tech Stack
- **Frontend:** React Native with Expo, Redux
- **Backend:** Django, Django REST Framework
- **Database:** PostgreSQL
- **APIs:** RESTful API
- **Additional Tools:** Docker, pytest for testing

## Getting Started

### Prerequisites
- Python 3.8 or newer
- pip (Python package installer)
- Virtual environment (recommended)
- Node.js
- Expo CLI
- Android Studio for the Android emulator

### Installation

1. **Clone the repo:**
   ```bash
   git clone https://github.com/Finli-Hill/KSG-App.git
Set up a virtual environment:

bash
Copy code
cd KSG-App
python -m venv venv
Activate the virtual environment:

On Windows:
bash
Copy code
.\venv\Scripts\activate
On Unix or MacOS:
bash
Copy code
source venv/bin/activate
Install the required backend packages:

bash
Copy code
pip install -r requirements.txt
Install the required frontend packages:

bash
Copy code
cd frontend
npm install
Start the Expo development server for testing on Android Emulator:

bash
Copy code
npx expo start --android
Running the App
Make migrations and migrate the database:

bash
Copy code
python manage.py makemigrations
python manage.py migrate
Start the Django development server:

bash
Copy code
python manage.py runserver
Launch the app on the Android emulator:

bash
Copy code
npx expo start --android
Testing
Backend tests:

bash
Copy code
python manage.py test
Frontend tests (adjust as necessary for your React Native tests):

bash
Copy code
npm test

Contact
Your Name - 
Project Link: https://github.com/Finli-Hill/KSG-App

Acknowledgements:
- https://reactnative.dev/
- https://www.djangoproject.com/
- https://www.django-rest-framework.org/
- https://www.postgresql.org/
