# Threat Intelligence Briefs

This repository is a cybersecurity portfolio project focused on short, structured threat intelligence briefs.

The goal is to practice security analysis, communicate technical risk clearly, and build a body of work for graduate school applications in cybersecurity, network security, or threat intelligence.

## Current Briefs

| Brief | Topic | Focus |
|---|---|---|
| [Brief 001](briefs/brief-001-credential-phishing-cloud-account-takeover.md) | Credential Phishing and Cloud Account Takeover | Phishing, stolen credentials, cloud account abuse, MFA risk |

## Method

Each brief follows a consistent structure:

1. Executive summary
2. Threat scenario
3. Attack flow
4. MITRE ATT&CK mapping
5. Detection ideas
6. Defensive recommendations
7. Key learning points

The briefs avoid unverified indicators of compromise. When specific indicators are not available from reliable public sources, the analysis focuses on behaviors, detection logic, and defensive controls.

## Research Direction Fit

My current research direction is AI-assisted cybersecurity investigation and threat intelligence analysis for identifying attack patterns and improving incident response.

This project supports that direction by:

- Turning public security incidents and attack scenarios into structured intelligence briefs that can be used during early incident triage.
- Mapping attacker behavior to MITRE ATT&CK techniques, detection ideas, and defensive recommendations, which creates the kind of structured context an AI-assisted investigation workflow would need.
- Practicing clear English security communication so technical findings can be converted into incident response notes, executive summaries, and follow-up analysis.

For a fuller explanation, see [Research Direction Fit](docs/research-direction.md).

## Portfolio Roadmap

The next related portfolio project should move from written briefs to AI-assisted incident triage. A focused `ai-assisted-incident-triage` or `threat-intel-correlation-lab` project could analyze 3-5 public incidents or phishing samples, organize IOCs and attack methods, generate an incident summary, suggest ATT&CK mappings, assign a priority score, and propose response recommendations.

## Why This Project

My background combines language ability, networking fundamentals, and cybersecurity preparation:

- TOEIC 955
- JLPT N1
- CCNA
- Current focus: Security+, network security, phishing analysis, and threat intelligence

This project is designed to show that I can read security material, structure a threat scenario, map attacker behavior to known frameworks, and communicate risk in clear English.

## Repository Structure

```text
threat-intelligence-briefs/
├── README.md
├── briefs/
│   └── brief-001-credential-phishing-cloud-account-takeover.md
├── docs/
│   └── research-direction.md
├── templates/
│   └── brief-template.md
└── notes/
    └── glossary.md
```

## Reference Frameworks

- [MITRE ATT&CK](https://attack.mitre.org/)
- [CISA Cybersecurity Resources](https://www.cisa.gov/cybersecurity)
- [CISA MFA Guidance](https://www.cisa.gov/mfa)
