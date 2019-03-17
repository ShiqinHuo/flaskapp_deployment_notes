# flaskapp_deployment_notes

### Structure of the flaskapp

root/
├── flaskapp/
│   ├── app.py
│   ├── db.py
│   ├── robot.txt
│   ├── auth.py
│   ├── video.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── auth/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   └── video/
│   │       ├── create.html
│   │       ├── index.html
│   │       └── update.html
│   └── static/
│       └── style.css
├── tests/
│   ├── config_test.py
│   ├── data.sql
│   ├── test_db.py
│   ├── test_auth.py
│   └── test_video.py
