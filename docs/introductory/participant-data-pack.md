# Participant Handout — Marraburra Secondary College Data Pack

**Workshop:** AI Skills for Busy School Admin Teams
**Date:** 5 March 2026 | **Presenters:** Tracy Anthony and Dr Dennis Wollersheim, Real Minds AI

**Important:** All data in this handout is **entirely fictional and synthetic**. Marraburra Secondary College does not exist. Student IDs (e.g., S1048) are used instead of names. This data is designed for safe AI practice.

---

## About Marraburra Secondary College (Fictional)

- **Location:** Outer Melbourne, Victoria, Australia
- **Type:** Government secondary school, Years 7-12
- **Enrolment:** Approximately 920 students
- **EAL/D students:** Approximately 18% (including Mandarin and Cantonese speakers)
- **Current priorities:** Attendance improvement (Years 7-8), incident recording consistency, Block B building works and room moves, complaints handling consistency
- **Systems:** SchoolSphere (SIS), LearnDock (LMS), SafeTrack (incidents), LedgerLite (finance), PeoplePulse (HR), Microsoft 365 (comms)

---

## Artifact 01 — Attendance Export

**Use with:** Exercise 6 (Spreadsheet Formulas), Exercise 8 (Escalation Letters)

```
Date,StudentID,YearLevel,Homeroom,AttendanceCode,MinutesLate,ExplanationText,ParentContactStatus,Prior20DaysAbsences,Prior20DaysLate,SupportPlan,EAL
2026-02-24,S1007,7,7A,L,12,Late bus connection,SMS sent,2,4,N,Y
2026-02-25,S1007,7,7A,P,0,,,2,4,N,Y
2026-02-26,S1007,7,7A,L,7,Late dropped off late,Parent portal note,2,4,N,Y
2026-02-27,S1007,7,7A,P,0,,,2,4,N,Y
2026-03-02,S1007,7,7A,P,0,,,2,4,N,Y
2026-02-24,S1019,8,8C,U,0,,Not yet,5,1,N,N
2026-02-25,S1019,8,8C,U,0,,Not yet,5,1,N,N
2026-02-26,S1019,8,8C,P,0,,,5,1,N,N
2026-02-27,S1019,8,8C,U,0,,Call attempted,5,1,N,N
2026-03-02,S1019,8,8C,P,0,,,5,1,N,N
2026-02-24,S1048,8,8A,E,0,Medical appointment AM,Parent portal note,6,2,Y,N
2026-02-25,S1048,8,8A,U,0,,Not yet,6,2,Y,N
2026-02-26,S1048,8,8A,U,0,,Call made,6,2,Y,N
2026-02-27,S1048,8,8A,P,0,,,6,2,Y,N
2026-03-02,S1048,8,8A,P,0,,,6,2,Y,N
2026-02-24,S1089,9,9D,L,18,Late conflict at home reported,Wellbeing notified,3,5,N,N
2026-02-25,S1089,9,9D,U,0,,Call made,3,5,N,N
2026-02-26,S1089,9,9D,P,0,,,3,5,N,N
2026-02-27,S1089,9,9D,L,9,Late missed train,SMS sent,3,5,N,N
2026-03-02,S1089,9,9D,P,0,,,3,5,N,N
2026-02-24,S1121,10,10A,L,8,Late traffic,SMS sent,1,6,N,N
2026-02-25,S1121,10,10A,L,11,Late traffic,SMS sent,1,6,N,N
2026-02-26,S1121,10,10A,L,9,Late traffic,SMS sent,1,6,N,N
2026-02-27,S1121,10,10A,P,0,,,1,6,N,N
2026-03-02,S1121,10,10A,L,14,Late unknown,Call attempted,1,6,N,N
2026-02-24,S1188,8,8B,U,0,,Not yet,4,2,N,Y
2026-02-25,S1188,8,8B,P,0,,,4,2,N,Y
2026-02-26,S1188,8,8B,U,0,,SMS sent,4,2,N,Y
2026-02-27,S1188,8,8B,P,0,,,4,2,N,Y
2026-03-02,S1188,8,8B,U,0,,Call attempted,4,2,N,Y
2026-02-24,S1202,7,7A,E,0,Wellbeing plan anxiety morning,Wellbeing note,7,1,Y,Y
2026-02-25,S1202,7,7A,E,0,Wellbeing plan partial day,Wellbeing note,7,1,Y,Y
2026-02-26,S1202,7,7A,P,0,,,7,1,Y,Y
2026-02-27,S1202,7,7A,U,0,,Call made,7,1,Y,Y
2026-03-02,S1202,7,7A,E,0,GP note received,Front office sighted,7,1,Y,Y
```

