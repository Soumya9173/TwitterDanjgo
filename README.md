# TwitterDjango

TwitterDjango is a simple Twitter-clone web application built using the Django framework.

## Features

- **User Authentication:** Sign up, log in, and secure sessions.
- **Microblogging:** Users can post 'tweets'.
- **Responsive UI:** Styled and structured layout for optimal user experience.

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:
- [Python](https://www.python.org/downloads/) (3.x recommended)
- `pip` (Python package installer)

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Soumya9173/TwitterDanjgo.git
   cd TwitterDanjgo
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv .venv
   ```

3. **Activate the virtual environment:**
   - **Windows:**
     ```powershell
     .venv\Scripts\activate
     ```
   - **macOS / Linux:**
     ```bash
     source .venv/bin/activate
     ```

4. **Install backend dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Navigate to the target sub-directory:**
   ```bash
   cd mytwitter
   ```

6. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```

7. **Run the development server:**
   ```bash
   python manage.py runserver
   ```
   Open your browser and navigate to `http://127.0.0.1:8000/` to test out the application!
