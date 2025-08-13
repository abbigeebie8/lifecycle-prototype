# lifecycle-prototype
Prototype deployment for LifeCycle Partners' Bid to Stallings Family Fun Center
# Lifecycle Partners – Case Management Prototype (Static SPA)

This is a **static, front-end-only** prototype of the Lifecycle Partners Client Tracking & Case Management System.

## Features
- Role-based demo login (admin/casemanager/vendor)
- Clients, Contacts, Vendors (create/read/update/delete)
- Dashboard KPIs + Reports (Chart.js)
- LocalStorage persistence with base64 "envelope" (simulated encryption)
- Audit log of key actions
- Device-aware UI: responsive (Tailwind) + user agent pill
- Single-page app router via URL hash

## Quick Start
1. Demo accounts:
   - admin / admin123
   - casemanager / case123
   - vendor / vendor123

> Demo only. Not secure. Do not add real PHI (pls for the love of god)

## Next Steps (Hypothetical next steps if this were a real bid)
- Replace base64 with proper WebCrypto AES-GCM (demo key)
- Add CSV import/export for clients and contacts
- Add filtering, search, pagination
- Add simple task/ticket module mapped to SLAs 
- Add printable reports 
