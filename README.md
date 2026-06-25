# RAKEZ Web-to-Lead Landing Flow

Static HTML/CSS Salesforce Web-to-Lead flow for RAKEZ business inquiries.

## Pages

- `index.html` - public lead form
- `thank-you.html` - Salesforce redirect confirmation page

## Before Deploying

In `index.html`, replace:

- `REPLACE_WITH_DEPLOYED_THANK_YOU_PAGE_URL` with the full deployed URL for `thank-you.html`

The Salesforce Org ID is already set to `00Dfj00000Q6QvJ`.

## Notes

The form posts directly to Salesforce Web-to-Lead with a normal HTML `POST`. There is no backend, AJAX, or JavaScript submission.
