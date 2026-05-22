I work across cloud products, developer platforms, AI workflows, and operational systems.

Most of the public work here is intentionally small and practical: workflow checks, planning utilities, OCI Functions starter patterns, and short notes on where adoption, trust, and execution usually break. The pattern I keep caring about is whether a repo makes the first proof, the next handoff, and the rerun path obvious.

## Start by what you want

- **Context first**: [Portfolio site](https://winnielinnie.github.io/winstonlin-site/) for the cleanest route across case studies, writing, and selected repos
- **Higher-context product work**: [Case studies](https://winnielinnie.github.io/winstonlin-site/case-studies/) for cloud, platform, and operating-model work
- **Grouped repo view**: [Projects page](https://winnielinnie.github.io/winstonlin-site/projects/) for the tracks behind the public tools and starter repos
- **Route labels on the site**: [Start Cards Should Name the Route](https://winnielinnie.github.io/winstonlin-site/blog/start-cards-should-name-the-route/) for why the homepage and track cards now say more explicitly whether they lead to proof, context, or published work
- **Discovery-path rule**: [Discovery Paths Should Name the First Move](https://winnielinnie.github.io/winstonlin-site/blog/discovery-paths-should-name-the-first-move/) for why the homepage intent cards now say whether the first click is a case study, context note, project guide, or something else
- **Evidence behind the homepage stats**: [Proof Points Should Route to Evidence](https://winnielinnie.github.io/winstonlin-site/blog/proof-points-should-route-to-evidence/) for why the proof row now points directly to the supporting case study instead of stopping at the number
- **Repo standard behind the batch**: [Good Small Repos Should Show the Second Move](https://winnielinnie.github.io/winstonlin-site/blog/good-small-repos-should-show-the-second-move/)
- **How the surfaces fit together**: [GitHub Should Prove and the Site Should Route](https://winnielinnie.github.io/winstonlin-site/blog/github-should-prove-and-the-site-should-route/)
- **Profile routing rule**: [GitHub Profiles Should Keep One Context Link Per Track](https://winnielinnie.github.io/winstonlin-site/blog/github-profiles-should-keep-one-context-link-per-track/) for why the repo groups below now keep one visible context link each
- **How I think about AI work**: [What Working With Codex Taught Me About AI Work](https://winnielinnie.github.io/winstonlin-site/blog/what-working-with-codex-taught-me-about-ai-work/)

## One proof + one context per track

These are the three starting pairs I want carrying the public repo surface first.

- **Workflow checks**: proof = [`repo-onramp-check`](https://github.com/winnielinnie/repo-onramp-check), guide = [site page](https://winnielinnie.github.io/winstonlin-site/projects/repo-onramp-check/), context = [Examples Are the Interface for Small Tools](https://winnielinnie.github.io/winstonlin-site/blog/examples-are-the-interface-for-small-tools/)
- **Reusable artifacts**: proof = [`one-page-canvas`](https://github.com/winnielinnie/one-page-canvas), guide = [site page](https://winnielinnie.github.io/winstonlin-site/projects/one-page-canvas/), context = [One-Page Tools Beat Premature Decks](https://winnielinnie.github.io/winstonlin-site/blog/one-page-tools-beat-premature-decks/)
- **OCI Functions starter patterns**: proof = [`oci-fn-object-storage-router`](https://github.com/winnielinnie/oci-fn-object-storage-router), guide = [site page](https://winnielinnie.github.io/winstonlin-site/projects/oci-fn-object-storage-router/), context = [Functions Design Patterns](https://blogs.oracle.com/cloud-infrastructure/oci-functions-common-patterns/)

<details>
<summary>Expand full repo inventory by track</summary>

## Repo tracks

### Workflow checks

- [`repo-onramp-check`](https://github.com/winnielinnie/repo-onramp-check) — checks whether a public repo makes first useful success obvious, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/repo-onramp-check/)
- [`doc-ship-check`](https://github.com/winnielinnie/doc-ship-check) — catches last-mile docs issues before publishing or handoff, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/doc-ship-check/)
- [`release-note-diff-cli`](https://github.com/winnielinnie/release-note-diff-cli) — surfaces the release-note additions most likely to matter, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/release-note-diff-cli/)
- [`incident-timeline-formatter`](https://github.com/winnielinnie/incident-timeline-formatter) — turns rough incident notes into a stable Markdown timeline, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/incident-timeline-formatter/)

### Reusable artifacts

- [`one-page-canvas`](https://github.com/winnielinnie/one-page-canvas) — local-first strategy canvas for tighter one-page thinking, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/one-page-canvas/)
- [`tiny-deck-linter`](https://github.com/winnielinnie/tiny-deck-linter) — catches crowded outlines and vague slide titles before a review, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/tiny-deck-linter/)
- [`decision-journal-cli`](https://github.com/winnielinnie/decision-journal-cli) — keeps decision logs tied to owners, assumptions, and revisit dates, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/decision-journal-cli/)
- [`dependency-risk-check`](https://github.com/winnielinnie/dependency-risk-check) — flags overdue, unowned, and blocked work before the handoff hides the risk, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/dependency-risk-check/)
- [`exec-brief-cli`](https://github.com/winnielinnie/exec-brief-cli) — turns rough notes into a tighter one-page brief with a stable structure, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/exec-brief-cli/)

### OCI Functions starter patterns

- [`oci-fn-object-storage-router`](https://github.com/winnielinnie/oci-fn-object-storage-router) — reusable Python pattern for routing Object Storage events to downstream systems, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/oci-fn-object-storage-router/)
- [`oci-fn-csv-quality-gate`](https://github.com/winnielinnie/oci-fn-csv-quality-gate) — validates inbound CSVs against a small schema contract before deeper processing, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/oci-fn-csv-quality-gate/)
- [`oci-fn-file-manifest-writer`](https://github.com/winnielinnie/oci-fn-file-manifest-writer) — turns inbound file batches into one compact manifest handoff artifact, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/oci-fn-file-manifest-writer/)
- [`oci-fn-webhook-signature-verifier`](https://github.com/winnielinnie/oci-fn-webhook-signature-verifier) — verifies signed inbound webhooks without hiding the audit step, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/oci-fn-webhook-signature-verifier/)
- [`oci-fn-slack-alert-normalizer`](https://github.com/winnielinnie/oci-fn-slack-alert-normalizer) — cleans up noisy alert payloads before they hit chat, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/oci-fn-slack-alert-normalizer/)
- [`oci-fn-queue-worker-starter`](https://github.com/winnielinnie/oci-fn-queue-worker-starter) — shows a queue-driven worker boundary with a small normalized result shape, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/oci-fn-queue-worker-starter/)
- [`oci-fn-scheduled-finops-digest`](https://github.com/winnielinnie/oci-fn-scheduled-finops-digest) — turns recurring usage data into a compact scheduled digest, with a [site guide](https://winnielinnie.github.io/winstonlin-site/projects/oci-fn-scheduled-finops-digest/)

### Public surface

- [`winstonlin-site`](https://github.com/winnielinnie/winstonlin-site) — the portfolio site that routes into the writing, case studies, and repo tracks

</details>

## What ties it together

- **AI workflows**: real tools, files, review loops, and usable output instead of one-off prompting
- **Platform product**: onboarding, migration, reliability, and the friction that decides adoption
- **Operational clarity**: dependencies, incidents, handoffs, and the structures teams rely on day to day
- **Small public tools**: narrow utilities and fun projects that leave behind a reusable output, check, or handoff instead of stopping at a one-time demo

## Elsewhere

- [Functions Design Patterns](https://blogs.oracle.com/cloud-infrastructure/oci-functions-common-patterns/) for the clearest Oracle post on the same boundary-first and design-checklist preferences behind the starter repos
- [Long-Running Functions and Response Destinations](https://blogs.oracle.com/cloud-infrastructure/longrunning-functions-and-response-destinations/) for the async handoff model behind some of the newer Functions notes
- [Oracle blogs](https://blogs.oracle.com/authors/winstonlin_1/)
- [LinkedIn](https://www.linkedin.com/in/winston-lins/)
- [Email](mailto:winstonl.96@gmail.com)
