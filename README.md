# Amazing Assistants Online

This folder is the website. It can run on your computer, and it can be published on Render.

## On your computer

Double-click `run.bat`. The site opens at http://127.0.0.1:5070/

## On Render

Create a new Web Service and connect the GitHub repository for this folder.

- Language: Python 3
- Branch: `main`
- Root directory: leave empty
- Build command: leave the one Render fills in
- Start command: `gunicorn --bind 0.0.0.0:$PORT app:app`
- Environment variables: leave blank

The free plan works. Accounts and new listings are saved on that service. On the free plan they are cleared when the service sleeps or is updated.
