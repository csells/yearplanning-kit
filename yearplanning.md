# /yearplanning - Annual Planning Ceremony

Set strategic direction for the year through structured reflection, capacity mapping, goal definition, and stress-testing via a simulated Board of Directors.

## Overview

This ceremony guides you through annual planning in 5 phases:
1. **Context Gathering** - Review previous year, current state
2. **Capacity Mapping** - Map known time commitments for realistic planning
3. **Open-Mind Intentions** - Reflective interview to surface authentic desires
4. **Big Rocks Definition** - Define 3-4 major goals with slogans and outcomes
5. **Board Simulation** - Stress-test your plan through diverse perspectives

**Duration:** 3-5 hours across 1-2 sessions. Phase 4 (Board) typically runs 90-120 min.

---

## Session Startup

### Gather Personal Context

Before beginning, collect context that will inform the planning process.

```
ASK USER (via AskUserQuestion):

1. "What are your 2-4 core values that guide major decisions?"
   - Options: [Provide my values, Skip - use example values]

2. "Do you have a 3-5 year vision or life direction statement?"
   - Options: [Yes - I'll share it, No vision statement, Skip]

3. "What identity pillars or roles define who you want to be?"
   - Example: "Builder, Leader, Partner, Creator"
   - Options: [Provide my pillars, Skip - use examples]

4. "Do you have notes from last year's planning or review to reference?"
   - Options: [Yes - I'll paste/share them, No - start fresh]
```

**If user skips:** Use these example frameworks to demonstrate the process:
- Example values: Authenticity, Growth, Impact, Balance
- Example pillars: Builder, Thinker, Partner
- Example vision: "Build sustainable income through meaningful work while prioritizing health and relationships"

Store responses in: `year-[YYYY]-planning/00-personal-context.md`

---

## Working Files

All session progress stored in: `year-[YYYY]-planning/`

Create directory at session start. Files created during session:
- `00-personal-context.md` - Values, vision, pillars from startup
- `01-context-summary.md` - Previous year review, current state
- `02-preloaded-year.md` - Capacity analysis
- `03-intentions.md` - Interview notes, Destination Postcard
- `04-big-rocks.md` - Rock candidates, selection, outcomes
- `05-board-simulation.md` - Challenge responses, refinements
- `06-final-plan.md` - Completed annual plan

---

## Phase 1: Context Gathering (~15-20 min)

**Facilitation:** Review and synthesis

**Purpose:** Ground the planning in reality - what happened, what exists.

```
FRAME:
"Let's review where you're coming from before planning where you're going."

1. PREVIOUS YEAR REVIEW
   "Looking back at [YYYY-1]:

   What were your major goals or intentions?
   [If user has notes, review them. If not, reconstruct from memory]

   What did you achieve?
   What fell short?
   What surprised you?"

2. CURRENT COMMITMENTS
   "What's already on your plate?

   Active projects or initiatives:
   - [List what user mentions]

   Ongoing responsibilities (areas of life requiring maintenance):
   - [List areas: work, family, health, etc.]

   For each: Continue as-is, Rescope, or Wind down?"

   [Triage each explicitly]

3. EXTERNAL CONTEXT
   "Any major external factors affecting next year?
   - Market/industry changes?
   - Life transitions (moves, family changes)?
   - Known opportunities or threats?"
```

**Capture to `01-context-summary.md`**

---

## Phase 2: Pre-loaded Year Capacity (~20-30 min)

**Facilitation:** Interview style, practical, documenting

**Purpose:** Map known time commitments to create realistic capacity picture.

