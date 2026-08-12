# Agent Identity Registry Protocol Community Group Charter

_Based on the [W3C Community Group Charter Template](https://w3c.github.io/cg-charter/CGCharter.html) · June 2026_

---

> **Note:** 'ARIA' in this document refers to the Agent Registry for Identity & Authorization protocol developed by TrustLayer Foundation A.C. It is unrelated to W3C ARIA (Accessible Rich Internet Applications), which is a separate W3C standard for web accessibility.

---

| Field | Value |
|---|---|
| This Charter | https://github.com/w3c-cg/agent-identity/blob/main/CHARTER.md |
| Previous Charter | |
| Mailing List | public-agent-identity@w3.org |
| GitHub Repository | https://github.com/w3c-cg/agent-identity |
| Last Modified | |

---

## Goals

The Agent Identity Registry Protocol Community Group aims to develop shared understanding, use cases, requirements, and community specifications for cross-organizational AI agent identity, authorization, and trust infrastructure.

Specifically, the group seeks:

- To develop shared understanding of the requirements for AI agents to carry verifiable, cryptographically signed identities that survive crossing organizational boundaries. Note: throughout this charter, "ARIA" refers to the Agent Registry for Identity & Authorization protocol; it is unrelated to W3C WAI-ARIA (Accessible Rich Internet Applications).
- To produce use cases, requirements documents, and community specifications for cross-organizational agent identity — including the ARIA Protocol's DID method (did:aria), credential lifecycle, and Agent Trust Protocol (ATP) — as implemented at aria.bar.
- To gather implementation evidence and community feedback on the ARIA Protocol and adjacent agent identity approaches.
- To engage with adjacent standards work at IETF, DIF, OpenID Foundation, and other bodies engaged in agent identity, verifiable credentials, and trust infrastructure.
- To serve as the incubation stage for potential future standardization through the W3C Working Group track, when community participation and implementation evidence warrant it.

---

## Scope of Work

The group's work covers the following areas:

- Agent identity formats and credential structures for cross-organizational AI agent identification.
- Verification protocols for AI agent authorization, intent declaration, and delegation chains.
- Revocation mechanisms and audit trail requirements for AI agent credentials.
- Use cases for AI agents operating across organizational boundaries in regulated and unregulated contexts.
- Interoperability requirements between agent identity infrastructure and existing standards including OAuth 2.0, FAPI, MCP, W3C Verifiable Credentials, W3C DIDs, and NIST SP 800-63-4.
- Requirements for post-quantum cryptography in agent identity systems.

### Out of Scope

- **Normative authority over TLF-stewarded specifications.** The TLF Technical Steering Committee retains normative authority over the ARIA Protocol and all TLF-stewarded specifications. CG specifications are community outputs and do not supersede TLF-published normative specifications.
- **UCDM Protocol.** This CG will provide input about one of TLF's specifications, the ARIA Protocol. This CG will not provide input about a second TLF specification, the UCDM Protocol (Universal Commerce Data Model), addressed by a separate TLF Working Group.
- **W3C WAI-ARIA.** This group does not address web accessibility. See the W3C Accessibility Guidelines for WAI-ARIA work.
- **General AI safety, AI ethics, or AI regulation** beyond the specific technical scope of agent identity and authorization standards.

---

## Deliverables

### Specifications

The group may choose to develop community specifications within the scope defined above. The specific deliverables will be shaped by the group's participants once the community forms. Illustrative examples of specifications the group may choose to pursue include:

- Agent identity use cases and requirements documenting real-world scenarios for cross-organizational AI agent identity across regulated sectors such as finance, healthcare, and government.
- An interoperability profile describing how the ARIA Protocol composes with OAuth 2.0, FAPI, MCP, and W3C Verifiable Credentials in common deployment scenarios.

These examples are illustrative, not predetermined; the group's participants will decide its actual deliverables. Any specification produced by the group is a Community Group output and does not constitute a W3C Recommendation.

_Note on specification layers: The ARIA Protocol is published and maintained by TrustLayer Foundation as the normative specification. This Community Group's work — use cases, requirements, and community specifications — informs that process but does not supersede it. Should a future W3C Working Group be chartered, it would produce a normative profile under W3C process._

### Non-Normative Reports

The group may produce other Community Group Reports within the scope of this charter that are not Specifications, such as use cases, requirements, or white papers.

### Test Suites and Other Software

The group does not currently plan to produce test suites or reference software as formal CG deliverables.

Note: Participants are encouraged to implement and test the ARIA Protocol using TLF's published specification and SDK at aria.bar. If this changes, test suite contribution licensing information will be governed by the GitHub LICENSE file in the group's repository.

---

## Dependencies or Liaisons

### TrustLayer Foundation A.C.

TrustLayer Foundation A.C. (TLF) stewards the ARIA Protocol, which is the primary specification this group provides input on. From time to time the CG may invite TLF to review proposals that are communicated via the CG's repository, along with instructions for how TLF can comment on the proposals. For reference, TLF's governance structure and its relationship to this Community Group are documented in TLF's Governance Framework, available in TrustLayer Foundation's public documents repository at github.com/trustlayer-foundation.

### Other Groups

The group intends to coordinate with the following external bodies on adjacent and related work:

- **IETF WIMSE Working Group** (Workload Identity in Multi-System Environments) — adjacent work on cross-system identity.
- **Decentralized Identity Foundation (DIF)** — particularly the Trusted AI Agents Working Group (TAIWG) and Identifiers & Discovery Working Group.
- **OpenID Foundation** — IPSIE Working Group on enterprise identity for AI agents.
- **W3C Credentials Community Group (CCG)** — adjacent work on Verifiable Credentials and DIDs.
- **NIST National Cybersecurity Center of Excellence** — AI agent identity standards alignment.

---

## Community and Business Group Process

The group operates under the [Community and Business Group Process](https://www.w3.org/community/about/process). Terms in this Charter that conflict with those of the Community and Business Group Process are void.

As with other Community Groups, W3C seeks organizational licensing commitments under the [W3C Community Contributor License Agreement (CLA)](https://www.w3.org/community/about/process/cla/). When people request to participate without representing their organization's legal interests, W3C will in general approve those requests, with the following understanding: W3C will seek and expect an organizational commitment under the CLA starting with the individual's first request to make a contribution to a group Deliverable. The section on Contribution Mechanics describes how W3C expects to monitor these contribution requests.

The [W3C Code of Conduct](https://www.w3.org/policies/code-of-conduct/) and [W3C Antitrust and competition policy](https://www.w3.org/policies/antitrust-2024/) apply to participation in this group.

---

## Work Limited to Charter Scope

The group will not publish specifications on topics other than those listed under Specifications above. See below for how to modify the charter.

---

## Contribution Mechanics

Substantive contributions to specifications can only be made by Community Group Participants who have agreed to the [W3C Community Contributor License Agreement (CLA)](https://www.w3.org/community/about/process/cla/).

Reports other than Specifications published by this group should use the [W3C Software and Document License](https://www.w3.org/copyright/software-license-2023/) where possible.

Community Group participants agree to make all contributions in the GitHub repository the group is using for the particular document — e.g., via pull requests, issues, or comments on existing issues.

All GitHub repositories attached to the Community Group must contain a copy of the [CONTRIBUTING](https://github.com/w3c/licenses/blob/main/CG-CONTRIBUTING.md) and [LICENSE](https://github.com/w3c/licenses/blob/main/CG-LICENSE.md) files.

> **IPR note:** Participation in this Community Group and signing the W3C CLA does not constitute a Contribution to the ARIA Protocol specification. ARIA Protocol specification contributions are governed separately by TLF's IPR Policy and require execution of TLF's Developer Certificate of Origin (DCO), independent of W3C CLA obligations. Community Group work — including use cases, requirements documents, and CG specifications — informs the TLF specification process but does not supersede TLF-published normative specifications.

---

## Transparency

The group will conduct all technical work in public. If the group uses GitHub, technical work will occur in its GitHub repositories (and not privately on mailing lists).

Meetings may be restricted to Community Group participants, but a public summary or minutes must be posted to the group's public mailing list or as an issue on GitHub.

---

## Decision Process

This group will seek to make decisions where there is consensus. Groups are free to decide how to make decisions (e.g., Participants who have earned Committer status for a history of useful contributions assess consensus, or the Chair assesses consensus, or where consensus isn't clear there is a Call for Consensus [CfC] to allow multi-day online feedback for a proposed course of action). It is expected that participants can earn Committer status through a history of valuable contributions, as is common in open source projects. After discussion and due consideration of different opinions, a decision should be publicly recorded (where GitHub is used as the resolution of an Issue).

If substantial disagreement remains (e.g., the group is divided) and the group needs to decide an Issue in order to continue to make progress, the Committers will choose an alternative that had substantial support (with a vote of Committers if necessary). Individuals who disagree with the choice are strongly encouraged to take ownership of their objection by taking ownership of an alternative fork. This is explicitly allowed (and preferred to blocking progress) to let implementation experience inform which spec is ultimately chosen by the group to move ahead with.

Any decisions reached at any meeting are tentative and should be recorded in a GitHub Issue for groups that use GitHub and otherwise on the group's public mail list. Any group participant may object to a decision reached at an online or in-person meeting within 7 days of publication of the decision provided that they include clear technical reasons for their objection. The Chairs will facilitate discussion to try to resolve the objection according to this decision process.

It is the Chairs' responsibility to ensure that the decision process is fair, respects the consensus of the CG, and does not unreasonably favor or discriminate against any group participant or their employer.

---

## Chair Selection

Participants in this group choose their Chair(s) and can replace their Chair(s) at any time using whatever means they prefer. However, if 5 participants, no two from the same organization, call for an election, the group must use the following process to replace any current Chair(s) with a new Chair, consulting the Community Development Lead on election operations (e.g., voting infrastructure and using [RFC 3797](https://datatracker.ietf.org/doc/html/rfc3797)).

- Participants announce their candidacies. Participants have 14 days to announce their candidacies, but this period ends as soon as all participants have announced their intentions. If there is only one candidate, that person becomes the Chair. If there are two or more candidates, there is a vote. Otherwise, nothing changes.
- Participants vote. Participants have 21 days to vote for a single candidate, but this period ends as soon as all participants have voted. The individual who receives the most votes, no two from the same organization, is elected chair. In case of a tie, RFC 3797 is used to break the tie. An elected Chair may appoint co-Chairs.

Participants dissatisfied with the outcome of an election may ask the Community Development Lead to intervene. The Community Development Lead, after evaluating the election, may take any action including no action.

---

## Amendments to This Charter

The group can decide to work on a proposed amended charter, editing the text using the Decision Process described above. The decision on whether to adopt the amended charter is made by conducting a 30-day vote on the proposed new charter. The new charter, if approved, takes effect on either the proposed date in the charter itself, or 7 days after the result of the election is announced, whichever is later. A new charter must receive 2/3 of the votes cast in the approval vote to pass. The group may make simple corrections to the charter such as deliverable dates by the simpler group decision process rather than this charter amendment process. The group will use the amendment process for any substantive changes to the goals, scope, deliverables, decision process or rules for amending the charter.

---

_Template source: https://w3c.github.io/cg-charter/CGCharter.html_
