<p align="center">
  <img src="readme-banner.svg" width="100%" alt="CAMY Community Event Registration" />
</p>

<p align="center"><b>A lightweight event registration experience connected to Google Sheets through a serverless API.</b></p>

---

## Project Snapshot

| | |
|---|---|
| **Problem** | Event registration needs to be simple for guests and easy to manage for organizers. |
| **Solution** | A responsive registration page with validation, confirmation and Google Sheets storage. |
| **Backend style** | Vercel serverless function + Google Apps Script. |
| **Focus** | Simple user flow, reliable submission and duplicate protection. |

## Event Preview

<div align="center">
<table>
<tr>
<td align="center" width="52%"><img src="Invite - Camy Meetup.png" width="92%" alt="CAMY Meetup invitation" /></td>
<td align="center" width="48%"><img src="Screenshot 2026-09-18 092439.png" width="92%" alt="Registration page preview" /></td>
</tr>
</table>
</div>

## Key Features

- Responsive event registration form
- Input validation before submission
- Vercel serverless registration API
- Google Sheets data storage through Apps Script
- Duplicate protection and registration references
- Safe handling of spreadsheet formula-like input
- Invitation download after confirmation
- Automated tests for the submission API

## Registration Flow

`Open event page` → `Enter details` → `Validate` → `Serverless API` → `Google Sheets` → `Confirmation`

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/HTML-5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML" />
  <img src="https://img.shields.io/badge/CSS-3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS" />
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=111827" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Vercel-Functions-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
</p>

## Run & Test

```bash
npx vercel dev
```

```bash
npm test
node --check app.js
```

> A normal static server cannot execute `/api/register`; use Vercel development or deployment for the full registration flow.

---

<p align="center"><b>Simple registration for guests. Structured data for organizers.</b></p>
