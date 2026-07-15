# Connect Radi8 to Claude (the MCP connector)

This lets **Claude run Radi8 for you** — Claude can read your brand, write on-brand posts, plan, and
schedule, right from a normal Claude chat (even on your phone). Once it's set up, you can say things like
*"is my brand up to date?"* or *"write and schedule a LinkedIn post for tomorrow"* and Claude does it.

> **Plain-language version:** a "connector" (also called MCP) hands Claude a set of tools from another
> app. This one hands Claude your Radi8 brain, so it always has your context.

---

## Before you start
- A **Radi8** account with your brand set up → [radi8.com](https://radi8.com). (Do the brand guide first —
  that's the context Claude will use. See the [Start Here handout](../handouts/start-here.md).)
- A **Claude** account → [claude.ai](https://claude.ai). *Custom connectors need a paid Claude plan
  (Pro or Team). On the free plan you can still use all the [copy-paste prompts](../prompts/) instead.*

---

## Steps

**1. Get your connector link from Radi8.**
In Radi8, find the **Connect Claude** button and copy the connector URL it shows you.

![Radi8 Connect Claude button](../assets/radi8-connect-claude.png)

> Radi8 connector URL (paste yours, or use the one from the button):
> `PASTE-YOUR-RADI8-CONNECT-URL-HERE`

**2. Open Claude's connectors.**
In [claude.ai](https://claude.ai): **Settings → Connectors** (or the toolbox icon → Connectors). Click
**Add custom connector** (the **+** button).

![Claude add custom connector](../assets/claude-connectors-add.png)

**3. Paste the Radi8 link and add it.**
Paste the URL from step 1, give it a name (e.g. "Radi8"), and add it.

**4. Authorize.**
Claude will ask you to sign in / allow access to Radi8. Approve it. Done — Radi8's tools are now available
to Claude.

![Authorize the connector](../assets/claude-connector-authorize.png)

**5. Try it.**
Start a new chat and type:
```
What do you know about my brand from Radi8?
```
Claude will pull your brand context. Now try:
```
Write a LinkedIn post about [topic] using my brand voice, and schedule it for tomorrow morning.
```

---

## Handy things to say once it's connected
- `Switch to [my other company] in Radi8` — work on a different brand (your context stays separate).
- `Is my Radi8 brand context and strategy up to date? What's missing?`
- `Have we posted anything recently? What's scheduled this week?`
- `Take this blog post and fan it out to LinkedIn, Instagram, and X in my voice.`

## Tip
Install **Claude on your phone** and add the same connector. Then you can run your whole marketing engine
from bed — write and schedule posts by just typing what you want.

---
*From the [Be the Answer](../README.md) workshop · CC BY 4.0*
