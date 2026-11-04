# ALIRIM website

Public ALIRIM introduction website with links to the free research and education apps.

## Edit the words in GitHub

1. Open `index.html` and click the pencil (Edit this file).
2. Find the heading or sentence you want to change. Edit the words between the HTML tags; keep the tags and links intact.
3. Click **Commit changes** and commit to `main`.
4. GitHub Pages publishes the updated website automatically. Allow a few minutes, then refresh https://aliameri75.github.io/alirim-website/.

Useful search terms in `index.html`:

| What to change | Search for |
| --- | --- |
| Main headline | `From pipeline data` |
| Main description | `A research-based platform` |
| App launch links | `https://pipeline-integrity-research.streamlit.app/` |
| Platform descriptions | `Data Exploration`, `Preliminary Analysis`, `Inspection Planning` |
| Education section | `Make pipeline integrity` |
| Contact address | `amerifar@ualberta.ca` |
| Frequently asked questions | `<details>` |

`style.css` controls colours, fonts and layout. `app.js` controls the mobile menu and explanatory workflow tabs. The hero image is `assets/pipeline-hero.png`.

## Two website addresses

- Editable GitHub Pages version: https://aliameri75.github.io/alirim-website/
- Original Sites-hosted version: https://alirim-platform.ua-smra.chatgpt.site/

Committing here updates **GitHub Pages only**. The original Sites-hosted version needs a separate deployment; there is no automatic connection between these hosts. Use the GitHub Pages address when you want edits made in GitHub to publish automatically.

## Pilot enquiry form

`Discuss a Pilot` opens `pilot.html`. Edit its field labels, introduction and questions in that file. `pilot.css` controls its appearance. The form sends name, role, organisation, email, message and contact consent to **amerifar@ualberta.ca** through FormSubmit. The default spam-protection check remains enabled.

**One-time activation required:** submit your own test request from the live page, then open the FormSubmit activation email in amerifar@ualberta.ca and confirm the form. Check spam if it is missing. Submit a second test after activation to verify actual inbox delivery before inviting customers. Email forwarding has not been verified by the developer; only the recipient can complete activation. See https://formsubmit.co/documentation and https://formsubmit.co/help.

`pilot-request-sent.html` is the return page after a successful submission. Keep the hidden `_next` and `_url` values in `pilot.html` aligned with the website address if you change domains. The form is not connected to the separate ChatGPT Sites copy.

## Apps and contact

The free-app links open https://pipeline-integrity-research.streamlit.app/ and education opens https://alirim-education.streamlit.app/. The website does not run calculations. Pilot requests use the form described above; other email links open an email to amerifar@ualberta.ca.

The current ALIRIM app is a research prototype. The website does not claim validated operational outcomes or measured customer savings. The hero image is an AI-generated illustrative landscape, not an identified real pipeline. No competitor branding or assets have been copied. Google Fonts fall back to system fonts when unavailable.

## Local preview

Serve this folder with any static web server, for example `python3 -m http.server 8000`, then open http://localhost:8000.