**Attendance codes:** P = Present, L = Late, U = Unexplained absence, E = Explained absence

---

## Artifact 03 — Parent Complaint Email

**Use with:** Exercise 4 (Email Thread Summarizer)

```
From: Renee Nguyen <renee.nguyen@example.com>
To: Marraburra Secondary College Front Office <info@marraburrasc.edu.au>
Date: Monday 2 March 2026 07:18
Subject: Ongoing bullying + lack of follow-up (Year 9)

Dear Principal Team,

I am writing again because I am very concerned about the lack of follow-up
regarding bullying involving my child in Year 9.

On 10 February I reported repeated harassment that has been happening:
- nasty comments in a group chat after school hours
- name calling in the corridor near the library
- my child being filmed on a phone without consent

Since then, my child has been anxious and has started arriving late because
they are trying to avoid certain students in the morning. I was told someone
would contact me, but I have not received a clear update on what has been done.

I appreciate that you may not be able to share details about other students,
but I do need to know:
1. what steps the school is taking to keep my child safe at school
2. who I should be contacting as the point person
3. when we can meet to put a plan in place

Please treat this as urgent. If I don't hear back this week, I will need to
escalate the complaint.

Regards,
Renee Nguyen
(Mobile: 04xx xxx xxx)

Internal reference: StudentID S1089, Year 9
```

---

## Artifact 04 — Budget Snapshot

**Use with:** Exercise 7 (Data to Board Narrative)

```
CostCentre,AnnualBudget,YTD_Budget,YTD_Actual,YTD_Variance,Forecast_FY,Forecast_Variance,Notes
Relief Teaching (CRT),220000,36667,54500,17833,255000,35000,Higher staff absences Feb
Education Support Overtime,48000,8000,11200,3200,52000,4000,Enrolment spike + incident follow-up
Utilities Electricity,145000,24167,19800,-4367,138000,-7000,Milder summer + LED savings
ICT Software Licences,165000,27500,30100,2600,172000,7000,New cyber security add-on
Student Wellbeing Programs,92000,15333,20150,4817,102000,10000,Additional Year 8 group program
Building Maintenance,180000,30000,41200,11200,205000,25000,Urgent Block B roof leak repairs
Professional Learning,78000,13000,8400,-4600,70000,-8000,Some PL moved to Term 2
Printing and Stationery,52000,8667,9100,433,54000,2000,Stable
Excursions and Camps,115000,19167,12600,-6567,110000,-5000,Most excursions Term 2
Cleaning Contracted,210000,35000,36200,1200,214000,4000,Extra cleans after community events
```

---

## Artifact 05 — Complaints Handling Policy Excerpt

**Use with:** Exercise 5 (Policy to Plain Language)

```
MARRABURRA SECONDARY COLLEGE — Parent Communication and Complaints Handling
Procedure (Excerpt)

Purpose
This procedure describes how Marraburra Secondary College communicates with
parents/carers about student matters and manages complaints in a timely, fair,
and consistent way.

Scope
Applies to all staff when communicating with parents/carers about attendance,
wellbeing, behaviour, incidents, learning progress, and complaints received by
email, phone, in person, or via social media.

Principles
- We communicate respectfully and protect student privacy.
- We respond as soon as practicable and aim to resolve issues at the lowest
  appropriate level.
- We keep appropriate records to support continuity and accountability.

B. Complaints handling steps

1 Receipt
- Complaints may be received via any channel. Staff should remain calm and
  acknowledge the concern.
- If the complaint is complex, staff may request the complainant put the
  matter in writing.

2 Acknowledgement
- The school will acknowledge complaints within 2 business days where possible.
- The acknowledgement will outline next steps and a likely timeframe.

3 Assessment
- The receiving leader will decide whether the complaint is minor, moderate,
  or serious.
- Serious matters may be escalated to the Principal Team.

4 Investigation
- The school may speak with relevant staff and students and may review
  available records.
- The school will not disclose confidential information about other students.

5 Response
- The response should address the concern, outline actions taken (where
  appropriate), and offer a way forward.

6 Recording and closure
- A summary record should be kept in the complaint register.

C. Guidance on tone and content (staff)
- Use plain language and avoid jargon.
- Avoid statements that imply fault or liability.
- If you are unsure, seek advice from a member of the Principal Team.
```

