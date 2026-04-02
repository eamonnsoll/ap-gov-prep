# AP Gov Exam Prep

A fully self-contained AP U.S. Government and Politics exam prep web app.

## Live App

👉 **[Open the App](https://eamonnsoll.github.io/ap-gov-prep/)**

*(Replace `YOUR-USERNAME` with your actual GitHub username after deploying)*

---

## Features

- **210 quiz questions** across all 5 AP Gov units (42 per unit), randomly pulled
- **Study Notes** — full content notes for each unit, readable before quizzing
- **15 required SCOTUS cases** with full facts, holdings, significance, and FRQ tips
- **9 foundational documents** with context, main claims, and essay strategies
- **FRQ Lab** — all 4 FRQ types with rubrics, timers, and scaffolds
- **AI Grading** — free Gemini AI grades student FRQ responses with rubric feedback
- **Progress tracking** — accuracy by unit, skill, cases, and documents
- **Dark mode** — toggle in the top right corner

---

## Deploying to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Account
Go to [github.com](https://github.com) and sign up for a free account if you don't have one.

### Step 2 — Create a New Repository
1. Click the **+** icon in the top right → **New repository**
2. Name it `ap-gov-prep` (or anything you like)
3. Set it to **Public**
4. Leave everything else at defaults
5. Click **Create repository**

### Step 3 — Upload the File
1. On your new repository page, click **Add file** → **Upload files**
2. Drag and drop `index.html` into the upload area
3. Scroll down and click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Click the **Settings** tab in your repository
2. In the left sidebar, click **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** and **/ (root)**
5. Click **Save**

### Step 5 — Get Your Link
Wait 1-2 minutes, then refresh the Pages settings page. Your app URL will appear:
```
https://YOUR-USERNAME.github.io/ap-gov-prep/
```

Share this link with your students. It works on any device with a browser — phone, tablet, Chromebook, laptop.

---

## Setting Up AI Grading (Free)

The FRQ Lab includes AI-powered grading using Google Gemini — completely free, no credit card required.

### Get a Free API Key
1. Go to [aistudio.google.com](https://aistudio.google.com)
2. Sign in with a **personal** Google account (not a school/district account — those may have Gemini disabled by the administrator)
3. Click **Get API key** in the top left
4. Click **Create API key**
5. Copy the key — it starts with `AIza`

### Enter the Key in the App
1. Open the app and go to the **FRQ Lab** tab
2. Scroll to the bottom of any FRQ — you'll see the **AI Grading Setup** box
3. Paste your key and click **Save Key**
4. The key is stored in your browser only — it never leaves your device

### Share with Students
Each student needs to enter their own free API key. Walk them through the steps above during the first FRQ Lab session. The free tier gives each account 1,500 grading requests per day — far more than any student will need.

---

## File Structure

```
ap-gov-prep/
└── index.html    ← The entire app (HTML + CSS + JavaScript in one file)
└── README.md     ← This file
```

Everything is in `index.html`. No build tools, no dependencies, no server required.

---

## Updating the App

When a new version of the app is available:
1. Go to your GitHub repository
2. Click on `index.html`
3. Click the pencil (edit) icon, or click **...** → **Delete file** and re-upload the new version
4. Commit the change — GitHub Pages updates automatically within a minute

---

## Customizing

The app is a single HTML file with clearly organized JavaScript sections. If you want to add questions, edit content notes, or modify FRQ prompts, open the file in any text editor (VS Code, Notepad++, TextEdit) and find the relevant data section near the top of the `<script>` block.

---

*Built for Virginia Beach City Public Schools AP Government classes.*
