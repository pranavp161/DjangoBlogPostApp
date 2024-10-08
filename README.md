# Blog App (Backend + Frontend)

This project consists of two parts:
- Backend (Django)
- Frontend (Flutter)

## Requirements

### Backend (Django)
- Python 3.x
- Django
- Virtual Environment (`venv`)
- SQLite (default in Django, no need for external installation)

### Frontend (Flutter)
- Flutter SDK
- Dart
- Android Studio or Visual Studio Code (recommended IDE)
- Android/iOS Emulator or a Physical Device

## Setup Instructions

### Backend Setup

1. **Clone the repository** (or download it).
   ```bash
   git clone <your-repo-url>

# 2. Navigate to the backend directory:

cd blogapp_backend


# 3. Create a virtual environment
To isolate dependencies for this project, it's recommended to use a virtual environment.

python -m venv connectfd

# 4. Activate the virtual environment
For Windows:

connectfd\Scripts\activate

For macOS/Linux:

source connectfd/bin/activate

# 5. Activate the virtual environment: On Windows:

connectfd\Scripts\activate

On MacOS/Linux:

source connectfd/bin/activate


# 6. Install required dependencies:

pip install -r requirements.txt


# 7. Run database migrations:

python manage.py migrate

# 8. Start the Django development server:

python manage.py runserver


#  Frontend Setup
#  1. Navigate to the frontend directory:

cd blogapp_frontend

# 2. Ensure Flutter is installed and the path is set. To check, run:

flutter --version


# 3. Run the Flutter app:

flutter run

using cmd use chrome browser

# 4. If using an emulator, ensure it is set up and running before executing the above command.


   # Additional Notes
    Backend: The backend is built using Django, which includes a REST API for the frontend to interact with.
    Frontend: The frontend is built using Flutter and Dart, which is used to create cross-platform mobile apps.
    Ensure that both backend and frontend are running for full functionality.