---

## Artifact 06 — Authority Circular (New Expectations)

**Use with:** Exercise 5 Bonus (Policy Gap Analysis)

```
STATE EDUCATION AUTHORITY — OPERATIONAL BULLETIN OB-2026-04 (FICTIONAL)
Issued: 15 Feb 2026
Subject: Student Incident Recording, Parent/Carer Notification, and
Recordkeeping

2 Recording requirements (minimum)
2.1 Incidents must be entered into the incident management system no later
    than 24 hours after the incident is known to the school.
2.2 Records must be factual and avoid speculation.
2.3 Each record must include:
    - date/time, location, category, roles of those involved
    - immediate actions taken
    - parent/carer contact attempts and outcomes
    - evidence sources where applicable
    - follow-up owner and review date

3 Parent/carer notification expectations
3.1 For physical incidents, schools must make reasonable attempts to contact
    a parent/carer on the same day.
3.2 Where same-day contact is not possible, schools must record attempts
    and continue attempts the next school day.
3.3 Schools must provide parents/carers with:
    - a factual summary of what is known
    - immediate steps taken to ensure safety
    - next steps and expected timeframe for follow-up

5 Email and messaging caution
5.1 Schools must avoid sending sensitive personal information about students
    via unsecured channels.

Effective date: From Monday 2 March 2026.
```

---

## Artifact 07 — Executive Meeting Notes (Raw)

**Use with:** Any exercise as bonus material

```
EXECUTIVE TEAM MEETING — Raw Notes
Date: Monday 2 March 2026, 08:15-08:45
Attendees (roles): Principal, AP Wellbeing, AP Curriculum, Business Manager,
Wellbeing Leader, Facilities Manager

Attendance
- Year 8C and Year 7A showing spike in unexplained absences + late arrivals.
- StudentIDs flagged: S1019, S1048, S1202, S1188, S1121.
- Action: AP Wellbeing to produce triage list + parent contact plan by Wed 4 Mar.

Incident follow-up (Fri 27 Feb, basketball court)
- Record entered in SafeTrack? Check completion + evidence links.
- CCTV may be partially obstructed due to scaffolding.
- Parent contact: one made same day; one voicemail + SMS.
- Action: Wellbeing Leader to obtain witness statements by Tue 3 Mar.

Building works (Block B roof leak)
- Rooms B2-B6 unavailable from Mon 9 Mar for approx 3 weeks.
- Need rooming plan and comms to staff/parents/students.
- Action: AP Curriculum + Timetabler to issue draft room move list by Thu 5 Mar.

Board meeting preparation (Wed 18 Mar)
- Board paper needed: Attendance + Wellbeing + incident recording compliance.
- Business Manager to provide YTD budget commentary by Mon 9 Mar.

Complaints handling
- Increase in parent complaints re bullying + communications delays.
- Need consistent acknowledgement template + case logging.
- Action: AP Wellbeing to draft acknowledgement email template.

Decisions
- Trial weekly attendance digest to year-level coordinators (pilot Year 8).
- Move basketball courts to increased supervision list during works.

Action register
1 AP Wellbeing — attendance triage + contact plan — due 2026-03-04
2 Wellbeing Leader — witness statements + CCTV check — due 2026-03-03
3 AP Curriculum — room move list — due 2026-03-05
4 Business Manager — budget variance commentary — due 2026-03-09
5 Principal — board paper draft — due 2026-03-12
```

---

## Artifact 08 — Draft Term 2 Calendar

**Use with:** Exercise 9 (Spot the Error / Calendar Checker)

