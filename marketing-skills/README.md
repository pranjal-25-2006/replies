# Free marketing skills for Claude (6 ready-to-upload zips)

These are 6 skills from **marketingskills** by Corey Haines: https://github.com/coreyhaines31/marketingskills
License: **MIT** (free to use and share; the license file is inside each zip). Checked on 5 Nov 2026: 58,000+ GitHub stars, 53 skills in the full library. I am not affiliated with the author.

A "skill" is a folder of instructions that teaches Claude how to do one job well. These were written for founders and marketers, so some examples lean towards software products; they work fine for shops, services, coaches and creators if you tell Claude about your business.

## What is in the pack
| Zip | What it helps with | Try this prompt |
|---|---|---|
| copywriting.zip | Write and fix page copy: homepage, landing page, about, product pages | "Use the copywriting skill. I run a [business] in [city]. Rewrite my Instagram bio and website headline. Here is what I have now: [paste]." |
| offers.zip | Build an offer people say yes to: value, bonuses, guarantee, naming | "Use the offers skill. I sell [service] for [price]. Make the offer stronger: a name, 2 bonuses and a guarantee." |
| lead-magnets.zip | Plan a free checklist, guide or template that brings in customers | "Use the lead-magnets skill. Suggest 5 free resources I could give people in exchange for their email or WhatsApp number." |
| pricing.zip | Pricing and packaging decisions | "Use the pricing skill. My costs are [paste] and competitors charge [paste]. Suggest 3 price points and what each includes." |
| social.zip | Social posts and content plans for Instagram, LinkedIn, X and more | "Use the social skill. Make a 7-day Instagram plan for [business], with a hook and caption for each day." |
| customer-research.zip | Understand what customers want, in their own words | "Use the customer-research skill. Here are 20 customer messages or reviews: [paste]. What do they struggle with and what words do they use?" |

## How to add a skill to Claude (official steps)
1. Turn on code execution: Settings > Capabilities (it may be called "Create and edit files" in newer versions). On Team or Enterprise plans an admin turns it on.
2. Go to **Customize > Skills**, click **+**, then **Create skill** and **Upload a skill**.
3. Choose one of the zip files from this pack. Repeat for each skill.
4. Make sure the skill is switched on, then start a chat and name the skill in your prompt (see the table).

Official guide: https://support.claude.com/en/articles/12512198-how-to-create-custom-skills (menu names can change between app versions).

## Using Claude Code instead
Unzip a skill into `~/.claude/skills/` (all projects) or `.claude/skills/` (one project), or install the whole library:
```
npx skills add coreyhaines31/marketingskills
```

## Honest notes
- Tell Claude about your business first (what you sell, who buys, price range). The skills work much better with that context.
- Always read what Claude writes before you publish it. You decide the price, the promise and the final wording.
- The full library mentions optional paid partner tools (disclosed in its README). You do not need any of them to use these six skills.
- A skill can make Claude run commands in Claude Code, so read a skill's SKILL.md before installing anything from the internet.
- I made the zips by packaging the skill folders unchanged and adding the license file. I have not run them inside every Claude plan.

Made by @aipranjal.
