# Org Chart Builder

A React app for building and managing org charts.

## Deploy to Netlify

### Option 1: Drag & Drop (Easiest)
1. Install dependencies and build:
   ```bash
   npm install
   npm run build
   ```
2. Go to [netlify.com](https://netlify.com) and log in
3. Drag and drop the `dist/` folder onto the Netlify dashboard

### Option 2: Connect GitHub Repo
1. Push this folder to a GitHub repository
2. Go to [netlify.com](https://netlify.com) → "Add new site" → "Import an existing project"
3. Connect your GitHub repo
4. Netlify will auto-detect the settings from `netlify.toml`:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
5. Click **Deploy site**

## Local Development
```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.
