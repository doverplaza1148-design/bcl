# Bay City Laundrymat – GitHub Pages Website

Live website for **Bay City Laundrymat**, Perth Amboy, NJ.

---

## 📁 Folder Structure

```
/
├── index.html          ← Main webpage (upload this as-is)
├── README.md           ← This file
└── images/             ← Create this folder and add all images below
    ├── hero-laundry.jpg
    ├── service-wash-fold.jpg
    ├── service-self-service.jpg
    ├── service-commercial.jpg
    ├── service-pickup.jpg
    ├── strip-fresh.jpg
    ├── strip-machine.jpg
    ├── about-interior.jpg
    ├── step-schedule.jpg
    ├── step-pickup.jpg
    └── step-delivered.jpg
```

---

## 🖼️ Image Downloads

Download each image from Unsplash and save it to your `images/` folder using the exact filename listed.

| Filename | Unsplash URL |
|---|---|
| `hero-laundry.jpg` | https://images.unsplash.com/photo-1545173168-9f1947eebb7f?w=1920&q=80 |
| `service-wash-fold.jpg` | https://images.unsplash.com/photo-1582735689369-4fe89db7114c?w=700&q=80 |
| `service-self-service.jpg` | https://images.unsplash.com/photo-1604335399105-a0c585fd81a1?w=700&q=80 |
| `service-commercial.jpg` | https://images.unsplash.com/photo-1558618666-fcd25c85cd64?w=700&q=80 |
| `service-pickup.jpg` | https://images.unsplash.com/photo-1581578017093-cd30fce4eeb7?w=700&q=80 |
| `strip-fresh.jpg` | https://images.unsplash.com/photo-1527515637462-cff94aca3f53?w=800&q=80 |
| `strip-machine.jpg` | https://images.unsplash.com/photo-1521656958802-278837a5ea13?w=800&q=80 |
| `about-interior.jpg` | https://images.unsplash.com/photo-1489274495757-95c7c837b101?w=900&q=80 |
| `step-schedule.jpg` | https://images.unsplash.com/photo-1611532736597-de2d4265fba3?w=140&q=80 |
| `step-pickup.jpg` | https://images.unsplash.com/photo-1568702846914-96b305d2aaeb?w=140&q=80 |
| `step-delivered.jpg` | https://images.unsplash.com/photo-1529374255404-311a2a4f1fd9?w=140&q=80 |

> **Note:** `hero-laundry.jpg` is used in three places (hero background, image strip, and strip-3). You only need one copy.

---

## 🚀 Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `baycity-laundrymat`)
2. Upload `index.html`, `README.md`, and the `images/` folder
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)` folder
5. Click **Save** — your site will be live at:  
   `https://YOUR-USERNAME.github.io/baycity-laundrymat/`

---

## ✏️ What Was Changed from the Original

- All 11 Unsplash image URLs replaced with local `images/` paths
- Cloudflare email obfuscation replaced with plain `mailto:info@baycitylaundrymat.com`
- Cloudflare email-decode script removed (no longer needed)
- All other content, styles, and functionality are unchanged

---

## 📧 Updating the Email Address

If `info@baycitylaundrymat.com` is not the correct email, search for it in `index.html` and replace both occurrences (the `href` and the visible text).
