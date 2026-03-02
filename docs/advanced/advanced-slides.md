---
marp: true
theme: default
paginate: true
size: 16:9
footer: 'Real Minds AI  |  wisdom, amplified'
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Epilogue:wght@400;500;600;700&display=swap');

:root {
  --rmai-purple: #A77ACD;
  --rmai-purple-dark: #6B4D8A;
  --rmai-orange: #F26541;
  --rmai-orange-dark: #C04E2D;
  --rmai-black: #1A1B25;
  --rmai-slate: #373841;
  --rmai-offwhite: #FAF9F7;
  --rmai-oat: #F1E8D7;
  --rmai-blue: #5791C7;
  --rmai-blue-dark: #2D6A9F;
  --rmai-green: #349990;
  --rmai-green-dark: #1E6B64;
  --rmai-border: #E7E7EA;
  --rmai-red: #C62828;
}

section {
  background-color: var(--rmai-offwhite);
  color: var(--rmai-black);
  font-family: 'Epilogue', 'Inter', 'SF Pro', 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  font-weight: 400;
  font-size: 22px;
  line-height: 1.5;
  padding: 50px 60px;
  border-top: 6px solid var(--rmai-purple);
}

h1, h2, h3 { font-weight: 700; margin: 0; padding: 0; }
h1 { font-size: 48px; color: var(--rmai-purple-dark); line-height: 1.2; }
h2 { font-size: 36px; color: var(--rmai-purple-dark); margin-bottom: 24px; border-bottom: 3px solid var(--rmai-purple); padding-bottom: 12px; }
h3 { font-size: 26px; color: var(--rmai-slate); font-weight: 600; margin-top: 16px; }

ul, ol { padding-left: 28px; }
li { margin-bottom: 8px; }
strong { color: var(--rmai-purple-dark); font-weight: 700; }
em { color: var(--rmai-slate); }

table { border-collapse: collapse; width: 100%; font-size: 18px; margin: 12px 0; }
th { background-color: var(--rmai-purple-dark); color: white; font-weight: 600; padding: 10px 12px; text-align: left; }
td { border: 1px solid var(--rmai-border); padding: 8px 12px; }
tr:nth-child(even) { background-color: white; }

code { background: var(--rmai-oat); color: var(--rmai-slate); padding: 2px 6px; border-radius: 3px; font-size: 0.9em; }
footer { font-size: 14px; color: var(--rmai-slate); opacity: 0.7; }

blockquote { border-left: 4px solid var(--rmai-purple); background: var(--rmai-oat); padding: 12px 20px; margin: 16px 0; border-radius: 0 8px 8px 0; font-style: italic; }