```
MARRABURRA SECONDARY COLLEGE — DRAFT Term 2 Calendar 2026

Week  Date         Day        Event
  1   Mon 20 Apr   Monday     Term 2 begins — staff return
  1   Tue 21 Apr   Tuesday    Students commence
  1   Fri 24 Apr   Friday     ANZAC Day assembly (early finish 2:30pm)
  2   Sat 25 Apr   Saturday   ANZAC Day public holiday
  2   Wed 29 Apr   Wednesday  Year 7 immunisations
  3   Mon 5 May    Monday     Curriculum Day (student-free)
  3   Wed 7 May    Wednesday  Year 9 careers expo 9:00-12:00
  3   Wed 7 May    Wednesday  Whole-school cross-country carnival
  4   Tue 13 May   Wednesday  NAPLAN Writing — Years 7 and 9
  4   Wed 14 May   Wednesday  NAPLAN Reading — Years 7 and 9
  4   Thu 15 May   Thursday   NAPLAN Numeracy — Years 7 and 9
  5   Mon 19 May   Monday     Year 10 work experience week begins
  5   Wed 21 May   Wednesday  Parent-Teacher Interviews 4:00-8:00pm
  6   Mon 26 May   Monday     Queen's Birthday public holiday
  6   Thu 29 May   Thursday   Year 8 camp departs (3 days)
  7   Mon 2 Jun    Monday     Report writing day (student-free)
  7   Wed 4 Jun    Wednesday  VCE GAT exam
  8   Mon 9 Jun    Monday     Queens Birthday public holiday
  8   Fri 13 Jun   Friday     Semester 1 reports published
  9   Mon 16 Jun   Monday     Year 12 exam week begins
  9   Thu 19 Jun   Thursday   Year 8 immunisations round 2
 10   Fri 26 Jun   Friday     Last day Term 2 — early finish 2:30pm
```

**Note:** This calendar contains deliberate errors for the exercise. Can you find them all?

---

## Artifact 09 — Vendor Quotes (Three Suppliers)

**Use with:** Exercise 10 (Vendor Quote Comparison)

```
--- QUOTE 1: OfficePro Direct ---
From: sales@officeprodirect.com.au
Date: 27 Feb 2026
Subject: RE: Stationery order Marraburra SC

Hi there,

Happy to quote on the below. Prices are ex-GST, free delivery over $500.

- A4 copy paper (80gsm white) 10 reams: $52.00
- Whiteboard markers (assorted 10-pack): $18.50
- Binder clips 32mm box of 12: $4.20
- Sticky notes 76x76mm 12-pack: $14.90
- Laminating pouches A4 100-pack: $28.00
- Printer toner (HP 26X black): $89.00
- Glue sticks 36g 10-pack: $9.50

Subtotal: $216.10 + GST = $237.71

Cheers,
Tanya

--- QUOTE 2: SchoolSupply Co ---
From: orders@schoolsupplyco.com.au

Item                           Qty    Unit Price (inc GST)   Total
Copy Paper A4 80gsm (ream)       10         $5.72            $57.20
Whiteboard Markers Asst (10pk)    1        $21.45            $21.45
Binder Clips 32mm (box/12)       1         $3.85             $3.85
Post-it Notes 76mm (12pk)        1        $16.50            $16.50
Laminating Pouches A4 (100pk)    1        $25.30            $25.30
HP Toner 26X Black               1        $95.70            $95.70
Glue Sticks 36g (10pk)           1        $11.00            $11.00
                                           TOTAL:          $231.00
Delivery: Free over $200. Lead time 3-5 business days.

--- QUOTE 3: Aussie Ed Supplies ---
Phone quote transcribed by front office:

- Paper (A4 white 80g) 10 reams — $48 plus GST so $52.80
- Whiteboard markers pack — she said $16.50 inc GST for pack of 8 (not 10)
- Binder clips big ones — $4.40 inc GST per box
- Those yellow sticky notes — $13.20 inc GST for a pack of 10 (not 12)
- Laminating sleeves A4 box of 100 — $31.90 inc GST
- HP black toner, thinks its the 26X — $82.50 inc GST
- Glue sticks — doesn't stock, would need to order separately
- Delivery: $15 flat rate
```

---

## Artifact 15 — Storm Scenario Brief

**Use with:** Exercise 3 (Crisis Communication)

```
SCENARIO BRIEF — Severe Storm Warning
Date: Thursday 5 March 2026
Event: Severe storm warning + local power outage risk

Known facts:
- Severe storm warning from 11:00 onwards
- School will remain OPEN in the morning
- All outdoor activities cancelled from 10:30
- Wet weather timetable for recess and lunch
- Families may collect students early
- Status update by 12:00
- If power fails, school will use SMS and website for updates

Constraints:
- Do not promise early closure unless a decision is made
- Keep messages calm and practical
```

---

*Real Minds AI | wisdom, amplified | realmindsai.com.au*
