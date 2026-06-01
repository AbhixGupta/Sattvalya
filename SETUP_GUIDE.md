# 🚀 Sattvalya Saar - Deployment & Setup Guide

## ✅ What's Already Done

- ✅ GitHub repository created (AbhixGupta/Sattvalya)
- ✅ Version 2 with Pinterest-inspired enhancements merged to main
- ✅ Original version backed up in `original` branch
- ✅ Contact form integrated (Web3Forms)
- ✅ WhatsApp integration ready
- ✅ Thank you page created

---

## 📋 3 Things You Need to Complete

### 1️⃣ Get Web3Forms Access Key (2 minutes, FREE)

**Steps:**
1. Go to https://web3forms.com
2. Enter your email address where you want to receive form submissions
3. Click "Create Access Key"
4. Copy the access key (looks like: `a1b2c3d4-e5f6-g7h8-i9j0-k1l2m3n4o5p6`)

**Then update the website:**
- Open `index.html`
- Find line with: `<input type="hidden" name="access_key" value="YOUR_WEB3FORMS_ACCESS_KEY_HERE">`
- Replace `YOUR_WEB3FORMS_ACCESS_KEY_HERE` with your actual key

**Why Web3Forms?**
- ✅ Completely FREE, unlimited submissions
- ✅ No signup required initially
- ✅ Emails arrive instantly to your inbox
- ✅ No database or backend needed

---

### 2️⃣ Update WhatsApp Number (1 minute)

**Steps:**
1. Get your WhatsApp Business number (same number you use normally is fine)
2. Format: Country code + number (no spaces, dashes, or + sign in the URL)
   - Example: For +91 98765 43210 → use `919876543210`

**Then update in 3 places in `index.html`:**

Search and replace all instances of `919876543210` with your actual number:
- Line ~1762: Phone display
- Line ~1785: "Book on WhatsApp" button
- Line ~1847: Footer WhatsApp link

**Also update `thank-you.html`:**
- Replace `919876543210` with your number

**Pro Tip:** Download WhatsApp Business app for better customer management
- Auto-replies when you're busy
- Business profile with hours, location
- Message labels and quick replies

---

### 3️⃣ Replace Vaidya Photo (1 minute)

**Requirements:**
- Professional photo of Vaidya Neha
- Recommended: Traditional attire (saree/salwar), natural background
- Format: JPG or PNG
- Size: 800-1200px wide (portrait orientation preferred)

**Steps:**
1. Save the photo as `vaidya-photo.jpg` in the project folder
2. Replace the current placeholder file
3. Done! The website will automatically use it

**Current placeholder:** Dog photo (temporary) - just overwrite this file

---

## 🌐 Deploy to GitHub Pages (5 minutes)

### Option A: Via GitHub Website (Easier)

1. Go to https://github.com/AbhixGupta/Sattvalya
2. Click **Settings** (top right)
3. Click **Pages** (left sidebar)
4. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 2-3 minutes
7. Your website will be live at: **https://abhixgupta.github.io/Sattvalya/**

### Option B: Via Command Line (You're Already Set Up!)

```bash
# Just push your changes (already done)
git add .
git commit -m "Add form integration and deployment setup"
git push origin main
```

Then enable GitHub Pages via the website (steps above).

---

## 📧 Update Email & Address (Optional but Recommended)

**Current placeholders:**
- Email: `contact@sattvalyasaar.com`
- Phone: `+91 98765 43210`
- Address: `123 Wellness Lane, Mumbai, Maharashtra 400001`

**Update these in 2 files:**
1. `index.html` (Contact section around line 1760-1780)
2. `thank-you.html` (Footer if you added one)

**Professional Email Options:**
- **FREE:** Gmail (yourname@gmail.com)
- **Custom Domain ($4/month):** Google Workspace (contact@sattvalyasaar.com)
  - Requires buying domain: sattvalyasaar.com (~₹800/year from GoDaddy/Namecheap)

