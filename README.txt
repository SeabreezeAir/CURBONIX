Curbonomix Full Stack (3D + Branding) — 2025-09-21
1) Backend: Curbonomix-backend
   - Put your CSV at Curbonomix-backend/storage/rtu_master.csv
   - python -m venv .venv && (activate) && pip install -r requirements.txt && python app.py
   - Health: http://127.0.0.1:8000/api/health
2) Frontend: curbonomix-app
   - npm i && npm run dev
   - For production, set .env.production VITE_API_BASE to your backend URL
