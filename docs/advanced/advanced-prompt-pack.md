# Advanced Prompt Pack — AI Skills for Busy School Admin Teams

**Workshop:** 5 March 2026 | **Real Minds AI**

These prompts work with the **Messy Mini-Pack** — intentionally broken data containing duplicates, contradictions, missing fields, and privacy traps. Start every session by pasting your **Context Card** first.

---

## Your Context Card

Paste this at the start of every AI conversation:

```
[YOUR CONTEXT CARD GOES HERE — you built this in Exercise 1]
```

---

## Exercise A1: Incident Pack Assembly

Paste your context card, then **all five of these documents** from your Messy Mini-Pack:
- Artifact 02: Yard Duty Staff Account
- Artifact 03: Student Services Intake Note
- Artifact 04: First Aid Log Excerpt
- Artifact 05: Parent Contact Log
- Artifact 06: CCTV Maintenance Ticket

Then add this prompt:

```
Using these five documents about the same incident, please:

1. Create a Known / Unconfirmed / Unknown fact list (bullet points).
   - "Known" = confirmed by 2+ sources or physical evidence
   - "Unconfirmed" = mentioned by one source, not contradicted
   - "Unknown" = key fact that no source provides

2. Produce a SafeTrack incident entry in structured fields:
   Date, TimeRange, Location, Category, PeopleInvolved (StudentIDs only),
   ImmediateActions, Injuries, ParentContactAttempts, Evidence,
   FollowUpOwner, ReviewDate

3. List exactly what must be verified by a human before finalising.

Constraints: do not invent facts. Clearly mark all conflicts between
sources. Where two sources disagree, show both versions.
```

**Bonus prompt (cross-reference):**
```
Now compare this incident record against the requirements in the
Authority Bulletin (below). Flag any missing fields or areas where
the record does not meet the minimum expectations.

[Paste Artifact 10 — Authority Bulletin here]
```

---

## Exercise A2: Fix the Problematic Email

Paste your context card, then the **Problematic Draft Email** (Artifact 07), then add:

```
This draft email is problematic and must not be sent as-is.
Rewrite it so that it:
- does not mention or identify any other student
- does not promise specific outcomes (no "never again", no suspension
  details)
- does not claim evidence that has not been verified
- includes clear next steps with a timeframe and a named contact point
- maintains a calm, empathetic, factual tone

Provide three versions:
A. A phone call script (dot points for the call)
B. A follow-up email (under 200 words)
C. An SMS (under 160 characters)
```

**Bonus prompt (reverse audit):**
```
Now list every problem in the original draft email. For each problem,
state:
- what the text says
- why it is a governance failure
- the potential consequence if sent
- what the corrected version should say instead

Present this as a table.
```

---

## Exercise A3: Attendance Triage Under Uncertainty

Paste the **Messy Attendance CSV** (Artifact 01 from Messy Mini-Pack), then add:

```
This attendance export has data quality issues. Please:

1. List every data quality problem you find (duplicates, inconsistent
   codes, missing fields, impossible values, typos, format issues).
2. For each problem, suggest how to fix it or what to verify.
3. After noting the issues, produce a triage list: students who need
   parent contact this week, ranked by urgency (highest
   absence/late pattern first).
4. For each student on the triage list, draft a one-sentence contact
   note appropriate to their situation.

Where data is uncertain, note what you are assuming and what needs to
be verified in the source system.
```

**Bonus prompt (comparison):**
```
Now compare this messy export against the clean attendance data from
the main Data Pack (below). Flag any discrepancies between the two
data sets for the same students and dates.

[Paste Artifact 01 from the main Data Pack here]
```

---

## Exercise A4: Policy Alignment Change Log

Paste the **Old Local Procedure** (Artifact 09) AND the **Authority Bulletin** (Artifact 10), then add:

```
Compare the school's local procedure with the authority bulletin.

Output a change log table with columns:
- Requirement (what the bulletin requires)
- CurrentProcedure (what the school currently says)
- Gap or Risk (where they don't align)
- RequiredUpdate (what needs to change)
- OwnerRole (who should make the change)
- Evidence (how you prove compliance)

Then draft a revised 10-14 step procedure that meets the new minimum
expectations. Include owners and timeframes for each step.
```

**Bonus prompt (implementation plan):**
```
Based on the gap analysis, create a 4-week implementation plan.
For each week, list:
- what changes need to be made
- who is responsible
- what evidence of completion looks like
- what the risk is if this step is delayed

Format as a table with columns: Week, Action, Owner, Evidence, Risk.
```

---

## Exercise A5: Messy Minutes to Action Register

Paste the **Messy Exec Meeting Notes** (Artifact 11), then add:

```
These meeting notes are messy and incomplete. Please:

1. Format as professional meeting minutes with clear headings
2. Extract all action items into a table: Action, Owner, DueDate, Status
3. Where the owner is unclear, write "OWNER TBC" and suggest who it
   might be
4. Where the date is vague, write "DATE TBC" and suggest a reasonable
   deadline
5. List any items that sound like decisions but are not clearly
   confirmed — mark these as "DECISION TBC"
6. Draft a 5-sentence email summary to send to attendees, asking them
   to confirm their action items
```

**Bonus prompt (complaints template):**
```
The meeting notes mention needing a complaints acknowledgement template.
Using the school's Complaints Handling Policy (below) as a guide,
draft an acknowledgement email template with placeholders like
[Parent Name], [Date Received], [Issue Summary], [Contact Person],
[Next Step Date].

The template should be under 150 words, empathetic, and professional.

[Paste Artifact 09 — Old Local Procedure here]
```

---

## Verification Prompts (Use with Any Exercise)

### Privacy check
```
Review the text below for any potential privacy breaches. Flag
anywhere that:
- another student is identified (directly or by implication)
- personal information could be inferred
- health or behavioural details are disclosed
List each issue with a suggested fix.
```

### Over-promise check
```
Review the text below and flag any promises, commitments, or
guarantees that:
- have not been formally decided
- the school cannot reasonably guarantee
- imply specific outcomes for other students
For each, suggest alternative wording that is factual without
over-committing.
```

### Compliance check
```
Compare the text below against these requirements:
[Paste Artifact 10 — Authority Bulletin]
Flag any areas where the text does not meet the minimum expectations.
For each gap, suggest specific wording that would bring it into
compliance.
```

---

## Quick Reference: Advanced Prompt Patterns

| Pattern | When to use | Example starter |
|---------|-------------|-----------------|
| **Reconcile** | Multiple sources conflict | "Using these documents about the same event..." |
| **Audit** | Check for governance failures | "Review this for privacy breaches..." |
| **Clean** | Messy data needs fixing | "List every data quality problem..." |
| **Compare** | Old vs new requirements | "Compare the local procedure with..." |
| **Extract** | Structure from chaos | "Extract all action items into a table..." |
| **Verify** | Before sending anything | "Flag anything that needs human confirmation..." |

---

*Real Minds AI | wisdom, amplified | realmindsai.com.au*
