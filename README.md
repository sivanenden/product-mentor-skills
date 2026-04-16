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

3. Add this to your `~/.claude/CLAUDE.md`:
cat > ~/product-mentor-skills/README.md << 'EOF'
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

3. Add this to your `~/.claude/CLAUDE.md`:
cd ~/product-mentor-skills
git init
git add .
git commit -m "Initial commit: 8 product mentor skills for Claude Code"
git remote add origin https://github.com/sivanenden/product-mentor-skills.git
git branch -M main
git push -u origin main
cd ~/product-mentor-skills
git remote add origin https://github.com/sivanenden/product-mentor-skills.git
git branch -M main
git push -u origin main
