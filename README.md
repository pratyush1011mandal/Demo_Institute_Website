# Aditi Institute of Excellence — Static Website

Simple static website for Aditi Institute of Excellence (HTML, CSS, images).

## View locally
- Open `index.html` in your browser.
- Or run a simple local server:

```bash
# Python 3
python -m http.server 8000
# Then open http://localhost:8000
```

## Git & Deploy
Initialize a repo and push to GitHub:

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

Deploy to Vercel:
- In Vercel, choose "Import Project" → connect GitHub → select this repo.
- Framework: "Other / Static Site" (no build command). Vercel will auto-deploy on push.

## Notes
- Asset paths are relative (`images/...`) so deployment should work without changes.
- Add a license or README details as needed.
