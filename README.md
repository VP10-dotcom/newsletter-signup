# Newsletter sign-up page

Public two-tap sign-up page for David MacLeod's Cape Breton Residential and Commercial newsletters.

Live URL: https://vp10-dotcom.github.io/newsletter-signup/

Each button is a mailto link that matches the Gmail invite and signature buttons:

- To: david.macleod@viewpoint.ca
- Residential subject: `SUBSCRIBE: Residential newsletter`
- Commercial subject: `SUBSCRIBE: Commercial newsletter`
- Both subject: `SUBSCRIBE: Both newsletters`
- Body: `Yes, please send me your newsletter.`

Replies are handled by the existing Gmail search and `/workspace/brevo/gmail_invites/subscribe_replies.py`. No change to those scripts was needed: they already add people who are not in `queue.csv` and send the welcome emails.

Source of truth on the box: `/workspace/brevo/signup_page/index.html`.
