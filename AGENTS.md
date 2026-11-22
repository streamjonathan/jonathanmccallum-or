# AGENTS.md — jonathanmccallum-or (Odia mirror of jonathanmccallum.com)

Odia mirror site. Same theme and design as the main site (Paper Light),
content translated into Odia, meaning-first. Repo: streamjonathan/jonathanmccallum-or.
Live: jonathanmccallum-or.pages.dev (Jonathan approved all 50 mirrors live, 22 Nov 2026).
Custom subdomain or.jonathanmccallum.com comes later, via the dashboard.

## Mission

Mirror jonathanmccallum.com in Odia — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## Publishing

Jonathan approved all 50 language mirrors live (22 Nov 2026), so this mirror
goes live on jonathanmccallum-or.pages.dev with its 5 proof articles.
The custom subdomain or.jonathanmccallum.com is a later dashboard step. New articles stay drafts
until he approves them.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Register: ତୁମେ (tume) — warm, familiar-but-respectful second person for direct
  address. God and Jesus take respectful third-person forms (ସେ / ତାଙ୍କ).
- Names (never vary): God ପରମେଶ୍ୱର, Jesus ଯୀଶୁ, Christ ଖ୍ରୀଷ୍ଟ, Aslan
  ଆସଲାନ୍, Narnia ନାର୍ନିଆ, Lucy ଲୁସି, Digory ଡିଗୋରୀ, Tirian ଟିରିଆନ୍,
  Adam and Eve ଆଦମ ଓ ହାବା (Odia Bible), Lewis ଲୁଇସ୍. Book titles are kept in
  English with an Odia meaning-gloss on first mention only — no published Odia
  translations found, flagged for Jonathan.
- Bible verses: the bread/water of life lines are Jonathan's paraphrase —
  ଜୀବନର ରୁଟି / ଜୀବନର ଜଳ — never quoted as Scripture.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
