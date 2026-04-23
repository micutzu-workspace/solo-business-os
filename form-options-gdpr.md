# Form Options Under GDPR Constraint — Solo Business OS

## Goal
Collect the minimum viable personal data while keeping the flow low-friction and legally cleaner.

## Option 1 — mailto link
### How it works
The CTA opens the visitor's email client to send an email manually.

### Pros
- no automatic third-party form processor needed
- minimal infrastructure
- very low data-processing complexity

### Cons
- poor conversion rate
- clunky UX
- no structured storage

## Option 2 — simple form backend with email-only capture
### How it works
A simple hosted form endpoint receives just the email address and consent signal.

### Pros
- better UX
- structured capture
- still privacy-manageable if minimal

### Cons
- needs provider review and a privacy notice aligned to the actual provider
- still involves a third-party processor

## Option 3 — direct email service embed
### How it works
Use an email platform's embedded signup form.

### Pros
- practical if we later run email updates there

### Cons
- heavier processor implications
- can become overkill too early

## Recommendation
For strict caution right now:
- start with either a compliant email-only form backend or even a mailto fallback
- do not collect anything beyond email until demand is validated and the legal/docs layer is cleaner