```
FRAME:
"Let's map out the year's capacity. I'll walk through known commitments
to calculate realistic working days per quarter."

1. PUBLIC HOLIDAYS
   "What public holidays affect your work capacity?
   [Ask user's country/region, then research or ask them to list]

   Which of these actually impact your availability?"

2. SCHOOL/FAMILY CALENDAR (if applicable)
   "Do school vacations or family schedules affect your work rhythm?

   - Winter/spring break periods?
   - Summer vacation expectations?
   - Fall breaks?
   - Holiday season (Dec)?

   Mark periods of reduced capacity."

3. PLANNED TIME OFF
   "What vacation time is planned or intended?

   - Summer plans?
   - Other trips or getaways?
   - Family events (weddings, graduations, etc.)?"

4. FIXED PROFESSIONAL COMMITMENTS
   "Known work commitments with fixed dates?

   - Conferences or industry events?
   - Board meetings or reviews?
   - Contract milestones?
   - Recurring obligations?"

5. ENERGY SEASONS
   "Looking at the year's shape, where do you anticipate:
   - High energy periods?
   - Recovery/low periods?
   - Crunch times?

   Q1 (Jan-Mar): [user input]
   Q2 (Apr-Jun): [user input]
   Q3 (Jul-Sep): [user input]
   Q4 (Oct-Dec): [user input]"
```

**Capture to `02-preloaded-year.md`:**

```markdown
# Pre-loaded Year [YYYY]

## Capacity by Quarter

| Quarter | Months | Est. Working Days | Energy Season |
|---------|--------|-------------------|---------------|
| Q1 | Jan-Mar | ~[X] | [pressure/recovery/neutral] |
| Q2 | Apr-Jun | ~[X] | [pressure/recovery/neutral] |
| Q3 | Jul-Sep | ~[X] | [pressure/recovery/neutral] |
| Q4 | Oct-Dec | ~[X] | [pressure/recovery/neutral] |
| **YEAR** | | ~[X] total | |

## Time Off & Reduced Capacity
- [Date range]: [Description]

## Fixed Commitments
- [Date]: [Event]

## Energy Notes
- Q1: [Notes]
- Q2: [Notes]
- Q3: [Notes]
- Q4: [Notes]
```

---

## Phase 3: Open-Mind Intentions (~20-30 min)

**Facilitation:** Reflective interview, exploratory, no judgment

**Purpose:** Surface authentic desires and motivations before goal-setting.

```
GROUNDING:
"Before we plan, let's ground in what matters.

FROM YOUR CONTEXT:
- Values: [from startup or examples]
- Vision: [from startup or examples]
- Identity pillars: [from startup or examples]

LAST YEAR'S JOURNEY:
[1-2 sentence arc from Phase 1]"

INTERVIEW:

1. LOOKING BACK
   "What from [YYYY-1] are you most proud of?"
   [Listen, capture]

   "What do you wish you had done differently?"
   [Listen, capture]

   "What lessons are you carrying forward?"
   [Listen, capture]

2. LOOKING FORWARD
   "What's calling to you for [YYYY]? What feels exciting?"
   [Listen, capture]

   "What feels heavy or obligatory? What would you drop if you could?"
   [Listen, capture]

   "Any fears or concerns about the year ahead?"
   [Listen, capture]

3. DESTINATION POSTCARD
   "Imagine it's December 31, [YYYY]. You're feeling deeply satisfied.

   Describe that moment:
   - What's true?
   - What did you accomplish?
   - What does your life look like?"

   [Capture vivid description - this becomes the mission foundation]

4. BALANCE CHECK
   "What does balance look like for you this year?"
   [Listen, capture]

   "Where do you need more of something? Less of something?"
   [Listen, capture]
```

**Capture to `03-intentions.md`:**

```markdown
# Year [YYYY] Intentions

## Looking Back at [YYYY-1]
### Proud of:
- [item]

### Would do differently:
- [item]

### Lessons carrying forward:
- [item]

## Looking Forward
### What's calling/exciting:
- [item]

### What feels heavy/would drop:
- [item]

### Fears/concerns:
- [item]

## Destination Postcard
[Vivid paragraph describing Dec 31 satisfaction]

## Balance Needs
### More of:
- [item]

### Less of:
- [item]
```

---

## Phase 4: Big Rocks Definition (~30-40 min)

**Facilitation:** Goal-oriented, iterative, structured