/* Lead slides — purple gradient: all text white */
section.lead {
  background: linear-gradient(135deg, #A77ACD 0%, #7B5BA0 60%, #5D3F7E 100%);
  color: white; border-top: none;
  display: flex; flex-direction: column; justify-content: center; text-align: center;
}
section.lead h1 { color: white; font-size: 52px; }
section.lead h2 { color: rgba(255,255,255,0.9); border-bottom: 3px solid rgba(255,255,255,0.4); }
section.lead h3 { color: rgba(255,255,255,0.85); }
section.lead p { color: rgba(255,255,255,0.9); font-size: 24px; }
section.lead strong { color: white; }
section.lead em { color: rgba(255,255,255,0.85); }
section.lead li { color: rgba(255,255,255,0.95); }
section.lead blockquote { background: rgba(255,255,255,0.12); border-left-color: rgba(255,255,255,0.4); color: rgba(255,255,255,0.9); }
section.lead footer { color: rgba(255,255,255,0.5); }

/* Theory slides — oat bg: orange accent */
section.theory {
  background: var(--rmai-oat);
  border-top: 6px solid var(--rmai-orange);
}
section.theory h2 { color: var(--rmai-orange-dark); border-bottom-color: var(--rmai-orange); }
section.theory strong { color: var(--rmai-orange-dark); }
section.theory blockquote { background: rgba(255,255,255,0.5); }

/* Exercise slides — white bg: blue accent */
section.exercise {
  background: white;
  border-top: 6px solid var(--rmai-blue);
}
section.exercise h2 { color: var(--rmai-blue-dark); border-bottom-color: var(--rmai-blue); }
section.exercise strong { color: var(--rmai-blue-dark); }

/* Debrief slides — light purple bg: green accent */
section.debrief {
  background: linear-gradient(180deg, var(--rmai-offwhite) 0%, #EDE4F3 100%);
  border-top: 6px solid var(--rmai-green);
}
section.debrief h2 { color: var(--rmai-green-dark); border-bottom-color: var(--rmai-green); }
section.debrief strong { color: var(--rmai-green-dark); }

/* Warning slides — light orange bg: red accent */
section.warning {
  background: #FFF3E0;
  border-top: 6px solid var(--rmai-red);
}
section.warning h2 { color: var(--rmai-red); border-bottom-color: var(--rmai-red); }
section.warning strong { color: var(--rmai-red); }

/* Break slides — oat gradient */
section.break-slide {
  background: linear-gradient(135deg, var(--rmai-oat) 0%, #E8D5C4 100%);
  border-top: none;
  display: flex; flex-direction: column; justify-content: center; text-align: center;
}
section.break-slide h1 { color: var(--rmai-slate); font-size: 56px; }
</style>

<!-- _class: lead -->
<!-- _paginate: false -->

# Advanced AI Skills
## Verification, Governance and the Real World

Real Minds AI
Tracy Anthony and Dr Dennis Wollersheim

---

## Why "Advanced"?

### The morning exercises used clean data. Real life is messy.

In the real world, the data you feed AI is:
- **Incomplete** — fields missing, logs partial, records half-finished
- **Contradictory** — two people remember the same event differently
- **Ambiguous** — "soon", "when convenient", "where appropriate"
- **Risky** — one wrong word in an email can breach privacy or over-promise

### This session teaches you to use AI safely when the inputs are imperfect

> The question is not "can AI write this?" but "should I send what AI wrote?"

---

<!-- _class: theory -->

## The AI Sandwich

### The workflow that keeps you safe

**Step 1: System A outputs** (raw notes, exports, logs, emails)
These are messy, partial, sometimes contradictory

**Step 2: AI transforms** (triage, structure, draft comms)
AI imposes structure and generates drafts — fast but unchecked

**Step 3: Human verifies** (facts, privacy, policy, approvals)
You check every claim, every name, every commitment

**Step 4: System B inputs** (incident record, complaint register, final comms)
Clean, verified, auditable output goes into your systems

> AI sits in the middle. **You are the bread.** Nothing gets through without your verification.

---

## Advanced Exercise Overview

| # | Exercise | What you will do | Key skill |
|---|----------|-----------------|-----------|
| A1 | **Incident Pack Assembly** | Reconcile 2 conflicting accounts into one record | Verification |
| A2 | **Fix the Problematic Email** | Rewrite a privacy-breaching draft | Governance |
| A3 | **Attendance Triage Under Uncertainty** | Build contact plan from messy data | Uncertainty |
| A4 | **Policy Alignment Change Log** | Compare old procedure to new requirements | Compliance |
| A5 | **Messy Minutes to Action Register** | Extract clean actions from vague notes | Structure |

### Your data pack

The **Messy Mini-Pack** is intentionally broken: duplicate rows, conflicting times, missing fields, privacy traps, and unclear ownership. This is realistic.

---

<!-- _class: lead -->

# Exercise A1

Incident Pack Assembly

---

<!-- _class: theory -->

## Verification and Cross-Checking

### The theory: when sources disagree

- In any incident, different people observe different things at different times
- Two staff accounts of the same event **will** contain discrepancies (times, sequence, severity)
- Your job is not to pick one account — it is to **reconcile** them into a single factual record

### The Known / Unconfirmed / Unknown framework

| Category | Definition | Example |
|----------|-----------|---------|
| **Known** | Confirmed by 2+ sources or physical evidence | "S1188 had a graze — confirmed by first aid log" |
| **Unconfirmed** | Mentioned by one source, not contradicted | "Bystander called out a name — one account only" |
| **Unknown** | Key fact that no source provides | "Exact start time of the altercation" |

> AI can build this framework from messy inputs. **You** decide what moves from "Unconfirmed" to "Known".

---

<!-- _class: exercise -->

## Exercise A1: Incident Pack Assembly

### Instructions (20 minutes)

You have **5 documents** about the same incident. Open from your Messy Mini-Pack:
- Artifact 02: Yard duty staff account
- Artifact 03: Student services intake note
- Artifact 04: First aid log
- Artifact 05: Parent contact log
- Artifact 06: CCTV maintenance ticket

Paste your context card, then **all five documents**, then add:

> *Using these five documents about the same incident, please:*
> *1. Create a Known / Unconfirmed / Unknown fact list (bullet points)*
> *2. Produce a SafeTrack incident entry in structured fields: Date, TimeRange, Location, Category, PeopleInvolved (StudentIDs only), ImmediateActions, Injuries, ParentContactAttempts, Evidence, FollowUpOwner, ReviewDate*
> *3. List exactly what must be verified by a human before finalising*
>
> *Constraints: do not invent facts. Clearly mark all conflicts between sources.*

### What to look for

- Does the AI catch the **time discrepancy** between the two accounts?
- Does it correctly flag the CCTV "no signal" gap?
- Does it mark the "punch" claim as unconfirmed?

---

<!-- _class: debrief -->

## Exercise A1: What You Learned

### Key contradictions in the data

- **Time:** Yard duty says "approx 13:05" arrival, Student Services says students arrived "approx 13:12" — times are estimates
- **Physical contact:** Yard duty is uncertain about a punch; both students told Student Services there was no punching
- **First aid log:** Two entries for S1188 at different times (13:16 and 13:18) — possible duplicate or two visits
- **CCTV:** Dashboard showed "NO SIGNAL" during the exact window (13:10-13:25) — footage may not exist
- **Parent contact:** S1048 contact logged at 13:25 (attempt) and 13:32 (success) — Student Services notes "13:25" but may be the attempt time

### The principle

> AI organises conflicting information. **You** verify which facts are confirmed. Never let AI resolve contradictions — that is a human judgment call.

---

<!-- _class: lead -->

# Exercise A2

Fix the Problematic Email

---

<!-- _class: warning -->

## Spot the Problems

### This draft email contains at least 6 governance failures

Read the **Problematic Draft Email** (Artifact 07 in your Messy Mini-Pack):

| Problem | Why it matters |
|---------|---------------|
| Mentions "the other student" and implies identity | **Privacy breach** — must not disclose info about other students |
| Says student "has a history of behaviour issues" | **Privacy breach** — disclosing another student's record |
| Claims "we will be suspending them for 5 days" | **Over-promise** — outcome not yet decided or approved |
| Claims "CCTV clearly shows this" | **False claim** — CCTV had "no signal" during the incident |
| Promises "this will never happen again" | **Over-promise** — cannot guarantee future behaviour |
| Asks parent for "screenshots of the group chat" | **Evidence handling risk** — may breach other students' privacy |

> Every one of these could lead to a formal complaint, a privacy investigation, or a legal problem.

---

<!-- _class: exercise -->

## Exercise A2: Fix the Problematic Email

### Instructions (15 minutes)

Paste your context card, then the **Problematic Draft Email** (Artifact 07), then add:

> *This draft email is problematic and must not be sent as-is. Rewrite it so that it:*
> *- does not mention or identify any other student*
> *- does not promise specific outcomes (no "never again", no suspension details)*
> *- does not claim evidence that has not been verified*
> *- includes clear next steps with a timeframe and a named contact point*
> *- maintains a calm, empathetic, factual tone*
>
> *Provide three versions:*
> *A. A phone call script (dot points for the call)*
> *B. A follow-up email (under 200 words)*
> *C. An SMS (under 160 characters)*

### What to check

- Has the AI removed **all** references to other students?
- Are there any promises of specific outcomes?
- Is the tone empathetic without being defensive?

---

<!-- _class: debrief -->

## Exercise A2: What You Learned

### The comms safety checklist

Before sending any incident-related communication, check:

- **No other students identified** (directly or by implication)
- **No outcomes promised** until decisions are formally made
- **No evidence claimed** unless verified and available
- **No blame assigned** in either direction
- **Next steps are specific** (who to contact, by when, what happens next)
- **Tone is calm and factual** (not defensive, not dismissive)

### The principle

> AI drafts fast. Fast drafts are dangerous. The **human review step** is not optional — it is where governance happens.

### Try this at work

- Run every sensitive email through AI with the instruction "check this for privacy breaches, over-promises, and unverified claims"
- AI is excellent at **catching your blind spots** in comms you have already drafted

---

<!-- _class: lead -->

# Exercise A3

Attendance Triage Under Uncertainty

---

<!-- _class: theory -->

## Working with Imperfect Data

### The theory: real exports are never clean

The attendance CSV in the Messy Mini-Pack has deliberate problems:
- **Duplicate rows** — S1188 appears twice for the same date
- **Inconsistent codes** — "Unexplained", "LATE", "X" instead of standard U, L codes
- **Missing fields** — blank YearLevel, blank AttendanceCode, blank Prior20Days count
- **Impossible values** — MinutesLate of -3 (negative time)
- **Typos** — "S12O2" instead of "S1202" (letter O instead of zero)
- **Date format inconsistency** — one row uses DD/MM/YYYY instead of YYYY-MM-DD
- **Non-standard homeroom** — "8Z" does not exist in the school

### What this exercise demonstrates

- AI can **identify data quality issues** before you start analysis
- Cleaning data is a necessary step before making decisions
- AI handles the tedious work of spotting inconsistencies — you make the calls

---

<!-- _class: exercise -->

## Exercise A3: Attendance Triage

### Instructions (20 minutes)

Paste the **Messy Attendance CSV** (Artifact 01 from Messy Mini-Pack), then add:

> *This attendance export has data quality issues. Please:*
> *1. List every data quality problem you find (duplicates, inconsistent codes, missing fields, impossible values, typos, format issues)*
> *2. For each problem, suggest how to fix it or what to verify*
> *3. After noting the issues, produce a triage list: students who need parent contact this week, ranked by urgency (highest absence/late pattern first)*
> *4. For each student on the triage list, draft a one-sentence contact note appropriate to their situation*
>
> *Where data is uncertain, note what you are assuming and what needs to be verified in the source system.*

### What to look for

- Does AI catch the **S12O2 typo** (letter O instead of zero)?
- Does it flag the **negative minutes late** value?
- Does it identify the **duplicate S1188 row**?
- Does it handle the **non-standard attendance codes** (Unexplained, LATE, X)?

---

<!-- _class: debrief -->

## Exercise A3: What You Learned

### Data quality issues in the messy export

| Issue | Row | Detail |
|-------|-----|--------|
| Duplicate | S1188, 2026-03-04 | Exact duplicate row |
| Code inconsistency | S1019, 2026-03-04 | "Unexplained" instead of "U" |
| Code inconsistency | S1007, 2026-03-04 | "LATE" instead of "L" |
| Unknown code | S1089, 2026-03-05 | "X" is not a valid attendance code |
| Impossible value | S1102, 2026-03-04 | MinutesLate = -3 |
| Missing field | S1095, 2026-03-04 | YearLevel is blank |
| Typo (StudentID) | 2026-03-05 | "S12O2" should be "S1202" |
| Date format | S1048, 2026-03-05 | "05/03/2026" instead of YYYY-MM-DD |
| Invalid homeroom | S1048, 2026-03-06 | "8Z" does not exist |
| Missing code | S1121, 2026-03-05 | AttendanceCode is blank |

### The principle

> Clean data before you analyse. AI finds the mess. **You** decide the fixes.

---

<!-- _class: lead -->

# Exercise A4

Policy Alignment Change Log

---

<!-- _class: theory -->

## AI as Compliance Translator

### The theory: old policy vs new requirements

- Schools receive new regulatory bulletins regularly
- Comparing a 3-page local procedure against a 2-page authority bulletin **by hand** takes hours
- AI can do a structured comparison in seconds — flagging gaps, risks, and required updates

### The "change log" pattern

Ask AI to produce a table with:

| Column | Purpose |
|--------|---------|
| **Requirement** | What the new bulletin requires |
| **Current procedure** | What your local document says |
| **Gap or risk** | Where they do not align |
| **Required update** | What needs to change |
| **Owner** | Who should make the change |
| **Evidence** | How you prove compliance |

This pattern works for **any** regulatory comparison — not just incident recording.

---

<!-- _class: exercise -->

## Exercise A4: Policy Alignment

### Instructions (15 minutes)

Paste the **Old Local Procedure** (Artifact 09) AND the **Authority Bulletin** (Artifact 10), then add:

> *Compare the school's local procedure with the authority bulletin.*
> *Output a change log table with columns: Requirement, CurrentProcedure, Gap or Risk, RequiredUpdate, OwnerRole, Evidence.*
> *Then draft a revised 10-14 step procedure that meets the new minimum expectations. Include owners and timeframes for each step.*

### Key gaps to expect

- **Recording timeframe:** Local says "within a few days" vs authority says "within 24 hours"
- **Complaints acknowledgement:** Local says "5 business days" vs good practice is 2
- **Unconfirmed marking:** Authority requires "UNCONFIRMED" labels; local procedure has no such requirement
- **Privacy guidance:** Local says "provide enough detail"; authority says "do not disclose other students"

### What to check

- Has AI identified all the major gaps?
- Is the revised procedure realistic for your school to implement?

---

<!-- _class: debrief -->

## Exercise A4: What You Learned

### Key takeaways

- AI performs **structured document comparison** faster and more thoroughly than manual review
- The change log format makes gaps visible and actionable — not buried in paragraph text
- AI can draft a revised procedure, but the **owner assignments and timeframes** need human input

### The principle

> AI translates between "what the authority requires" and "what your school currently does" — the gap analysis is instant, the implementation is human

### Try this at work

- Every time a new circular, bulletin, or regulatory update arrives, paste it alongside your current procedure
- Ask for a change log table — this becomes your compliance evidence
- Assign owners in a staff meeting, not in the AI output

---

<!-- _class: lead -->

# Exercise A5

Messy Minutes to Action Register

---

<!-- _class: theory -->

## Imposing Structure on Chaos

### The theory: meeting notes are always messy

The messy exec meeting notes (Artifact 11) have deliberate problems:
- **Unclear ownership** — "send list to coordinators" (who sends? which coordinators?)
- **Vague dates** — "maybe Wed?", "due Tue (or Wed?)", "start soon"
- **Missing decisions** — "decision-ish" (was it actually decided?)
- **Ambiguous actions** — "need a plan" (what plan? who writes it?)

### What this exercise demonstrates

- AI can extract action items even from terrible notes
- AI **flags ambiguity** rather than silently resolving it
- The output is a clean action register that you can paste into your task system
- The human step is confirming owners, dates, and whether "decision-ish" items were actually decided

---

<!-- _class: exercise -->

## Exercise A5: Messy Minutes

### Instructions (15 minutes)

Paste the **Messy Exec Meeting Notes** (Artifact 11), then add:

> *These meeting notes are messy and incomplete. Please:*
> *1. Format as professional meeting minutes with clear headings*
> *2. Extract all action items into a table: Action, Owner, DueDate, Status*
> *3. Where the owner is unclear, write "OWNER TBC" and suggest who it might be*
> *4. Where the date is vague, write "DATE TBC" and suggest a reasonable deadline*
> *5. List any items that sound like decisions but are not clearly confirmed — mark these as "DECISION TBC"*
> *6. Draft a 5-sentence email summary to send to attendees, asking them to confirm their action items*

### What to look for

- Does AI flag "maybe Wed?" as uncertain?
- Does it handle "decision-ish" appropriately?
- Does the email ask attendees to **confirm**, not just inform?

---

<!-- _class: debrief -->

## Exercise A5: What You Learned

### Key ambiguities in the messy notes

| Item | Problem | Resolution needed |
|------|---------|-------------------|
| "Send list to coordinators" | Who sends? Which coordinators? | Owner and recipient TBC |
| "Due Tue (or Wed?)" | Conflicting dates | Confirm with Wellbeing Leader |
| "Decision-ish: increase supervision" | Was this formally decided? | Confirm with Principal |
| "Trial weekly digest — start soon" | No start date, no owner | Assign owner and date |
| "10-slide deck outline — who drafts?" | No owner assigned | Assign at next meeting |

### The principle

> AI imposes **structure** on messy inputs. You impose **accountability** — confirming owners, dates, and decisions. Neither step works without the other.

---

## The Advanced Toolkit

### Five patterns for messy data

| Pattern | When to use | Key output |
|---------|-------------|------------|
| **Known / Unconfirmed / Unknown** | Conflicting sources | Fact classification list |
| **Comms Safety Check** | Any sensitive draft | Privacy and promise audit |
| **Data Quality Audit** | Messy exports / CSVs | Issue list with fix suggestions |
| **Change Log Comparison** | Old vs new requirements | Gap table with owners |
| **Ambiguity Flagging** | Vague meeting notes | Action register with TBCs |

### The golden rule for all advanced exercises

> AI is fast. Fast is dangerous when the data is messy. **The human verification step is where safety happens.**

---

## Bringing It Together

### The AI Sandwich in practice

Every task you do at work follows this pattern:

**Raw input** (messy email, partial export, scribbled notes)
   ↓
**AI transforms** (structures, drafts, flags issues)
   ↓
**You verify** (check facts, check privacy, check promises)
   ↓
**Clean output** (system entry, sent email, filed record)

### Your verification checklist

- Are **facts** confirmed by 2+ sources?
- Are **people** identified only by role or ID (not by name in general text)?
- Are **promises** limited to what has been decided?
- Are **evidence** claims backed by actual records?
- Are **owners and dates** specific (not "someone" or "soon")?

---

<!-- _class: lead -->
<!-- _paginate: false -->

# Thank You

**Tracy Anthony** and **Dr Dennis Wollersheim**
Real Minds AI

hello@realmindsai.com.au | realmindsai.com.au

*wisdom, amplified*
