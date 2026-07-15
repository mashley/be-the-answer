# Skills

Two ready-made **Claude skills** for content marketing. A skill is a small instruction file that teaches
Claude to do a repeatable job well, every time — so you don't re-explain yourself.

| Skill | What it does |
|---|---|
| [be-the-answer](be-the-answer/SKILL.md) | Turns any customer question into content that answers it, matched to the journey stage |
| [brand-voice-builder](brand-voice-builder/SKILL.md) | Interviews you to build your brand context, then keeps every piece of content on-brand |

## How to use them

**Easiest (Claude.ai — for total beginners):**
1. Open [claude.ai](https://claude.ai) and start a new **Project** (left sidebar).
2. Open a skill's `SKILL.md`, copy everything below the top `---` block, and paste it into the Project's
   **custom instructions**.
3. Now every chat in that Project follows the skill. Just tell it what you need.

**Or, in Claude Code / with Skills support:** copy the skill's folder into `.claude/skills/` (in your
project) or `~/.claude/skills/` (always available), then invoke it with `/be-the-answer`.

> New to all of this? Start with the [Start Here handout](../handouts/start-here.md).
