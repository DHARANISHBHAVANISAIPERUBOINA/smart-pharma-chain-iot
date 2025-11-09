# Nanochip Hackathon - Pharma Supply Chain (Flask)

Local Flask app with SQLite to model a simple pharma supply chain.

Quick start (PowerShell):

1. Create a virtualenv and activate it:

```powershell
python -m venv .venv; .\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Run the app:

```powershell
python run.py
```

Endpoints:
- Web UI: http://127.0.0.1:5000/
- IoT update: POST /api/iot/update (JSON)
- FDA approve: POST /api/fda/approve/<manufacturer_id>

Notes: Tailwind is loaded via CDN in templates. SQLite DB file `data.db` will be created in the project root.
