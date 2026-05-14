# PHC 2025 Annual Report Microsite

## Files
- `index.html` — main page
- `images/` — all photos
- `vercel.json` — Vercel routing config

## Deploying to Vercel
1. Push this folder to a GitHub repo
2. Connect the repo in Vercel
3. Deploy — no build step needed, it's static HTML

## Adding the video
In `index.html`, find the comment `<!-- VIDEO SWAP -->` and replace the placeholder div with:
```html
<iframe 
  src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
  width="100%" height="100%"
  style="border:0;border-radius:12px"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen
  title="Patterson Health Center 2025 Annual Report video">
</iframe>
```

## Photo credits
Photos extracted from the PHC 2025 Annual Report PDF. Cover photo by JC Photos.
