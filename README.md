# Login System (Flask)

A minimal login system with:
- User registration
- Password hashing
- Session-based login/logout
- Protected dashboard route

## Run locally

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

Then open `http://127.0.0.1:5000`.

## Notes

- Change `SECRET_KEY` in `app.py` before deploying.
- Data is stored in `users.db` (SQLite).
