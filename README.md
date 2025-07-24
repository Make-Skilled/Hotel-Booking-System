# Hotel Booking System

A web-based hotel booking system built with Flask and MongoDB. Users can register, log in, view available rooms, and book rooms. Admins can manage rooms and view all bookings.

## Features
- User registration and login
- Room listing and booking
- Admin dashboard for room management
- Booking management (accept/reject by admin)
- Image upload for rooms
- User dashboard for booking history
- Contact and About pages

## Project Structure
- `app.py`: Main Flask application
- `templates/`: HTML templates (home, login, signup, admin, rooms, bookings, etc.)
- `static/uploads/`: Uploaded room images

## Setup Instructions
1. **Clone the repository**
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Start MongoDB**
   - Ensure MongoDB is running locally on the default port (27017)
4. **Run the application**
   ```bash
   python app.py
   ```
   The app will run on http://localhost:5500

## Default Admin Credentials
- Username: `admin`
- Password: `1234567890`

## Notes
- Room images are stored in `static/uploads/`
- Update MongoDB connection string in `app.py` if needed

## License
MIT 