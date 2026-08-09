Local Marketplace Web
FastAPI + SQLAlchemy marketplace for customers, sellers and admins.
Python 3.9-compatible build. Run on Windows/Git Bash:
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt
cp .env.example .env
uvicorn app.main:app --reload
Open http://127.0.0.1:8000
Demo:
admin@localmarket.test / admin123
seller@localmarket.test / seller123
customer@localmarket.test / customer123
Use PostgreSQL in production by changing DATABASE_URL.
Payment credentials belong only in .env/server secrets.
