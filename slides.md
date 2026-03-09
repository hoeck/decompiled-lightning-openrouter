---
theme: default
colorSchema: light
class: text-center
highlighter: shiki
lineNumbers: false
transition: slide-left
title: Openrouter
mdc: true
export:
  format: pdf
  timeout: 30000
  dark: false
  withClicks: false
  withToc: false
canvasWidth: 600
---

Openrouter

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

#0 early ai hype

<!--

#0 ai hype

- love control and knowing how things work
- love playing with cheap things
- archlinux, emacs, terminals
- didn't like the way how coding AIs are tightly integrated into editors
- didn't like subscriptions (they get worse overtime, see enshittyfication of streaming)
- at we-are-developers '25 (basically every 2nd talk was about AI)
  at yet another AI talk someone said: "just try out any model, typically they're super cheap"

-->

---

#1 to the rescue: coding clis & openrouter

<!--

- use any model you want, with any tool you want
- no subscription required, no virtual currency, pay per token with, prepaid cash balance
- proved to be perfect for playing around in private projects
- started using it with claude-code via https://github.com/musistudio/claude-code-router
- but it became to tedious switching models

-->

---

#2 pi agent

<!--

- so I switched to "pi"
(- put it in a docker jail first so it cannot mess with my non-project files)
- switching models is dead easy
- OR provides up-to-date tokens-per-second for all models/providers
- PI reads OR data for accurate pricing
  (include cost screenshot)
- I learned to like the fast & cheap gemini flash models

- run your own experiments to verify what others say online ? easy !
  - commit context.md
  - run pi with different models / different agent setups in a git branch
  - compare results in git and costs from pi log

- pi agent fetches models from
- curl https://openrouter.ai/api/v1/models
- and https://models.dev/ - a database of models

check: https://github.com/badlogic/pi-mono/blob/main/packages/ai/scripts/generate-models.ts

-->

---

#3 alternatives to the alternative

<!--

- https://vercel.com/ai-gateway
- aws bedrock (more expensive than openrouter)
- cloudflare AI gateway

-->

---

#4 conclusion

i have spent way more time playing around with models and agents than actually doing useful coding

but it has been *fun* XD
