# SCS Mayyit Notice Generator

A secure, password-protected web-based generator for creating Saaberie Chishty Society Mayyit Notices. Built as a single self-contained HTML file — no internet connection, server, or external dependencies required after deployment.

---

## 🔒 Access

The generator is protected by a password gate. Only authorised personnel should have access to the password.

**Password:** *(shared privately via WhatsApp)*

> Keep this password confidential. Share only via private WhatsApp to authorised members.

---

## 🚀 Deployment

The live application is deployed on **Netlify**. The repository is private and not hosted via GitHub Pages.
Authorised personnel can access it at the link shared privately via WhatsApp.

### To deploy a new version:

1. Open `index.html` in a text editor
2. Make your changes (or use an updated file)
3. Upload the new `index.html` to Netlify (drag-and-drop deploy, or push to the connected Git branch)
4. Verify the new version loads correctly in a browser

---

## 📋 How to Use

1. Open the link in any browser (mobile, tablet, or desktop)
2. Enter the password and click **Enter** (or press Enter)
3. Fill in the form on the left:
   - **Saved Notices** — switch between previously edited notices, create a new one with **＋**, or delete the current one with **🗑**
   - **Notice Label** — optional name to help identify the notice in the dropdown (auto-saves as you type)
   - **Date** — select the date; Hijri date is shown automatically (toggle off if not needed)
   - **Deceased Name** — full name of the deceased
   - **Relations** — select the relationship (Father of, Wife of, Son of, etc.), type the relative's name, click **+** or press Enter. Repeat for multiple relations. Choose **Custom…** from the dropdown to type any relationship not in the list.
   - **Will Leave From** — home address (use commas to split across lines, e.g. `10 Main Road, Springfield`)
   - **Pick Up Time** — select from dropdown
   - **Show TIME CHANGE** — optional red label shown above the pickup time
   - **Janazah Salah At** — masjid name and area
   - **In Conjunction With** — optional additional service
   - **Janazah Time** — select a clock time OR use the salaah dropdown below
   - **Salaah Timing** (optional) — pick from preset options like *Before Fajr Salaah*, *After Esha Salaah*, *Before Jumu'ah Salaah*, etc. If selected, this replaces the clock time.
   - **Time Update** (optional) — tick this box and enter a new time to show a red **TIME UPDATE** label above the updated time. The original time is replaced completely.
   - **Cemetery** — cemetery name
4. The notice preview updates live on the right
5. Click **▶ Generate Notice** to refresh
6. Click **⬇ Download Image** to save as a high-resolution PNG ready for WhatsApp

---

## 💾 Auto-Save & Multi-Notice Support

- Every change you make is **automatically saved** to your browser's local storage
- You can work on **multiple notices simultaneously** — each gets its own entry in the **Saved Notices** dropdown
- Refresh the page, close the tab, or come back later — your work is preserved
- Use the **＋** button to start a new blank notice without losing the current one
- Use the **🗑** button to permanently delete a notice (confirms before deleting)

> Notices are saved per-browser-per-device. Clearing your browser data will remove saved notices. They do not sync between devices.

---

## ✏️ Editing Relations

- Click the **✎** icon on a chip to edit a relation
- Click the **×** icon to remove a relation

---

## 📅 Hijri Date

- Hijri date is shown by default next to the Gregorian date
- Uncheck **Show Hijri Date** to display the Gregorian date only

---

## 🖼️ Output

- The downloaded PNG is captured at a fixed **1080 × 1920 resolution** regardless of device, so it looks identical on mobile, tablet, and desktop downloads.
- Crisp, sharp quality for WhatsApp or print.

---

## 🔑 Changing the Password

1. Open `index.html` in a text editor (e.g. VS Code, Notepad++)
2. Find the line near the top of the `<script>` section:
   ```
   const PW = "***********";
   ```
3. Replace with your new password
4. Save and re-deploy to Netlify
5. Notify authorised members of the new password

---

## 📁 File Structure

```
index.html        ← The entire application (template image + fonts embedded inside)
README.md         ← This file
```

Everything is self-contained in a single HTML file. No separate image files, font files, or stylesheets are needed.

---

## 🛠️ Built With

- Vanilla HTML / CSS / JavaScript
- [html2canvas](https://html2canvas.hertzen.com/) for image export
- **Intelo** font family (Bold, SemiBold, Light Italic) — embedded as base64
- **Calibri Light Italic** — embedded as base64 (used for the family/relations line)
- **Amiri** (Arabic, Google Fonts) — used on the password gate
- Saaberie Chishty Society blank template — embedded as base64
- Browser `localStorage` — for auto-save and multi-notice management

---

## ⚠️ Important Notes

- This tool is for **authorised Saaberie Chishty Society personnel only**
- Do not share the password publicly or on open group chats
- If the password is compromised, change it immediately (see above)
- Always double-check all details before downloading and sharing a notice
- The Hijri date is calculated algorithmically — verify manually if needed for official notices
- Saved notices live in your browser only; back up important ones by downloading the PNG before clearing browser data

---

*Saaberie Chishty Society — Est. 1982*

---

* Link to site *
  https://scs-mayyit-generator.netlify.app/


## Built By

**FTL Collective**
Built and maintained by FTL Collective to simplify the notice generation process for the Bayview Muslim Burial Service team.

For support or improvements, reach out to FTL Collective.

---

*May Allah SWT grant all the deceased the highest stage in Jannah. Aameen.*
