# AIJAO Azure Static Website

This folder is a standalone public website for AIJAO.com.

It is intentionally separated from the local AIJAO MVP and does not connect to:

- PostgreSQL
- local APIs
- bank statement data
- CFDI data
- journal data
- contract OCR data
- reimbursement OCR data

## Files

- `index.html` - public landing page
- `payables.html` - Phase 1 Payables Assistant page
- `site.css` - standalone styles
- `aijao-hero.png` - public visual asset
- `staticwebapp.config.json` - Azure Static Web Apps route config

## Before Publishing

Replace the LinkedIn placeholder in both HTML files:

```text
https://www.linkedin.com/in/aijaocom
```

with the founder's actual LinkedIn URL.

## Azure Static Web Apps Deployment

Recommended Azure service:

```text
Azure Static Web Apps
```

Suggested build settings:

```text
App location: /
API location: leave blank
Output location: leave blank
```

After deployment, add the custom domain:

```text
AIJAO.com
www.AIJAO.com
```

through Azure Static Web Apps > Custom domains.