**Purpose:** Translate intentions into 3-4 Big Rocks with memorable slogans, measurable outcomes, and value statements.

```
FRAME:
"Big Rocks are the major goals that, if achieved, would make the year
successful. Maximum 3-4 total.

Key principles:
- Outcome-based, NOT project-specific
- Each needs: slogan + outcome + value statement
- Slogans designed for weekly re-reading

Working days available: ~[X]
Energy pattern: [summary from Phase 2]"

PROCESS:

1. BRAINSTORM CANDIDATES
   "Based on your intentions and Destination Postcard, what are candidate
   Big Rocks? List all possibilities, don't filter yet."

   [Capture 5-10 candidates]

2. CONSOLIDATE TO OUTCOMES
   "Let's reframe any project-specific items as outcome-based.

   X Project-specific: 'Launch Product X'
   OK Outcome-based: 'Validated revenue stream generating $X/month'

   For outcomes with multiple paths, use sub-items:"

   Example:
   "Financial security achieved"
   (a) Through new job
   (b) Through freelance revenue
   (c) Through combination

3. SPLIT PROFESSIONAL / PERSONAL
   "Separate into Professional (PRO) and Personal (PRI) rocks.

   Some may span both - the split is for prioritization, not rigid categories."

   [Tag each: PRO1, PRO2, PRO3... PRI1, PRI2, PRI3...]

4. ADD VALUE STATEMENTS
   "For each rock: Why does this matter beyond the outcome?
   Connect to your values. This creates emotional resonance for weekly re-reading."

   [Capture value statement for each rock]

5. DRAFT SLOGANS
   "Create a slogan for each rock:
   - Memorable, re-readable weekly
   - Value-oriented, not just 'do X'
   - Under 10 words

   This takes iteration - we'll refine these."

   Good examples:
   - "Secure the runway, choose authentically"
   - "Build in service, not in silence"
   - "Team Us - together after the storm"

   Weak examples (avoid):
   - "Get a good job" - too generic
   - "Ship MVP by Q2" - too specific, not value-oriented
   - "Improve health" - vague, not memorable

   [Draft initial slogans, expect 2-3 iteration rounds]

6. FORCE RANK (after slogans are solid)
   "Now force rank. If you could only achieve ONE thing this year:

   Professional: Which one?"
   [Capture PRO #1, then #2, then #3]

   Personal: Which one?"
   [Capture PRI #1, then #2, then #3]

7. DOCUMENT CONSOLIDATED OUT
   "What candidates did we NOT select? Capture with reasons.
   This validates the process and provides quarterly review reference."

   [List items with rationale]
```

**Capture to `04-big-rocks.md`:**

```markdown
# Year [YYYY] Big Rocks

## Rock Table

| Key | Slogan | Outcome | Value |
|-----|--------|---------|-------|
| PRO1 | "[slogan]" | [outcome] | [why it matters] |
| PRO2 | "[slogan]" | [outcome] | [value] |
| PRO3 | "[slogan]" | [outcome] | [value] |
| PRI1 | "[slogan]" | [outcome] | [value] |
| PRI2 | "[slogan]" | [outcome] | [value] |

## Force Ranking

### Professional
1. [PRO key] - "If only ONE professional thing"
2. [PRO key] - "If only TWO"
3. [PRO key] - "If only THREE"

### Personal
1. [PRI key] - "If only ONE personal thing"
2. [PRI key] - "If only TWO"

## Consolidated Out
| Candidate | Reason Not Selected |
|-----------|---------------------|
| [item] | [rationale] |
```

---

## Phase 5: Board Simulation (~90-120 min)

**Facilitation:** Dynamic deliberation, multiple rounds, REQUIRED

**Purpose:** Stress-test the plan through diverse perspectives before committing.

**IMPORTANT:** This phase is not optional. The Board simulation surfaces blind spots and tensions that would otherwise emerge mid-year. Expect 3-6 deliberation rounds.

### Board Composition

