# Python Flask Feedback form

> Python Flask Feedback form that sends data to Postgres database and emails user (Mailtrap)

## Quick Start

```bash
# Add your DATABASE URI in app.py and your mail params in send_mail.py

# Install dependencies
pipenv shell
pipenv install

# Serve on localhost:5000
python app.py

# Create/Initialise db using SQLAlchemy
python3
from app import db
db.create_all()
```