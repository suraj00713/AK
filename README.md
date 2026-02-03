# Valentine's Day Puzzle Website for Akshara 💕

A romantic three-page experience with a jigsaw puzzle, upgraded Wordle game, and Valentine's proposal!

## 🎮 Features

### 🎯 Enhanced Wordle Challenge
- **4 Words to Guess**: Must guess all 4 five-letter words
- **6 Total Attempts**: Complete the challenge within 6 tries
- **Word Tracker**: Visual progress indicator showing which words are found
- **Reset Button**: Start over anytime
- **Smart Hints**: Color coding helps across all target words

### 📜 Scrollable Valentine Page
- Content now scrolls smoothly if text extends beyond viewport
- Custom styled scrollbar matching the theme
- Auto-scrolls to show "Reasons I love you" after clicking Yes

## 🚀 How to Deploy to GitHub Pages

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create your account

### Step 2: Create a New Repository
1. Click the **"+"** icon in the top right
2. Select **"New repository"**
3. Name it something like `valentine-akshara` or any name you want
4. Make sure it's set to **Public**
5. Click **"Create repository"**

### Step 3: Upload Your Files
1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop these 3 files:
   - `index.html` (Puzzle)
   - `wordle.html` (Wordle Game)
   - `valentine.html` (Proposal)
3. Click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to your repository's **Settings** (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"main"** branch
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 5: Get Your Website Link
Your site will be live at:
```
https://YOUR-USERNAME.github.io/valentine-akshara/
```

Replace `YOUR-USERNAME` with your GitHub username and `valentine-akshara` with your repository name!

## 🎮 How It Works

### Page 1: Puzzle (`index.html`)
- Solve the 8x8 jigsaw puzzle (64 pieces)
- Click pieces to swap positions
- Complete the image to proceed to Wordle

### Page 2: Wordle Game (`wordle.html`)
- Guess 4 five-letter words: **TULIP, HEART, ROSES, LOVED**
- You have 6 total attempts to find all 4 words
- Track your progress with the word indicators at the top
- Green tiles = correct letter in correct position
- Yellow tiles = correct letter in wrong position
- Gray tiles = letter not in any remaining word
- **Reset Button**: Click to restart the challenge
- Complete all 4 words to proceed to the final page

### Page 3: Valentine Proposal (`valentine.html`)
- The final question with a playful "No" button that runs away!
- Scrollable content to view all the reasons
- Beautiful animations and effects

## ✏️ Customization Guide

### Change the Wordle Words
Edit `wordle.html` around line 300:
```javascript
const TARGET_WORDS = ['TULIP', 'HEART', 'ROSES', 'LOVED'];
```
Replace with any 4 five-letter words you want!

### Change the Puzzle Image
The puzzle image is embedded as base64 data in `index.html`. To change it:
1. Use an image converter to convert your image to base64
2. Replace the `imageData` variable value in the JavaScript section

### Customize the Valentine Message
Edit `valentine.html`:
- **Name**: Change "Akshara" in the main heading
- **Love reasons**: Edit the list items in the "reasons" section
- **Button text**: Change "I love you BUBBA" in the JavaScript

## 💡 Tips

- Share the link with Akshara when ready
- The experience automatically progresses through each page
- Test the entire flow before sharing
- The puzzle image is embedded, so no external hosting needed!
- All content is scrollable and mobile-friendly

## 🎨 Features Summary

✅ Beautiful jigsaw puzzle
✅ 4-word Wordle challenge with tracker
✅ Reset functionality for Wordle
✅ Scrollable Valentine page
✅ Beautiful animations and effects
✅ Mobile responsive design
✅ Fully customizable content

## ❤️ Made with Love

Created as a special Valentine's Day surprise! 🌹

Enjoy the journey! 💕
