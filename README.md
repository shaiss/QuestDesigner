# Quest Designer for NEAR Legion

Quest Designer is a structured framework for designing, managing, and validating Builder track missions for NEAR Legion. It provides comprehensive Cursor rules to ensure consistent, high-quality mission design aligned with NEAR ecosystem pillars.

## Overview

NEAR Legion Builder track activates builders on four technical pillars:
- **Shade Agents**: AI agents on NEAR infrastructure
- **NEAR Intents OneClick API**: Cross-chain swap execution
- **Cross-Chain Signatures**: Multi-chain operations and verification
- **NEAR Private AI**: Privacy-preserving AI inference

Missions route work through NERN for bounties and publish guides on Dev Hub.

## Project Structure

```
QuestDesigner/
├── .cursor/
│   └── rules/          # Cursor rules for quest design
├── Near_Legion_Builder_Track.md  # Main mission specifications
└── README.md
```

## Cursor Rules

This project includes 12 Cursor rules that guide mission design:

### Always Applied
- **quest-designer-role**: Core role definition, output style, and constraints

### Contextual Rules (Fetched as Needed)
- **rank-gates**: Five rank definitions and progression requirements
- **mission-template**: Standard mission specification format
- **evidence-rules**: Submission and review requirements
- **reviewer-checklist**: Standard review process and criteria
- **difficulty-map**: Difficulty progression across ranks
- **metrics**: Success tracking and quality indicators
- **near-pillars**: Technical pillar definitions and integration
- **nern-integration**: Bounty and milestone requirements
- **dev-hub-publishing**: Content publishing standards
- **partner-integrations**: Partner integration requirements
- **mission-design-defaults**: Default choices for efficient design

## Rank Structure

### Initiate
Entry-level setup and single-pillar tasks. Complete 5 of 7 missions.

### Ascendant
Dual-pillar demos, CI, first NERN proposal. Complete 5 of 7 missions.

### Vanguard
MVP delivery, package release, public demo. Complete 4 of 6 missions.

### Prime
Partner integration, indexer/API, production readiness. Complete 4 of 6 missions.

### Mythic
Production release, maintainership, mentorship. Complete 3 of 4 missions.

## Mission Design Principles

1. **Verifiable Output**: Every mission produces code, data, or content with a link
2. **Quick Review**: Each mission reviewable in under 15 minutes
3. **Progressive Difficulty**: Escalate difficulty each rank, no grind
4. **Reusable Modules**: Prefer reusable patterns over one-off demos
5. **Public References**: Reference only public links or catalog repos

## Mission Format

```
**B-[Rank]-[#]. [Title]**

- Task. One paragraph with exact outcome.
- Evidence. Required links (repo, explorer, NERN, video).
- Acceptance. Binary checks reviewers follow.
```

## Evidence Requirements

- **Link required** on every submission
- **Code**: Repo URL + tag/commit + README with run steps
- **On-chain**: Explorer links or NERN links
- **Demos**: Short clip or live URL
- **Text limit**: 500 characters
- **Screenshots**: Up to 5 files, 1 MB each

## Review Standards

- Links resolve and match task
- Project builds from clean clone with one command
- Tests or CI pass
- Explorer links valid
- No plagiarism or duplicates
- **Target SLA**: 72 hours

## Usage with Cursor

The Cursor rules automatically:
- Apply Quest Designer style guidelines to all conversations
- Fetch relevant rules based on your task
- Validate missions against standards
- Suggest improvements following best practices

### Example Workflows

**Add new mission:**
```
"Add a new Ascendant mission for Shade agents + NEAR Intents"
```

**Review missions:**
```
"Review all Vanguard missions for consistency"
```

**Create content:**
```
"Generate reviewer training document"
```

## NERN Integration

Missions integrate with NERN (NEAR bounty platform):
- Ascendant requires NERN proposal
- Vanguard requires awarded bounty or accepted milestone
- All significant work routes through NERN

## Dev Hub Publishing

Content requirements:
- Prime rank requires Dev Hub blueprint
- Guides must install and run from scratch
- Include working code samples and troubleshooting
- Enable ecosystem reuse

## Contributing

Follow the mission design defaults:
- Reduce review time
- Increase reuse potential
- Align with NEAR ecosystem standards
- Produce verifiable evidence

## Metrics Tracked

- Submission count and acceptance rate
- Time to review and bounce rate
- NERN proposals, awards, and milestones
- Package downloads, forks, guide views
- Builder progression and retention

## License

This framework is designed for NEAR Legion Builder track mission design.

## Links

- [NEAR Legion](https://near.org)
- [NERN Platform](https://nern.near.org)
- [Dev Hub](https://dev.near.org)
