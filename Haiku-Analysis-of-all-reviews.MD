# Claude Haiku Latest
*2026-11-20T12:53:19.369Z*

# Consolidated Review: USU–AGI SLA Draft 2.0

**Sources:** Four review files: ChatGPT (24 recommendations), Claude (18 suggestions), Perplexity (28 findings), and Copilot (10 recommendations). I did not have the SLA itself, so page references are as the reviewers reported them.

**Overall:** The four reviews agree that the governance design is sound but the agreement is not yet operational. They differ on how serious the gaps are. Perplexity's review is the most thorough and cites the most pages. Copilot's is the least specific.

---

## 1. Strong Agreement (3–4 reviews, same direction)

| Theme | ChatGPT | Claude | Copilot | Perplexity | Shared position |
|---|---|---|---|---|---|
| **Numeric targets missing** | R03 (Critical) | S06 (High) | #2 (High) | F-02 (Critical), F-09 | Define targets, owners, and measurement before signing |
| **Undefined key terms** ("material," "prompt," "timely") | R04 | S09 | #1, #3 | F-03 (Critical), F-12 | Central definitions with numeric or objective thresholds |
| **Escalation and incident clocks** | R04 (Critical) | S08 (High) | #7 (Medium) | F-12, F-20 | Severity levels with fixed notification windows |
| **Systems inventory / "CNS" undefined** | R15 (High) | S11 (Medium) | #9 (Low) | F-07 (High), F-28 | Controlled system appendix; resolve CNS before execution |
| **Data return, exit, and transition** | R05, R07 (High) | S10 (High) | #4 (High) | F-14 (High) | Export formats, timelines, and a tested exit plan |
| **Decision rights / reserved authority** | R01 (Critical) | S01 (High) | #1 (High) | F-06, F-17 (High) | Operational decision-rights schedule and precedence rule |
| **Schedules must be complete before execution** | R02 (Critical) | S17 (Medium) | — | F-02, F-04 (Critical) | Pre-execution gate with named owners and dates |

**Interpretation:** These items are the core of the review. Reviewers rank them differently, but none disputes that they are needed.

---

## 2. Medium Agreement (2–3 reviews, or same concern with different remedies)

- **Employer of record and HR approvals:** ChatGPT R13 (High), Copilot #6 (Medium), Perplexity F-04 (Critical) and F-17 (High). Priority ranges from Medium to Critical.
- **Legal and commercial terms** (term, termination, liability, governing law): ChatGPT R07 and R19, Claude S03, Perplexity F-01 (Critical). Copilot does not address them.
- **Vendor and subcontractor oversight:** ChatGPT R16, Copilot #5, Perplexity F-15 and F-22.
- **Shared-cost allocation:** ChatGPT R06 and Perplexity F-11. Both flag it as the classic parent-subsidiary risk.
- **Regulatory and Title IV controls:** ChatGPT R11 and R12, Perplexity F-16 and F-18, Claude S13.
- **Named owner roster:** ChatGPT R09, Claude S14, Perplexity F-10.
- **Biannual review cadence and rating definitions:** Claude S04 and S07, Perplexity F-08 and F-09, ChatGPT R08.
- **Approval record and Board sign-off:** ChatGPT R23, Claude S17, Perplexity F-05 and F-19.
- **Change control:** ChatGPT R18, Claude S15, Copilot #3, Perplexity F-21.
- **Org chart reporting lines:** Claude S05 and S14, Perplexity F-06. Both flag that the chart appears to place USU roles under the AGI CEO.
- **AI and algorithmic tools:** ChatGPT R24 and Claude S12 are the only detailed treatments. Copilot and Perplexity do not address AI, even though the CEO letter describes a CRM recommendation algorithm.

---

## 3. Direct Disagreement

1. **Overall severity.** Copilot states that the design is "fundamentally well designed" and that most risks concern "operational precision rather than structural deficiencies." Perplexity calls the missing term and exit provisions "the single largest structural omission," and ChatGPT says the draft "needs additional operational and contractual machinery to function reliably." **The Board should treat the missing term, exit, and legal provisions as structural.**

2. **Where legal terms belong.** ChatGPT (R19) suggests cross-referencing an existing master or intercompany agreement. Claude (S03) accepts either an SLA section or a companion MSA. Perplexity (F-01) requires a Term section inside this document. **Resolve this by first checking what the 2017 acquisition and intercompany agreements already cover.**

3. **Timing of the execution gate.** ChatGPT (R02) makes completed schedules a condition precedent to *effectiveness*, which allows signing with time-limited interim arrangements. Perplexity (F-02) says *no signature* until the metrics exhibit is approved. These are materially different sequencing rules.

4. **Priority of the systems inventory and accreditation clauses.** Copilot rates the systems inventory and the accreditation-protection clause as Low. ChatGPT and Perplexity rate them High or Critical. The inventory supports incident response, access control, and exit planning, so the higher rating is more defensible.

5. **Escalation windows.** Copilot offers specific deadlines (security 24 hours, accreditation 48 hours, service failure 5 business days). Perplexity proposes 24 hours for initial notice and 72 hours for a written report. ChatGPT leaves the clocks for the parties to define, and Claude leaves them for USU to set. **Copilot's figures are the only concrete proposals for accreditation and compliance events, so they are a useful starting point.**

6. **Confidence in external requirements.** ChatGPT explicitly declines to verify WSCUC requirements or legal obligations. Perplexity states external expectations as fact (e.g., "WSCUC reviewers also expect a documented exit plan," the 30% CDR threshold, and specifics about the 2017 agreements) without flagging them for verification. Claude repeatedly defers to counsel. **Do not adopt external-compliance claims from any review without verification.**

7. **Board role in approval.** Perplexity asks for a Board Chair signature. ChatGPT asks the Board to confirm whether it approves the SLA or delegates execution. These are compatible, but the Board should decide which it wants.

---

## 4. Single-Reviewer Issues Worth Considering

- **Conflict-of-interest and recusal rules** for trustees or officers with AGI roles (Claude S05 only). This is important because AGI owns USU.
- **Promotional claims** in the CEO and President letters, such as the federal aid statement and the "approximately 45 states" figure (Claude S16 only).
- **Privilege, independent counsel, and whistleblower routing** (Perplexity F-13 only).
- **Marketing data-use limits** and approved lead vendors (Perplexity F-15 only).
- **Insurance minimums** (Perplexity F-25 only).
- **Recovery time and recovery point objectives** (ChatGPT R21, with Perplexity F-21 covering availability targets).

---

## 5. Recommended Next Steps

1. **Adopt a shared pre-execution gate list:** metrics exhibit, employer register, systems inventory, delegation schedule, and term and exit provisions.
2. **Settle the location of legal terms** by reviewing the existing 2017 agreements.
3. **Have the Board set the definition of "material"** and approve the escalation clocks.
4. **Verify all external-regulatory assertions** with counsel and compliance before the draft is adopted.
5. **Add AI-tool governance and conflict-of-interest rules,** which only one or two reviews addressed but which bear directly on the risks described.