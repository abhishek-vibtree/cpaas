# OneML — CPaaS documentation

Documentation for **OneML**, OneInbox's Twilio-compatible CPaaS built on Asterisk/ARI.
OneML is a strict TwiML superset: an existing Twilio voice app works by changing the
API domain.

This repository is a [Mintlify](https://mintlify.com) docs site.

## Contents

- **Get Started** — introduction, architecture, authentication, request signatures
- **Voice webhooks** — Voice URL request, action continuation, status callbacks
- **OneML verbs** — `<Dial>`, `<Gather>`, `<Play>`, `<Conference>`, and more
- **Conference** — rooms, participants, and the event stream
- **Outbound** — routing through the Routes table
- **API Reference** — the Twilio-compatible REST API
- **Compatibility & roadmap** — what's implemented vs. what's pending

## Local preview

```bash
npm i -g mintlify
mintlify dev
```

Then open http://localhost:3000.

## Deploy

Connect this repository to Mintlify; it deploys from `docs.json` at the repo root.
