# Year Planning Kit

A structured annual planning ceremony for Claude Code (or any Claude session).

## What This Is

A methodology for annual planning that guides you through:
1. **Context review** - Reflect on the previous year
2. **Capacity mapping** - Calculate realistic working days
3. **Open-mind interview** - Surface authentic desires (not just obligations)
4. **Big Rocks definition** - Define 3-4 major goals with memorable slogans
5. **Board of Directors simulation** - Stress-test your plan through 6 diverse perspectives

The Board simulation is the core differentiator. Instead of just setting goals, you'll have a virtual advisory board challenge your thinking:
- **The Architect** (Strategist) - Long-term vision alignment
- **The Guardian** (Wellbeing) - Sustainability and balance
- **The Catalyst** (Growth) - Ambition and learning
- **The Realist** (Finance) - Resources and timing
- **The Sage** (Mentor) - Inner alignment and self-knowledge
- **The Coordinator** (Chairman) - Synthesis and hard questions

## Setup

### Option A: As a Slash Command (Recommended)

1. Create the commands directory in your project:
   ```bash
   mkdir -p .claude/commands
   ```

2. Copy `yearplanning.md` to `.claude/commands/yearplanning.md`

3. Start a Claude Code session and run:
   ```
   /yearplanning
   ```

### Option B: Paste into Any Claude Session

1. Start a new Claude session (Claude.ai, API, etc.)
2. Paste the contents of `yearplanning.md` as your first message
3. Ask Claude to guide you through the ceremony

## What You'll Need

### Before Starting
- **2-4 hours** - Can span multiple sessions
- A text editor or notes app for working files
- Optionally: notes from last year's planning or review

### During the Session
Claude will ask for:
- Your core values (2-4 guiding principles)
- Your vision or life direction (optional)
- Identity pillars (who you want to be)
- Previous year context (achievements, lessons)

If you skip the personalization, example values are used to demonstrate the process.

## Output

The ceremony produces:
- `year-[YYYY]-planning/06-final-plan.md` - Your completed annual plan
- Working files from each phase (can be deleted after)

Your final plan includes:
- **Through-line** - Organizing principle for the year
- **Mission statement** - 1-2 sentence direction
- **Big Rocks** - 3-4 major goals with slogans, outcomes, and values
- **Capacity overview** - Realistic working days by quarter
- **Board guidance** - Do's and Don'ts from the simulation
- **Quarter kickoff notes** - Initial context for Q1-Q4 planning

## Customization

### Modifying the Board
The board members in Phase 5 can be adjusted. Some variations:
- Add a **Technical Advisor** for builder-heavy plans
- Replace **The Realist** with a **Risk Manager** for non-financial contexts
- Adjust **The Sage's** philosophical grounding to match your worldview

### Adjusting Phases
- Phase 0.5 (PARA alignment) was removed from this export but can be added if you use a PARA system
- Capacity mapping can be simplified if detailed scheduling isn't your style
- The Destination Postcard is optional but powerful for mission clarity

## Tips

1. **Don't rush the slogans** - They need 2-3 iteration rounds to resonate
2. **Board simulation is required** - It catches blind spots you won't see alone
3. **Outcome-based, not project-based** - "Validated revenue stream" not "Launch Product X"
4. **3 rocks is better than 6** - Focus beats ambition
5. **Take breaks** - Phase 5 benefits from a pause to let ideas settle

## Credits & Inspiration

This methodology synthesizes several frameworks into a cohesive planning ceremony. Understanding the sources helps you adapt the process to your needs.

### Core Concepts

| Concept | Source | How It's Used Here |
|---------|--------|-------------------|
| **Big Rocks** | [Stephen Covey](https://www.franklincovey.com/courses/the-5-choices/choice-3/) (origin), [Dan Martell](https://www.youtube.com/@danmartell) (application) | Year-level priorities with slogans and outcomes. "Put the big rocks in first—they won't fit later." |
| **Pre-loaded Year** | [Dan Martell](https://www.youtube.com/@danmartell) | Capacity mapping: holidays, commitments, energy seasons laid out before setting goals. Reality check prevents overcommitment. |
| **Destination Postcard** | [Chip & Dan Heath, *Switch*](https://heathbrothers.com/books/switch/) | Year-end visualization exercise. "Write a postcard from future you" describing satisfaction and achievement. |
| **Board Simulation** | [Nate B. Jones](https://sloanreview.mit.edu/article/how-i-built-a-personal-board-of-directors-with-genai/), [Andrej Karpathy](https://karpathy.ai/) | Virtual advisory board stress-testing your plan through diverse perspectives. |
| **PARA** | [Tiago Forte](https://fortelabs.com/blog/para/) | Projects, Areas, Resources, Archive. Referenced in Phase 1 for current commitments review. |
| **Slow Productivity** | [Cal Newport](https://calnewport.com/my-new-book-slow-productivity/) | Philosophical grounding: do fewer things, work at natural pace, obsess over quality. |

### Framework Compatibility

This ceremony works well with:
- **PARA** (Tiago Forte) - For organizing projects and areas
- **GTD** (David Allen) - For capturing and processing tasks after planning
- **OKRs** - Big Rocks can be expressed as Objectives with Key Results
- **12 Week Year** - Quarterly planning follows similar milestone logic
- **Human Design** - The Sage board member can incorporate HD insights

### Original Contributions

Elements developed specifically for this ceremony:
- **The Sage** as internal-lens board member (balancing external perspectives)
- **Through-Line** as emergent organizing principle
- **Slogan + Outcome + Value** structure for Big Rocks
- **Force ranking** as late-stage prioritization (after rocks are well-defined)
- Integration of reflective interview with structured goal-setting

### License

Share freely. No attribution required, but appreciated.
