# Digital Solutions Founding — Landing Page

A public, responsive founding-information and candidate-interest landing page for a proposed hybrid digital solutions and technology company.

**Repository:** https://github.com/jark-zenith/digital-solutions-founding

## Current status

This is a founding-stage proposal. The company name, legal entity, final leadership appointments, candidate selection, ownership and signed founders' agreement have not been finalized. The page intentionally labels roles and governance as proposed.

## Run locally

No build step is required. Open `index.html` in a browser, or run a local static server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Personalize before public launch

1. Add the founder's approved portrait as `assets/founder-photo.jpg` (JPEG recommended, 4:5 crop).
2. Confirm the founder bio and public contact email.
3. Choose and clear the final company name; update the placeholder brand text and metadata.
4. Review all five public working documents with the founding candidates.
5. Replace the current mailto-based application handoff with a secure form backend before collecting applications at scale.
6. Add a privacy notice appropriate to the final data-processing setup and applicable Kenyan law.
7. Configure a domain and static hosting after the final brand decision.

## Application flow

The interest form validates required fields in the browser and opens a prefilled email to the currently configured contact address. The applicant must review and send the email. The website does not store application data or claim that an application has been received. Do not use this as a long-term recruitment database.

## AI-assisted work

The site describes ChatGPT, Claude, Grok and Gemini as AI tools used for research, drafting, development assistance and review. They are tools, not employees or accountable decision-makers. Human review remains mandatory.

## Documents

See `docs/` for the five public working drafts. The founders' agreement is expressly a discussion draft and is not ready for signature or legal reliance.
