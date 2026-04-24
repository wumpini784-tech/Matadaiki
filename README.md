# Tadaaiki Foundation Website – CMS Setup Guide

## 📁 Files Included
- `index.html` – Your main website
- `admin/index.html` – CMS admin panel
- `admin/config.yml` – CMS configuration
- `netlify.toml` – Netlify settings
- `images/` – Upload your images here

---

## 🚀 One-Time Setup on Netlify (5 minutes)

### Step 1 – Connect to a Git repo
1. Push all these files to a GitHub repository
2. In Netlify: **Add new site → Import from Git → Choose your repo**

### Step 2 – Enable Netlify Identity
1. In your Netlify dashboard, go to **Site Settings → Identity**
2. Click **Enable Identity**
3. Under **Registration**, set to **Invite only** (recommended)
4. Scroll to **Services → Git Gateway** → Click **Enable Git Gateway**

### Step 3 – Invite yourself as admin
1. In **Identity tab** → Click **Invite users**
2. Enter your email address
3. Check your email and accept the invite
4. Set your password

### Step 4 – Deploy your site
1. Drag and drop this entire folder onto Netlify, OR push to GitHub
2. Your site will be live

---

## ✏️ How to Edit Your Website

1. Go to `https://yoursite.netlify.app/admin`
2. Log in with your email and password
3. You'll see a dashboard with sections:
   - **⚙️ Site Settings** – Name, email, phone, social links
   - **🏠 Hero Section** – Main banner text, image, stats
   - **ℹ️ About Section** – About text and image
   - **📋 Programs** – Add/edit/delete programs
   - **👥 Team Members** – Add/edit team photos and bios
   - **📰 News & Blog** – Write and publish articles
   - **📊 Impact Numbers** – Update your stats
   - **💝 Donate Section** – Donation amounts and payment details

4. Make your changes and click **Publish** — the site updates automatically!

---

## 🖼️ How to Change Images
1. Log in to `/admin`
2. Click on the section with the image (e.g. Hero, About, Team)
3. Click the image field → **Choose an image** or **Upload**
4. Select your new image file
5. Click **Save** then **Publish**

---

## ❓ Need Help?
Contact your web developer or refer to Decap CMS docs at https://decapcms.org/docs
