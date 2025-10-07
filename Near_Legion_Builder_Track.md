# Builder track goals

- Activate builders on Shade agents, NEAR Intents, cross-chain signatures, private AI.
- Move work from POC to MVP to production with NERN.
- Produce code, docs, and partner integrations the ecosystem reuses (more [Tech Enablement Content Types](https://www.notion.so/Tech-Enablement-Content-Types-237da22d7b6480bd95e5ea906cfd0716?pvs=21).

# Rank gates for Builder

- Initiate. Complete 5 of 9 Initiate missions. At least 1 Feedback and 4 Build missions.
- Ascendant. Complete 5 of 7 Ascendant missions. Must include "Submit NERN proposal."
- Vanguard. Complete 3 of 4 Vanguard missions. Must include "Awarded NERN bounty" or "Accepted NERN milestone."
- Prime. Complete 3 of 4 Prime missions. Must include 1 Partner integration and 1 Dev Hub blueprint.
- Mythic. Complete 3 of 4 Mythic missions. Must include "Production release" or "Maintainer-ship."

# Mission spec template

- **Cape-Rank-#. Title**
- Task. What you ship.
- Evidence. Required links and files.
- Acceptance. Checklist reviewers follow.

## Initiate pack

**B-I-1. NEAR account and wallet setup**

- Task. Create a NEAR account and wallet. Send a test transaction and verify it on explorer.
- Evidence. NEAR account ID, wallet address, and explorer link to test transaction.
- Acceptance. Transaction appears on NEAR explorer with correct details.

**B-I-2. Dev environment ready**

- Task. Install NEAR CLI and SDK. Scaffold a project.
- Evidence. Repo link with initial commit. CLI version in README.
- Acceptance. Repo has working project scaffold. CLI version matches installation guide.

**B-I-3. Deploy Shade agent sandbox**

- Task. Run the sandbox and change one agent behavior.
- Evidence. Repo link and short demo clip or hosted page.
- Acceptance. Diff shows the change. Demo runs.

**B-I-4. Intents demo run**

- Task. Execute a cross-chain swap using near intents OneClick API.
- Evidence. Tx hash link. Code repo
- Acceptance. Tx is valid on explorer.

**B-I-5. Cross-chain signature round-trip**

- Task. Produce a signature on chain X. Verify in a NEAR contract.
- Evidence. Repo link with test, verifier contract, and test output.   Tx hash link
- Acceptance. Tx is valid on explorer.

**B-I-6. Private AI quickstart**

- Task. Run a NEAR Private AI example locally and log one inference.
- Evidence. Repo link and console log screenshot.
- Acceptance. Log shows model name and inference hash.

**B-I-7. Feedback ticket on a prototype**

- Task. File one high-quality issue on a prototype from the catalog.
- Evidence. Issue link with label "legion-feedback".
- Acceptance. Issue demonstrates understanding of the codebase and provides actionable feedback.

**B-I-8. Documentation improvement feedback**

- Task. Review a prototype's README and suggest specific documentation improvements.
- Evidence. Issue link with label "legion-feedback" and specific suggestions.
- Acceptance. Feedback addresses real documentation gaps with concrete examples.

**B-I-9. Code review feedback**

- Task. Review a prototype's code and provide constructive technical feedback.
- Evidence. Issue link with label "legion-feedback" and code-specific suggestions.
- Acceptance. Feedback shows code analysis and suggests testable improvements.

## Ascendant pack

**B-A-1. Submit a NERN proposal**

- Task. Propose work tied to a vetted POC from the catalog.
- Evidence. NERN proposal link. Repo plan and milestones in the proposal.
- Acceptance. Proposal delivers on prototyping needs.

**B-A-2. Ship a public tech demo**

- Task. Build a demo using one pillar tech. Publish a short blog.
- Evidence. Repo link, live demo link, blog link.
- Acceptance. README has run steps. Blog explains what you built and why.

**B-A-3. Two verified feedback issues**

- Task. Open two issues across two prototypes.
- Evidence. Two issue links with “legion-feedback”.
- Acceptance. Maintainer adds acknowledgement label.

**B-A-4. First PR to a prototype**

- Task. Submit a non-trivial PR, for example bug fix or docs with code sample.
- Evidence. PR link.
- Acceptance. PR merged or reviewed with actionable comments.

**B-A-5. Partner SDK hello-world replacement**

- Task. Replace an existing partner example with another NEAR-aligned partner.
- Evidence. Repo fork, PR link to partner repo if external.
- Acceptance. Example runs and references NEAR.

## Vanguard pack

**B-V-1. Awarded NERN bounty or accepted milestone**

- Task. Win a bounty or deliver Milestone 1.
- Evidence. On-chain award or milestone acceptance link.
- Acceptance. NERN shows status.

**B-V-2. MVP Milestone 1 delivery**

- Task. Deliver core functionality for a prototyping catalog POC.
- Evidence. Release tag, merged PRs, demo video.
- Acceptance. Maintainer sign-off.

**B-V-3. Tech Enablement Content**

- Task. Publish a how-to or blueprint for your demo.
- Evidence. Content link.
- Acceptance. Guide installs and runs from scratch.

**B-V-4. Community demo session**

- Task. Present a 5–10 minute live demo or recorded talk.
- Evidence. Recording link and slides link.
- Acceptance. Shows code and run steps.

## Prime pack

**B-P-1. Partner integration**

- Task. Build and document an integration with a listed partner, for example Alchemy, Ankr, Infura, thirdweb, a wallet, or an auth provider.
- Evidence. Repo, guide, and sample app.
- Acceptance. Partner contact adds acknowledgement or merges a docs PR.

**B-P-2. Multi-partner demo application**

- Task. Build a demo app that integrates at least two different partners (e.g., wallet + indexer, or auth provider + storage).
- Evidence. Repo link, live demo, and integration guide showing both partner APIs.
- Acceptance. Demo successfully uses both partner services with clear separation of concerns.

**B-P-3. Partner SDK contribution**

- Task. Contribute improvements to a partner's NEAR SDK or documentation.
- Evidence. PR link to partner repository and merged confirmation.
- Acceptance. Contribution improves NEAR developer experience with the partner's service.

**B-P-4. Cross-partner compatibility layer**

- Task. Build an abstraction layer that works with multiple similar partners (e.g., multiple indexers or wallets).
- Evidence. Repo with compatibility layer, usage examples for 2+ partners, and migration guide.
- Acceptance. Layer successfully abstracts partner differences and enables easy switching.

## Mythic pack

**B-M-1. Production release**

- Task. Ship v1 to mainnet or a production endpoint with SLOs.
- Evidence. Release notes, uptime dashboard, and on-chain txs or usage stats.
- Acceptance. 30-day uptime target defined. Dashboard public.

**B-M-2. Maintainership**

- Task. Take ownership of a module or repo.
- Evidence. Maintainer file update and three merged PRs from others.
- Acceptance. Two contributors confirm reviews were helpful.

**B-M-3. Mentor two builders to Vanguard**

- Task. Mentor two named builders through Ascendant to Vanguard.
- Evidence. Their Legion profiles and short write-ups on what they shipped.
- Acceptance. Both reach Vanguard. They add your handle in their submission.

**B-M-4. Partner reference integration**

- Task. Land a partner-approved reference guide or sample in their docs.
- Evidence. Live partner docs link.
- Acceptance. Partner repo or site shows your work.

# Evidence rules

- Link field required on every mission.
- For code, include repo URL, tag or commit, and run steps.
- For on-chain steps, include explorer links or NERN links.
- For demos, include a short clip or a live URL.
- Proof text limit 500 chars. Focus on what you built and where to find it.
- Images up to 5 files, 1 MB each. Screenshots required when marked.

# Reviewer checklist

- Links resolve and match the task.
- Repo builds and runs from README.
- Tx hashes are valid.
- Issues and PRs meet the content standard above.
- No plagiarism or duplicate submissions.
- Target reviewer SLA, 72 hours.