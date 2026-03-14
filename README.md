# CDS Tracker - Charity & Gender CDS
## Aba North LGA - Monthly Dues Management System

A comprehensive web application for managing CDS monthly dues, attendance tracking, and financial reporting.

---

## 🚀 DEPLOYMENT GUIDE - VERCEL (15 MINUTES)

### **Step 1: Create Accounts (5 minutes)**

#### A) Create GitHub Account
1. Go to https://github.com
2. Click "Sign up"
3. Enter your email, create password
4. Choose a username
5. Verify your email
6. ✅ Done!

#### B) Create Vercel Account
1. Go to https://vercel.com
2. Click "Sign Up"
3. Click "Continue with GitHub" (use your new GitHub account)
4. Authorize Vercel
5. ✅ Done!

---

### **Step 2: Upload Project to GitHub (5 minutes)**

#### Option A: Using GitHub Website (Easiest)

1. **Go to GitHub** (https://github.com)
2. **Click the "+" button** (top right) → "New repository"
3. **Fill in details:**
   - Repository name: `cds-tracker`
   - Description: "CDS Monthly Dues Tracker"
   - Make it **Public**
   - ✅ Check "Add a README file"
4. **Click "Create repository"**
5. **Upload files:**
   - Click "Add file" → "Upload files"
   - Drag ALL files from the `deployment` folder
   - Click "Commit changes"
6. ✅ Done!

#### Option B: Using Git Command Line (If you know Git)

```bash
# In the deployment folder
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/cds-tracker.git
git push -u origin main
```

---

### **Step 3: Deploy to Vercel (5 minutes)**

1. **Go to Vercel** (https://vercel.com/dashboard)
2. **Click "Add New Project"**
3. **Import your GitHub repository:**
   - You should see `cds-tracker` in the list
   - Click "Import"
4. **Configure project:**
   - Project Name: `cds-tracker` (or choose your own)
   - Framework Preset: Vite (should auto-detect)
   - Root Directory: `./` (leave as is)
   - Build Command: `npm run build` (should be auto-filled)
   - Output Directory: `dist` (should be auto-filled)
5. **Click "Deploy"**
6. **Wait 2-3 minutes** for deployment to complete
7. **🎉 You'll get a live URL!** (e.g., `cds-tracker.vercel.app`)

---

## 🎯 AFTER DEPLOYMENT

### **Your Live App:**

You'll get a URL like:
- `https://cds-tracker.vercel.app`
- or `https://cds-tracker-YOUR_USERNAME.vercel.app`

### **Share with Members:**

Send this message to your CDS WhatsApp group:

```
📱 CDS DUES TRACKER NOW LIVE!

Check your CDS dues anytime at:
https://cds-tracker.vercel.app

Login Instructions:
1. Select your Batch (A, B, or C)
2. Enter your 4-digit State Code
3. Enter last 4 digits of your phone
4. Enter your password

President Login:
- Use 0000 for phone digits
- Use your setup password

Questions? Contact the President.

Charity & Gender CDS - Aba North LGA
```

---

## 📱 USING THE APP

### **President First Login:**
1. Visit your Vercel URL
2. Complete president setup:
   - Choose batch
   - Enter 4-digit state code
   - Create password
3. Login with your credentials (use 0000 for phone digits)

### **Adding Members:**
1. Go to "Members" tab
2. Click "Add Member"
3. Fill in:
   - Name
   - Phone
   - Batch
   - 4-digit State Code
   - Year
4. System generates login credentials
5. Share with member

### **Member Login:**
1. Visit the Vercel URL
2. Select batch
3. Enter state code
4. Enter last 4 digits of phone
5. Enter password (default is last 4 of phone)

---

## 🔧 TROUBLESHOOTING

### **Issue: App not loading**
- Wait 5 minutes, Vercel might still be building
- Check your Vercel dashboard for deployment status
- Make sure all files were uploaded to GitHub

### **Issue: Files missing on GitHub**
- Re-upload all files from the deployment folder
- Make sure you uploaded the entire folder structure

### **Issue: Build failed on Vercel**
- Check the build logs in Vercel dashboard
- Make sure package.json was uploaded
- Try redeploying

---

## 📂 PROJECT STRUCTURE

```
cds-tracker/
├── index.html          # Main HTML file
├── package.json        # Dependencies
├── vite.config.js      # Build configuration
├── vercel.json         # Vercel settings
├── .gitignore          # Git ignore file
└── src/
    ├── main.jsx        # React entry point
    └── App.jsx         # Main application
```

---

## 🎁 FEATURES

✅ President Dashboard
✅ Member Portal
✅ Batch Selection (A, B, C)
✅ 4-digit State Code System
✅ Attendance Tracking (Week 2, 3, 4)
✅ Financial Reports
✅ Excel Export
✅ WhatsApp Message Generator
✅ Cloud Storage (Browser)
✅ Mobile Responsive

---

## 🔐 SECURITY

- President has full access
- Members see only their own data
- Passwords are required
- All data saved in browser storage
- (Phase 2 will add Firebase for true cloud sync)

---

## 📞 SUPPORT

Questions? Issues? Contact:
- President: Walter Tamunopribo
- CDS: Charity & Gender, Aba North LGA

---

## 🚀 WHAT'S NEXT (Phase 2)

Coming soon:
- Real-time cloud database (Firebase)
- Executive roles (VP, Treasurer, etc.)
- Financial tracking
- Payment verification
- Welfare requests
- Multi-device sync

---

## 📝 LICENSE

© 2024 Charity & Gender CDS - Aba North LGA
For internal CDS use only.
