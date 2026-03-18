# Point Card System — Setup Guide

## What You Need
- A Google account (for Firebase — free)
- A GitHub account (for hosting — free)

---

## PART 1: Create Firebase Database (5 minutes)

### Step 1: Go to Firebase Console
1. Open https://console.firebase.google.com/
2. Sign in with your Google account
3. Click "Create a project" → Name it: point-cards
4. Disable Google Analytics → Click Create project

### Step 2: Create the Database
1. Click "Build" in the left sidebar → "Realtime Database"
2. Click "Create Database"
3. Choose closest location → Select "Start in test mode" → Enable
4. Copy the URL shown (like: https://point-cards-xxxxx-default-rtdb.firebaseio.com/)

### Step 3: Set Security Rules
1. Click the "Rules" tab
2. Replace with:   {"rules": {".read": true, ".write": true}}
3. Click Publish

---

## PART 2: Set Up GitHub Pages (5 minutes)

### Step 1: Create GitHub Account
Go to https://github.com → Sign up (free)

### Step 2: Create Repository
Click "+" → "New repository" → Name: point-cards → Public → Add README → Create

### Step 3: Upload Files
Click "Add file" → "Upload files" → Drag index.html and cards/ folder → Commit

### Step 4: Enable GitHub Pages
Settings → Pages → Source: main → Save
Your site: https://YOUR-USERNAME.github.io/point-cards/](https://christophetokyo.github.io/Laurus-Online-Point-Card

---

## PART 3: First-Time App Setup (1 minute)

1. Open your GitHub Pages URL
2. Paste your Firebase Database URL　https://loa-pointcards-default-rtdb.asia-southeast1.firebasedatabase.app/
3. Choose a teacher password　laurusoa2026
4. Click Save and Start — done!

---

## Adding New Card Designs

1. Create new card image (same layout as Mage card)
2. Upload to cards/ folder in GitHub
3. Ask your developer to add a few lines to the CARD_DESIGNS section in index.html
