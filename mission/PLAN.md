# Mission: Find a need. Fill it. Make a business.

## Who I am (facts, not vibes)
- Cybersecurity: email protection, threat response & intelligence. Technical support SME (TAP / TRAP / API).
- Shift: 5pm–3am EST, Sun–Thu. Off Fri + Sat.
- Goal: use AI + my job skills to build an open-source Linux tool that gets me hired/paid, then a business.

## The niche (decided — no more "discovering")
**AI phishing-triage agent for teams that can't afford an enterprise email-security stack.**
Small MSPs, SMBs, solo IT admins. They get "is this email safe?" tickets all day and have no analyst.

Tool: `mailtriage` — open-source Linux CLI/agent.
1. Takes a `.eml` / forwarded message
2. Parses headers, SPF/DKIM/DMARC, Received chain, URLs, attachments (hashes)
3. Checks free threat-intel (URLhaus, PhishTank, VirusTotal free tier, AbuseIPDB)
4. LLM writes: verdict + evidence + a plain-English reply for the end user
5. Later: watch a mailbox, auto-triage, Slack/Teams alert, SOAR-style actions

Why me: I do this work every night. Most AI builders have never read a Received header.

## Hard rules
- ZERO employer data, customer data, internal docs, or proprietary vendor info. Public docs + public samples only.
- Read my employment agreement (moonlighting / IP / non-compete clauses) THIS WEEK.
- Ship something public every week. Unshipped = didn't happen.
- 1 build block per workday (90 min, ~1pm–2:30pm). Fri + Sat: 2 blocks each.
- Log every day in LOG.md. Empty log = missed day. No excuses accepted.

## 90 days
- **Weeks 1–2:** Learn Python + Claude API basics by building v0.1: parse .eml → JSON report. Push to GitHub.
- **Weeks 3–4:** Add threat-intel lookups + LLM verdict. Write README with a demo GIF.
- **Weeks 5–8:** Talk to 10 MSP/IT people (Reddit r/msp, r/sysadmin, LinkedIn). Ask what they'd pay for. Post 1 public phishing teardown per week (public samples only).
- **Weeks 9–12:** Hosted/managed version or paid setup service for 3 first customers. Or use the repo + posts to land a security-automation role. Either way, you win.

## Scoreboard (updated weekly)
| Week | Blocks done / target | Shipped | Conversations | Notes |
|------|----------------------|---------|---------------|-------|
