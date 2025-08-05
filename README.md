# CoviNet - COVID-19 Resource Management System

CoviNet is a Django-based web application that helps manage and track COVID-19 resources across hospitals while providing real-time COVID-19 statistics.

## Features

### 1. COVID-19 Statistics Tracker
- Real-time statistics using the COVID-19 RapidAPI
- Country-wise data including:
  - New cases
  - Active cases
  - Critical cases
  - Recovered cases
  - Total cases
  - Deaths

### 2. Resource Management System
- Hospital resource tracking
- Real-time availability of:
  - ICU Beds
  - Remdesivir
  - Ventilators
  - Vaccines
- Resource booking system for patients
- Hospital staff dashboard for resource updates

### 3. Social Module
- Community posts and updates
- User interactions
- Information sharing platform

### 4. User Management
- Multiple user roles:
  - Normal Users (Patients)
  - Hospital Staff
  - Admin Users
- Secure authentication system
- Role-based access control

## Technical Stack

- Backend: Django
- Frontend: Bootstrap 4
- Database: SQLite
- APIs: COVID-19 RapidAPI
- Forms: Django Crispy Forms

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Create superuser:
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

## Project Structure

```
CovidProject/
├── Covid_Module/      # COVID-19 statistics tracking
├── Resources_Module/  # Hospital resource management
├── Social_Module/     # Community interaction
├── Registration_Module/# User authentication
└── templates/         # HTML templates
```

## Usage

1. **For Patients**:
   - Register as a normal user
   - View hospital resources
   - Book required resources
   - View COVID-19 statistics
   - Participate in community discussions

2. **For Hospital Staff**:
   - Register as hospital staff
   - Manage hospital resources
   - Update resource availability
   - View booking requests

3. **For Administrators**:
   - Manage users
   - Monitor system
   - Access admin dashboard

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
