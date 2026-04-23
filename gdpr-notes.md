# GDPR Notes — Solo Business OS Early Access

## Practical compliance stance for MVP
This is not legal advice. It is the operational baseline we should follow to reduce legal risk for an EU-facing early-access landing page.

## Core GDPR principles to apply
Based on GDPR Articles 5, 6, and 13:
- lawfulness, fairness, transparency
- purpose limitation
- data minimisation
- storage limitation
- integrity and confidentiality
- accountability

## Recommendation for this landing page
For the early-access phase, collect the minimum viable personal data:
- email address only

Avoid for now:
- name
- free-text notes
- profiling questions
- unnecessary analytics tied to identity

## Recommended lawful basis
For an early-access email capture, the safer practical basis is:
- consent for being contacted about Solo Business OS early access and launch updates

Why this is safer for MVP:
- clearer user expectation
- easier transparency
- lower ambiguity than stretching legitimate interest for pre-launch marketing

## Information that should be shown at collection time
At minimum, the page/form should clearly state:
- who collects the data (controller identity/contact)
- purpose: early-access updates about Solo Business OS
- legal basis: consent
- what data is collected: email only
- where data is stored / recipient categories (e.g. form processor / email provider)
- retention period or rule
- right to withdraw consent
- rights of access, rectification, erasure, restriction, portability, objection (where relevant)
- right to complain to a supervisory authority

## MVP retention recommendation
- keep waitlist data only until launch decision + reasonable follow-up window
- default recommendation: 6 months max unless the person becomes an active customer/subscriber through a new lawful basis and updated notice

## Security recommendation
- do not store personal data in public repos
- do not expose API keys in chat or committed files
- keep secrets in local non-versioned files
- prefer providers with clear privacy/security posture
- restrict access to collected emails

## Product decision flowing from GDPR
Current recommendation:
- landing page with email-only capture
- explicit consent checkbox (unchecked by default)
- short privacy notice next to form
- link to a fuller privacy notice page

## Operational no-go items for now
- collecting names or business pain notes without strong need
- hidden marketing consent
- pre-checked consent boxes
- vague retention
- sending unrelated marketing later
