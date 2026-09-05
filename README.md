# CISSP Study Guide

> **Status: HISTORICAL LEARNING ARCHIVE**  
> CISSP achieved in August 2026. This repository is retained as original study material for other learners; it is not an active professional project and is not intended to represent my current technical portfolio.

Practical notes and exam-preparation guidance for the **ISC2 Certified Information Systems Security Professional (CISSP)**, based on the approach I used to pass.

> Original notes only. No recalled exam questions, braindumps, or confidential ISC2 exam content.

## The 8 CISSP Domains

1. Security and Risk Management
2. Asset Security
3. Security Architecture and Engineering
4. Communication and Network Security
5. Identity and Access Management (IAM)
6. Security Assessment and Testing
7. Security Operations
8. Software Development Security

## How I Approached CISSP

CISSP rewards broad security understanding and sound judgement more than reflexively choosing the most technical answer. I found it useful to think in terms of **business objective → risk → policy/process → control → technology**.

My preparation was built around four things:

1. Establish enough breadth to recognise the major concepts across all eight domains.
2. Use practice questions diagnostically rather than simply chasing a score.
3. Identify weak domains and drill those instead of studying every domain equally.
4. Practise answering from the perspective appropriate to the question — particularly governance, risk and management.

## Practice-Question Method

For every wrong answer, ask why it was wrong:

- Knowledge gap?
- Confused two similar concepts?
- Answered as an engineer rather than at the required management/governance level?
- Missed a FIRST/BEST/MOST qualifier?
- Chose a technical control before the required process step?

That error classification is more useful than the raw practice-test percentage.

## Exam Mindset

When several answers appear valid, ask:

- What is the business objective?
- What should happen **first**?
- Who owns or accepts the risk?
- Is the question asking for prevention, detection, correction or recovery?
- Does policy, assessment or approval come before implementation?
- Am I solving a larger technical problem than the question actually asks?

## High-Value Memory Aid

### Bell-LaPadula vs Biba

**Bell-LaPadula = Confidentiality** — No Read Up, No Write Down.  
**Biba = Integrity** — No Read Down, No Write Up.

## Exam Technique

Pay close attention to **BEST, MOST, FIRST, PRIMARY, LEAST**. For difficult questions:

1. Eliminate clearly wrong options.
2. Reduce to the plausible choices.
3. Identify whether the question operates at a technical, operational, managerial or governance level.
4. Re-read the qualifier.
5. Choose the answer that most directly satisfies the requirement.

## Contents

- [`domains/README.md`](domains/README.md) — eight-domain revision map
- [`exam-strategy.md`](exam-strategy.md) — question-answering approach
- [`memory-aids.md`](memory-aids.md) — mnemonics and easily confused concepts
- [`study-plan.md`](study-plan.md) — preparation workflow
- [`resources.md`](resources.md) — legitimate resource categories

## Exam Integrity

This repository intentionally excludes braindumps, recalled questions and material that could violate ISC2 examination rules. It is retained as a learning archive, not as current certification guidance; candidates should verify current ISC2 requirements from official sources.