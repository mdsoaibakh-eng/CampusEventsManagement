# College Event Management System

A Flask-based web application for managing college events, allowing administrators to create events and students to register for them.

## Features

- **Admin Portal**:
  - Secure login/logout.
  - Create, Edit, and Delete events.
  - View all student registrations.
  - Approve pending registrations.
- **Student Portal**:
  - Secure registration and login.
  - View available events.
  - Register for events.
  - Dashboard to view registered events and their status.
- **Public View**:
  - List of all upcoming events with pagination.
  - Detailed view of each event.

## Technology Stack

- **Backend**: Python, Flask
- **Database**: SQLite (via Flask-SQLAlchemy)
- **Frontend**: HTML, CSS (Bootstrap/Custom), Jinja2 Templates

## Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/mdsoaibakh-eng/CampusEventsManagement.git
    cd CampusEventsManagement
    ```

2.  **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    # Windows
    venv\Scripts\activate
    # Mac/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Environment Configuration**:
    Create a `.env` file in the root directory (if not already present) and add the following:
    ```env
    SECRET_KEY=your_secret_key
    DATABASE_URL=sqlite:///college_events.db
    ```

5.  **Initialize the Database**:
    The application automatically creates the database tables on the first run.

## Usage

1.  **Run the application**:
    ```bash
    python app.py
    ```

2.  **Access the App**:
    Open your browser and navigate to `http://127.0.0.1:5000`.

3.  **Admin Setup**:
    - Navigate to `/admin/register` to create an admin account.
    - Login at `/admin/login`.

4.  **Student Access**:
    - Students can register at `/student/register`.
    - Login at `/student/login` to view the dashboard and register for events.

## Project Structure

- `app.py`: Main application file containing routes and logic.
- `models.py`: Database models (Admin, Student, Event, Registration).
- `templates/`: HTML templates for the application.
- `static/`: Static files (CSS, JS, Images).
