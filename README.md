# WellaPath a Community -Driven Ai Health Companion
offers clinic locator, symptom checker and health education
#  Backend architecture 
* FastAPI – high-performance API framework
* PostgreSQL – relational DB
* SQLAlchemy – ORM
* Auth – JWT-based
* Celery + Redis – async background tasks
* Pydantic – for validation
* Optional AI modules – for symptom analysis
# SKELETAL FRAME-WORK
app/
***├── main.py
├── api/
│   ├── auth.py
│   ├── clinic.py
│   ├── symptom.py
│   ├── education.py
│   └── community.py
├── models/
│   ├── user.py
│   ├── clinic.py
│   ├── symptom.py
│   └── post.py
├── db/
│   ├── session.py
│   └── base.py
├── core/
│   ├── config.py
│   ├── security.py
│   └── tasks.py
├── schemas/
│   ├── user.py
│   ├── clinic.py
│   └── ...
***
