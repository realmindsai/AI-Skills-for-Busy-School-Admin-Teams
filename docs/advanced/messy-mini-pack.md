# Participant Handout — Messy Mini-Pack

**Workshop:** AI Skills for Busy School Admin Teams (Advanced Exercises)
**Date:** 5 March 2026 | **Real Minds AI**

**Important:** All data is **entirely fictional and synthetic**. This pack is **intentionally messy** — it contains duplicates, contradictions, missing fields, privacy traps, and ambiguous wording. This is realistic. Your job is to use AI to find the problems, not to trust AI to fix them silently.

---

## Artifact 01 — Attendance Export (Partial, Messy)

**Use with:** Exercise A3 (Attendance Triage Under Uncertainty)

```
Date,StudentID,YearLevel,Homeroom,AttendanceCode,MinutesLate,ExplanationText,ParentContactStatus,Prior20DaysAbsences,Prior20DaysLate,SupportPlan,EAL
2026-03-03,S1019,8,8C,U,,,Not yet,5,1,N,N
2026-03-03,S1048,8,8A,P,0,,,6,2,Y,N
2026-03-03,S1188,8,8B,U,0,,SMS sent,4,2,N,Y
2026-03-03,S1202,7,7A,E,0,Wellbeing plan - partial day,Wellbeing note,7,1,Y,Y
2026-03-03,S1121,10,10A,L,14,Late - traffic,Call attempted,1,6,N,N
2026-03-04,S1019,8,8C,Unexplained,0,,Call made,5,1,N,N
2026-03-04,S1188,8,8B,U,9,Missed bus? (unconfirmed),,4,2,N,Y
2026-03-04,S1188,8,8B,U,9,Missed bus? (unconfirmed),,4,2,N,Y
2026-03-04,S1007,7,7A,LATE,7,Late bus connection,SMS sent,2,4,N,Y
2026-03-04,S1102,11,11A,L,-3,Late - unknown,SMS sent,0,3,N,N
2026-03-04,S1095,,7B,E,0,Medical certificate provided,Front office sighted,2,0,N,N
2026-03-05,S12O2,7,7A,E,0,GP note received,Front office sighted,7,1,Y,Y
05/03/2026,S1048,8,8A,U,0,,Not yet,6,2,Y,N
2026-03-05,S1089,9,9D,X,0,,,3,5,N,N
2026-03-05,S1033,9,9B,P,0,,,1,0,N,N
2026-03-05,S1121,10,10A,,12,Late - traffic,SMS sent,1,6,N,N
2026-03-06,S1019,8,8C,U,0,,Voicemail left (07:42); asked to call back,5,1,N,N
2026-03-06,S1188,8,8B,P,0,,,4,2,N,Y
2026-03-06,S1202,7,7A,U,0,,Call attempted,,1,Y,Y
2026-03-06,S1048,8,8Z,E,0,Medical appointment,Parent portal note,6,2,Y,N
```

**Standard codes:** P = Present, L = Late, U = Unexplained, E = Explained

---

## Artifact 02 — Incident Account: Yard Duty Staff

**Use with:** Exercise A1 (Incident Pack Assembly)

```
INCIDENT ACCOUNT — Yard Duty Staff Note (RAW)
School: Marraburra Secondary College
Date: Fri 27 Feb 2026
Entered: Fri 27 Feb 2026 15:46
Staff role: Teacher on Yard Duty (North yard)

What I saw / heard
- At approx 13:05 I heard yelling near the basketball courts (north side).
- I walked quickly toward the courts and saw two Year 8 students
  (StudentIDs: S1048 and S1188) in a physical altercation.
- It looked like there was pushing and possibly a punch thrown
  (I did not clearly see contact — may have been blocked by other students).
- A bystander called out "Stop it, Sam!" (not sure which student they meant).
  NOTE: I did not confirm any names.

Actions
- I instructed surrounding students to move back and called for additional
  staff support.
- The two students were separated within about 30 seconds of my arrival.
- I directed both students to sit on opposite sides of the court.
- Education Support staff arrived and assisted escorting students.

Injuries
- I noticed S1188 holding their left arm. Unsure if injury occurred during
  incident or earlier.
- No other injuries observed by me.

Possible context (UNCONFIRMED)
- Several students said there has been "ongoing drama" in a group chat.
- I did not verify this and did not view any messages.

CCTV / environment
- Scaffolding near Block B walkway might obstruct camera view.
- The area felt crowded today.

Open questions
- Confirm exact time of start (I arrived after voices started).
- Confirm if any punch occurred (I am not certain).
- Identify witnesses (students) and obtain statements.
```

---

## Artifact 03 — Incident Account: Student Services

**Use with:** Exercise A1 (Incident Pack Assembly)

