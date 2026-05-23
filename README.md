# Bupreme v8 - Jersey PDF Generator Pro

Production-ready full-stack app for jersey PDF generation.

## Features
✅ Client Sign Up / Login / Admin
✅ Mobile-responsive sidebar (hamburger menu)
✅ Excel parser (reads ALL rows, supports Name/No/Size variations)
✅ Server-side PDF generation (300 DPI, blue stripes)
✅ All 8 dashboard tabs working
✅ SQLite database

## Deploy to Render (Free)

### Step 1: Upload to GitHub
1. Create new repo: `bupreme-v8`
2. Upload all files from this zip:
   - app.py
   - requirements.txt
   - templates/index.html
3. Commit

### Step 2: Deploy on Render
1. Go to render.com → New → Web Service
2. Connect GitHub repo
3. Settings:
   - **Environment:** Python 3
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `python app.py`
   - **Plan:** Free
4. Click Create Web Service
5. Wait 2-3 minutes → Your URL: `https://your-app.onrender.com`

### Step 3: Test
- Open URL
- Click **Sign Up** → create account
- Login → upload Excel → Generate PDFs
- Admin login: dhub0005@gmail.com / dhub@0005

## Local Test
```bash
pip install -r requirements.txt
python app.py
# open http://localhost:5000
```

## File Structure
```
bupreme-v8/
├── app.py              # Flask backend
├── requirements.txt    # Python deps
└── templates/
    └── index.html      # Frontend
```

## Support
UPI: muhammerihan7775@oksbi
Version: v8.0 PRODUCTION
