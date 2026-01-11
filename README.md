# Year Planning Kit

A structured annual planning ceremony for Claude Code.

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

## Compatibility

This kit is configured for **Claude Code v2.1.4+** with:
- YAML frontmatter for command configuration
- Pre-configured tool permissions for uninterrupted planning sessions
- Automatic year detection based on current date

## Setup

### Quick Start (Recommended)

1. Clone or download this repository
2. Open the directory in Claude Code:
   ```bash
   cd yearplanning-kit
   claude
   ```
3. Run the command:
   ```
   /yearplanning
   ```

The command is pre-configured with:
- Proper YAML frontmatter for Claude Code v2.1.4
- Tool permissions in `settings.local.json` for uninterrupted flow
- Automatic planning year inference

### Manual Setup (Add to Existing Project)

1. Copy `.claude/commands/yearplanning.md` to your project's `.claude/commands/` directory

2. Optionally add these permissions to your `.claude/settings.local.json`:
   ```json
   {
     "permissions": {
       "allow": [
         "Bash(mkdir *)",
         "Write(year-*-planning/*)",
         "Edit(year-*-planning/*)",
         "Read(year-*-planning/*)"
       ]
     }
   }
   ```

3. Run `/yearplanning` in your Claude Code session

## What You'll Need

### Before Starting
- **2-4 hours** - Can span multiple sessions
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
- Capacity mapping can be simplified if detailed scheduling isn't your style
- The Destination Postcard is optional but powerful for mission clarity

## Tips

1. **Don't rush the slogans** - They need 2-3 iteration rounds to resonate
2. **Board simulation is required** - It catches blind spots you won't see alone
3. **Outcome-based, not project-based** - "Validated revenue stream" not "Launch Product X"
4. **3 rocks is better than 6** - Focus beats ambition
5. **Take breaks** - Phase 5 benefits from a pause to let ideas settle

## Project Structure

```
yearplanning-kit/
├── .claude/
│   ├── commands/
│   │   └── yearplanning.md    # The planning ceremony command
│   └── settings.local.json    # Pre-configured permissions
└── README.md
```

## Credits & Inspiration

This methodology synthesizes several frameworks into a cohesive planning ceremony.

### Core Concepts

| Concept | Source | How It's Used Here |
|---------|--------|-------------------|
| **Big Rocks** | Stephen Covey (origin), Dan Martell (application) | Year-level priorities with slogans and outcomes |
| **Pre-loaded Year** | Dan Martell | Capacity mapping before setting goals |
| **Destination Postcard** | Chip & Dan Heath, *Switch* | Year-end visualization exercise |
| **Board Simulation** | Nate B. Jones, Andrej Karpathy | Virtual advisory board stress-testing |
| **PARA** | Tiago Forte | Referenced for current commitments review |
| **Slow Productivity** | Cal Newport | Do fewer things, work at natural pace |

### Original Contributions

- **The Sage** as internal-lens board member
- **Through-Line** as emergent organizing principle
- **Slogan + Outcome + Value** structure for Big Rocks
- **Force ranking** as late-stage prioritization
- Integration of reflective interview with structured goal-setting

### License

Share freely. No attribution required, but appreciated.
