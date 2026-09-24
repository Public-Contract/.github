Public Contract

Executable public contracts for deterministic AI execution, validation, replay, receipts, and bounded compliance evidence.

Public Contract is the public-facing execution and validation surface for work developed by Kevin Flint / Latent Studios around deterministic AI runtime behavior, Monoidal Calculus (MC), Omega-SBS, replayable evidence, component classification, and machine-readable validation receipts.

The organization is designed so a reviewer can move from a public technical claim to an inspectable execution path instead of relying on prose alone.

Start Here

Public Contract Browser Laboratory

Launch: https://public-contract.github.io/

The browser laboratory contains the Public Contract PC01-PC10 series and a local, client-side validation environment.

A visitor can:

- read the canonical Public Contract posts;
- move between plain-language, walkthrough, lab, evidence, technical, and notes views;
- execute bounded local demonstrations;
- inspect OPEN / REVIEW_REQUIRED / HALT outcomes;
- generate machine-readable receipts;
- inspect replay and evidence behavior;
- export receipt and Pixel Witness evidence;
- follow the declared claim boundaries for each contract.

No external backend is required for the public baseline.

The Public Contract Execution Path

REQUEST
  |
  v
DECLARE
  |
  v
EXECUTE
  |
  v
VALIDATE
  |
  +-------------------------------+
  |               |               |
  v               v               v
OPEN      REVIEW_REQUIRED        HALT
  |               |               |
  +---------------+---------------+
                  |
                  v
       AUTHORIZE WHERE REQUIRED
                  |
                  v
               COMMIT
                  |
                  v
               RECEIPT

The central distinction is simple:

«A correct-looking output is evidence about an answer. It is not automatically evidence that the declared computation occurred.»

Public Contract therefore treats generation, execution, validation, authorization, commit, and evidence as distinct operations.

Signal Semantics

Signal| Meaning
"OPEN"| The declared evidence path passed for the stated scope.
"REVIEW_REQUIRED"| A material boundary remains unresolved and requires explicit review before the affected claim or action proceeds.
"HALT"| A required boundary failed or execution left the admitted path.

"OPEN" is not a statement of regulatory approval, legal approval, universal correctness, or unrestricted authorization. It is a bounded validation result tied to declared evidence and scope.

Public Contract Series

The public series develops one control model across ten connected contracts:

Contract| Focus
"PC01"| Execution, not answer appearance
"PC02"| Runtime security and admitted paths
"PC03"| Contract-to-receipt evidence
"PC04"| Replay identity
"PC05"| Validate before commit
"PC06"| Residual opacity and unresolved evidence
"PC07"| Executable compliance grammar
"PC08"| Archive identity and DOI boundaries
"PC09"| Component-level classification
"PC10"| Unified control plane

The browser laboratory keeps the canonical post text separate from teaching, testing, and evidence layers.

Current Public Repository

"Public-Contract.github.io"

Repository:
https://github.com/Public-Contract/Public-Contract.github.io

Purpose:
Public browser laboratory for deterministic AI execution, validation, replay, receipts, and the Public Contract series.

Current public implementation characteristics include:

- static browser execution;
- no required server-side runtime;
- deterministic bounded fixtures;
- local validation gates;
- replayable receipt generation;
- SHA-256 evidence binding;
- Pixel Witness evidence;
- explicit claim boundaries;
- PC01-PC10 navigation and teaching layers.

Source and Archival References

Primary public archival records:

- Zenodo: https://zenodo.org/records/22742076
- Zenodo: https://zenodo.org/records/22822421

Professional reference:

- Kevin Flint: https://www.linkedin.com/in/kevin-flint-76ab76303

These references identify public source, archival, and professional context. Archive identity and claim authority remain separate evidence planes.

Component Classification Vocabulary

Public Contract uses bounded component-level classification rather than assigning one label to an entire system:

NOT_AI_DETERMINISTIC
AI_COMPONENT
HYBRID_COMPONENT
PARITY_CONVERTED_COMPONENT
COMPLIANCE_VERIFICATION_INFRASTRUCTURE
UNKNOWN_PENDING_REVIEW

Classification attaches to the operative component and use case under review.

Review Path

A technical reviewer can reproduce the public-facing path as follows:

1. Open the Public Contract Browser Laboratory.
2. Read "PC01" in canonical "Read" mode.
3. Inspect "Understand" and "Walkthrough" for the corresponding mechanism.
4. Run the bounded "Lab" fixture.
5. Inspect the resulting signal and checks.
6. Open "Evidence".
7. Inspect or export the receipt and Pixel Witness.
8. Continue through "PC02-PC10".
9. Use the linked Zenodo records to inspect frozen archival material separately from the executable browser surface.

This creates a direct path from public statement -> mechanism -> execution -> validation -> evidence -> archival reference.

Scope Boundary

The public browser laboratory is a bounded demonstration and teaching surface.

It does not imply that:

- every Latent Studios runtime component is published;
- every production validation package is represented by the public fixtures;
- a DOI upgrades or proves a technical claim by itself;
- an "OPEN" signal grants legal, regulatory, security, deployment, or organizational authorization;
- public access grants a license beyond any separately published license terms.

Attribution

Public Contract / MC / Omega-SBS work presented here is authored and developed by Kevin Flint / Latent Studios unless a source is explicitly attributed otherwise.

Third-party mathematics, architectures, standards, papers, and source material remain attributed to their respective authors and authorities.

Repository and Evidence Principle

PUBLIC CLAIM
    |
    v
DECLARED MECHANISM
    |
    v
BOUNDED EXECUTION
    |
    v
VALIDATION GATE
    |
    v
MACHINE-READABLE RECEIPT
    |
    v
REPLAY / EVIDENCE

The objective is not to make a claim look authoritative.

The objective is to make the claimed execution path inspectable.

---

(c) 2026 Kevin Flint / Latent Studios. All Rights Reserved.

No license grant is implied by this organization profile except where a separately published license expressly states otherwise.