---

## 🎯 Complete Launch Checklist

Before announcing your website to patients:

- [ ] ✅ Get Web3Forms access key and update `index.html`
- [ ] ✅ Update WhatsApp number in `index.html` and `thank-you.html`
- [ ] ✅ Replace `vaidya-photo.jpg` with real photo
- [ ] ✅ Update email, phone, and clinic address
- [ ] ✅ Test the contact form (submit a test entry)
- [ ] ✅ Test WhatsApp button (click and verify it opens WhatsApp)
- [ ] ✅ Enable GitHub Pages in repository settings
- [ ] ✅ Visit your live website and test on mobile
- [ ] ✅ Share the link! 🎉

---

## 🧪 Testing Your Website

### Test Form Submission:
1. Go to your website
2. Scroll to "Book Your Consultation" form
3. Fill it out completely
4. Submit
5. Check if you receive an email from Web3Forms

### Test WhatsApp Integration:
1. Click "Book on WhatsApp" button
2. Should open WhatsApp with pre-filled message
3. If not working, double-check the phone number format

### Test on Multiple Devices:
- [ ] Desktop (Chrome, Safari, Firefox)
- [ ] Mobile (iPhone/Android)
- [ ] Tablet (iPad)

---

## 🔧 Troubleshooting

### Form Not Sending Emails?
- ✅ Double-check the Web3Forms access key is correct
- ✅ Check your spam/junk folder
- ✅ Verify email address in Web3Forms dashboard

### WhatsApp Button Not Working?
- ✅ Remove any spaces, dashes, or special characters from phone number
- ✅ Format: 91XXXXXXXXXX (country code + number)
- ✅ Make sure WhatsApp is installed on the device you're testing

### Website Not Loading After Deployment?
- ✅ Wait 5-10 minutes for GitHub Pages to build
- ✅ Clear your browser cache (Ctrl+Shift+R / Cmd+Shift+R)
- ✅ Check GitHub Pages status in Settings > Pages

### Images Not Showing?
- ✅ Make sure file names match exactly (case-sensitive!)
- ✅ `vaidya-photo.jpg` not `Vaidya-Photo.JPG`
- ✅ File should be in the root folder, not in a subfolder

---

## 🎨 Future Enhancements (Optional)

After launch, you can add:
- [ ] Custom domain (sattvalyasaar.com)
- [ ] Google Analytics for tracking visitors
- [ ] Online booking system (Calendly integration)
- [ ] Blog section for Ayurvedic tips
- [ ] Instagram feed integration
- [ ] Video testimonials
- [ ] Before/after patient galleries (with consent)

---

## 💰 Cost Summary

| Item | Free Option | Premium Option |
|------|-------------|----------------|
| **Hosting** | GitHub Pages (FREE) | Netlify/Vercel (FREE) |
| **Form Handling** | Web3Forms (FREE) | Formspree ($10/mo) |
| **Email** | Gmail (FREE) | Google Workspace ($6/mo) |
| **Domain** | .github.io subdomain (FREE) | Custom .com ($12/year) |
| **WhatsApp** | WhatsApp Business (FREE) | WhatsApp Business API ($?) |
| **TOTAL/month** | **₹0** | **₹500-1000** |

**Recommended for Starting:** Stick with 100% FREE setup. Upgrade later when you have regular patients.

---

## 📞 Need Help?

If you run into any issues:
1. Check this guide first
2. Google the specific error message
3. Ask Claude Code for help! 😊

---

## 🙏 You're Almost There!

Just need:
1. 📧 Email for Web3Forms
2. 📱 WhatsApp number
3. 📸 Vaidya photo

Then you're **LIVE**! 🚀

---

**Last Updated:** June 2026
**Website:** https://abhixgupta.github.io/Sattvalya/ (once deployed)
**Repository:** https://github.com/AbhixGupta/Sattvalya
