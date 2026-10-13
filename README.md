<div align="center">

# CAMY Community Event Registration

**Simple event registration with Google Sheets integration**

<img src="Invite - Camy Meetup.png" alt="CAMY Meetup Invitation" width="650" />

</div>

---

## Overview

A responsive registration page for CAMY community events. Registrations are submitted through a secure serverless API and stored in Google Sheets using Apps Script.

## Main Features

- Responsive registration form
- Google Sheets data storage
- Vercel serverless API
- Input validation
- Duplicate protection
- Registration reference generation
- Invitation download

## Preview

<div align="center">
  <img src="Screenshot 2026-09-18 092439.png" alt="CAMY Registration Preview" width="720" />
</div>

## Tech Stack

`HTML` · `CSS` · `JavaScript` · `Vercel Functions` · `Google Apps Script`

## Local Development

```bash
npx vercel dev
```

The `/api/register` route requires Vercel development or deployment. A normal static server cannot run the API.

## Testing

```bash
npm test
node --check app.js
```

## Google Sheets Setup

1. Open the Google Sheet.
2. Go to **Extensions → Apps Script**.
3. Use `google-apps-script/Code.gs`.
4. Deploy it as a Web App.
5. Add the deployment URL as `GOOGLE_SCRIPT_URL` in Vercel.

---

<div align="center">
  <b>Register • Confirm • Connect</b>
</div>
