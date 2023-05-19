---
layout: sub-navigation
order: 1
title: Automation in code
date: git Last Modified
tags:
- Ways of working
- Build release and deploy
- Automation
---

Last updated: {{ page.date | postDate }}
Tags: {{ tags | join(', ') }}

Everything should be codified in version control for maintenance, collaboration and repeatability. 

---

## Rationale

Reducing errors, reducing risk of manual knowledge, increase speed of iteration, eliminating TOIL

---

## Applications and Implications

- Reduce manual processes
- IaaC - DRY, KISS
- Build process
- Examples of things to automate: Linting, Vuln scanning, Updating dependencies (e.g. dependabot), Incidents/notifications,Change requests (e.g. SNow; snowtify)

---
