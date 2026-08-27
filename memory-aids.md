# CISSP Memory Aids

These are compact revision cues. Understand the underlying concept rather than relying on the mnemonic alone.

## Bell-LaPadula vs Biba

### Bell-LaPadula — Confidentiality

**BLP Blocks Leaks of Private information.**

- No Read Up
- No Write Down

Goal: prevent information from leaking from higher classifications to lower classifications.

### Biba — Integrity

**Biba Builds Integrity.**

- No Read Down
- No Write Up

Goal: protect higher-integrity information from contamination by lower-integrity sources.

## CIA Triad

- Confidentiality — prevent unauthorised disclosure
- Integrity — prevent unauthorised/inappropriate modification
- Availability — ensure reliable access when required

## AAA

- Authentication — who are you?
- Authorization — what can you do?
- Accounting — what did you do?

## Risk treatment

**Avoid — Mitigate — Transfer — Accept**

Remember that risk acceptance requires appropriate authority.

## Control functions

- Preventive — stop it
- Detective — find it
- Corrective — fix it
- Deterrent — discourage it
- Recovery — restore it
- Compensating — alternative protection

## Business continuity numbers

- RTO — how quickly the service must be restored
- RPO — how much data loss measured in time can be tolerated

A useful distinction: **RTO is about time to service; RPO is about point in data.**

## Due care vs due diligence

- Due diligence — investigate, understand and continuously assess
- Due care — take reasonable action based on what is known

## Need-to-know vs least privilege

- Need-to-know — access only to information required
- Least privilege — only the permissions necessary to perform the role

## Authentication factors

- Something you know
- Something you have
- Something you are

Location and behavioural characteristics may also appear in broader authentication discussions; distinguish factor categories based on the context/question.

## Symmetric vs asymmetric

- Symmetric — same shared secret; efficient for bulk encryption
- Asymmetric — public/private key pair; useful for key exchange, signatures and identity-related mechanisms

## Hashing

Hashing is one-way and is primarily associated with integrity-related use cases. It is not encryption.