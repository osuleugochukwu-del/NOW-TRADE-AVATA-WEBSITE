TRADE AVATA EMAIL LAYER

This package includes the complete Trade Avata build plus a provider-agnostic email foundation.

Zero-cost mode:
- no mailbox required
- no domain hard-coded
- no provider key required
- queue-only/dry-run by default

Backend:
- functions/email/config.js
- functions/email/service.js
- functions/email/templates.js
- processEmailQueue Cloud Function
- emailLogs collection

Frontend/admin:
- src/lib/firebase/email.js
- /admin/email/ template/campaign centre
- /admin/email-settings/ configuration UI

Provider boundary:
- none (default)
- SMTP
- Resend

Security:
Provider credentials are server-side only. Do not put SMTP passwords or API keys in Astro/Firebase client code or commit them to GitHub.