```
INCIDENT ACCOUNT — Student Services Intake Note (RAW)
School: Marraburra Secondary College
Date: Fri 27 Feb 2026
Entered: Fri 27 Feb 2026 14:10
Staff role: Student Services Officer (Wellbeing)

Intake summary
- Two Year 8 students presented to Student Services: S1048 and S1188.
- Students arrived at approx. 13:12 (bell had just gone for Period 5).
- Students reported verbal argument then "pushing".
  Both students stated there was NO punching.
- Both were calm after ~10 minutes.

First aid
- S1188 had a small graze to left elbow and requested a bandage.
- S1048 reported no injury.

Restorative conversation
- Brief restorative chat at approx. 13:35 with both students.
- Agreement: avoid contact for remainder of day; follow-up meeting next week.

Parent contact attempts (times uncertain)
- S1188 parent: call at approx. 13:30, voicemail. SMS sent.
- S1048 parent: contacted, requested email summary (time recorded as 13:25
  in my notes, but may be the attempt time rather than successful contact).

Context (UNCONFIRMED)
- Students referenced "messages online" earlier in the week.
  No evidence provided.

Missing information
- Exact start time
- Independent witness accounts
- CCTV availability
```

---

## Artifact 04 — First Aid Log Excerpt

**Use with:** Exercise A1 (Incident Pack Assembly)

```
Date,Time,StudentID,PresentingIssue,Treatment,Disposition,Notes
2026-02-27,13:18,S1188,Graze (left elbow),Cleaned + dressed,Returned to class (P5),Time recorded by first aid officer
2026-02-27,13:20,S1048,Nil reported,N/A,Returned to Student Services,Student stated no injury
2026-02-27,13:16,S1188,Graze (left elbow),Bandage,Student Services,Time may be approximate
```

**Note:** There are two entries for S1188 at different times with slightly different treatment descriptions.

---

## Artifact 05 — Parent Contact Log (Partial)

**Use with:** Exercise A1 (Incident Pack Assembly)

```
Date,CaseID,StudentID,Channel,Time,Outcome,Notes,StaffRole
2026-02-27,INC-2026-018,S1048,Phone call,13:25,Attempted,No answer; left voicemail,AP Wellbeing
2026-02-27,INC-2026-018,S1048,Phone call,13:32,Successful contact,Parent requested email summary,AP Wellbeing
2026-02-27,INC-2026-018,S1048,Email,15:05,Sent,Summary sent to parent email on file,AP Wellbeing
2026-02-27,INC-2026-018,S1188,Phone call,13:30,Attempted,Voicemail,Student Services
2026-02-27,INC-2026-018,S1188,SMS,13:35,Sent,Please call school re: lunchtime incident,Student Services
2026-02-28,INC-2026-018,S1188,Phone call,09:10,, ,Student Services
2026-02-27,,S1188,Email,16:40,Drafted,Draft only; not sent (unclear),
```

**Note:** Last two rows have missing fields (outcome, case ID, staff role).

---

## Artifact 06 — CCTV Maintenance Ticket

**Use with:** Exercise A1 (Incident Pack Assembly)

```
CCTV MAINTENANCE TICKET
Ticket ID: FAC-2026-0331
Logged: Thu 26 Feb 2026 16:22
Area: North Yard / Block B walkway

Issue
- Camera B-North-02 reported intermittent dropouts.
- Scaffolding may obstruct field of view toward basketball courts.

Notes
- 26 Feb 17:05: reboot completed.
- 27 Feb 12:40: camera status shows ONLINE in dashboard.
- 27 Feb 13:10-13:25: dashboard shows "NO SIGNAL" (unclear if network or camera).
- 27 Feb 14:05: camera status shows ONLINE again.

Action
- Check footage availability for 27 Feb between 12:50 and 13:30.
- If footage missing, record in incident evidence log.

Caution
- Even if camera is online, scaffolding may block key angles.
```

**Note:** The "NO SIGNAL" window (13:10-13:25) overlaps with the incident time.

---

## Artifact 07 — Problematic Draft Email (DO NOT SEND)

**Use with:** Exercise A2 (Fix the Problematic Email)

```
DRAFT — NOT FOR SENDING

Subject: Update re: fight at basketball courts — actions taken

Dear Parent/Carer,

I'm writing to let you know your child was involved in a fight at lunchtime
today. The other student has a history of behaviour issues and we will be
suspending them for 5 days. We have also told their parents.

Your child said the other student punched first and we have CCTV that
clearly shows this. We will ensure this never happens again.

Please reply with any screenshots of the group chat so we can take
further action.

Kind regards,
[Staff name]
Assistant Principal Wellbeing
Marraburra Secondary College
```

**Problems to find:** At least 6 governance failures including privacy breaches, over-promises, false evidence claims, and inappropriate evidence requests.

---

## Artifact 08 — Complaints Register (Partial, Messy)

**Use with:** Any exercise as bonus context

