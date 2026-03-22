# CreatorLink

Your personal links page. Built with CreatorLink Builder.

---

## Files

```
creatorlink/
├── index.html       ← Your main page
├── themes.html      ← Visual theme picker gallery
├── Scripts/
│   └── app.js       ← Page engine
└── Styles/
    └── styles.css   ← Styles
```

---

## Hosting on GitHub Pages (free)

1. Create a new repo on github.com (public)
2. Push this folder:
```bash
git init
git add .
git commit -m "my site"
git remote add origin https://github.com/YOURUSERNAME/REPONAME.git
git push -u origin main
```
3. Go to repo Settings → Pages → Deploy from `main` branch root
4. Your site goes live at: `https://YOURUSERNAME.github.io/REPONAME`

---

## Custom Domain (optional, ~$10/yr)

Buy from Namecheap / Porkbun / Cloudflare Registrar.

1. Create a `CNAME` file in this folder containing just your domain:
```
yourdomain.com
```
2. In your DNS settings add these A records:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
And a CNAME record: `www` → `YOURUSERNAME.github.io`

3. In GitHub Pages settings, enter your custom domain and tick Enforce HTTPS.
4. DNS propagation takes up to 24hrs.

---

## Making Changes

To update your site, go back to the **CreatorLink Builder**, make your changes, and download a new zip. Replace the files in your repo and push — your live site updates automatically.

You can also switch themes any time using the palette button on your page, or by visiting `themes.html`.

---

Built with CreatorLink · github.com/Kill3rKai/creatorlink