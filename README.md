# Confetti & Co. — Children's Party Planning Website

Professional website for Confetti & Co., a children's party planning service in Sawbridgeworth, Hertfordshire.

## 📁 Files

- **index.html** — Main website (responsive, all sections)
- **flyer.html** — Print-ready A4 flyer
- **admin-reviews.html** — Review management panel
- **netlify.toml** — Netlify configuration (forms & email setup)

## 🚀 Deploy to Netlify

### Option 1: Auto-Deploy from GitHub (Recommended)

1. **Create a GitHub repository**
   - Go to github.com and create a new repo named `confetti-website`
   - Choose "Public" or "Private"

2. **Push this code to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Confetti & Co website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/confetti-website.git
   git push -u origin main
   ```

3. **Connect to Netlify**
   - Go to app.netlify.com
   - Click "Add new site" → "Import an existing project"
   - Choose GitHub, authorize, and select your `confetti-website` repo
   - Netlify auto-detects the `netlify.toml` file
   - Deploy! 🎉

4. **Set custom domain** (optional)
   - In Netlify: Site settings → Domain management
   - Point `confettiandcoparties.co.uk` to your site

### Option 2: Manual Deploy (Drag & Drop)
- Drag the entire `confetti-website` folder onto Netlify
- Wait 30 seconds for deployment

## 📝 How Forms Work

### Feedback Form
- Users submit star rating, name, review, and optional photo
- Netlify sends verification email automatically
- Once verified, you see submission in Netlify dashboard
- Copy approved reviews into `admin-reviews.html`

### Enquiry Form
- Users submit contact details, party date, ideas
- Netlify sends verification email
- Once verified, notification goes to budai_reka@yahoo.com

## 👨‍💼 Manage Reviews

1. Go to your Netlify site → **Forms** tab
2. Click **"feedback"** to see all submissions
3. Open `admin-reviews.html` (locally or via your website)
4. Copy review details and click "Approve & Publish"
5. Reviews appear instantly on your website

## 📧 Email Notifications

- Users get verification emails from Netlify
- You get form notifications at budai_reka@yahoo.com
- Both are automatic — no setup required!

## ✨ Ready to Go

Your website includes:
- Fully responsive design (mobile, tablet, desktop)
- Party planning service information
- Pricing, FAQ, contact forms
- Admin panel for reviews
- Print-ready flyer

No backend needed — everything runs on static HTML + Netlify's free form handling.

---

**Questions?** Check the admin panel (`admin-reviews.html`) for step-by-step instructions.
