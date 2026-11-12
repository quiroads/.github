# QuiroAds

> QuiroAds is a marketing agency that works only with chiropractic clinics: Google Ads, Meta Ads, TikTok Ads, SEO and automation. 70+ clinics in 12 countries since 2020.
>
> QuiroAds es una agencia de marketing que trabaja solo con clínicas quiroprácticas: Google Ads, Meta Ads, TikTok Ads, SEO y automatización. Más de 70 clínicas en 12 países desde 2020.

This organization publishes QuiroAds' open-source agent skills for the people who market health clinics: agencies, consultants, developers, clinic owners and practice managers.

## Agent skills

[`quiroads/clinic-marketing-skills`](https://github.com/quiroads/clinic-marketing-skills) holds four MIT-licensed agent skills for Claude Code, Codex, Cursor, Gemini CLI, Hermes Agent and the other agents that read `SKILL.md`, in English and Spanish:

| Skill | What it does |
| --- | --- |
| [`clinic-meta-ads-access-audit`](https://github.com/quiroads/clinic-marketing-skills/tree/main/skills/clinic-meta-ads-access-audit) | Walks you through Meta Business Suite screen by screen to find out who owns and controls the clinic's ad account, Page, Instagram, dataset, WhatsApp account and domain, and ranks the risks with the official fix for each. |
| [`clinic-ad-compliance-review`](https://github.com/quiroads/clinic-marketing-skills/tree/main/skills/clinic-ad-compliance-review) | Checks an ad, a landing page, an organic post or a WhatsApp sales message against the Meta and Google health ad policies and the health advertising rules of Spain, the United Kingdom, the United States and Australia, and rewrites the piece. |
| [`clinic-lead-follow-up`](https://github.com/quiroads/clinic-marketing-skills/tree/main/skills/clinic-lead-follow-up) | Designs a speed-to-lead system that works with any tool, from a spreadsheet to a CRM: the first WhatsApp message, call and voicemail scripts, follow-ups, reminders, consent texts and a sheet to measure the results. |
| [`clinic-patient-retention`](https://github.com/quiroads/clinic-marketing-skills/tree/main/skills/clinic-patient-retention) | Scripts the first visit and the report of findings, presents the care plan and the payment options, answers the usual objections, and sets up the messages for missed visits, renewals, reactivation and reviews. |

Install them with the `skills` CLI:

```sh
npx skills add quiroads/clinic-marketing-skills
```

The skills are plain instructions: they connect to no ad platform or clinic software, read no web pages and never need patient data. They are also listed on [skills.sh](https://skills.sh/quiroads/clinic-marketing-skills) and in the QuiroAds [agent skills catalog](https://quiroads.com/.well-known/agent-skills/index.json).

## Links

- Website: https://quiroads.com
- In Spanish: https://quiroads.com/es
- For AI assistants: https://quiroads.com/llms.txt
- Agent skills catalog: https://quiroads.com/.well-known/agent-skills/index.json
- Contact: ajustame@quiroads.com
