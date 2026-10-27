# Release Notes

## Django To-Do List Application

**Version:** 1.0.0  
**Release Date:** 27 October 2026  
**Release Type:** Initial Release

## Overview

Version 1.0.0 is the initial release of the Django To-Do List application. The application helps users manage everyday tasks through a simple web interface. It supports task creation, completion tracking, and deletion.

## Features

### 1. Task Management
- Create new tasks by entering a task title.
- Display the list of saved tasks.
- Mark tasks as completed or change them back to incomplete.
- Delete individual tasks.
- Remove all completed tasks in one operation.

### 2. Database Integration
- Store tasks using Django's ORM.
- Maintain task completion status.
- Automatically record task creation and last-update timestamps.
- Display incomplete tasks before completed tasks, with newer tasks appearing first within each group.

### 3. Web Application Structure
- Use Django views to process task-related requests.
- Use URL routing to connect application endpoints to their respective views.
- Render task data through Django templates.
- Use Django models to define and manage task records.

## Technology Stack

- **Backend:** Python and Django
- **Database:** Django-configured database
- **Frontend:** HTML and Django Templates
- **Database Access:** Django ORM
- **Dependencies:** Django, `dj-database-url`, `psycopg2-binary`

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/codershalini210/project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd project
   ```

3. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

6. Start the development server:

   ```bash
   python manage.py runserver
   ```

7. Open the application in your browser:

   `http://127.0.0.1:8000/`

## Limitations

- User authentication and individual user task ownership are not included in this release.
- Task editing is not currently implemented.
- Task creation ignores empty titles rather than displaying a dedicated validation message.
- Production deployment and security configuration should be verified before public use.

## Future Improvements

Potential enhancements for future releases include:

- User registration and login.
- Editing existing tasks.
- Task priorities and due dates.
- Search, filtering, and sorting options.
- Improved form validation and user feedback.
- Automated tests for task management functionality.
- Enhanced responsive styling and accessibility.

## Release Summary

Version 1.0.0 provides the core functionality required for a basic task management application using Django. It establishes the foundation for future improvements to usability, security, and task organisation.

