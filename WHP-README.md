# Women’s Health Physiotherapy — Demo (not clinical use)

This is an **isolated prototype branch**, kept separate from the repository's main branch and all existing sites.

## Preview
https://raw.githack.com/QatifRunners-bit/greeting-cards/womens-health-physiotherapy-demo/index.html

Raw.githack is a third-party HTML preview service; it may show a confirmation interstitial before rendering. This is NOT a Netlify deployment and does not provide uptime guarantees.

## Features
- Bilingual PFDI-20 questionnaire (20 questions; 3 domains)
- On-device illustrative score calculation (0–300)
- Demo admin-entry page with sample aggregate dashboard
- 124 synthetic records for chart preview
- No network storage, no real login credentials, no clinical database, no true admin authentication

## Critical safety boundaries
- English wording is based on a source file; Arabic wording is an **unvalidated working translation** pending specialist review and necessary permissions.
- **DO NOT** collect real employee responses or upload any identifiable or personal health information.
- The Admin Portal is only a mockup and does not protect real data.
- Production needs hospital IT/privacy approval, approved secure identity/database infrastructure, server-side role authorization, separated clinical referrals, and reviewed scoring.

## Editing with Codex
1. Open this branch in GitHub or Codex.
2. Edit `index.html`.
3. Commit to this branch; the preview URL generally reflects changes after a short cache delay.
4. Do not merge into `main` without explicit intent.

## Production
A separate proper host (e.g. Netlify with verified app permissions and hospital-approved data controls) is required for a real clinical service. This GitHub preview is not production.