| Role | Name | Lens | Focus |
|------|------|------|-------|
| Chairman | The Coordinator | Process, synthesis | Runs meeting, asks hard questions |
| Strategist | The Architect | Long-term vision | Opportunity cost, 3-5yr alignment |
| Wellbeing | The Guardian | Sustainability | Family, health, balance |
| Growth | The Catalyst | Ambition | Learning edge, boldness |
| Finance | The Realist | Resources | Cash, runway, timing |
| Mentor | The Sage | Inner wisdom | Alignment, self-knowledge |

### The Sage (Internal Lens)

The Sage provides the only *internal* lens, balancing the external perspectives.

**Core question:** "Does this plan honor who you actually are, or who you think you should be?"

**Philosophical grounding:**
- Acceptance, non-attachment to outcome
- Pattern recognition over prescription
- Lived experience as teacher
- Clarity emerges retrospectively

**Key questions The Sage asks:**

| Question | Planning Implication |
|----------|---------------------|
| "Which rocks feel like 'yes' vs obligation?" | Are these authentic desires or constructed shoulds? |
| "Have these priorities had an emotional cycle?" | Plans made today may feel different tomorrow |
| "Where does willpower compensate for misalignment?" | Sustainable goals flow with your nature |
| "What's being avoided vs chosen?" | Sometimes what we don't say matters most |

### Deliberation Structure

```
FRAME:
"Before we commit, let's stress-test this plan. I'll simulate your board:

EXTERNAL LENSES:
- THE ARCHITECT (Strategist): Long-term alignment, opportunity cost
- THE GUARDIAN (Wellbeing): Family, health, sustainability
- THE CATALYST (Growth): Learning, pushing boundaries
- THE REALIST (Finance): Resources, runway, timing

INTERNAL LENS:
- THE SAGE (Mentor): Inner alignment, patterns, self-knowledge

THE COORDINATOR (Chairman): Facilitates, synthesizes, asks hard questions

This is a board deliberation - they'll discuss among themselves, request
information, and surface tensions before challenging you directly."

---

ROUND 1: INITIAL DELIBERATION

COORDINATOR:
"Board, we're reviewing the Year [YYYY] plan.

Mission direction: [from Destination Postcard]
Big Rocks:
1. [Rock with slogan and outcome]
2. [Rock with slogan and outcome]
3. [Rock with slogan and outcome]
Capacity: ~[X] working days

Your initial perspectives?"

[Board members converse organically - agree, disagree, build on each other]
[Board may request facts/numbers from CEO (the user)]

COORDINATOR:
"[Synthesizes discussion into 2-3 questions for CEO]"

[CEO (user) responds]

---

ROUND 2+: DEEPER PROBING

[Board responds to CEO's answers]
[The Sage may request introspection or felt-sense reporting]
[Additional fact requests if needed]

Continue until:
- Consensus emerges
- Tensions are acknowledged (even if unresolved)
- 3-6 rounds complete

COORDINATOR should ask: "Is there an organizing principle that unifies these rocks?"
(This becomes the "through-line")

---

FINAL ROUND: SYNTHESIS

Each board member provides:
- Final statement (1-2 paragraphs)
- 3-5 Do's
- 3-5 Don'ts

COORDINATOR:
"Board recommendation: [Proceed / Revise X / Add consideration Y]

Points of alignment: [list]
Tensions resolved: [list]
Tensions acknowledged but unresolved: [list]

Through-line: [organizing principle if emerged]"
```

### Information The Board Should Request

- **Facts:** "What's your actual runway in months?"
- **Numbers:** "Current revenue/savings figures?"
- **Intentions:** "If forced to choose between A and B?"
- **History:** "What happened last time you tried X?"
- **Constraints:** "What's the hard limit on Y?"

### Concepts That May Surface

- **Lynchpins:** Variables that fork the year's trajectory
- **Core Frictions:** Tensions requiring ongoing management
- **Win Calibration:** "Start of win" vs "Definite win" per domain
- **Through-Line:** Organizing principle unifying all rocks

