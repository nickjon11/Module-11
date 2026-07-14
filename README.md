# Module 11 Calculation Model

This project extends the Module 10 FastAPI application with a SQLAlchemy
Calculation model, Pydantic validation, calculation factory classes, unit
tests, PostgreSQL integration tests, and CI/CD deployment.

## Supported Operations

- Add
- Sub
- Multiply
- Divide

The application rejects invalid operation types and division by zero.

## Run Locally

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Docker Reminder

Like Module 10, you will need to supply your own account in order to grant access to this. 

Go to ci-cd.yml, line 73-74 and change the username and password with your own. It should work as intended after that. 

