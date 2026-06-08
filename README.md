# NIHR Email Launcher — Leeds BRC

A lightweight standalone web page that opens pre-filled emails in your default email app with a single click. Built for Kevin Ohuchukwu, Information, Impact and Reporting Coordinator, NIHR Leeds Biomedical Research Centre.

---

## What it does

Two email launcher buttons — one per email template. Click a button, your email app opens with the subject line and full body pre-filled. You only need to:

1. Change **Dear [Name]** to the recipient's name
2. Add the recipient's email address
3. Attach any files
4. Hit **Send**

No retyping. No copy-pasting. Every time.

---

## Email templates included

### Email 1 — ACD / Theme objectives & impact stories
- **Subject:** ACD input needed for NIHR annual reporting for your workstream
- **Content:** Requests Theme leads to update Theme objectives (columns Q–U) and submit an Impact story draft by 1st May

### Email 2 — University of Leeds BRC-funded staff spreadsheet
- **Subject:** University of Leeds input needed for NIHR annual reporting
- **Content:** Requests contacts to complete the staff spreadsheet for all BRC-funded University of Leeds staff, with full NIHR guidance notes, due by 8th May

---

## How to use

### Option A — Open locally
Double-click `index.html` to open it in your browser. The buttons work offline — no internet required.

### Option B — Host on GitHub Pages (recommended)
1. Create a new **public** GitHub repository
2. Upload `index.html` (must be named exactly `index.html`)
3. Go to **Settings → Pages**
4. Set source to **Deploy from branch → main → / (root)**
5. Save — your live URL will be: `https://yourusername.github.io/your-repo-name`

Share that URL with your client. They bookmark it and use it any time.

---

## How to update email content

Open `index.html` in any text editor (Notepad, VS Code, etc.) and find the `openEmail1()` or `openEmail2()` JavaScript functions. Edit the text inside the `encodeURIComponent(...)` block. Save and re-upload to GitHub — the page updates immediately.

---

## Tech stack

- Pure HTML, CSS, JavaScript — no frameworks, no dependencies
- Google Fonts (DM Sans) loaded via CDN
- Works in all modern browsers
- `mailto:` protocol — opens whatever email app is set as default (Outlook, Gmail, Apple Mail, etc.)

---

## File structure

```
index.html      ← the entire app (single file)
README.md       ← this file
```

---

## Built by
Princewill a.k.a (Bobprince).
