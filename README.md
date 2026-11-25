# 🐙 Octocrew Marketing Skills

Three [Agent Skills](https://agentskills.io/) for recurring work in SEO, paid media, and conversion analysis. Built by [Octocrew](https://www.octocrew.ai/), the team that implements and maintains AI marketing agents inside existing marketing teams.

## Pick a skill

| Skill | Use it to | You get |
| --- | --- | --- |
| 🔎 [SEO + GEO Content Loop](skills/seo-geo-content-loop/README.md) | Review search performance, find content gaps, and plan what to update or publish | A weekly SEO report, prioritized topics, and templates for drafting and review |
| 🎯 [Tracking Confidence Check](skills/tracking-confidence-check/README.md) | Check whether CAC, CPA, and ROAS are reliable enough to guide a paid media decision | A confidence rating, a decision recommendation, and follow-up checks |
| 📊 [Funnel Quality Review](skills/funnel-quality-review/README.md) | Find where visitors drop off and which sources bring qualified leads or customers | A stage-by-stage breakdown, a likely cause to investigate, and one proposed test |

## Get started

Download or clone the repository. From its root, copy the entire folder of the skill you want into your agent's skills directory. For example, in Claude Code:

```bash
mkdir -p ~/.claude/skills
cp -R skills/seo-geo-content-loop ~/.claude/skills/
```

Try asking, “Run our weekly SEO report.” Each skill page has more example prompts and a list of inputs. Bring a report or grant read access to the relevant data in your agent environment.

The skills separate measured findings from hypotheses. Proposed changes to budgets, campaigns, pages, or publishing go to a human for approval.

## License

MIT. See [LICENSE](LICENSE).
