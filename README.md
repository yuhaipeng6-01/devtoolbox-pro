# DevToolbox Pro — Developer Utilities

A set of 11 essential developer tools with a Pro tier.
Built as a single HTML file for instant deployment.

## 🚀 One-Click Deploy

### Deploy to Vercel (Free)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/devtoolbox)

Or manually:
```bash
npm i -g vercel
vercel deploy devtoolbox.html
```

### Deploy to Netlify (Free)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/YOUR_USERNAME/devtoolbox)

Or drag-and-drop `devtoolbox.html` to https://app.netlify.com/drop

### Deploy to GitHub Pages (Free)
1. Push to a GitHub repo
2. Go to Settings → Pages → Deploy from main branch

## 💰 Monetization Setup

### Stripe Integration
1. Create a [Stripe account](https://stripe.com)
2. Create a Payment Link for $9/month subscription
3. Replace `PLACEHOLDER` in the `handleUpgrade()` function with your Stripe Payment Link URL
4. That's it — payments flow directly to your Stripe account

### Alternative: Buy Me a Coffee / Ko-fi
Replace `handleUpgrade()` with your Ko-fi or Buy Me a Coffee URL.

## 🛠 Tools Included

### Free
- JSON Formatter (pretty-print & minify)
- Base64 Encoder / Decoder
- URL Encoder / Decoder
- UUID Generator (v4)
- Lorem Ipsum Generator
- Color Converter (HEX ↔ RGB ↔ HSL)

### Pro ($9/month)
- JWT Debugger
- Regex Tester with highlighting
- Cron Expression Parser
- Hash Generator (MD5, SHA-1, SHA-256)
- Diff Checker
- Priority support

## 🔒 Privacy

All processing happens in your browser. No data is ever sent to a server.

## 📈 Revenue Potential

At $9/month per Pro user:
- 10 users = $90/month
- 100 users = $900/month
- 1,000 users = $9,000/month

Market your tool on:
- Product Hunt
- Reddit (r/webdev, r/programming)
- Hacker News
- Dev.to
- Twitter/X
