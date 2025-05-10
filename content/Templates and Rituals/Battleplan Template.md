<%*
let today = tp.date.now("YYYY-MM-DD")
let title = tp.file.title
%>
---
project_name: "<%= title %>"
project_type: battleplan
project_status: planning
registered: <%= today %>
tags: [systems, optimization, battleplan]
readiness: 0
---

# <%= title %>

> “This isn’t just a process doc. It’s the spellbook I use to break red tape.”

## ⚔️ Pain Point

What inefficiency, dysfunction, or frustration does this battleplan address?

## 🧠 Conceptual Model

Describe the desired state: automation, standardization, or culture shift?

## 🛠️ Tactical Components

- [ ] What tools are required?
- [ ] What agents are involved?
- [ ] What existing workflows does it replace or enhance?

## ✅ Success Conditions

How do we know this is working? Metrics? Behavioral changes? Logs?

## 🚧 Implementation Notes

What broke during testing? What edge cases still exist?

## 🔁 Future Upgrades

Ideas for v2, v3, or integrations into broader systems.
