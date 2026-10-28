# Personal Job Command Center

Independent prototype inside the existing ApplyPilot repository. Does not modify the upstream Python application.

## Run

```bash
cd personal-dashboard
npm install
npm run dev
```

Open http://localhost:3000.

## Current scope

- Responsive action-first dashboard
- Manually add jobs, open application links, and advance stages
- Outreach prompt after logging an application
- Feedback toasts

**Important:** This is a UI scaffold, not a live job scraper. Data is held in React memory and resets on refresh. Do not treat it as a durable tracker yet. No external integrations, emails, or applications are sent.

## Next

1. Create a separate Supabase project and persist jobs, application events, and outreach events.
2. Import a copy of the Google Sheets tracker with deduplication.
3. Add scheduled ATS feed ingestion (Greenhouse / Lever / Ashby where supported), timestamps and fit scoring.
4. Add contact discovery and draft-only outreach with user approval.

## Safety

Never commit resumes, private contact details, credentials, or application history to this public repository.
