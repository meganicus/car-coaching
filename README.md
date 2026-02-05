# Bay Area Car Buying Coaching Website

Professional website for car buying coaching services.

## 🚀 Quick Deploy to GitHub Pages

1. **Upload this repository to GitHub**
2. **Go to Settings → Pages**
3. **Source: Deploy from branch → main → root**
4. **Save**
5. Your site will be live at: `yourusername.github.io/repo-name`

## 📁 Files Included

- `index.html` - Main website file (complete, ready to deploy)
- `README.md` - This file

## 🌐 Custom Domain Setup

To use `bayareacarcoaching.com`:

1. In your GitHub repo: Settings → Pages → Custom domain
2. Enter: `bayareacarcoaching.com`
3. In Cloudflare DNS, add:
   - Type: `CNAME`
   - Name: `www`
   - Target: `yourusername.github.io`
   - Proxy: Off (gray cloud)
   
   - Type: `A` (4 records for apex domain)
   - Name: `@`
   - IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`

## 🔧 Customization

### Update Form Links
Replace the Google Form URL with your booking link (Calendly, Typeform, etc.):

Find and replace in `index.html`:
```
https://docs.google.com/forms/d/e/1FAIpQLSdHerr9h0rRJgt8zNPUrA-nrnOx79uLiw4KZsKA4uRNvIrBzw/viewform
```

With your new form/booking URL.

### Change Colors
- Primary Blue: `#2563eb`
- Text Gray: `#64748b`
- Background Gray: `#f8fafc`

Search and replace these hex codes in `index.html` to change the color scheme.

### Update Content
All content is directly in `index.html` - just edit the text between HTML tags.

## 📝 License

© 2026 Bay Area Car Buying Coaching. All rights reserved.
