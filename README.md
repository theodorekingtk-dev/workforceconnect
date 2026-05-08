# WorkforceConnect

A full-stack workforce registration application built using:

- Python
- Flask
- MySQL
- Gunicorn
- Nginx
- Ubuntu Linux (WSL)

## Features

- User registration form
- MySQL database integration
- Registration records viewer
- Reverse proxy architecture using Nginx
- Production-style Gunicorn deployment
- Linux-based deployment workflow

## Architecture

Browser → Nginx → Gunicorn → Flask → MySQL

## Technologies Used

- Python 3
- Flask
- MySQL
- Gunicorn
- Nginx
- Git/GitHub
- Ubuntu WSL
- VS Code

## Setup

```bash
chmod +x setup.sh
./setup.sh
```

## Run Application

```bash
source venv/bin/activate
gunicorn --bind 0.0.0.0:5000 app:app
```

Open:

```text
http://localhost
```

## Author

Theodore King


## Screenshots

### VS Code Project Structure
![VS Code Structure](screenshots/01-vscode-structure.png)

### Registration Form
![Registration Form](screenshots/02-localhost-form.png)

### Registration Records
![Registration Records](screenshots/03-registration-records.png)

### Gunicorn Running
![Gunicorn Terminal](screenshots/04-gunicorn-terminal.png)