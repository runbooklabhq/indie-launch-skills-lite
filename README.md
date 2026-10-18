# Indie Launch Skills: Lite (free)

Two free Claude Code skills for the two ends of a solo product launch: **positioning** before you write a word of copy, and the **launch review** after the numbers come in.

Each one is a `SKILL.md` with explicit inputs, tests and a fixed output format, so it's a procedure Claude follows rather than a one-off prompt. Describe the situation and Claude loads the matching skill.

| Skill | Say something like… | You get |
|---|---|---|
| `positioning` | "Who is this for and why would they switch?" | One positioning statement, 3 pass/fail tests, a headline + subheadline, and the riskiest assumption to check this week |
| `launch-review` | "How did the launch go?" (paste your numbers) | Funnel table, the one bottleneck, channel ranking, and three experiments ranked by effort |

## Install

```bash
git clone https://github.com/kritikosgns-web/indie-launch-skills-lite
cd indie-launch-skills-lite
bash install.sh            # all your projects (~/.claude/skills)
bash install.sh --project  # current project only (./.claude/skills)
```

Restart Claude Code and type `/` to see them. They also work pasted into a Claude.ai Project, Claude Cowork, Cursor rules, or any agent that reads Markdown.

## Want the six in between?

The full pack adds `landing-page-copy`, `pricing-page`, `launch-plan`, `product-hunt-launch`, `community-post` and `launch-email`. They read the positioning output and hand their numbers to the launch review, so the eight run as one sequence from "it works" to "people paid".

**[Get the full 8-skill pack for €14.99 →](https://kritikos12.gumroad.com/l/ppxgwi?utm_source=github&utm_campaign=ils-lite)**

Also on [Etsy](https://www.etsy.com/listing/4597283831/claude-skills-bundle-for-product-launch).

Freelancer? See **[Freelancer Ops Skills](https://kritikos12.gumroad.com/l/freelancer-ops-skills?utm_source=github&utm_campaign=ils-lite)**: 10 skills for proposals, pricing, contracts, scope and late invoices.

## License

MIT for the two skills in this repo: use, modify and share them freely. The full packs are sold separately under their own license.

Not affiliated with or endorsed by Anthropic or Product Hunt. "Claude" is a trademark of Anthropic, PBC.
