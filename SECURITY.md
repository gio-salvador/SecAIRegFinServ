# Vulnerability disclosure policy

This repository is the public companion pack for the book *Securing AI in
Regulated Financial Services* by Giovanni Salvador (Salvador Cloud Ltd). It
contains documentation, checklists, and templates (Markdown and CSV) — there is
no application to exploit, but the repository, its CI/CD, and its supply chain
are in scope.

## Where to report

- **Email**: <security@salvador.cloud>
- **GitHub Security Advisory** (private):
  <https://github.com/gio-salvador/SecAIRegFinServ/security/advisories/new>

Please do not open a public issue for a security report.

## What to expect (timelines)

- **Acknowledgement** within **2 working days**
- **Initial triage** within **5 working days**
- **Resolution** within **30 days** for High / Critical, **90 days** otherwise
- **Coordinated disclosure** with the reporter; default 90-day window

## In scope

- This repository itself (CI/CD workflows, supply chain, GitHub Actions)
- Brand-asset misuse or impersonation of Salvador Cloud
- Content integrity issues that could mislead a reader (for example, a tampered
  control catalogue or crosswalk)

## Out of scope

- Third-party services (report to the vendor; we may help coordinate)
- Social engineering of Salvador Cloud staff or contractors
- Physical security
- The accuracy of regulatory interpretation in the materials — these are
  practitioner aids, not legal advice, and the owning chapter in the book
  governs (see `README.md`)

## Safe harbour

We will **not pursue legal action** against good-faith research that:

- Avoids privacy violations, data destruction, and service disruption
- Only touches your own accounts and test data
- Gives reasonable time before public disclosure (default 90 days)
- Does not deliberately exfiltrate beyond what is needed to demonstrate the
  vulnerability

## What we will not do

- We do not run a paid bug-bounty programme. We acknowledge contributions
  publicly with the reporter's consent.
- We will not publicly disclose your identity without your written consent.

---

*Last reviewed: 2026-06-11.*
