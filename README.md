# InsightfulPipe PR & Communications Skills

**19 free Claude skills for PR: press releases, press kits, media pitches and lists, coverage reports, crisis communications, events, awards and sponsorships.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/pr-skills
/plugin install insightfulpipe-pr@insightfulpipe-pr
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/pr-skills
```

Add `--skill analyst-relations-planner` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (19)

| Skill | What it does | |
|---|---|---|
| [Analyst Relations Planner](skills/analyst-relations-planner/) | Plans B2B analyst relations, scoring the analyst firms and evaluations that cover your category and timing a year of briefings, inquiry calls, a briefing deck and… |  |
| [Award Entry Writer](skills/award-entry-writer/) | Picks the marketing and business awards worth entering and writes the award submission to each award's criteria and word limits, with results checked in GA4, Klaviyo… |  |
| [Brand Impersonation Response](skills/brand-impersonation-response/) | Finds scam ads, lookalike domains, fake sites and fake profiles using your brand in the Meta, Google, TikTok, LinkedIn and Microsoft ad libraries, ranks them by risk… |  |
| [Conference Speaker Proposal Writer](skills/speaker-proposal-writer/) | Finds conferences with open calls for speakers, ranks them by buyers in the room, and writes the talk title, abstract and speaker bio to each event's limits. |  |
| [Crisis Communications Plan](skills/crisis-comms-plan/) | Writes a crisis communications plan before anything goes wrong, with a risk register, numeric response levels, sign-off chain, holding statements and a pause list of… |  |
| [Crisis Response Kit](skills/crisis-response-kit/) | Handles a PR crisis happening now. |  |
| [Event and Sponsorship ROI Calculator](skills/event-sponsorship-roi/) | Prices a sponsorship or exhibitor package from your CRM conversion rates with break-even, a walk-away fee and a buy, negotiate or pass verdict, then measures event ROI… |  |
| [Event and Trade Show Marketing Plan](skills/event-marketing-plan/) | Builds a dated marketing plan for one trade show stand, hosted customer day or target-account dinner, with targets from your past events, a budget verdict, outreach… |  |
| [Gift Guide and Product Seeding Planner](skills/gift-guide-seeding-planner/) | Plans gift guide PR and product seeding for an online store, picking products by margin and stock from Shopify or WooCommerce, timing pitches to each outlet's lead time… |  |
| [Media Interview Prep](skills/spokesperson-interview-prep/) | Prepares a spokesperson for one media interview, podcast, panel or TV or radio slot. |  |
| [Media List Builder](skills/media-list-builder/) | Builds a media list for one story from journalists, trade outlets, bloggers and YouTube shows that covered your topic or competitors in the last year, with recent… |  |
| [Media Monitoring and PR Report](skills/pr-coverage-report/) | Monitors press coverage of your brand and builds the monthly or campaign PR report with outlet tiers, sentiment, message pull-through, share of voice, GA4 referrals… |  |
| [Media Pitch Writer](skills/media-pitch-writer/) | Writes a personal media pitch per journalist, editor or producer for one story, each tied to a recent article, with subject lines, exclusive or embargo terms, two… |  |
| [Newsjacking and Reactive PR Finder](skills/newsjacking-angle-finder/) | Finds news stories and X trends a brand can comment on within hours, screens out tragedy, politics and legal cases, scores fit and timing, and drafts an expert comment… |  |
| [Podcast Guesting Planner](skills/podcast-guest-pitching/) | Gets a founder or expert booked as a guest on other podcasts, vetting active shows on YouTube, writing the one-sheet, a pitch per host with follow-ups and a booking… |  |
| [PR Strategy Plan Builder](skills/pr-strategy-plan/) | Builds a 6 or 12 month PR strategy from your own evidence, scoring story angles for newsworthiness, tiering outlets that cover your category and laying out a monthly… |  |
| [Press Kit Builder](skills/press-kit-builder/) | Builds a company press kit or newsroom page, or audits the press page you have. |  |
| [Press Release Writer](skills/press-release-writer/) | Writes a press release or media advisory for one piece of news, such as a launch, funding round, hire or data story, checking each number in GA4, Shopify or Google… |  |
| [Sponsorship Proposal Writer](skills/sponsorship-proposal-writer/) | Writes a sponsorship deck, priced package tiers and sponsor pitch emails for an event, nonprofit or club, using audience proof from GA4, Klaviyo, Mailchimp and social. |  |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
