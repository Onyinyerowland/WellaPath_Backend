## Welcome to Wellapath 
** A Community -Driven Ai Health Companion
This provides real time, localized health guidaince and offers clinic locator and symptom checker

This backend is built with **FastAPI**, following a clean modular structure.

---

##  Backend architecture

```
* FastAPI – high-performance API framework
* PostgreSQL – relational DB
* SQLAlchemy – ORM
* Auth – JWT-based
* Celery + Redis – async background tasks
* Pydantic – for validation
* Optional AI modules – for symptom analysis

```
---

##  Getting Started

1. **Clone the repo:**

   ```bash
   git clone https://github.com/Tinyuka-Team-12/WellaPath.git
   cd WellaPath/wellapath-backend
   ```

2. **Create and activate virtual environment:**

   ```bash
   python -m venv venv
   venv\Scripts\activate  # For Windows
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the development server:**

   ```bash
   uvicorn app.main:app --reload
   ```

---

## SKELETAL FRAME-WORK

```
WellaPath/
└── wellapath-backend/
    ├── app/
    │   ├── core/          # Configuration settings
    │   ├── db/            # In-memory database (temporary)
    │   ├── middleware/    # Custom middlewares (e.g., logger)
    │   ├── models/        # Pydantic models
    │   ├── routes/        # API endpoints (e.g., /auth)
    │   ├── schemas/       # Request/response data formats
    │   ├── services/      # Authentication and business logic
    │   └── main.py        # FastAPI app entry point
    ├── .env               # Environment variables
    ├── requirements.txt   # Dependency list
    └── README.md          # Project overview
```
---
