# my-medical-appointments
Personal medical appointment tracker with reminders, pre/post remarks and PDF export
# My Medical Appointments 🏥

A personal medical appointment tracker web app — built to help you manage your health appointments with ease. Add appointments at any time, get browser reminders, write pre and post remarks, and export your records as PDF. No sign-up required. Works fully offline in any browser.

---

## Features

- **Add appointments** with doctor/hospital, specialty, date, time, location, and reminder
- **Pre-appointment remark** — notes to prepare before your visit (e.g. fast 8 hours, bring reports)
- **Post-appointment remark** — fill in after your visit (e.g. medication, follow-up date, doctor's advice)
- **Auto-sorted by date** — appointments always reorder in ascending date order automatically
- **Upcoming tab** — shows today and all future appointments with a stats bar (Today / Upcoming / Completed)
- **Past tab** — view all completed appointments
- **All tab** — full appointment history in one place
- **Browser notifications** — get reminded 30 minutes, 1 hour, 2 hours, 1 day, or 2 days before your appointment
- **Download as PDF** — export upcoming, past, or all appointments as a neatly formatted PDF file
- **Copy to clipboard** — copy your appointment list as plain text to share anywhere
- **Edit & Delete** — update any appointment detail at any time
- **Auto-save** — all data stored locally in your browser, no internet needed
- **Mobile-friendly** — fully responsive, works great on phones and tablets

---

## Demo

> Open `index.html` directly in your browser — no installation or internet connection required.

---

## Getting Started

### Option 1 — Run locally

1. Clone or download this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
3. Start adding your appointments!

```bash
git clone https://github.com/yourusername/my-medical-appointments.git
cd my-medical-appointments
open index.html
```

### Option 2 — Host on GitHub Pages

1. Fork or upload this repository to your GitHub account
2. Go to **Settings → Pages**
3. Under **Source**, select the `main` branch and click **Save**
4. Your app will be live at:

```
https://yourusername.github.io/my-medical-appointments
```

### Option 3 — Deploy on Netlify

1. Go to [netlify.com](https://netlify.com) and sign in
2. Drag and drop the project folder onto the Netlify dashboard
3. Get an instant shareable URL — no configuration needed

---

## How to Use

### Adding an Appointment
1. Open the **➕ Add** tab
2. Fill in the Doctor/Hospital name, Date, and Time *(required)*
3. Optionally add Specialty, Location, Reminder, and Remarks
4. Tap **Add Appointment** — it will appear sorted by date in the Upcoming tab

### Reminders
1. Tap the **🔔 Notify** button in the top right header
2. Allow browser notification permission when prompted
3. Your browser will send you a notification at the time you set before each appointment

> **Note:** Keep the app open in your browser tab for reminders to fire. For persistent reminders, consider pinning the tab.

### Pre & Post Remarks
- **Pre-remark** — write preparation notes before your appointment (e.g. bring IC, fast 8 hours)
- **Post-remark** — fill in after your visit (e.g. prescribed medication, next follow-up date)
- Tap any appointment card to expand and view/edit remarks

### Exporting
- Go to **📅 Upcoming**, **🗂 Past**, or **📋 All** tab
- Tap **Download PDF** to save a formatted PDF to your device
- Tap **Copy** to copy appointment details as plain text to your clipboard

---

## Pi Browser (App Studio)

This app is fully compatible with **Pi Browser App Studio**.

To add it:
1. Host the file online (GitHub Pages or Netlify)
2. Open **Pi Browser → App Studio**
3. Create a new app and paste your hosted URL
4. Set your app name, description, and a medical icon
5. Save — your app appears on your Pi Browser home screen

**Suggested App Studio details:**
- **Name:** My Medical Appointments
- **Description:** Personal medical appointment tracker with reminders, pre/post remarks and PDF export
- **Icon:** Green cross or stethoscope image

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML / CSS / JavaScript | Core app — no frameworks needed |
| [jsPDF](https://github.com/parallax/jsPDF) | PDF generation and download |
| [Tabler Icons](https://tabler.io/icons) | UI icons |
| Web Notifications API | Browser push reminders |
| localStorage | Persistent data storage in the browser |

---

## Screenshots

> *(Add your own screenshots here)*

---

## Roadmap

- [ ] Pi SDK login integration
- [ ] Multiple family member profiles
- [ ] Recurring appointment support
- [ ] Medication tracker
- [ ] Export to CSV
- [ ] Dark mode
- [ ] Calendar view

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## License

[MIT](LICENSE)

---

> Built for personal health management. Stay on top of your health — never miss an appointment again. 💚
