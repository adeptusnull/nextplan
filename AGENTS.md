# AGENTS.md

Instructions for AI coding assistants (Claude Code, Cursor, Copilot, etc.) working with this repository.

## Project Overview

**NextPlan** is a knowledge base documenting ADHD-friendly productivity systems. It contains methodology documentation, implementation guides, and templates—not application code.

## Repository Structure

```
nextplan/
├── README.md           # Project overview and navigation
├── AGENTS.md           # This file - AI assistant instructions
└── docs/               # Documentation directory
    └── *.md            # Productivity system documentation
```

## Content Guidelines

### Documentation Style

- Use **clear, structured markdown** with headers, lists, and tables
- Include **practical implementation guides** (spreadsheet, Notion, bullet journal)
- Provide **scientific backing** where relevant (neuroscience, psychology)
- Write for readers who may have ADHD—keep sections scannable
- Use **bold** for key terms on first introduction
- Include **tables** for comparisons
- Add **code blocks** for templates and structures

### Document Structure

Each productivity system document should include:

1. **Executive Summary** — Quick overview of the system
2. **Core Philosophy** — Underlying principles
3. **How It Works** — Step-by-step methodology
4. **Implementation Methods** — Practical guides for various tools
5. **Key Takeaways** — Summary and actionable insights
6. **Resources** — Links and references

### Formatting Standards

```markdown
# System Name

**Complete Review & Implementation Guide**

Based on: [Source]

---

## Table of Contents
[Auto-generated or manual TOC]

## Executive Summary
[2-3 paragraphs max]

## Core Philosophy
### Principle 1
### Principle 2

## How It Works
### Component 1
### Component 2

## Implementation Methods
### 1. Spreadsheet
### 2. Notion
### 3. Bullet Journal

## Key Takeaways
[Bullet points or table]

## Resources
[Links with descriptions]
```

## Tasks for AI Agents

### When Adding New Productivity Systems

1. Research the system thoroughly (original source, creator, methodology)
2. Document the underlying philosophy and science
3. Create practical implementation guides for multiple formats
4. Include templates and examples
5. Add entry to README.md documentation table

### When Updating Existing Documentation

1. Preserve the existing structure
2. Add new sections at appropriate locations
3. Update the table of contents if present
4. Keep formatting consistent with existing content

### When Creating Templates

Use clear, copy-paste ready formats:

**For Spreadsheets:**
```
Column A    Column B    Column C
─────────   ─────────   ─────────
Data        Data        Data
```

**For Notion:**
```markdown
## Database Properties
- Property Name (Type): Description
```

**For Bullet Journal:**
```
SYMBOL KEY
⭐ = Daily Highlight
🎯 = Micro-Commitment
□ = Task
```

## Research Guidelines

When documenting productivity systems:

1. **Find original sources** — Creator's website, videos, books
2. **Include scientific backing** — Neuroscience, psychology research
3. **Note ADHD-specific adaptations** — Why it works for neurodivergent brains
4. **Acknowledge limitations** — No system works for everyone

### Preferred Research Sources

- Creator's official content (websites, YouTube, books)
- Peer-reviewed research (PMC, PubMed, Psychology Today)
- ADHD-specific resources (ADDitude Magazine, CHADD)
- Productivity research (academic and practitioner sources)

## File Naming Conventions

- Use **kebab-case** for file names: `system-name-description.md`
- Keep names descriptive but concise
- Place all documentation in `docs/` directory

Examples:
- `kaizen-adhd-productivity-system.md`
- `pomodoro-adhd-adaptations.md`
- `gtd-simplified-for-adhd.md`

## Commit Message Format

```
Add [system name] productivity system documentation

[Brief description of what was added]

- Key point 1
- Key point 2
- Key point 3
```

## Quality Checklist

Before completing documentation:

- [ ] Executive summary is clear and concise
- [ ] Philosophy and science are explained
- [ ] Step-by-step methodology is documented
- [ ] Implementation guides for 3+ formats included
- [ ] Templates are copy-paste ready
- [ ] Sources and resources are linked
- [ ] Formatting is consistent with existing docs
- [ ] README.md is updated with new entry

## Notes for Specific AI Assistants

### Claude Code
- Use the Task tool with Explore agent for researching new systems
- WebSearch for finding original sources and research
- Commit documentation with descriptive messages

### Cursor / Copilot
- Follow the document structure template above
- Reference existing docs in `docs/` for style consistency
- Keep implementations practical and actionable

---

*This file helps AI assistants understand and contribute to NextPlan effectively.*
