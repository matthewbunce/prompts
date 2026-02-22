# Prompts

## Overview

A library of reusable prompts with supporting documentation. Use this repo to store, version, and share prompt templates across projects.

## How to Use

1. Browse the `prompts/` directory by category to find a relevant prompt
2. Copy the prompt text and fill in any `{{variables}}` with your specific values
3. Use the `templates/prompt-template.md` when contributing a new prompt
4. Use the `templates/readme-template.md` to document each new prompt

## Structure

```
prompts/
├── prompts/
│   ├── coding/       # Prompts for code generation, review, and debugging
│   ├── writing/      # Prompts for drafting, editing, and summarising
│   └── analysis/     # Prompts for research, reasoning, and data tasks
└── templates/
    ├── prompt-template.md    # Template for writing a new prompt
    └── readme-template.md    # Template for documenting a prompt
```

## Tips

- Keep prompts focused on a single task — compose them together for complex workflows
- Use `{{variable}}` placeholders for anything that changes between uses
- Version your prompts (e.g. `v1.0`) so you can track what changed and why
- Include a worked example so others can see the expected output

## FAQ

**Q: How do I add a new prompt?**
A: Copy `templates/prompt-template.md` into the relevant `prompts/` subdirectory, fill it in, and add a matching `README.md` using `templates/readme-template.md`.

**Q: What belongs in each category?**
A: `coding/` for anything code-related, `writing/` for prose and content tasks, `analysis/` for structured reasoning, research, or data interpretation. Add new categories as needed.
