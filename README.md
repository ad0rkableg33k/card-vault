# 🃏 Card Vault — AI Sports Card Cataloger

> Upload photos of your sports card collection and let AI identify every card, extract all the details, and build you a spreadsheet ready for pricing research. **100% free — no credit card needed.**

**Live App → [ad0rkableg33k.github.io/card-vault](https://ad0rkableg33k.github.io/card-vault)**

---

## ✨ What It Does

- 📸 **Upload single cards or entire lot photos** — batch upload supported
- 🔄 **Front + Back pair mode** — scan both sides for maximum data accuracy
- 🤖 **AI reads every card** and extracts:
  - Player Name, Year, Brand / Manufacturer
  - Set Name, Card Number, Team, Position, Sport
  - Special Tags (Rookie Card, Autograph, Patch, Hall of Fame, etc.)
  - Birth Info, Condition Notes, and more
- ✏️ **Edit any field** in the results table before exporting
- 📊 **Export to CSV or Excel** — ready for any pricing tool or marketplace
- 🔗 **One-click price lookup** links per card:
  - 🔴 eBay Sold Listings
  - 🔵 eBay Active Listings
  - 🟢 130point.com
  - 🟣 Beckett
  - 🟠 COMC (Check Out My Cards)

---

## 🆓 Completely Free — Powered by Google Gemini

Card Vault uses **Google Gemini Flash** — Google's free AI vision model.

- ✅ No credit card required
- ✅ Just a Google account
- ✅ **1,500 free card scans per day**
- ✅ Get your key in about 2 minutes

---

## 🚀 How to Use

### Step 1 — Get Your Free Google Gemini API Key

1. Go to **[aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)**
2. Sign in with your **Google account** (Gmail, etc.)
3. Click **"Create API Key"** → **"Create API key in new project"**
4. Copy the key — it looks like `AIzaSy...`
   - You can always come back to this page to retrieve it again
5. Paste your key into the **API Key field** at the top of the app — it turns green when valid

> 🔒 Your API key stays in your browser only. It is never stored, sent to any server, or shared anywhere. Card Vault has no backend.

### 💰 Free Tier Limits

| Cards Scanned | Cost | Notes |
|---|---|---|
| 12 cards (one lot photo) | **$0.00** | Way under the limit |
| 100 cards | **$0.00** | Still free! |
| 500 cards | **$0.00** | Free tier is 1,500/day |
| 1,500 cards | **$0.00** | Max free scans per day |

Front + Back pair mode uses 2 images per card — so 750 pairs free per day. Very generous!

---

### Step 2 — Upload Your Card Photos

**Single / Batch Mode**
- Drag and drop one photo or many at once
- Great for lot photos showing multiple cards at once

**Front + Back Pair Mode**
- Drop all front photos in the left zone
- Drop all back photos in the right zone (match the order!)
- AI reads both sides — picks up card numbers, stats, birthplace, position, and more from the back

Supported formats: **JPG · PNG · WEBP · HEIC**

---

### Step 3 — Scan

Click **🔍 Scan All Cards**. Each card shows its status:
- **Pending** → waiting to be scanned
- **⏳ Scanning** → AI is reading it now
- **✓ Done** → data extracted successfully
- **✗ Error** → something went wrong (check your API key)

---

### Step 4 — Review & Edit

Results appear in a table. **Every cell is editable** — click any field to correct it. AI is very good but not perfect, especially on worn or sideways cards!

---

### Step 5 — Look Up Prices

Each card row has five price lookup buttons. Click any to open a pre-built search in a new tab:

| Button | What It Shows |
|---|---|
| 🔴 eBay Sold | Completed sold listings — best for real market value |
| 🔵 eBay Active | Current listings — what sellers are asking |
| 🟢 130point | Historical sales data with trend charts |
| 🟣 Beckett | Industry standard price guide |
| 🟠 COMC | Check Out My Cards marketplace |

---

### Step 6 — Export

- **⬇️ CSV** — works with Google Sheets, Excel, COMC uploads, etc.
- **⬇️ Excel** — includes a Summary tab with collection totals

---

## 🖥️ Hosting on GitHub Pages

1. Create a new GitHub repo named `card-vault` (Public, add a README)
2. Upload `index.html` to the repo root
3. Go to **Settings → Pages → Source: Deploy from branch → main / root**
4. Your app is live at `https://yourusername.github.io/card-vault` in ~2 minutes

---

## 🛠️ Running Locally

This is a single self-contained HTML file — zero install required.

```bash
git clone https://github.com/ad0rkableg33k/card-vault.git
cd card-vault
open index.html   # or just double-click the file
```

---

## 🗂️ Project Structure

```
card-vault/
├── index.html    # The entire app — one self-contained file
└── README.md     # This file
```

---

## 🤝 Credits

Built by **[ad0rkableg33k](https://github.com/ad0rkableg33k)** & **BabyyBat & G33KY**  
Powered by [Google Gemini Flash](https://deepmind.google/technologies/gemini/) · [SheetJS](https://sheetjs.com) for Excel export

---

## 📬 Feedback & Issues

Found a bug or have a feature idea? [Open an issue](https://github.com/ad0rkableg33k/card-vault/issues) on GitHub!

---

*Card Vault is a fan-made tool for collectors. Not affiliated with Topps, Beckett, eBay, or any card manufacturer.*
