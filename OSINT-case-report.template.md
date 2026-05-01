---
title: "OSINT Case Report – <Case Title>"
date: <% tp.date.now("YYYY-MM-DD") %>
analyst: "<Your Name>"
contact: "<Email/Contact Info>"
classification: "Internal | Confidential | Public"
tags: [osint, investigation, case-report]
---
# OSINT Case Report

---

## Cover Page

**Case Title:** \<Case Title\>  
**Date:** <% tp.date.now("YYYY-MM-DD") %>  
**Analyst:** \<Your Name>  
**Contact Information:** <Email / Org>  
**Case ID:** \<Optional Unique Identifier>  
**Classification:** \<Internal / Confidential / Public>  

---

## Executive Summary

> Provide a concise, high-level summary of the investigation.  
> Focus on **key findings, impact, and relevance**.

- \<Key finding #1>
- \<Key finding #2>
- \<Key risk/impact>
- \<Primary conclusion>

---

## Scope & Objectives

**Scope:**
- Target(s): \<Domain, Individual, Organization, Infrastructure, Group>
- Timeframe: \<Start Date – End Date>
- Data Types: \<Social media, DNS, metadata, etc.>

**Objectives:**
- \<Objective 1>
- \<Objective 2>
- \<Objective 3>

---

## Methodology

**Approach:**
- Passive OSINT (no interaction)
- Active OSINT (if applicable)
- Automated collection vs manual analysis

**Tools Used:**
- \<Tool Name> – Purpose
- \<Tool Name> – Purpose
- \<Custom Scripts / Pipelines>

**Techniques:**
- Search operators (Google dorks, etc.)
- Metadata analysis
- Network enumeration
- Behavioral correlation

---

## Findings

> Document **facts only** — no interpretation here.

### Finding 1 – \<Title>

- **Description:**  
  \<What was discovered>

- **Source(s):**  
  - \<URL>
  - \<Archived link (Wayback, etc.)>

- **Evidence:**
  - Screenshot: \![[path/to/image.png]]
  - Raw Data:
```
<Logs / JSON / Extract>
```

- **Timestamp:** \<ISO 8601 format>

---

### Finding 2 – \<Title>

- **Description:**  
  \<Details>
- **Source(s):**  
  - \<URL>
- **Evidence:**
  - Screenshot: \![[path/to/image.png]]
- **Timestamp:** <ISO 8601>

---

## Analysis

> Investigative analysis

**Key Insights:**
- \<Insight 1>
- \<Insight 2>

**Correlations:**
- \<Finding A ↔ Finding B>
- \<Behavioral / temporal patterns>

**Attribution Indicators:**
- \<Weak / Moderate / Strong signals>
- \<Why they matter>

**Confidence Level:**
- High / Medium / Low  
- Justification: \<Reasoning>

---

## Conclusion

> Summarize the case in terms of **impact and clarity**.

- \<Primary takeaway>
- \<Secondary takeaway>
- \<Third takeaway>
- \<Verified Correlations noted>
- \<Unverifiable Correlations noted>
- \<Recommended next steps (if applicable)>
- \<General conclusive finding with traceable evidence acquisition paths>  
---

## Appendix

### A. Raw Data

```
<Logs, JSON, extracted metadata>
```

---

### B. Timeline

| Timestamp | Event | Source |
|----------|------|--------|
| \<time> | \<event> | \<link> |

---

### C. Additional Screenshots

\![[path/to/image1.png]]  
\![[path/to/image2.png]]

---

### D. Notes

- \<Loose observations>
- \<Unverified leads>
- \<Future investigation paths>

### E. Chain-of-Custody Tracking


- **Evidence Hash (SHA256):** <hash>
- **Collected By:** <name>
- **Collection Method:** <tool/process>
- **Date/Time**: MM/DD/YY:2400

---
