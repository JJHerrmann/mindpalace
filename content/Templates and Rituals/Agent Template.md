<%*
let today = tp.date.now("YYYY-MM-DD")
let default_title = tp.file.title
%>
---
agent_name: "<%= default_title %>"
title: ""
readiness: 0
status: Concept
sparked: false
domain: []
tags: [AI Agent, Placeholder]
registered: <%= today %>
dependencies: []
---

# <%= default_title %>

> “Agent quote goes here.”

## 🧩 Pain Point

Describe the real-life problem that made you want to create this agent.

## 🛠️ Role and Purpose

What this agent does, what it connects to, and what kind of voice/personality it has (if any).

## 🔧 Current Status

- Readiness: Level `<%= tp.frontmatter.readiness %>` – `<%= tp.frontmatter.status %>`
- Integration: None yet
- Activation trigger: _Pending_
- Data storage: _Pending_

---

## 💾 Download Availability

This agent is currently at **Readiness Level `<%= tp.frontmatter.readiness %>` – <%= tp.frontmatter.status %>**.

> Agents will not be released as full-function download bundles until they reach **Readiness Level 4 – Autonomous**. This ensures that what you receive is a complete, tested, modular tool—not just a concept.

The paid bundle (once available) will include:

- The full `.md` file with operational scaffolding
- YAML metadata stub
- Prompting structure (`prompts.md`)
- Folder structure and file naming conventions
- Usage instructions for connecting it to your own vault or agent system

---

## ⚠️ Important Note on Memory & Privacy

This agent was originally developed using **private memory structures**, including `.json` vector files derived from personal notes. These memory files **are not** included in any public or paid version.

---

## 🛍️ Licensing & Use

All released agents are:
- **CC BY-NC-SA 4.0** (Attribution–NonCommercial–ShareAlike)
- Intended for personal use in knowledge management and automation systems
- Not to be resold, repackaged, or redistributed without permission

If you want a custom agent based on this archetype, contact the Archivist.
