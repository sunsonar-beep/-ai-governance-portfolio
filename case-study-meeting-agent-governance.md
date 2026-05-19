# Case Study: LLM Governance for an AI Meeting Summary Agent

**Domain:** LLM Governance
**Type:** Internal Deployment — Automated Meeting Summarisation
**Deliverables:** Governance Report · Compliance Process · Policy Documentation

---

## Background

An organisation deployed an LLM-based agent to automatically summarise meetings — integrating with calendar systems, retrieving context, and delivering summaries to attendees via automated workflows. As the solution scaled, concerns arose around hallucination risk, output accuracy, privacy compliance, and access control.

I led governance validation for this solution, ensuring all AI controls were audit-ready before wider rollout.

---

## Problem Statement

- LLM outputs were not evaluated for hallucination frequency or factual accuracy
- Privacy risks from calendar integration and context retrieval were unaddressed
- Access controls for who could receive AI-generated summaries were undefined
- Automated delivery workflows lacked governance checkpoints
- No audit trail existed for generated summaries or model decisions

---

## My Role

- Led end-to-end governance validation for the LLM summarisation pipeline
- Assessed hallucination risks and defined controls to manage them
- Evaluated privacy and access control compliance across the integration layer
- Ensured all governance controls were documented and audit-ready

---

## Approach

### 1. Hallucination Risk Assessment
- Reviewed LLM prompting patterns for susceptibility to confabulation
- Defined hallucination categories relevant to meeting summaries (e.g. fabricated action items, incorrect attributions, invented decisions)
- Designed a spot-check and feedback mechanism for ongoing output monitoring
- Recommended prompt engineering guardrails and grounding techniques

### 2. Output Accuracy Validation
- Established accuracy criteria for summaries (completeness, attribution correctness, tone neutrality)
- Designed a human-in-the-loop validation step for high-stakes meeting types
- Defined acceptable error thresholds and escalation triggers

### 3. Privacy & Access Control Compliance
- Mapped data flows: calendar integration → context retrieval → summary generation → delivery
- Identified personal data exposure risks at each stage
- Documented access control requirements (role-based summary access, opt-out mechanisms)
- Aligned controls with internal data privacy policies

### 4. Audit Readiness
- Designed logging requirements for all pipeline stages
- Documented governance controls in a format suitable for internal audit review
- Created a compliance checklist for future deployments of similar LLM agents

---

## Deliverables

| Deliverable | Description |
|---|---|
| Hallucination Risk Assessment | Risk taxonomy, likelihood ratings, and recommended mitigations |
| Output Accuracy Framework | Criteria, validation process, and human review triggers |
| Privacy & Access Control Policy | Data flow map, access rules, and opt-out process |
| Audit-Ready Governance Report | End-to-end controls documentation for internal audit |
| Compliance Checklist | Reusable checklist for LLM agent deployments |

---

## Outcomes

- Delivered a comprehensive governance layer for an LLM agent in production
- Identified and mitigated key hallucination and privacy risks prior to full rollout
- Produced audit-ready documentation that satisfied internal compliance review
- Established a reusable governance template for future LLM deployments across the organisation

---

## Key Skills Demonstrated

`LLM Governance` `Hallucination Risk Assessment` `Privacy Compliance` `Access Control Design` `Audit Readiness` `LLM Output Validation` `AI Policy Writing` `Internal AI Frameworks`
