Anti-AI Website Design

A reusable AI-agent skill for designing and reviewing websites without falling into generic, template-driven "AI-looking" design patterns.

The goal is not to ban modern design techniques. It is to make visual decisions intentional, product-specific, usable, accessible, and credible.

## What the skill does

- Identifies 30 common visual and UX clichés to avoid by default.
- Guides agents through product understanding and visual direction.
- Encourages purposeful typography, color, layout, imagery, and motion.
- Prohibits fabricated testimonials, metrics, customer logos, and product claims.
- Requires meaningful loading, empty, error, and success states.
- Includes a responsive, accessibility, and credibility review checklist.

## Installation

### Claude Code

Copy `SKILL.md` into your project's skill directory:

```text
.claude/skills/anti-ai-website-design/SKILL.md
```

You can also install it in your personal Claude Code skills directory if you want to use it across projects.

### Codex

Copy the skill into:

```text
.agents/skills/anti-ai-website-design/SKILL.md
```

Then ask Codex to use the `anti-ai-website-design` skill when planning, implementing, or reviewing a website.

### Replit Agent and other coding agents

Add the contents of `SKILL.md` to the project's agent instructions (for example, `replit.md`) or provide the file to the agent as a project-level design standard. Exact skill discovery support depends on the agent.

## Usage

Ask your coding agent to use this skill before it starts designing or modifying the website. For example:

> Read and follow the Anti-AI Website Design skill. First inspect the existing product, audience, content, and codebase. Then propose a product-specific visual direction before implementing. Do not apply the listed patterns by default. Explain any deliberate exceptions and review the running website before calling the work complete.

## Design philosophy

The 30 anti-patterns are warnings, not absolute bans. A technique may be appropriate when it serves the product, brand, content, or user request. The agent should be able to explain why it used it.

## Contributing

Suggestions, issue reports, and improvements are welcome. When proposing a new rule, explain the problem it prevents and when the pattern may still be appropriate.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
