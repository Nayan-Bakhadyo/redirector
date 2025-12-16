# UCO Foundation Redirector

A simple static HTML page that redirects to internal services.

## Services

- **Backend (RE)**: http://10.98.39.123:8000
- **Frontend (FE)**: http://10.98.39.123:8001

## Deployment Options

### 1. GitHub Pages
1. Create a new GitHub repository
2. Upload `index.html`
3. Go to Settings → Pages → Enable GitHub Pages
4. Your page will be available at `https://yourusername.github.io/repo-name`

### 2. Vercel
```bash
npm i -g vercel
vercel
```

### 3. Netlify
1. Drag and drop the folder on netlify.com/drop
2. Or use Netlify CLI:
```bash
npm i -g netlify-cli
netlify deploy
```

### 4. Simple HTTP Server (Local Testing)
```bash
# Python 3
python3 -m http.server 3000

# Node.js
npx serve
```

Then open `http://localhost:3000` in your browser.

## Features

- Clean, modern UI
- Mobile responsive
- Smooth animations
- Clear service identification
- One-click redirects

## Customization

Edit `index.html` to:
- Change colors (modify the CSS gradient values)
- Update service names
- Modify IP addresses/ports
- Add more services
