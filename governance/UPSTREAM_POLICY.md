# AROSA — Upstream Relationship and Contribution Policy

## Purpose

AROSA (Application Runtime Operating Services Abstraction) is an independent application and services platform written for AROS. It complements AROS and does not seek to replace it, appropriate its identity or assume authority over its development. AROSA may be delivered as an integrated distribution based on mainline AROS; this is a delivery mechanism for the platform, not an independent operating-system development programme.

## Mainline and downstream corrections

- **Mainline first.** Mainline AROS is the upstream baseline. Operating-system capabilities, including effective SMP, stability and reliability, must be qualified against AROSA's technical requirements.
- **Minimum divergence.** Where necessary, AROSA may incorporate narrowly scoped downstream kernel corrections. These must address identified technical requirements rather than establish an alternative kernel roadmap.
- **Transparency.** Corrections must be documented, versioned and attributable, with their upstream baseline, rationale, applicable architectures, validation evidence and known limitations recorded.
- **Upstream contribution.** All such kernel corrections will be submitted to the AROS development team for evaluation and potential upstream integration, following its contribution procedures and applicable licensing requirements.
- **Upstream independence.** The AROS development team retains authority over its own development decisions, including acceptance or rejection of contributions. Submission does not imply acceptance or endorsement.
- **Reconciliation.** Equivalent upstream solutions will be preferred and downstream corrections retired once the upstream solution has been validated against AROSA's requirements. Any retained correction must remain justified and documented.
- **Compatibility and qualification.** AROSA will preserve compatible operation and controlled degradation where capabilities are unavailable, without claiming unverified SMP or stability support.

## Scope and cooperation

AROSA does not intend to develop or maintain an alternative version of AROS. Its primary development objective is the application and services platform. Cooperation with the AROS development team is encouraged through constructive technical dialogue, reproducible diagnostics and applicable contributions.

AROSA remains independent and does not claim official AROS affiliation or endorsement.

See also the [Community and Contribution Principles](https://github.com/danilos#community-and-contribution-principles).

Policy adopted: 2026-11-28.
