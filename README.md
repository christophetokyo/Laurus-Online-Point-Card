# Point Card System / ポイントカードシステム

Interactive point card system for schools.

## GitHub Pages Setup Guide (Step-by-Step)

### Step 1: Create a GitHub Account
1. Go to https://github.com and click "Sign up"
2. Create a free account with your email

### Step 2: Create a Repository
1. Click the "+" icon (top-right) → "New repository"
2. Name it: `point-cards`
3. Make sure "Public" is selected
4. Check "Add a README file"
5. Click "Create repository"

### Step 3: Upload the Files
1. In your new repository, click "Add file" → "Upload files"
2. Drag and drop ALL files from this folder:
   - `index.html`
   - `cards/` folder (with mage.png inside)
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository's "Settings" tab
2. In the left sidebar, click "Pages"
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes, then your site is live at:
   `https://YOUR-USERNAME.github.io/point-cards/`

### Step 5: Share with Teachers
Send the URL to all teachers. They can:
- Open it in any browser (Chrome, Safari, etc.)
- Add students and track points
- Share individual student URLs
- Export/import data for backup

## Adding New Card Designs
1. Create your card design image (same layout as mage.png)
2. Upload it to the `cards/` folder (e.g., `cards/warrior.png`)
3. Edit `index.html` and add the new design to the CARD_DESIGNS object
   (or ask your developer to do it)

## Notes
- Data saves in each teacher's browser automatically
- Use Export/Import to share data between teachers
- Each student can have multiple cards (when they exceed 100 points)
