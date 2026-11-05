# Design Resource Curator

A lightweight, bilingual skill for AI agents working on websites and product interfaces. It helps choose a small set of relevant design references, UI components, motion examples, and AI design tools for the task at hand.

**Languages:** [English](README.md) · [Русский](README.ru.md)

This repository contains two independent skills so agents can install only the language they need:

- **English:** `skills/design-resource-curator/SKILL.md`
- **Русский:** `skills/design-resource-curator-ru/SKILL.md`

The catalog is a set of links, not bundled plugins. The skill reads it only for relevant design work and picks a few resources instead of loading or recommending the whole list.

## Install

Using the open agent skills CLI:

```bash
npx skills add alexeenkoai1/design-resource-curator --skill design-resource-curator
```

For the Russian version:

```bash
npx skills add alexeenkoai1/design-resource-curator --skill design-resource-curator-ru
```

You can also browse the skills with `npx skills find design resources` or install either skill for a supported coding agent with the CLI's `--agent` option.

## What it helps with

- Finding visual references for websites, mobile apps, landing pages, and SaaS products
- Choosing UI component libraries that fit the project's framework and needs
- Finding focused examples of navigation, calls to action, gradients, and motion
- Selecting AI design tools and `DESIGN.md` references when they are useful
- Keeping reference discovery lightweight and tied to the design task

The skill asks agents to verify current availability, features, pricing, and terms when those details matter. It does not treat any listed resource as an endorsement or a requirement.

## Contents

- [English skill](skills/design-resource-curator/SKILL.md)
- [English resource catalog](skills/design-resource-curator/references/resource-catalog.md)
- [Русская версия скилла](skills/design-resource-curator-ru/SKILL.md)
- [Каталог ресурсов на русском](skills/design-resource-curator-ru/references/katalog-resursov.md)
