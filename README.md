# SCS Mayyit Notice Generator

A secure, password-protected web-based generator for creating Saaberie Chishty Society Mayyit Notices. Built as a single self-contained HTML file — no internet connection, server, or external dependencies required after deployment.

---

## 🔒 Access

The generator is protected by a password gate. Only authorised personnel should have access to the password.

**Password:** 

> Keep this password confidential. Share only via private WhatsApp to authorised members.

---

## 🚀 Deployment (GitHub Pages)

1. Create a **private** GitHub repository (e.g. `scs-mayyit-generator`)
2. Upload `scs-mayyit-generator.html` and rename it to `index.html`
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`
5. Click **Save**
6. Your site will be live at `https://yourusername.github.io/scs-mayyit-generator/`
7. Share the link + password privately with authorised members only

> The repository is private so the source code is hidden. The deployed Pages link is what you share.

---

## 📋 How to Use

1. Open the link in any browser
2. Enter the password and click **Enter** (or press Enter)
3. Fill in the form on the left:
   - **Date** — select the date; Hijri date is shown automatically (toggle off if not needed)
   - **Deceased Name** — full name of the deceased
   - **Relations** — select the relation type (W/O, S/O, D/O etc.), type the name, click **+** or press Enter. Repeat for multiple relations.
   - **Will Leave From** — home address (use commas to split across lines e.g. `10 Main Road, Springfield`)
   - **Pick Up Time** — select from dropdown
   - **Janazah Salah At** — masjid name and area
   - **Janazah Time** — select from dropdown
   - **Cemetery** — cemetery name
4. The notice preview updates live on the right
5. Click **▶ Generate Notice** to refresh
6. Click **⬇ Download Image** to save as a high-resolution PNG ready for WhatsApp

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

The downloaded image is exported at **3× resolution** for crisp, sharp quality when shared on WhatsApp or printed.

---

## 🔑 Changing the Password

1. Open `index.html` in a text editor (e.g. VS Code, Notepad++)
2. Find the line:
   ```
   const PW = "***********";
   ```
3. Replace `************` with your new password
4. Save and re-upload to GitHub
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
- Intelo font family (Bold, SemiBold, Light Italic) — embedded as base64
- Saaberie Chishty Society blank template — embedded as base64

---

## ⚠️ Important Notes

- This tool is for **authorised Saaberie Chishty Society personnel only**
- Do not share the password publicly or on open group chats
- If the password is compromised, change it immediately (see above)
- Always double-check all details before downloading and sharing a notice
- The Hijri date is calculated algorithmically — verify manually if needed for official notices

---

*Saaberie Chishty Society — Est. 1982*
