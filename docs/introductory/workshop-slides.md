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
  color: white;
  border-top: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
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

/* Break slides — oat gradient */
section.break-slide {
  background: linear-gradient(135deg, var(--rmai-oat) 0%, #E8D5C4 100%);
  border-top: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
}
section.break-slide h1 { color: var(--rmai-slate); font-size: 56px; }
</style>

<!-- _class: lead -->
<!-- _paginate: false -->

# AI Skills for Busy School Admin Teams

A practical workshop by Real Minds AI

Tracy Anthony and Dr Dennis Wollersheim
5 March 2026

---

## Welcome

- **Tracy Anthony** and **Dr Dennis Wollersheim** — Real Minds AI
- Full day: 9:30am to 3:00pm (online via Zoom)
- Three blocks with morning tea and lunch breaks
- Hands-on exercises using free AI tools you can use tomorrow
- You will need: laptop, browser, and free accounts on at least two of ChatGPT, Copilot, or Gemini

> The goal today: leave with practical AI skills you can use in your first hour back at work

---

## Your Day

| Time | Block | Focus |
|------|-------|-------|
| 9:30 - 11:00 | **Understanding AI** | What AI is, how to talk to it, first hands-on exercises |
| 11:00 - 11:30 | Morning Tea | |
| 11:30 - 1:00 | **Practical Skills** | Email, documents, spreadsheets, data |
| 1:00 - 1:30 | Lunch | |
| 1:30 - 3:00 | **Safety and Planning** | Privacy, quality control, your action plan |

---

## Introductions

### Who are you and why are you here?

- Your name and role
- Your school (and location)
- One thing you hope to take away today

### Quick poll

Where do you sit on the AI experience spectrum?

**Total novice** ---- **Had a play** ---- **Use it weekly** ---- **Daily user**

---

<!-- _class: theory -->

## Why Now? The Technology Adoption Curve

### You are at the front of the wave

- AI tools went from research labs to free browser tools in under 2 years
- School admin staff who learn now become the go-to experts at their school
- **Curiosity is the key skill** — you already have it (you signed up)
- Nobody knows exactly how AI will work in *your* context — you get to figure it out

### What makes you a great AI user

- You work with **text** all day (emails, policies, reports, notices)
- You have **real problems** that need solving (not theoretical ones)
- You bring **judgment** and **context** that AI lacks

---

<!-- _class: theory -->

## GenAI — What Is It?

### A calculator for text and knowledge

- Just as a calculator handles arithmetic you could do by hand (but faster, without errors), GenAI handles text tasks you could do by hand — but faster
- It is a **cultural technology**, like reading, writing, publishing, or Wikipedia
- It requires a **cultural shift** — new habits, new skills, new ways of thinking

### A new kind of tool

- Not a search engine (it generates, not retrieves)
- Not a human (it has no feelings, no memory between sessions, no accountability)
- Not magic (it makes mistakes, confidently)

> Think of it as a very well-read colleague who is eager to help but needs clear instructions and always needs to be checked

---

## How GenAI Works

### The 60-second technical version

**Training** — The model read most of the internet and learned statistical patterns between words and ideas (~600 billion connections)

**Inference** — When you type a prompt, it combines your words with everything it learned to predict the most helpful response

### The useful metaphor

> A "blurry photograph of the internet" combined with your specific context

- The AI has broad, general knowledge (the blurry photo)
- **You** supply the sharp, specific context (your school, your role, your task)
- Together, the output is useful and relevant

---

## Your Mental E-Bike

### What GenAI does for your brain

- **Calculator for text** — handles the mechanical work of writing and formatting
- **Metaphor engine** — connects ideas across domains you might not think to link
- **Extra cognitive capacity** — frees your brain for the hard thinking (judgment, relationships, decisions)

### Why "e-bike for the mind"?

- An e-bike amplifies your pedalling — it does not ride itself
- GenAI amplifies your thinking — it does not think for you
- The more you use it, the further you can go
- **You still choose the direction**

> **Polite and plausible** — AI output always sounds confident. Your job is to check whether it is also *correct*.

---

## GenAI — Functional Limits

| Limit | What it means | Watch out for |
|-------|---------------|---------------|
| **Limited context** | Knows general facts but not your school | Always provide your specific context |
| **Static knowledge** | Training data has a cutoff date | Do not rely on it for current events |
| **No understanding** | Predicts text patterns, not meaning | May miss nuance, sarcasm, or cultural context |
| **No accountability** | Cannot take blame for errors | Never use for legal, medical, or compliance decisions without checking |

### The golden rule

AI output is a **first draft**, never a final product

You bring: judgment, local knowledge, relationships, accountability

---

<!-- _class: lead -->

# Block 1: Understanding AI

Exercises 1 - 3 (9:45 - 11:00)

---

## Today's Exercises

| # | Exercise | What you will do | Time |
|---|----------|-----------------|------|
| 1 | **Context Card Builder** | AI interviews you, builds a reusable prompt context | 15 min |
| 2 | **Multilingual Translation** | Translate a notice into 4 languages simultaneously | 15 min |
| 3 | **Crisis Communication** | Generate SMS + email + social post from one brief | 15 min |
| 4 | **Email Thread Summarizer** | Summarize a complaint email into actions | 15 min |
| 5 | **Policy to Plain Language** | Rewrite policy as parent FAQ and staff guide | 15 min |
| 6 | **Spreadsheet Formula Helper** | Describe what you need, get exact Excel formulas | 15 min |
| 7 | **Data to Board Narrative** | Turn a budget table into a board-ready report | 15 min |
| 8 | **Escalation Letter Series** | Generate 3 graduated attendance letters | 15 min |

---

<!-- _class: theory -->

## Why Context Matters

### The theory: garbage in, garbage out (but for AI)

- AI knows everything in general but nothing about **your school**
- The single biggest improvement to AI output is telling it **who you are** and **what you need**
- A "context card" is a reusable block of text you paste at the start of every AI conversation

### What this exercise demonstrates

- AI can **interview you** (reversing the usual dynamic)
- The output is a practical artifact you will use **every day after today**
- This teaches the meta-skill: how to set up AI for success before asking it anything

---

<!-- _class: exercise -->

## Exercise 1: Build Your Context Card

### Instructions (15 minutes)

1. Open your preferred AI tool (ChatGPT, Copilot, or Gemini)
2. Paste this prompt:

> *I am going to start using AI tools for my work. Before I do, I would like you to interview me so you can understand my context. Ask me 5-6 questions one at a time about my role, my school, and what I typically do. Then generate a reusable context paragraph I can paste at the start of future conversations.*

3. Answer each question the AI asks
4. Review the context card it generates
5. Save it somewhere you can find it (email it to yourself, paste into Notes)

### What to check

- Does it capture your role accurately?
- Would a stranger reading it understand your work?

---

<!-- _class: debrief -->

## Exercise 1: What You Learned

### Key takeaways

- **Context is king** — the same prompt produces very different results depending on what context you provide
- AI can act as an **interviewer**, not just an answerer
- A reusable context card saves you time on **every future AI interaction**

### The principle

> The quality of AI output is directly proportional to the quality of context you provide

### Try this at work

- Paste your context card at the start of your next AI conversation
- Notice how much better the output is compared to a cold start
- Update your card as your role or priorities change

---

<!-- _class: theory -->

## AI as Universal Translator

### The theory: one input, many languages

- Before AI, translating a school notice into 4 languages required hiring translators or relying on Google Translate (one language at a time, often awkward)
- GenAI can translate into multiple languages simultaneously with natural phrasing
- This is one of the few things that was **genuinely impossible** before AI for a school admin person

### What this exercise demonstrates

- AI handles **multiple languages in a single prompt**
- Output includes scripts you cannot type (Arabic, Chinese, Hindi)
- You can add instructions like "include a contact line in each language"
- Particularly relevant for schools with **multilingual families**

---

<!-- _class: exercise -->

## Exercise 2: Multilingual Translation

### Instructions (15 minutes)

1. Paste your context card, then add this prompt:

> *Here is a school notice: "Marraburra Secondary College will hold a pupil-free day on Friday 14 March for staff professional learning. Students do not attend school on this day. Normal classes resume Monday 17 March. If you need emergency care arrangements, please contact the front office by Wednesday 12 March."*
>
> *Translate this into: Simplified Chinese, Vietnamese, Arabic, and Hindi. At the top of each translation, add a line in that language saying "If you need help understanding this notice, please contact the school office on (03) 9555 1234."*

2. Review the output — notice the different scripts and formatting
3. **Bonus**: Ask the AI to add a 5th language relevant to your school community

### What to check

- Did it maintain the key facts in each version?
- Did it add the contact line in each language (not just in English)?

---

<!-- _class: debrief -->

## Exercise 2: What You Learned

### Key takeaways

- AI can produce **multiple translations simultaneously** — no need to do one at a time
- The output includes scripts you cannot type yourself (this was impossible before)
- You can add **custom instructions** (like "add a contact line") and AI applies them across all versions

### The principle

> AI excels at **format multiplication** — taking one piece of content and producing multiple adapted versions

### Try this at work

- Next time you need to communicate with multilingual families, draft in English first, then ask AI to translate into the languages your community needs
- Always have a native speaker check critical translations — AI is good but not perfect

---

<!-- _class: theory -->

## One Input, Many Outputs

### The theory: format adaptation under pressure

- In a crisis (storm, power outage, incident), you need to communicate the same facts across **multiple channels** — SMS, email, social media, website
- Each channel has different constraints (SMS = 160 characters, email = full detail, social = public-facing tone)
- Writing all three manually takes 20-30 minutes. Under pressure, mistakes happen
- AI generates all three from a single brief in under a minute

### What this exercise demonstrates

- AI adapts **content to format constraints** automatically
- The same facts come out differently for each channel (this is genuinely impressive)
- Demonstrates the "one input, many outputs" pattern you will use constantly

---

<!-- _class: exercise -->

## Exercise 3: Crisis Communication

### Instructions (15 minutes)

1. Paste your context card, then add this prompt:

> *Scenario: A severe storm warning has been issued. The school will remain open this morning but all outdoor activities are cancelled from 10:30. Students will stay indoors during breaks (wet weather timetable). Families may collect students early. A status update will be sent by 12:00. If power fails, the school will use SMS and the website for updates.*
>
> *Write three versions of this communication:*
> *1. An SMS alert — under 160 characters*
> *2. A parent email — approximately 150 words, calm and practical*
> *3. A Facebook post — brief, reassuring, public-appropriate*

2. Count the SMS characters — is it actually under 160?
3. Compare the tone across all three versions

### What to check

- Does the SMS contain the essential facts only?
- Is the email appropriately detailed without being alarming?
- Is the Facebook post suitable for public viewing?

---

<!-- _class: debrief -->

## Exercise 3: What You Learned

### Key takeaways

- AI adapts the **same information** to different format constraints automatically
- SMS, email, and social media require genuinely **different writing** — AI handles this
- Under time pressure, having all three ready in seconds is a game-changer

### The principle

> AI is a **translation layer between formats** — same content, different packaging, instant output

### Try this at work

- Keep a "crisis comms prompt" saved with your standard scenarios
- When something urgent happens, paste the facts and get all channels at once
- Always review before sending — especially the SMS (character limits matter)

---

<!-- _class: break-slide -->
<!-- _paginate: false -->

# Morning Tea

Back at 11:30

---

<!-- _class: lead -->

# Block 2: Practical Skills

Exercises 4 - 8 (11:30 - 1:00)

---

<!-- _class: theory -->

## AI as Analyst

### The theory: extraction and synthesis

- Admin staff spend hours reading long email threads, extracting who said what, and figuring out what needs to happen next
- AI can read an entire thread and extract: summary, timeline, actions, tensions
- This is **analytical work** — AI is not just generating text, it is understanding structure

### What this exercise demonstrates

- AI extracts **multiple analysis layers** from a single input (summary + timeline + actions + tensions)
- The structured output format makes complex situations manageable
- This works for any long document: email threads, meeting notes, policy documents

---

<!-- _class: exercise -->

## Exercise 4: Email Thread Summarizer

### Instructions (15 minutes)

1. Open the **Parent Complaint Email** from your handout (Artifact 03)
2. Paste your context card, then the email, then add:

> *Analyse this email and give me:*
> *1. A one-sentence summary*
> *2. A chronological timeline of what has happened*
> *3. The current status*
> *4. Outstanding action items with who owns each one*
> *5. Any unresolved tensions or risks*
> *6. A draft acknowledgement reply (empathetic, professional, under 150 words)*

3. Review the output — does the timeline match the email?
4. **Bonus**: Ask AI to cross-reference with the school's Complaints Handling Policy (Artifact 05)

### What to check

- Are the action items genuinely in the email, or did AI invent them?
- Is the draft reply appropriately empathetic without admitting fault?

---

<!-- _class: debrief -->

## Exercise 4: What You Learned

### Key takeaways

- AI can extract **structured analysis** from unstructured text
- The multi-layer output (summary + timeline + actions + tensions) saves significant time
- Draft replies generated from complaint emails maintain appropriate tone

### The principle

> AI reads for **structure** — it can pull timelines, actions, and tensions from any document, no matter how messy

### Try this at work

- Use this pattern for any long email thread, parent complaint, or incident narrative
- Always verify action items against the original — AI occasionally infers actions that are not explicitly stated
- The acknowledgement reply is a first draft — adjust for your school's voice

---

<!-- _class: theory -->

## Text Transformation

### The theory: translating between audiences

- School admin teams constantly translate between audiences: the same information needs to be presented differently for parents, staff, the board, and regulators
- Dense policy language exists for legal precision — but parents need plain English and staff need a quick-reference guide
- AI transforms text **between register and audience** instantly

### What this exercise demonstrates

- AI rewrites dense language into plain English without losing meaning
- One input can generate **multiple audience-adapted outputs** (parent FAQ, staff guide, enrolment-pack bullets)
- This is the most common text transformation in school admin work

---

<!-- _class: exercise -->

## Exercise 5: Policy to Plain Language

### Instructions (15 minutes)

1. Open the **Policy Excerpt** from your handout (Artifact 05 — Complaints Handling)
2. Paste your context card, then the policy text, then add:

> *This is an excerpt from our school's complaints handling procedure. Please:*
> *1. Rewrite it in plain English that a parent would understand (max 200 words)*
> *2. Create a 5-question FAQ for the school website*
> *3. Produce a one-page staff quick-reference guide with the key steps*

3. Compare the three outputs — notice how the same content adapts
4. **Bonus**: Paste the Authority Circular (Artifact 06) and ask AI to flag where the school policy may not meet the new minimum expectations

### What to check

- Has any important meaning been lost in the simplification?
- Are the FAQ answers accurate to the original policy?
- Would you feel comfortable publishing the parent version on your website?

---

<!-- _class: debrief -->

## Exercise 5: What You Learned

### Key takeaways

- AI translates between **registers** (formal policy language to plain English) without losing meaning
- One source document can generate outputs for **multiple audiences** in a single prompt
- The "policy linter" bonus shows AI can **compare documents** and flag gaps

### The principle

> AI is "cognitive middleware" — it translates between the system language (policy, regulation) and the human language (plain English, FAQs, guides)

### Try this at work

- Every time your school updates a policy, ask AI to generate the parent-facing version and staff quick-reference at the same time
- Use the comparison feature when new regulations arrive — paste both documents and ask for a gap analysis

---

<!-- _class: theory -->

## AI as Technical Translator

### The theory: expert skills on demand

- Excel formulas are a language most school admin staff understand conceptually but struggle to write
- AI translates your plain-English description into exact, working formulas
- More importantly, it **explains what each formula does** — so you learn, not just copy

### What this exercise demonstrates

- You describe your spreadsheet layout in normal words
- AI returns exact, copy-paste-ready formulas
- AI adds plain-English explanations so you understand what you are pasting
- This works for conditional formatting, data validation, and pivot table setup too

---

<!-- _class: exercise -->

## Exercise 6: Spreadsheet Formula Helper

### Instructions (15 minutes)

1. Paste your context card, then this prompt:

> *I have an Excel spreadsheet tracking student attendance. The columns are:*
> *A = Student ID, B = Student Name, C = Year Level, D = Days Absent (Term 1), E = Days Late (Term 1), F = Total School Days (all students: 50)*
>
> *I need formulas for:*
> *1. Column G: Attendance percentage (present days divided by total)*
> *2. Column H: A status flag — "At Risk" if attendance is below 90%, "Monitor" if 90-95%, "OK" if above 95%*
> *3. Column I: A combined late-and-absent score (weight absences as 1 point, lates as 0.5 points)*
>
> *Give me the exact formulas and explain what each part does in plain English.*

2. If you have Excel open, paste the formulas in and test them
3. **Bonus**: Ask AI to add conditional formatting instructions (red, amber, green)

### What to check

- Do the formulas reference the correct columns?
- Does the attendance percentage calculation make sense?

---

<!-- _class: debrief -->

## Exercise 6: What You Learned

### Key takeaways

- AI generates **working formulas** from plain-English descriptions
- The explanations help you **understand** what you are pasting (not just copy blindly)
- This works for any spreadsheet task: VLOOKUP, conditional formatting, pivot tables

### The principle

> AI translates between **human intent** and **technical syntax** — you say what you want, it writes the formula

### Try this at work

- Next time you are stuck on an Excel problem, describe your layout and what you want in plain English
- Ask for the explanation every time — this is how you build your own formula skills
- Works equally well for Google Sheets

---

<!-- _class: theory -->

## Numbers to Story

### The theory: data literacy without the degree

- Boards and leadership teams need **narrative**, not raw numbers
- Writing a data narrative requires two skills: understanding the numbers AND writing clearly about them
- Most admin staff have the data but struggle to write the story — AI bridges the gap

### What this exercise demonstrates

- AI interprets data tables and writes **board-ready narrative**
- It identifies trends, flags concerns, and anticipates questions
- The output is a first draft that you refine with your local knowledge

---

<!-- _class: exercise -->

## Exercise 7: Data to Board Narrative

### Instructions (15 minutes)

1. Open the **Budget Snapshot** from your handout (Artifact 04)
2. Paste your context card, then the CSV data, then add:

> *This is our school's year-to-date budget snapshot. Please:*
> *1. Write a 3-paragraph executive summary for the school board (formal, factual)*
> *2. Flag the top 3 areas of concern with a brief explanation of each*
> *3. List 5 questions the board is likely to ask based on this data*
> *4. Suggest one recommended action for each concern*

3. Compare the AI narrative to the raw numbers — did it get the story right?
4. **Bonus**: Ask AI to also generate a one-slide summary (bullet points for a board slide)

### What to check

- Are the variance figures accurate (AI sometimes miscalculates)?
- Does the narrative flag the right concerns?
- Would you be comfortable presenting this to your board?

---

<!-- _class: debrief -->

## Exercise 7: What You Learned

### Key takeaways

- AI turns raw numbers into **readable narrative** with trends, concerns, and recommendations
- It anticipates **board questions** — helping you prepare, not just report
- Always verify the calculations — AI is better at narrative than arithmetic

### The principle

> AI translates between **data** and **story** — the numbers tell the facts, AI writes the meaning

### Try this at work

- Use this pattern for any data reporting: attendance stats, budget updates, survey results
- Paste the data as CSV or a table — AI handles both formats
- Always double-check the math, then focus your editing on tone and local context

---

<!-- _class: theory -->

## Tone Calibration

### The theory: graduated communication

- Schools often need to send escalating communications — starting warm and supportive, building to formal and firm
- Writing a coherent escalation series is hard because you need to **calibrate tone precisely** across 3 letters that form a sequence
- AI handles tone gradation remarkably well

### What this exercise demonstrates

- AI generates a **coherent series** with naturally escalating tone
- You can specify the tone level for each letter and AI maintains it
- The placeholder system (names, dates, percentages) makes outputs **reusable as templates**

---

<!-- _class: exercise -->

## Exercise 8: Escalation Letter Series

### Instructions (15 minutes)

1. Review the **Attendance CSV** from your handout (Artifact 01) — notice students with high absence counts
2. Paste your context card, then add:

> *I need three parent letters about a student's declining attendance. Use placeholders like [Parent Name], [Student Name], [Attendance Percentage], and [Days Absent].*
>
> *Letter 1: Warm check-in — "we have noticed" tone, supportive, offering help*
> *Letter 2: Formal concern — "we are concerned" tone, references school obligations, requests a phone call*
> *Letter 3: Meeting request — "we need to discuss" tone, firm but not threatening, references potential referral to wellbeing team*
>
> *Each letter should be under 200 words. The tone must escalate naturally across the series.*

3. Read all three letters in sequence — does the escalation feel natural?
4. **Bonus**: Ask AI to generate an SMS version (under 160 chars) for each letter level

### What to check

- Does Letter 1 feel genuinely warm (not corporate)?
- Does Letter 3 feel firm without being punitive?
- Are the placeholders consistent across all three?

---

<!-- _class: debrief -->

## Exercise 8: What You Learned

### Key takeaways

- AI calibrates **tone across a series** — warm → concerned → formal
- Placeholder-based outputs become **reusable templates** for your school
- The escalation pattern works for any graduated communication: fees, behaviour, compliance

### The principle

> AI handles **tone as a variable** — you specify the register, AI writes to match. This works across any communication series.

### Try this at work

- Save the three letters as templates — replace placeholders with real details each time
- Adapt the pattern for fee reminders, behaviour follow-ups, or compliance notices
- Always review the tone with a colleague before sending — especially Letter 3

---

<!-- _class: theory -->

## AI as Error Detector

### The theory: checking, not just creating

- Most people think of AI as a **generator** — it writes, drafts, and creates
- But AI is equally powerful as a **checker** — it spots errors humans miss
- Watching AI find a date that falls on a Saturday or a clash with NAPLAN is genuinely surprising

### What this exercise demonstrates

- AI catches logical errors (wrong day-of-week, double-bookings, holiday clashes)
- It brings **external knowledge** (public holidays, exam schedules) to verify your data
- The meta-lesson: use AI for **verification**, not just creation

---

<!-- _class: exercise -->

## Exercise 9: Spot the Error — Calendar Checker

### Instructions (10 minutes)

1. Open the **Draft Term 2 Calendar** from your handout (Artifact 08)
2. Paste your context card, then the calendar, then add:

> *Here is our draft Term 2 calendar for a Victorian secondary school. Check it for:*
> *1. Any dates where the day-of-week does not match the actual calendar*
> *2. Clashes with known Victorian public holidays*
> *3. Events double-booked on the same day*
> *4. NAPLAN scheduling issues*
> *5. Any other errors or concerns you notice*

3. Compare AI's findings to your own reading — did you spot the same errors?

### What to check

- Does AI catch the **NAPLAN day-of-week error** (Tue 13 May labelled Wednesday)?
- Does it spot the **double-booked** Wed 7 May?
- Does it flag the Queen's Birthday date issue?

---

<!-- _class: debrief -->

## Exercise 9: What You Learned

### Key takeaways

- AI is an excellent **proofreader for structured data** — dates, schedules, timetables
- It cross-references against external facts (public holidays, exam windows)
- The exercise shifts your mental model: AI is a **checker** as much as a creator

### The principle

> AI catches errors in structured data that tired eyes miss. Use it to **verify** calendars, timetables, and event schedules before publishing.

### Try this at work

- Paste your term planner or event calendar into AI before it goes to print
- Ask AI to check for weekend clashes, holiday conflicts, and double-bookings
- This takes 30 seconds and can prevent embarrassing published errors

---

<!-- _class: theory -->

## From Chaos to Structure

### The theory: extracting structured data from messy text

- Admin staff regularly receive information in **inconsistent formats** — different suppliers, different layouts, different terminology
- Manually copying numbers from emails into spreadsheets is tedious and error-prone
- AI excels at **parsing, normalising, and comparing** unstructured text

### What this exercise demonstrates

- AI extracts structured data from three different messy formats into one clean table
- It normalises inconsistencies (different pack sizes, GST handling, missing items)
- The comparison table becomes an **immediate decision tool**

---

<!-- _class: exercise -->

## Exercise 10: Vendor Quote Comparison

### Instructions (10 minutes)

1. Open the **Three Vendor Quotes** from your handout (Artifact 09)
2. Paste your context card, then all three quotes, then add:

> *Here are quotes from three suppliers for office stationery. They arrived in different formats. Please:*
> *1. Create a comparison table: Item, OfficePro price, SchoolSupply price, Aussie Ed price (all inc GST)*
> *2. Normalise pack sizes — note where quantities differ*
> *3. Highlight the cheapest option for each item*
> *4. Flag any items missing from a supplier*
> *5. Calculate the total cost from each supplier (including delivery)*

3. Check the AI's arithmetic — are the GST calculations correct?

### What to check

- Does AI handle the **mixed GST formats** (ex-GST vs inc-GST)?
- Does it flag the **different pack sizes** (8-pack vs 10-pack markers)?
- Does it note the **missing glue sticks** from Aussie Ed?

---

<!-- _class: debrief -->

## Exercise 10: What You Learned

### Key takeaways

- AI turns **messy, inconsistent supplier data** into a clean comparison in seconds
- It flags differences in pack sizes and missing items that you might overlook
- Always verify GST calculations — AI sometimes confuses ex-GST and inc-GST pricing

### The principle

> AI extracts structure from chaos. Three different formats become one clean table — but **you verify the numbers** before making a decision.

### Try this at work

- Use this pattern for any supplier comparison, quote evaluation, or price check
- Works equally well for comparing insurance quotes, contractor proposals, or service agreements
- Always double-check the arithmetic — paste the AI table into a spreadsheet for verification

---

<!-- _class: break-slide -->
<!-- _paginate: false -->

# Lunch

Back at 1:30

---

<!-- _class: lead -->

# Block 3: Safety, Privacy and Your Plan

1:30 - 3:00

---

## Safety and Privacy in Schools

### The golden rules of AI in a school context

- **Never enter real student names** or identifying information into AI tools
- **Never enter sensitive data** — incident details, medical information, family circumstances
- Use **student IDs or pseudonyms** when you need to work with real scenarios
- AI tools are **cloud services** — anything you type may be stored and used for training

### What you CAN safely do

- Draft templates with **placeholders** (as we have done today)
- Summarize **de-identified** data
- Generate **generic** communications and adapt them locally
- Ask for **process advice** without sharing real cases

> When in doubt, ask: "Would I be comfortable if this text appeared in a newspaper?"

---

## AI Quality Control

### Your checking checklist

Every piece of AI output should be checked for:

| Check | What to look for |
|-------|-----------------|
| **Accuracy** | Are facts, dates, and figures correct? |
| **Tone** | Does it sound like your school (not a corporate robot)? |
| **Completeness** | Has anything important been left out? |
| **Appropriateness** | Is this suitable for the intended audience? |
| **Privacy** | Does it contain any identifying information it should not? |

### Remember

- AI is **confidently wrong** — it never says "I am not sure"
- The first draft is rarely the final draft
- Your local knowledge is what makes AI output **useful** rather than generic

---

## Your AI Toolkit

### Free tools to start with today

| Tool | Best for | Access |
|------|----------|--------|
| **ChatGPT** | General writing, brainstorming, email drafting | chat.openai.com |
| **Microsoft Copilot** | If your school uses Microsoft 365 | copilot.microsoft.com |
| **Google Gemini** | If your school uses Google Workspace | gemini.google.com |
| **Claude** | Long documents, nuanced writing, analysis | claude.ai |

### Tips for choosing

- If your school is a **Microsoft school** — start with Copilot
- If your school is a **Google school** — start with Gemini
- For **general purpose** (any school) — ChatGPT or Claude
- Use your **context card** with any tool

---

## Action Planning

### Your personal AI action plan

Take 5 minutes to write down:

**This week I will:**
- Try one exercise from today on a **real task** at work
- Which exercise? _______________
- What task? _______________

**This month I will:**
- Share one AI technique with a **colleague**
- Set up my **context card** on my preferred AI tool
- Try AI for a task I currently find **tedious or time-consuming**

**My biggest insight from today:**
- _______________

> The best way to learn AI is to **use it on real work, this week**

---

## Resources and Next Steps

### Keep learning

- **Your context card** — paste it at the start of every AI conversation
- **Prompt pack** — today's exercise prompts are in your handout, ready to reuse
- **Data pack** — the Marraburra fictional data is yours to practice with

### Helpful starting prompts for any task

- "I am a [role] at a [type of school]. I need to [task]. Please [specific output]."
- "Rewrite this for [audience] in [tone]."
- "Summarize this and give me action items."
- "Create a template with placeholders I can reuse."

### Real Minds AI

- Website: realmindsai.com.au
- Contact: hello@realmindsai.com.au

---

<!-- _class: lead -->
<!-- _paginate: false -->

# Thank You

**Tracy Anthony** and **Dr Dennis Wollersheim**
Real Minds AI

hello@realmindsai.com.au | realmindsai.com.au

*wisdom, amplified*
