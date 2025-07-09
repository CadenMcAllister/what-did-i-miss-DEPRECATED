# What Did I Miss?

**What Did I Miss?** is a personal dashboard that summarizes what you missed while offline — across numerous news sources and topics — and delivers it as a clean, in-app markdown report.

**Link** Sadly you need to pay $30/month to upload to GitHub but I am not paying that so here's the link: 

https://preview.flutterflow.app/what-did-i-miss-b7l8z1/rFkdoaBe8vgU2OCX9ebH
---

## 🛠 Built With

- **FlutterFlow** – Rapid visual development for building the front end.
- **Supabase** – Used for user authentication, report storage, and real-time syncing.
- **Edge Functions** – Serverless functions (via Supabase) to handle API calls and backend logic.
- **LinkUp AI** – Summarizes current news and updates based on selected topics and date ranges.

---

## 📱 How It Works

1. **Choose your topics** and a date range (e.g., *"Gaming from June 1 to June 7"*).
2. Tap **Generate**, which:
   - Calls a Supabase Edge Function.
   - The Edge Function forwards the request to **LinkUp AI**.
   - LinkUp AI generates a summary and returns markdown.
   - The summary is saved to Supabase.
3. The summary is then **displayed in-app** as a styled markdown report.

---

## 🧩 Features

- 📅 Supports multiple reports with custom topics and date ranges.
- 🔄 Live loading states and visual feedback during generation.
- 📄 In-app markdown rendering for clean, readable summaries.
- 🚀 Supabase Edge Functions for fast, scalable server-side logic.
- 🌐 AI-driven content discovery and summarization

---

## 🔐 Auth & Storage

All user reports are stored securely in Supabase, associated with the authenticated user session.

---

## 📎 Notes

The app is pretty much done bar some UI tweaks here and there that I might make in the future.
