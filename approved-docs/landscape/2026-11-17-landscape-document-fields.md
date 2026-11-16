# Landscape document — fields

**Version:** 1.0, proposed for approval at the meeting of 2026-11-17
**Chair:** Adolfo Grego Micha

## What this is

A shared map of who is doing what in agent identity, so that efforts can see where they touch and who could benefit from each other's proposals. Entries are written by the participants who know the effort best.

## Fields

1. **Name.** What the effort calls itself.
2. **Type.** Open specification · standards group · company protocol · open-source project · paper · regulatory initiative.
3. **Link.** One canonical URL.
4. **What it is.** Two or three sentences.
5. **Where it touches agent identity.** Why it belongs on the map.
6. **Does not cover.** What it deliberately does not do.
7. **How it can be checked.** Whether someone outside the effort can verify its claims, and with what: a public specification, test vectors, conformance results, or nothing yet. Say whether the check needs the effort itself to be online, or can be repeated from a saved file.
8. **Status, as of [date].** Draft · testing · implemented · dormant. Always give the date.
9. **Who added this.** The name of whoever wrote the entry.

## Example: ARIA

- **Name:** ARIA — Agent Registry for Identity & Authorization
- **Type:** Open specification, stewarded by a nonprofit
- **Link:** <https://aria.bar/spec>
- **What it is:** An accountability layer for AI agents crossing organizational boundaries. Credentials are W3C Verifiable Credentials, signed with a post-quantum composite signature.
- **Where it touches agent identity:** Issues the credential an agent carries when it leaves its own trust domain, and defines the scope of what the agent is authorized to do.
- **Does not cover:** What an agent does after admission. Runtime attestation. On-chain presentation.
- **How it can be checked:** Specification: public at [aria.bar/spec](https://aria.bar/spec). Credentials: anyone can verify an agent's signature, trust level, scopes and revocation status at [aria.bar/verify](https://aria.bar/verify) without logging in; the check needs the ARIA resolver to be online, and the verifier currently reads a demonstration issuer. Code: open-source verification SDK and public resolver API. Working demo: [thebunny.bar](https://thebunny.bar) (issuer) and [thecarrot.rest](https://thecarrot.rest) (receiver).
- **Status, as of 2026-11-17:** Implemented at L0 and L1 in the live environment. L2 and L3 in a testing environment.
- **Who added this:** Adolfo Grego Micha

## How to add an entry

Participants of the group can add an entry by pull request, adding a row to the table in `landscape/README.md`. Anyone else can send the entry to the chair or open an issue in this repository. Entries are written in the fields above. The chair does not edit the substance of an entry.
