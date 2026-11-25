# KTU Calc

A free, browser-based academic calculator for students of **APJ Abdul Kalam Technological University (KTU)**.

**Live app:** https://itsnaveencm.github.io/ktu-calculator/

KTU Calc helps students estimate semester performance, track cumulative results and plan an academic target. It runs in the browser without requiring an account.

## Features

- **SGPA calculator** — credit-weighted semester grade calculation with editable course names and credits.
- **CGPA calculator** — weighted cumulative calculation using semester SGPA and credit inputs.
- **Target planner** — estimates the average SGPA required across remaining semesters to reach a target CGPA.
- **CGPA-to-percentage converter** — uses the conversion formula displayed in the application: `(CGPA - 0.75) × 10`.
- **Calculation history** — stores recent calculations locally in the browser.
- **Share and export** — copy, share or download a result image.
- **Progressive Web App support** — includes a web app manifest, service worker and install prompt handling.

## Built with

- HTML
- CSS
- Vanilla JavaScript
- Web App Manifest and Service Worker APIs

## Run locally

This is a static web application. Clone the repository and open `index.html` in a browser, or serve the directory with a local static server.

```bash
git clone https://github.com/itsnaveencm/ktu-calculator.git
cd ktu-calculator
```

## Important note

KTU Calc is an independent student utility, not an official university service. Course templates and calculations should be checked against the applicable university scheme and official academic records. Users can edit course names and credits to match their requirements.

## Privacy

The application stores recent calculation history and theme preference in browser local storage. It does not require account registration.

---

Built to make academic planning a little easier for KTU students.
