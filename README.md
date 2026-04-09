<p align="center">
  <img src="https://img.shields.io/badge/ReemCollection-Payment%20Tracker-1a6b3c?style=for-the-badge&logo=wallet&logoColor=white" alt="ReemCollection Payment Tracker">
</p>

<p align="center">
  <b>A modern, offline-first payment tracking solution for small businesses</b>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#usage">Usage</a> •
  <a href="#screenshots">Screenshots</a>
</p>

---

## ✨ Features

### 💰 Payment Management
| Feature | Description |
|---------|-------------|
| **Quick Entry** | Add payments in seconds with customer name, amount, and method |
| **Discount Support** | Apply discounts with automatic net amount calculation |
| **Invoice Tracking** | Record paid invoice numbers for reference |
| **Multiple Methods** | Cash 💵, Bank Transfer 🏦, POS/Card 💳 |

### 📊 Analytics & History
| Feature | Description |
|---------|-------------|
| **Smart Search** | Find records by customer name or payment method |
| **Date Filtering** | View records for any specific date |
| **Date Totals** | Instantly see exact money collected for selected date |
| **Statistics** | Total collected, transaction count, today's summary |

### 🎨 User Experience
| Feature | Description |
|---------|-------------|
| **Dark/Light Mode** | Toggle themes with saved preference |
| **Responsive Design** | Works perfectly on mobile, tablet, and desktop |
| **No Installation** | Single HTML file, just open and use |
| **Offline First** | No internet required to track payments |

### 📤 Data Portability
| Feature | Description |
|---------|-------------|
| **WhatsApp Share** | Send daily reports or full summaries |
| **JPG Export** | Generate professional report images |
| **JSON Backup** | Export/import data for safekeeping |
| **Privacy First** | All data stays on your device |

---

## 🚀 Getting Started

### Option 1: Direct Use (Recommended)
1. Download `reemcollection_payment_tracker.html`
2. Double-click to open in your browser
3. Start tracking payments immediately!

### Option 2: Host Online
Upload to GitHub Pages, Netlify, Vercel, or any static host:

```bash
# Example: GitHub Pages
# 1. Fork this repository
# 2. Go to Settings > Pages
# 3. Select main branch
# 4. Your site is live!
📖 Usage
Adding a Payment
Switch to "+ New Entry" tab
Fill in the details:
Customer name
Amount collected (QAR)
Discount (if any)
Invoice numbers (optional)
Date (defaults to today)
Payment method
Click "Add Payment Record"
Viewing History
Switch to "History" tab
Use search box to filter by name/method
Use date picker to filter by specific date
View the green total bar for selected date amount
Click "📱 Share date" to send via WhatsApp
Backing Up Data
Export:
plain
Copy
History → Scroll to "Backup & Restore" → Click "📤 Export Data"
Import:
plain
Copy
History → Scroll to "Backup & Restore" → Click "📥 Import Data" → Select JSON file
🛠️ Technical Details
Built With
HTML5 - Semantic structure
CSS3 - Custom properties, Flexbox, Grid, transitions
Vanilla JavaScript - Zero dependencies except html2canvas
localStorage API - Persistent client-side storage
Browser Support
Table
Browser	Status
Chrome/Edge	✅ Fully Supported
Firefox	✅ Fully Supported
Safari	✅ Fully Supported
Mobile Browsers	✅ Fully Supported
Data Structure
JavaScript
Copy
{
  id: 1712707200000,        // Timestamp
  name: "Customer Name",     // Customer name
  amount: 1500.00,          // Gross amount
  discount: 100.00,         // Discount applied
  invoices: "INV-001",      // Invoice numbers
  date: "2026-04-10",       // Payment date
  method: "cash"            // cash | bank | pos
}
🎨 Customization
Changing Currency
Edit the HTML file and replace:
"QAR" → Your currency code
en-QA locale in fmtAmt() function
Modifying Colors
Edit CSS variables in :root:
css
Copy
:root {
  --green: #1a6b3c;     /* Primary brand color */
  --amber: #8a5a00;     /* Cash payments */
  --blue: #1a4a8a;      /* Bank transfers */
  --red: #c0392b;       /* Discounts */
}
🔒 Privacy & Security
✅ 100% Offline - No server communication
✅ Local Storage - Data never leaves your device
✅ No Tracking - No analytics, cookies, or telemetry
✅ No Account - No registration or login required
⚠️ Backup Regularly - Browser data clearing will erase records
🐛 Troubleshooting
<details>
<summary><strong>Data not saving?</strong></summary>
Disable Incognito/Private mode
Ensure localStorage is enabled
Check browser storage permissions
</details>
<details>
<summary><strong>WhatsApp sharing not working?</strong></summary>
Mobile: Ensure WhatsApp is installed
Desktop: Connect WhatsApp Web first
Allow popups for this site
</details>
<details>
<summary><strong>Import failed?</strong></summary>
Verify file is valid JSON from this app
Check file isn't corrupted
Ensure correct file extension (.json)
</details>
📝 Changelog
v1.0.0 (2026-04-10)
✨ Initial release
💰 Payment recording with discounts
📊 History with search and filters
🌓 Dark/Light theme support
📱 WhatsApp integration
🖼️ JPG export
📤📥 JSON backup/restore
🤝 Contributing
This is an open template. Feel free to:
Fork and customize for your business
Add new features or improvements
Translate to other languages
Share your modifications
📄 License
MIT License - Free for personal and commercial use.
<p align="center">
  <b>Made with ❤️ for ReemCollection</b>
  <br>
  <sub>Track payments. Stay organized. Grow your business.</sub>
</p>
