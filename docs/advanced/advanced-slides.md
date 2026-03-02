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

Open **5 documents** from your Messy Mini-Pack: Artifacts 02-06 (yard duty account, student services note, first aid log, parent contact log, CCTV ticket)

Paste your context card, then **all five documents**, then add:

> *Using these five documents about the same incident, please:*
> *1. Create a Known / Unconfirmed / Unknown fact list*
> *2. Produce a SafeTrack incident entry with structured fields (Date, TimeRange, Location, Category, PeopleInvolved, ImmediateActions, Injuries, ParentContact, Evidence, FollowUpOwner, ReviewDate)*
> *3. List what must be verified by a human before finalising*
>
> *Do not invent facts. Clearly mark all conflicts between sources.*

### What to look for

- Does the AI catch the **time discrepancy** between the two accounts?
- Does it flag the CCTV "no signal" gap and the "punch" claim?

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

| Problem | Category |
|---------|----------|
| Implies the other student's identity | **Privacy breach** |
| Says student "has a history of behaviour issues" | **Privacy breach** |
| Promises "suspending them for 5 days" | **Over-promise** (not yet decided) |
| Claims "CCTV clearly shows this" | **False claim** (CCTV had no signal) |
| Promises "this will never happen again" | **Over-promise** |
| Asks for "screenshots of the group chat" | **Evidence risk** (other students' privacy) |

> Every one of these could trigger a formal complaint or privacy investigation.

---

<!-- _class: exercise -->

## Exercise A2: Fix the Problematic Email

### Instructions (15 minutes)

Paste your context card, then **Artifact 07** (Problematic Draft Email), then add:

> *This draft email must not be sent as-is. Rewrite it so that it: does not identify any other student, does not promise specific outcomes, does not claim unverified evidence, includes next steps with a timeframe and contact point, and uses a calm, empathetic tone.*
>
> *Provide three versions: A. Phone call script (dot points), B. Follow-up email (under 200 words), C. SMS (under 160 characters)*

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
- **Duplicates** — S1188 appears twice for the same date
- **Inconsistent codes** — "Unexplained", "LATE", "X" instead of standard codes
- **Missing fields** — blank YearLevel, blank AttendanceCode
- **Impossible values** — MinutesLate of -3 (negative time)
- **Typos and format issues** — "S12O2" (letter O), DD/MM/YYYY mixed with YYYY-MM-DD, non-existent homeroom "8Z"

### What this exercise demonstrates

- AI spots data quality issues **before** you start analysis
- AI handles the tedious work of finding inconsistencies — you make the calls

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

### Data quality issues found (1 of 2)

| Issue | Detail |
|-------|--------|
| Duplicate row | S1188 appears twice on 2026-03-04 |
| Code: "Unexplained" | S1019 — should be "U" |
| Code: "LATE" | S1007 — should be "L" |
| Unknown code "X" | S1089, 2026-03-05 |
| Impossible value | S1102 — MinutesLate = -3 |

---

<!-- _class: debrief -->

## Exercise A3: What You Learned (continued)

### Data quality issues found (2 of 2)

| Issue | Detail |
|-------|--------|
| Missing YearLevel | S1095, 2026-03-04 |
| StudentID typo | "S12O2" — letter O instead of zero |
| Date format | S1048 uses DD/MM/YYYY instead of YYYY-MM-DD |
| Invalid homeroom | S1048 assigned "8Z" (does not exist) |
| Missing AttendanceCode | S1121, 2026-03-05 |

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
- Comparing a local procedure against a new bulletin **by hand** takes hours
- AI produces a structured comparison in seconds — flagging gaps and required updates

### The "change log" pattern

Ask AI to produce a table with columns:

**Requirement** → **Current procedure** → **Gap or risk** → **Required update** → **Owner** → **Evidence**

This pattern works for **any** regulatory comparison — not just incident recording.

---

<!-- _class: exercise -->

## Exercise A4: Policy Alignment

### Instructions (15 minutes)

Paste **Artifact 09** (Old Local Procedure) AND **Artifact 10** (Authority Bulletin), then add:

> *Compare the school's local procedure with the authority bulletin. Output a change log table with columns: Requirement, CurrentProcedure, Gap/Risk, RequiredUpdate, Owner, Evidence. Then draft a revised procedure that meets the new minimum expectations.*

### Key gaps to expect

- **Recording timeframe:** "within a few days" vs "within 24 hours"
- **Complaints acknowledgement:** "5 business days" vs good practice of 2
- **Unconfirmed marking:** Authority requires it; local procedure does not
- **Privacy guidance:** "provide enough detail" vs "do not disclose other students"

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
- **Unclear ownership** — "send list to coordinators" (who? which ones?)
- **Vague dates** — "maybe Wed?", "due Tue (or Wed?)", "start soon"
- **Missing decisions** — "decision-ish" (was it actually decided?)
- **Ambiguous actions** — "need a plan" (what plan? who writes it?)

### What this exercise demonstrates

- AI extracts action items even from terrible notes and **flags ambiguity**
- The output is a clean action register — you confirm owners, dates, and decisions

---

<!-- _class: exercise -->

## Exercise A5: Messy Minutes

### Instructions (15 minutes)

Paste **Artifact 11** (Messy Exec Meeting Notes), then add:

> *These meeting notes are messy and incomplete. Please:*
> *1. Format as professional minutes with clear headings*
> *2. Extract action items into a table: Action, Owner, DueDate, Status*
> *3. Where owner/date is unclear, write "TBC" and suggest a reasonable value*
> *4. List items that sound like decisions but are not confirmed — mark "DECISION TBC"*
> *5. Draft a 5-sentence email summary asking attendees to confirm their action items*

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

**Raw input** → **AI transforms** → **You verify** → **Clean output**

### Your verification checklist

Before sending any AI output, check:

- **Facts** confirmed by 2+ sources?
- **People** identified by role or ID only (no names in general text)?
- **Promises** limited to what has been formally decided?
- **Evidence** claims backed by actual records?
- **Owners and dates** specific (not "someone" or "soon")?

---

<!-- _class: lead -->
<!-- _paginate: false -->

# Thank You

**Tracy Anthony** and **Dr Dennis Wollersheim**
Real Minds AI

hello@realmindsai.com.au | realmindsai.com.au

*wisdom, amplified*
