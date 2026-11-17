# ACU Online MBA – Programme Landing Page

A static, single-page site (HTML + CSS + JS, no build step) with programme details for the Adichunchanagiri University Online MBA.

## Structure
```
index.html          # the whole page (styles and scripts inline)
assets/
  acu-logo.png      # university logo
  hero.jpg          # hero model photo (replace with your South Indian model image, same name)
  campus.jpg
  chancellor.jpg
  logos/*.png       # alumni employer logos (scrolling strip)
vercel.json
```

## Deploy on Vercel
1. Push this repo to GitHub.
2. On vercel.com, click **Add New → Project** and import the repo.
3. Framework preset: **Other**. Leave the build command empty and the output directory as `./`.
4. Click **Deploy**. Every later push to `main` redeploys automatically.

## Connecting the lead form
Search `index.html` for `CONNECT YOUR LEAD BACKEND HERE` and send `data` to your CRM, webhook or Google Sheet there.

## Swapping images
Replace a file in `assets/`, keeping the same file name, then commit and push.
