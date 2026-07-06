# Money Routines

A concept for agent-driven personal banking. Describe what should happen with your money once, in plain language. An agent reads your account, builds the routine, and shows every assumption it made before anything runs.

**Live prototype:** https://saimalshafi.github.io/money-routines/

Best experienced on a phone.

## The idea

Standing orders are dumb: fixed amount, fixed date, no context. Money Routines explores what banking automation looks like when an agent can actually interpret intent and account data:

- **Describe once.** "When my salary arrives, pay my credit card in full, send €2,000 to Frank, move 10% to savings."
- **Every assumption is visible and editable.** The agent shows what it inferred (which salary, which Frank, which card) as tappable tokens before activation.
- **Permissions, not blind automation.** Per-routine choice between "Ask first" and "Automatic."
- **Full audit trail.** Everything the agent did, why it did it, and who approved it.

## What this is

A scripted interactive prototype. Single HTML file, no framework, no build step, no real accounts, dummy data. Built to explore the trust UX of autonomous money, not to move any.

## Try the flow

New routine → tap the chat bar → send → tap any underlined assumption → Change it → Activate → check the History tab and open the held bill.

---

Part of my [AI playground](https://saimalshafi.framer.website/ai-playground) · [Portfolio](https://saimalshafi.framer.website)
