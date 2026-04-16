# Product Mentor Skills for Claude Code

A library of mentor personas for product leaders, built as Claude Code skills.

Each mentor can be loaded in any Claude Code project to get advice, feedback, and coaching in that person's voice and framework.

## Mentors Included

| Mentor | Expertise |
|---|---|
| Marty Cagan | Product leadership, empowered teams, discovery |
| Shreyas Doshi | Product execution, prioritization, time management |
| Julie Zhuo | Managing teams, feedback, hiring, people leadership |
| Jeffrey Pfeffer | Corporate politics, power, organizational influence |
| Strategy (Roger Martin + Hamilton Helmer) | Business strategy, competitive advantage, where to play |
| Teresa Torres | Customer discovery, continuous research, opportunity solution tree |
| Brian Balfour | Product growth, retention, monetization, growth loops |
| Nancy Duarte | Executive communication, storytelling, presentations |

## Installation

1. Create the skills folder:
```bash
mkdir -p ~/.claude/skills/mentors
```

2. Copy all mentor files:
```bash
cp mentors/*.md ~/.claude/skills/mentors/
```

3. Add this to your ~/.claude/CLAUDE.md:
4. Optionally register slash commands — see each mentor file for suggested command names.

## How to Use

By name:
- "Review my PRD as Marty Cagan"
- "What would Shreyas say about my roadmap?"
- "Ask Jeffrey Pfeffer about this situation"

By category:
- "Check for product execution"
- "Help me with managing teams"
- "Review my strategy"
- "Help me with corporate politics"

By slash command:
- /mentor-leadership
- /mentor-execution
- /mentor-teams
- /mentor-politics
- /mentor-strategy
- /mentor-discovery
- /mentor-growth
- /mentor-communication

## Contributing

Found a mentor worth adding? Open a PR with a new skill file following the same structure.

## Credits

Built by [Sivan Yaron-Enden](https://www.linkedin.com/in/sivanenden/)
