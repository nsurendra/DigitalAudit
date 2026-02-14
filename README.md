# DecorRocket Digital Audit

AI-powered digital audit platform for interior designers in Hyderabad.

## Files

- `index.html` - Main application file
- `vercel.json` - Vercel deployment configuration
- `package.json` - Project metadata

## Deployment to Vercel

### Option 1: GitHub Integration (Recommended)

1. **Push these files to your GitHub repository:**
   ```bash
   git add index.html vercel.json package.json .gitignore
   git commit -m "Add Vercel deployment files"
   git push origin main
   ```

2. **In Vercel Dashboard:**
   - Go to your project settings
   - Make sure the **Root Directory** is set to `.` (or leave empty)
   - **Framework Preset**: Select "Other"
   - **Build Command**: Leave empty
   - **Output Directory**: Leave empty or set to `.`
   - Click "Deploy"

### Option 2: Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

### Option 3: Manual Upload

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Drag and drop your folder containing `index.html`

## File Structure

```
your-repo/
├── index.html          # Main application
├── vercel.json         # Vercel config
├── package.json        # Project metadata
├── .gitignore         # Git ignore file
└── README.md          # This file
```

## Troubleshooting

### 404 Error
- Make sure `index.html` is in the root directory
- Check that `vercel.json` is present
- Verify **Root Directory** in Vercel settings is `.` or empty

### Deployment Not Updating
- Clear Vercel cache and redeploy
- Check the deployment logs in Vercel dashboard

## Features

- ✅ Dark/Light theme toggle
- ✅ 20-question digital audit
- ✅ AI-powered insights
- ✅ Gap analysis
- ✅ Revenue impact calculator
- ✅ Personalized recommendations
- ✅ Mobile responsive

## Tech Stack

- Pure HTML/CSS/JavaScript
- Google Fonts (Poppins + Inter)
- LocalStorage for theme persistence
- No build process required