```
CaseID,DateReceived,Channel,ComplainantType,IssueCategory,Cohort,StudentID,Status,OwnerRole,NextStep,RiskRating,ContactEmail
COMP-2026-005,2026-02-10,Email,Parent/Carer,Bullying (online/offline),Year 9,S1089,Open,AP Wellbeing,Awaiting meeting booking,High,
COMP-2026-007,2026-02-24,Phone,Parent/Carer,Communication delay,Year 8,S1188,Closed,Front Office Manager,Resolved by call,Low,
,2026-03-02,Email,Parent/Carer,Bullying,Year 9,S1089,Open,,No acknowledgement sent yet,High,renee.nguyen@example.com
COMP-2026-005,2026-02-12,In person,Parent/Carer,Bullying,Year 9,S1089,Open,AP Wellbeing,Added note: group chat,High,
COMP-2026-009,2026-03-01,Social media,Community,Rumour (vaping),Year 10,,In progress,Principal Team,Need verify evidence,Med,
```

**Note:** Missing case IDs, duplicate entries for COMP-2026-005, missing owner for 2 March entry.

---

## Artifact 09 — Old Local Procedure Excerpt

**Use with:** Exercise A4 (Policy Alignment)

```
LOCAL PROCEDURE — Version in staff handbook (dated 2024)
Parent Communication and Complaints Handling — Extract

Incident communication
- Staff should notify parents/carers after incidents when it seems appropriate.
- The preferred method is phone call, but email may be used if time is limited.
- Records of parent contact should be kept where possible.

Incident recording
- Incident notes should be entered into SafeTrack when convenient, ideally
  within a few days.
- Staff should include relevant context to help understanding.

Complaints acknowledgement
- The school aims to acknowledge complaints within 5 business days where
  possible.
- If staff are busy, acknowledgement may be delayed.

Privacy
- Staff should be mindful of privacy but should also provide enough detail
  for parents to understand what occurred.
```

---

## Artifact 10 — Authority Bulletin (New Expectations)

**Use with:** Exercise A4 (Policy Alignment)

```
STATE EDUCATION AUTHORITY — OPERATIONAL BULLETIN OB-2026-04
Issued: 15 Feb 2026 | Effective: From Monday 2 March 2026

Minimum expectations — incident recording and parent/carer notification

1 Recording timeframe
- Physical and notifiable incidents must be entered into the incident
  management system no later than 24 hours after the incident is known.

2 Record quality
- Records must be factual and avoid speculation.
- Unconfirmed information must be clearly marked as UNCONFIRMED.
- Each record must include: date/time, location, category, roles of those
  involved, immediate actions, parent contact attempts and outcomes,
  evidence sources, follow-up owner, review date.

3 Parent/carer notification
- For physical incidents, make reasonable attempts to contact a parent/carer
  on the same day.
- If same-day contact is not possible, record attempts and continue the
  next school day.
- Do not disclose personal information about other students.

4 Messaging caution
- Avoid sending sensitive personal information via unsecured channels.
```

---

## Artifact 11 — Messy Exec Meeting Notes

**Use with:** Exercise A5 (Messy Minutes to Action Register)

```
EXECUTIVE TEAM MEETING — RAW NOTES (INTENTIONALLY MESSY)
Date/time: Monday 2 March 2026, 08:15-08:45
Attendees: Principal, AP Wellbeing, AP Curriculum, Business Manager,
           Wellbeing Leader, Facilities Manager

Attendance
- Yr 8 and Yr 7: unexplained absences rising (esp 8C, 7A) — need "a plan".
- StudentIDs mentioned: S1019, S1188, S1202, S1048, S1121.
- Action: "send list to coordinators" (who? by when?) maybe Wed?

Incident follow-up (Fri 27 Feb, basketball court)
- SafeTrack entry: not sure if done / maybe draft.
- Parent contact: one contacted (time unclear), one voicemail + SMS (same day).
- CCTV: camera might be online but scaffolding blocks view / also "no signal"
  around lunch?? (Facilities to confirm).
- Action: witness statements (roles only) — due Tue (or Wed?) — owner??
  (Wellbeing?)

Building works (Block B)
- B2-B6 closed from Mon 9 Mar for 3 weeks.
- Need room moves + comms pack.
- Action: draft room move list by Thu 5 Mar (APC + Timetable) — confirm.

Board prep (Wed 18 Mar)
- Need board paper: attendance + incident recording compliance + budget.
- Action: budget commentary by Mon 9 Mar (BM).
- Action: 10-slide deck outline (who drafts?) due mid-March.

Complaints handling
- Increase in complaints about bullying + delays.
- Need acknowledgement template + escalation logic + complaint register
  hygiene.

Decision-ish
- Increase supervision near courts during works.
- Trial weekly attendance digest (pilot Year 8) — start "soon".
```

---

*Real Minds AI | wisdom, amplified | realmindsai.com.au*
