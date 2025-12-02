
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
    git clone 
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


<img width="1366" height="768" alt="Screenshot (344)" src="https://github.com/user-attachments/assets/ec76ed5a-9f10-4e0b-8e27-92d36f4dce07" /><img width="1366" height="768" alt="Screenshot (351)" src="https://github.com/user-attachments/assets/b9cf1d5e-0309-49af-8d5d-bbc0b16d6df0" />

<img width="1366" height="768" alt="Screenshot (351)" src="https://github.com/user-attachments/assets/623550ff-30c8-4133-8ce4-21207537acc8" />
<img width="1366" height="768" alt="Screenshot (350)" src="https://github.com/user-attachments/assets/7d1b4520-9eb6-4462-a389-d630881be0b8" />
<img width="1366" height="768" alt="Screenshot (352)" src="https://github.com/user-attachments/assets/3cda40f6-9b1f-4029-8212-ea372a467159" />
<img width="1366" height="768" alt="Screenshot (353)" src="https://github.com/user-attachments/assets/a4f7c214-dc87-4517-aa96-6446d6225995" />
<img width="1366" height="768" alt="Screenshot (354)" src="https://github.com/user-attachments/assets/7902f3a1-42a0-4e5c-86cb-f031eba23c2e" />
<img width="1366" height="768" alt="Screenshot (355)" src="https://github.com/user-attachments/assets/a236092c-ad47-4764-9d0d-04a4249b5499" />
<img width="1366" height="768" alt="Screenshot (356)" src="https://github.com/user-attachments/assets/82b34562-3b9c-45d5-9a50-c5f4a73c19e0" />
<img width="1366" height="768" alt="Screenshot (357)" src="https://github.com/user-attachments/assets/a17d132f-c0fe-443e-a3b0-623a5e207103" />
<img width="1366" height="768" alt="Screenshot (358)" src="https://github.com/user-attachments/assets/d6542e4b-d64d-4ce4-8fba-e2dde54f1f12" />
<img width="1366" height="768" alt="Screenshot (359)" src="https://github.com/user-attachments/assets/c5bf4dd1-3e88-41a6-b7ed-7f9c85f53707" />
