Project : "StudyBuddy"

"Create a robust real-time communication platform reminiscent of Discord using Python Django, 
empowering users to engage in dynamic group discussions, exchange messages, and customize their profiles, 
all within a secure and adaptable web environment."
-----------------------------------------------

Table of Contents

1. Installation
2. Usage

-----------------------------------------------

1. Installation

1.1. Download the Project Zip File:
   - Download Python from internet [https://www.python.org/downloads/]

1.2. Extract the Zip Archive and installing python:
   - Use a file archiver program like WinZip, 7-Zip, or built-in tools on macOS and Linux to extract the contents of the zip file.
   - Install Pyhton in your system and check the box "Add to path." while installing.

1.3. Navigate to the Project Directory:

   cd path/to/project-directory

1.4. Create and Activate a Virtual Environment:

     check python version: python --version
   
Open terminal and run the following commands:
      install virtual environment: pip install virtualenv #to install virtual environment packages 

      python -m venv venv  # Create virtual environment
      source venv/bin/activate  # Activate virtual environment (Linux/macOS)
      venv\Scripts\activate  # Activate virtual environment (Windows)

1.5. Install Dependencies:

      pip install -r requirements.txt

1.6. Apply Database Migrations:

      python manage.py migrate

-----------------------------------------------

2. Usage

2.1. Run the Development Server:

   python manage.py runserver

2.2. Access the Application:

   - Open a web browser and navigate to http://127.0.0.1:8000/ (or the appropriate URL if you have configured differently).

2.3. Additional instructions or notes about using the project.


-----------------------------------------------
