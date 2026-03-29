# ARTICKETS 

Welcome to **ARTICKETS**, my very first web project from 2 years ago! This repository is kept here for nostalgia and as a testament to my coding journey.

It is a web application for booking and managing event tickets, built with Python and Flask.

##  Tech Stack

- **Backend:** Python + [Flask](https://flask.palletsprojects.com/)
- **Database:** PostgreSQL + [SQLAlchemy](https://www.sqlalchemy.org/) (ORM)
- **Frontend:** HTML, CSS, [Jinja2](https://jinja.palletsprojects.com/) Templates



##  Setup & Installation

If you want to run this project locally, follow these steps:

### 1. Requirements

- Python 3.8+ installed.
- PostgreSQL database installed and running.

### 2. Database Configuration

You need a local PostgreSQL database to run this app. By default, the application expects the following:

- **User:** `articket`
- **Password:** `articket`
- **Database Name:** `artickets`
- **Port:** `5432`

### 3. Clone and Install Dependencies

```bash
# Clone the repository
git clone https://github.com/your-username/ARTICKETSS.git
cd ARTICKETSS

# Create and activate a virtual environment (recommended)
python -m venv venv
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate

# Install the required Python packages
pip install -r requirements.txt
```

### 4. Environment Variables

Create a file named `.env` in the root folder of the project based on the `.env.example` file.
You can use it to override the default database connection string if necessary:

```env
DATABASE_URL=postgresql+psycopg2://<user>:<password>@localhost:5342/<database>
```

### 5. Run the Application

Once everything is set up, start the server:

```bash
python main.py
```

The application will be running at `http://localhost:5000` or `http://127.0.0.1:5000`.

## License & Notes

This project was built for educational purposes as my first project. It might contain beginner mistakes, but it holds a lot of sentimental value. Thanks for checking it out!
