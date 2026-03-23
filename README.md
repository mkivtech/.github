# .github

Org-wide default community health files and issue templates for MKIV.

Any repository in this organisation that does not have its own `.github/ISSUE_TEMPLATE/`
folder will automatically inherit these templates.

## Issue templates

| Template       | Purpose                             | Key methodology fields                        |
| -------------- | ----------------------------------- | --------------------------------------------- |
| User Story     | Sprint-level unit of work           | MoSCoW, acceptance criteria, story points, PI |
| Bug Report     | Defect tracking                     | Severity, MoSCoW impact, reproduction steps   |
| Feature / Epic | Large capability proposals          | WSJF scoring, business case, out of scope     |
| Technical Task | Infrastructure, refactoring, spikes | Spike timebox, business justification         |

## Methodology coverage

These templates are a superset drawn from Scrum, DSDM, SAFe, and XP —
so teams can use as much or as little rigour as their project needs.

## What to add here

- [ ] `CONTRIBUTING.md` — contribution guidelines for all repos in the org
- [ ] `CODE_OF_CONDUCT.md` — expected behaviour for contributors and maintainers
- [ ] `SECURITY.md` — how to report vulnerabilities responsibly
- [ ] `SUPPORT.md` — where to get help (Slack channel, docs site, etc.)
- [ ] `PULL_REQUEST_TEMPLATE.md` — standard PR checklist (description, testing, screenshots)
- [ ] `ISSUE_TEMPLATE/config.yml` — already done ✓
- [ ] Workflow templates (`workflow-templates/`) — reusable GitHub Actions for CI/CD

## Overriding templates per repo

If a specific repository needs different templates, add a local
`.github/ISSUE_TEMPLATE/` folder to that repo. It will take precedence
over these org-wide defaults automatically.
