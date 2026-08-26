# TRANSCEND Polska - Weekly Reports Website

Welcome to the official TRANSCEND Polska website for sharing weekly reports!

## Features

✅ **PDF Viewer** - View PDFs directly in your browser  
✅ **Download Option** - Download any report with one click  
✅ **Mobile Friendly** - Works on phones, tablets, and desktops  
✅ **Automatic Listing** - Reports are automatically discovered from the `reports/` folder  
✅ **Free Hosting** - Powered by GitHub Pages  

## How to Upload Weekly Reports

1. **Go to the `reports/` folder** in this repository
2. **Click "Add file" → "Upload files"**
3. **Drag and drop your PDF files**
4. **Commit the changes**
5. **Done!** Your reports will appear on the website within minutes

### Naming Convention (Optional)
For better organization, name your files like:
- `report-2026-08-26.pdf`
- `weekly-report-week-35.pdf`
- Or any naming scheme you prefer

The reports will appear in reverse alphabetical order (newest first).

## Setup Your Custom Domain

1. Go to **Settings** → **Pages**
2. Under "Custom domain", enter your domain (e.g., `TRANSCENDPolska.com`)
3. Follow GitHub's DNS setup instructions for your domain registrar
4. GitHub will verify and enable HTTPS automatically

## File Structure

```
michal-czarnecki-transcend.github.io/
├── index.html          (Main page)
├── style.css           (Styling)
├── reports/            (Your PDF files go here)
│   ├── report-2026-08-26.pdf
│   ├── report-2026-08-19.pdf
│   └── ...
└── README.md
```

## Technical Details

- **PDF Viewer**: Uses PDF.js (Mozilla's free, open-source library)
- **Hosting**: GitHub Pages (free)
- **HTTPS**: Automatic via GitHub
- **Updates**: Real-time (changes appear within minutes)

## Troubleshooting

**Reports not appearing?**
- Make sure files are in the `reports/` folder
- Check that they end with `.pdf`
- Wait a few minutes for the cache to update

**Custom domain not working?**
- Verify DNS records are correctly set at your registrar
- Check Settings → Pages for any errors
- DNS changes can take up to 48 hours

## Need Help?

Check out GitHub's documentation:
- [GitHub Pages Setup](https://docs.github.com/en/pages)
- [Custom Domain Configuration](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

**Last Updated**: August 26, 2026