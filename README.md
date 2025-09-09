
# Startup Funding Dashboard (ready-to-deploy)

This is a minimal Vite + React project that fetches your Google Sheet and displays funding opportunities as cards.

## How to deploy (no coding required)

### 1. Unzip the package
Unzip the downloaded folder `startup-funding-dashboard.zip` on your computer.

### 2. Create a GitHub repository (if you don't have one)
- Go to https://github.com and sign in or sign up.
- Click **New** → create a repository name like `startup-funding-dashboard` → Create repository.

### 3. Upload files to GitHub
- Open the repository → click **Upload files** → drag all files & folders (from the unzipped folder) → Commit changes.

### 4. Deploy to Vercel
- Go to https://vercel.com → Sign in → Click **New Project** → **Continue with GitHub** → select the repository → Import & Deploy.
- Vercel will build and give you a public link like `https://your-project.vercel.app`.

## Google Sheet
This project already points to your Google Sheet (public). If you want to change the sheet, open `src/App.jsx` and change the `SHEET_URL` constant.
