# Mentcare User's Guides (Team 4)

Phase I User's Guide and Walkthrough for the Mentcare system.
Team 4: Bogdan Borachuk, Lev Lavryniuk, Antonii Maltsev.

Mentcare is built in blocks by five teams. Team 4 builds the Admissions and Outreach block.

## Contents

- `index.html`: landing page linking both guides
- `mentcare-user-guide.html`: user's guide for the whole Mentcare system (21 screens, all user roles)
- `admissions-outreach-user-guide.html`: user's guide for the Team 4 Admissions and Outreach block (9 screens)
- `prototype.html`: clickable prototype of the Admissions and Outreach block, matching the guide's screens

## Using the prototype

Use the "Viewing as" menu at the top to switch between the referrer, intake coordinator, triage clinician, and patient and carer views, or start from the sign-in page. A full walkthrough:

1. As the referrer, send a referral (use "Fill with sample patient" to save typing).
2. As the intake coordinator, open it in the referral inbox, mark the documents reviewed, and assign it for triage.
3. As the triage clinician, open it, resolve the existing records check, and accept it.
4. As the intake coordinator, admit the patient from New patients: book a slot, then admit.
5. Send an outreach message, edit a reminder sequence, or create a session.
6. As the patient and carer, see the letter and texts received and register for the carer evening.

Changes are saved in the browser. "Reset demo data" restores the starting data. The prototype is plain HTML, CSS, and JavaScript with no build step and no server; screens for other blocks show a placeholder.

Each page is a single self-contained HTML file with inline CSS and no build step. Screens are HTML mockups of the planned product; all names and figures are sample data.

## Hosting on GitHub Pages

1. Put these files in the repository, either in the root or in a `docs/` folder.
2. On GitHub, open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main`, and choose `/ (root)` or `/docs` to match where the files are.
4. Save. The site is published at `https://<user>.github.io/<repo>/`.

To view locally, open `index.html` in a browser.

## Screenshots for the report

Each guide has a "Show step markers on screens" checkbox in the sidebar. Leave it on for walkthrough screenshots that match the numbered steps, or turn it off for clean screens.