**Capture to `05-board-simulation.md`:**

```markdown
# Board Simulation - Year [YYYY]

## Plan Presented
- Mission: [summary]
- Big Rocks: [list with slogans]
- Capacity: [X] days

## Round 1
### Board Deliberation
[Key points from each voice]

### Information Requested
- [Question]: [CEO answer]

### Chairman Questions
1. [Question]
2. [Question]

### CEO Response
[Summary]

## Round 2-N
[Same structure for each round]

## Final Round: Board Statements

### The Architect
**Statement:** [1-2 paragraphs]
**Do's:** [3-5 items]
**Don'ts:** [3-5 items]

### The Guardian
[Same structure]

### The Catalyst
[Same structure]

### The Realist
[Same structure]

### The Sage
[Same structure]

## Chairman Synthesis
**Aligned:** [points]
**Tensions resolved:** [points]
**Tensions acknowledged:** [points]
**Through-line:** [organizing principle]

## Board Recommendation
[Proceed / Revise X / Add Y]

## Adjustments Made
- [Changes from original plan]
```

---

## Phase 6: Final Commit

**Facilitation:** Summary, confirmation, documentation

**Compile final plan to `06-final-plan.md`:**

```markdown
# Year [YYYY] Plan

## Through-Line
[Organizing principle from board simulation]

## Mission Statement
[1-2 sentences from Destination Postcard + board refinement]

## Big Rocks

### PRO1: [Title]
**Slogan:** "[slogan]"
**Outcome:** [measurable result]
**Value:** [why it matters]
**Paths:** (a) [option] (b) [option] (c) [option]

### PRO2: [Title]
[Same structure]

### PRI1: [Title]
[Same structure]

[Continue for all rocks]

## Capacity Overview
- Total working days: ~[X]
- Q1: ~[X] days ([energy season])
- Q2: ~[X] days ([energy season])
- Q3: ~[X] days ([energy season])
- Q4: ~[X] days ([energy season])

## Lynchpins
[Variables that fork the year's trajectory]

## Win Conditions
| Domain | Start of Win | Definite Win |
|--------|--------------|--------------|
| [domain] | [threshold] | [target] |

## Board Guidance Summary
### Do's
- [item]

### Don'ts
- [item]

## Core Frictions (Ongoing Tensions)
- [tension]: [how to manage]

## Quarter Kickoff Notes

### Q1
- Focus rocks: [list]
- Capacity: ~[X] days
- Energy: [season note]
- Initial focus: [context]

### Q2-Q4
[Same structure]
```

**Present for confirmation:**
```
"Here's your Year [YYYY] Plan:

THROUGH-LINE: [organizing principle]

MISSION: [statement]

BIG ROCKS:
1. [Rock]: [outcome]
2. [Rock]: [outcome]
3. [Rock]: [outcome]

CAPACITY: ~[X] working days

Ready to finalize?"
```

**On confirmation:**
- Save final plan
- Offer to clear working files (keep or archive)
- Suggest next step: "Ready for Q1 planning? Create a quarterly planning session."

---

## Session Notes

### Duration Expectations
- Full ceremony: 3-5 hours
- Can span 1-2 days (Phase 5 often needs a break)
- Board Simulation (Phase 5): 90-120 minutes alone

### File Management
- All work in `year-[YYYY]-planning/` directory
- Files persist across session breaks
- Final plan is the deliverable; working files can be archived or deleted

### Phase Requirements
- Board simulation is REQUIRED (not optional)
- Destination Postcard is a tool (use if helpful)
- Maximum 3-4 Big Rocks (prefer 3)
- Each rock needs: slogan + outcome + value statement

### Common Pitfalls
- Rushing slogan iteration (they need refinement)
- Skipping board simulation (it catches blind spots)
- Project-specific rocks instead of outcome-based
- Too many rocks (3 is better than 6)
- Generic slogans that won't resonate weekly
