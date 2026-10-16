# pm-bots

## Overview

Four product roles as agent personas and skills: Product Manager, Product Marketer, Product Designer and Product Engineer, plus a collaboration skill for how they split and hand over work. Built from the public Grok Bot versions of these roles by Paweł Huryn ([The Product Compass](https://www.productcompass.pm)). Each role skill links the pm-skills it relies on by GitHub URL and keeps every author and framework credit.

## Install

- **Claude Code:** `claude plugin install pm-bots@pm-skills`
- **Cursor:** install `pm-bots` from this repo's `.cursor-plugin/marketplace.json`. The plugin ships the skills below and four agents in `agents/`.

## Skills (5)

- `product-manager` — Discovery, strategy, value proposition, lean PRDs, stories, roadmaps and post-mortems
- `product-marketer` — Positioning, beachhead segment (Crossing the Chasm), go-to-market, growth loops, North Star metric, SEO and copy
- `product-designer` — Prototypes, landing pages and redesigns grounded in personas and journey maps
- `product-engineer` — Buildability reviews, code review, security and performance audits, tests and evals
- `product-team-collaboration` — Who handles what, when to bring another role in, what to hand over, and the order for new product, launch, redesign and build check

## Agents (4)

`product-manager`, `product-marketer`, `product-designer`, `product-engineer` — short persona prompts that load the matching role skill and the collaboration skill.

## Commands

None. The role skills point to the pm-skills commands they use by GitHub URL.
