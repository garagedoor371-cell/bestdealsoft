# SEO Best Practices — Master Checklist

A consolidated checklist of everything the six reference articles agree you should do to earn
organic traffic from **Google**, **Bing**, and (increasingly) **AI answer engines** like Google AI
Overviews, ChatGPT, Perplexity, Gemini and Copilot.

Every item below is drawn from the sources listed at the bottom. Items marked **★ = consensus**
appear in 5–6 of the 6 sources, so treat those as non-negotiable. Items marked `P1` / `P2` / `P3`
are priority tiers (P1 = do first / biggest impact).

---

## 0. How to use this file

- Don't try to do everything today. Work top-down, or jump to the section that matches your problem.
- **Not sure where to start?** → Sections 1, 3 and 4.
- **Lots of content, no traffic?** → Sections 4, 5, 11 (content refresh).
- **Slow site / weird errors?** → Section 6.
- **Ranking fine but invisible in ChatGPT/AI Overviews?** → Section 9.
- **Experienced, just want more links?** → Section 8.
- Re-run the checklists in Section 11 on a schedule. SEO is maintenance, not a project.

---

## 1. Setup & measurement (do once, revisit quarterly)

- [ ] **★ Install Google Search Console (GSC)** `P1`
  - Verify the property, submit your sitemap, watch the **Pages / Indexing** report.
  - Use **URL Inspection** to see a page exactly as Googlebot sees it.
  - Check the **Performance** report for queries, impressions, CTR, average position.
  - Newer GSC also exposes AI-surface reporting (AI Overviews / AI Mode impressions).
- [ ] **★ Install Bing Webmaster Tools (BWT)** `P1`
  - Bing has 1B+ daily active users, and Bing data feeds Copilot + some partner AI surfaces.
  - BWT now includes an **AI Performance** report (citations across Copilot and AI summaries).
  - You can import your GSC sites into BWT in a couple of clicks.
- [ ] **★ Install an analytics platform (GA4 or equivalent)** `P1`
  - Track organic sessions, landing pages, engagement rate, conversions.
  - **Connect GA4 ↔ GSC** so search data shows up inside analytics.
  - Add a heatmap/session tool (e.g. Microsoft Clarity) if you care about on-page behaviour.
- [ ] **Define 1–2 KPIs before you start** `P1`
  - Organic traffic, keyword rankings (5–10 target terms), referring domains, or organic conversions.
  - Without a baseline number you can't tell whether any of this worked.
- [ ] **Set up rank tracking** `P2`
  - Track a small set of priority keywords across locations/devices.
  - Local business? Track **map-pack** rankings, not just blue links.
- [ ] **Install an SEO plugin (WordPress/Shopify)** `P2`
  - Yoast, Rank Math or The SEO Framework — handles titles, meta, sitemaps, canonicals, robots.txt, schema.
- [ ] **Audit your theme/template** `P2`
  - Mobile-friendly? Fast (PageSpeed Insights score)? Works in Chrome/Firefox/Safari? Recently updated? Good reviews?
- [ ] **Run a baseline full-site crawl** `P1`
  - Screaming Frog, Ahrefs Site Audit, Semrush Site Audit, or seoClarity. Fix crawl/index blockers first.
- [ ] **Review GSC for manual actions & coverage issues** `P1`
  - Manual actions, security issues, and "Not indexed" reasons. These override everything else.

---

## 2. Competitor analysis (do before keyword research)

- [ ] **★ Pick 2–3 real competitors and analyse them** `P1`
  - Which keywords do they rank for that you don't? (content gap)
  - Which of their pages pull the most organic traffic?
  - Are they winning on branded or non-branded terms?
- [ ] **Analyse their backlink profiles** `P2`
  - Look for directories, roundups, podcasts and publications you could also appear in.
- [ ] **Run a link gap / link intersect audit** `P2`
  - Domains linking to 2+ competitors but not to you = your best prospect list.
- [ ] **Find your page-2 keywords** `P1`
  - Queries where you already rank 11–20 are the fastest wins available — you already have a page Google trusts.

---

## 3. Keyword & topic research

- [ ] **★ Define your audience and their search intent first** `P1`
  - Who they are, their pain points, the words they actually use, which platforms they search on.
  - Intent categories: **learn / compare / buy / navigate**. Content format must match intent.
- [ ] **Build seed keywords** `P1`
  - Non-branded phrases that describe your product, category or problem you solve.
- [ ] **★ Expand with keyword tools** `P1`
  - Keyword Magic Tool, Keywords Explorer, KWFinder, Backlinko's free tool, Google Keyword Planner.
  - Note volume, keyword difficulty, CPC and SERP features for each.
- [ ] **Mine Google Suggest / autocomplete** `P2`
  - Type a seed term, don't hit enter. Free, real demand — but no volume data and personalised.
- [ ] **Harvest question keywords** `P2`
  - "People Also Ask", AnswerThePublic, and `site:reddit.com "<topic>" "how to"` style searches.
- [ ] **Mine communities for real phrasing** `P1`
  - Reddit, Quora, niche forums, your own sales/support calls, product reviews.
  - Note exact wording — this also doubles as your AI-prompt research (Section 9).
- [ ] **Prioritise low-competition, decent-volume terms early** `P1`
  - New/low-authority site? Ignore head terms. Win the long tail first.
- [ ] **Validate the target keyword per page** `P1`
  - One primary keyword per page. Check which variant is actually the "parent topic" (the term sending
    the most traffic to the top-ranking page) rather than guessing.
- [ ] **Map keywords → pages (keyword map)** `P1`
  - Group near-duplicate queries into one topic = one strong page. Prevents cannibalisation.
- [ ] **Assess keyword difficulty honestly** `P2`
  - Backlinks aren't the only barrier: big brands in the top 10, dominant content type you can't produce
    (video, interactive tool), high topical relevance of incumbents.
- [ ] **Check topical authority** `P2`
  - Sort GSC queries by clicks/impressions to see what Google already associates you with.
    Fill the gaps around your strongest topics instead of drifting into unrelated subjects.
- [ ] **Also record AI-style prompts** `P2`
  - Same research, different phrasing: "best X for Y", "X vs Y", "is X legit for Z".

---

## 4. On-page SEO — the per-page checklist

**Run this every single time you publish or update a page.**

- [ ] **★ One primary keyword, one clear page goal** `P1`
- [ ] **★ Short, descriptive URL slug containing the keyword** `P1`
  - Hyphens (not underscores), lowercase, no dates/session IDs/parameters if avoidable.
  - URLs containing the target keyword see a substantially higher CTR (Backlinko's 4M-SERP study: ~45%).
  - Don't change established URL structures on existing sites — the risk outweighs the gain.
- [ ] **★ Title tag: unique, accurate, keyword near the front** `P1`
  - Keep it short (~50–60 chars, max 70) to avoid truncation.
  - Add modifiers where honest: *Best, Top, Checklist, Guide, Review, [current year]*.
  - Never clickbait — Google rewards titles that match what's on the page.
- [ ] **★ Meta description: unique, 120–160 chars, benefit + light CTA** `P2`
  - Google rewrites it much of the time (~63% of the time it pulls from page copy), so it's a CTR
    lever, not a ranking lever.
- [ ] **★ Exactly one H1 containing the primary keyword** `P1`
- [ ] **★ Headings H2/H3 that read like a table of contents** `P1`
  - Someone should understand the whole page by scanning headings only.
  - Natural place to work in subtopics and question keywords.
- [ ] **★ Primary keyword in the first ~150 words** `P1`
  - Reassures users they're in the right place; tells search + AI systems what the page is about.
- [ ] **★ Target keyword in the opening paragraph and in the title** `P1`
- [ ] **Cover related terms and natural variations** `P2`
  - Synonyms, semantic variants, co-occurring concepts. Avoid keyword stuffing.
- [ ] **Answer the sub-questions the SERP implies** `P1`
  - Use "People Also Ask", top-ranking page patterns, and page-level content gaps of the top 3 results.
- [ ] **★ Add internal links to 2–5 relevant pages** `P1`
  - Descriptive anchor text ("on-page SEO"), never "click here".
  - Link from *high-traffic* pages where possible — that passes the most authority.
- [ ] **★ Add outbound links to trustworthy, relevant sources** `P2`
  - Citing stats? Link the source. Add `nofollow`/`sponsored` to anything you don't trust.
  - Auto-`nofollow` user-generated links (comments, forums).
- [ ] **★ Optimise every image** `P1`
  - Descriptive filename (`spinach-omelette.png`, not `IMG_9241.png`).
  - Descriptive alt text that explains the image *in context* — accessibility + image search + AI understanding.
  - Compress files; use modern formats; set explicit width/height to avoid layout shift.
  - Place images next to the relevant text, not randomly.
- [ ] **Add a table of contents on long posts** `P3`
  - Helps navigation, can win jump-to sitelinks, and makes content easier for AI to chunk.
- [ ] **Add structured data (schema)** `P2`
  - Organization/Person on the homepage; Article, Product, FAQ, HowTo, Recipe, Review, BreadcrumbList
    as relevant. Validate with the Rich Results Test / Schema Markup Validator.
- [ ] **✅ Then re-check**: mobile rendering, page speed, one canonical, indexable (no stray `noindex`).

---

## 5. Content quality & readability

- [ ] **★ Be genuinely useful and people-first** `P1`
  - Google's own guidance: helpful, reliable, people-first content beats clever optimisation.
- [ ] **★ Original, not scraped or rehashed** `P1`
  - Don't stitch together the H2s of the top 10 results. Add first-hand experience, testing, data,
    screenshots, case studies, or expert input.
- [ ] **★ Aim for "information gain"** `P1`
  - What does your page add that the current SERP doesn't have? Original research, real numbers,
    opinion from experience, better visuals, a clearer explanation.
- [ ] **★ Keep it current** `P1`
  - Refresh stats, screenshots, examples, product names, prices, and recommendations.
- [ ] **★ Chunk it for readability** `P1`
  - Short paragraphs, subheads, bullet lists, tables, bolded key points. No walls of text.
- [ ] **Write simply** `P1`
  - Short sentences, plain words, minimal jargon (roughly an 8th-grade reading level).
    A readability checker helps.
- [ ] **★ Use multimedia** `P2`
  - Images, charts, screenshots, video, infographics, interactive elements. Also a separate discovery
    channel (Google Images / Video).
- [ ] **Hook the reader in the intro (blog posts)** `P2`
  - Problem → Agitate → Solution. If the first screen doesn't match intent, people bounce back to the SERP.
- [ ] **Write self-contained paragraphs** `P2`
  - Each block should make sense if lifted out of context — AI systems extract at paragraph/sentence
    level. Define terms early, avoid ambiguous "this"/"it".
- [ ] **Front-load direct answers** `P2`
  - Lead each section with the answer, then the detail. Good for featured snippets and AI citations.
- [ ] **Optimise for video too** `P3`
  - Standalone page per video, descriptive title/description, embedded near relevant text,
    video schema, transcripts.
- [ ] **Avoid intrusive interstitials / ad clutter** `P2`
  - Pop-ups that block content hurt both UX and rankings.

---

## 6. Technical SEO

### Crawlability & indexability
- [ ] **★ Make sure your site can actually be indexed** `P1`
  - Watch for accidental site-wide `noindex` (very common on new sites and after migrations).
  - Check for `noindex` pages sitting inside your sitemap.
- [ ] **★ Create and submit an XML sitemap** `P1`
  - `/sitemap.xml` or `/sitemap_index.xml`; reference it in robots.txt; submit in GSC + BWT.
  - Only include canonical, indexable, 200-status URLs.
- [ ] **★ Write a deliberate robots.txt** `P1`
  - Block what shouldn't be crawled; never block CSS/JS/assets the renderer needs.
  - Reference your sitemap URL in it.
- [ ] **★ Fix crawl errors and "Not indexed" exclusions** `P1`
  - GSC → Pages → "Not indexed". Investigate every large exclusion bucket.
- [ ] **Use `Inspect URL` to debug individual pages** `P2`
  - Look for "indexing not allowed" and "different canonical chosen".
- [ ] **Keep crawl depth shallow** `P2`
  - Important pages within ~3 clicks of the homepage. Fix via hub/cornerstone pages and contextual links.
- [ ] **Check JavaScript rendering** `P2`
  - Many crawlers (including several AI crawlers) don't execute JS. Keep critical content server-rendered.
- [ ] **Group similar pages in directories** `P3`
  - Directories let search engines learn how often a group of URLs changes and crawl accordingly.

### Duplicates, canonicals & redirects
- [ ] **★ One canonical URL per piece of content** `P1`
  - Pick `https://www.` or `https://` and 301 the other three variants.
  - Test all four variants with a status checker — three should redirect to one.
- [ ] **★ Use 301 for permanent moves, not 302** `P1`
  - 302 keeps the old URL indexed and doesn't consolidate signals.
- [ ] **Fix redirect chains and loops** `P2`
  - Point every redirect straight at the final destination.
- [ ] **Fix HTTP links on HTTPS pages** `P2`
  - Each one triggers an unnecessary redirect hop.
- [ ] **Use `rel="canonical"` for parameterised/filtered URLs** `P2`
  - Sorting, tracking parameters, session IDs, pagination variants.
- [ ] **Kill or consolidate thin/duplicate pages** `P3`
  - Empty tag/category archives, outdated posts, zero-sale product pages, boilerplate pages —
    `noindex` them if you don't want to delete, or merge and 301.

### Performance
- [ ] **★ Pass Core Web Vitals** `P1`
  - **LCP** (loading) — aim < 2.5s
  - **INP** (responsiveness) — aim < 200ms
  - **CLS** (visual stability) — aim < 0.1
  - Measure with PageSpeed Insights (test the **mobile** tab) and GSC's CWV report.
- [ ] **Compress images / install a compression pipeline** `P1`
  - Wix and Shopify do this automatically; WordPress needs a plugin or a CDN.
- [ ] **Minimise and defer JavaScript & CSS** `P2`
  - Faster pages *and* more readable to non-JS-executing crawlers.
- [ ] **Use caching, a CDN, and a light theme** `P2`

### Security & mobile
- [ ] **★ Serve the whole site over HTTPS** `P1`
  - Valid certificate, auto-renewing, HTTP → HTTPS via 301, no mixed content.
- [ ] **★ Be mobile-friendly (mobile-first indexing)** `P1`
  - Readable text without zooming, tap targets big enough, no horizontal scroll,
    no blocking pop-ups, content parity with desktop.
  - Test in Chrome DevTools device mode, PageSpeed Insights, and GSC's mobile report.

### Hygiene
- [ ] **★ Find and fix broken links (404s) and broken outbound links** `P2`
  - Decide per case: restore, redirect, or remove the link.
- [ ] **★ Run recurring site audits** `P1`
  - Schedule a weekly/monthly crawl and turn on email alerts for new issues.
- [ ] **Check GSC Sitemaps report** `P3`
  - Confirm the file is fetched and read, and that listed pages actually get indexed.
- [ ] **Look at server logs / crawl budget if you're a big site** `P3`
  - Which bots hit which URLs, and whether they're wasting time on junk URLs.

---

## 7. Site architecture & internal linking

- [ ] **★ Plan a logical site structure up front** `P1`
  - Sketch it as a mind map: each branch is a category, each leaf is a page, each relationship is a link.
- [ ] **★ Use hub / cornerstone pages + topic clusters** `P1`
  - A strong pillar page linking out to in-depth supporting pages, which link back up.
- [ ] **★ Add contextual internal links to every new page** `P1`
  - 2–5 relevant links from existing pages on day one. Don't rely on the blog index alone.
- [ ] **Find internal-link opportunities systematically** `P2`
  - Search your CMS/crawler for pages that already mention the target keyword but don't link to it.
- [ ] **Fix orphan pages** `P1`
  - Pages with zero internal links are near-invisible. Link them from at least one relevant page,
    prioritising from high-traffic pages.
- [ ] **Fix pages with only 1 internal link** `P2`
- [ ] **Fix keyword cannibalisation** `P2`
  - Multiple pages competing for one query → merge, redirect, or re-target each page to a distinct term.
- [ ] **Use consistent, descriptive anchor text** `P2`
  - Both directions: what the linked page is about, and what the reader will get.

---

## 8. Off-page SEO & link building

Links remain one of the strongest authority signals — and recent research associates a strong
backlink profile with better AI-search visibility too.

- [ ] **★ Audit your existing link profile first** `P1`
  - Understand which links drive your authority; disavow/clean obviously toxic ones if needed.
- [ ] **★ Replicate competitors' easiest links** `P1`
  - Industry + local directories, association memberships, roundups, "best of" lists, podcast show notes.
- [ ] **★ Build genuinely linkable assets** `P1`
  - Original research, surveys, benchmark reports, data visualisations, free tools, definitive
    resources. This is what earns editorial links instead of begging for them.
- [ ] **Digital PR / expert commentary** `P2`
  - HARO/Connectively, Featured, MentionMatch, `#journorequest`, direct pitching to journalists.
- [ ] **Reverse-skyscraper outreach** `P2`
  - Find inferior pages that have links, build something better, then pitch everyone linking to them.
- [ ] **Be a podcast guest** `P3`
  - Show notes almost always link to guests. Vet invites — fake "tech check" scams are common.
- [ ] **Mention influencers/sites in your content, then tell them** `P3`
  - Simple, effective, and often earns shares as well as links.
- [ ] **Convert unlinked brand mentions into links** `P2`
  - Ask politely; even unlinked mentions help entity understanding, so don't obsess.
- [ ] **Guest posts & expert contributions** `P3`
  - Quality-over-quantity; relevance beats DA/DR.
- [ ] **Match the tactic to your resources** `P2`
  - Some tactics need content budget, some need only time. Pick what you can actually sustain at scale.

### Local SEO (if you serve a physical area)
- [ ] **★ Create and fully complete a Google Business Profile** `P1`
  - Categories, hours, services, photos, description, Q&A, posts.
- [ ] **Keep it accurate** `P1`
  - Hours, holiday hours, phone, products/services — outdated NAP data means bad reviews.
- [ ] **Build consistent citations across directories** `P2`
  - Same name, address, phone everywhere.
- [ ] **Earn locally relevant links & reviews** `P2`

---

## 9. AI search (GEO / AEO / "agentic" search optimisation)

This doesn't replace SEO — it's built on top of it. But it needs a few extra habits.

- [ ] **★ Make sure AI crawlers aren't blocked** `P1`
  - Check `yoursite.com/robots.txt` for `Disallow` against retrieval bots such as
    `OAI-SearchBot`, `ChatGPT-User`, `Claude-SearchBot`, `Claude-User`, `PerplexityBot`.
  - Also check `GPTBot` / `Google-Extended` policy decisions deliberately, not by accident.
- [ ] **★ Decide which AI surfaces matter for your audience** `P1`
  - Pick 2–3 (Google AI Overviews/AI Mode, ChatGPT, Perplexity, Gemini, Copilot) rather than all of them.
- [ ] **★ Document your real prompts** `P1`
  - Rewrite sales/support questions and community threads into natural prompts:
    "best [category] for [audience]", "[competitor] vs [you]", "is [brand] legit for [goal]".
- [ ] **Benchmark and track AI visibility** `P1`
  - Log per prompt + per platform: brand mentioned? pages cited? sentiment? Track a single
    "visibility rate" (% of prompts where you appear) over time, monthly.
- [ ] **Log which sources AI cites in your category** `P2`
  - Review sites, big publishers, niche blogs, forums, docs, marketplaces, YouTube.
    Those recurring domains belong on your PR / link-building / partnership roadmap.
- [ ] **★ Build "answer hub" pages** `P1`
  - Clear plain-language answer at the top, scannable H2/H3 subquestions, tables and bullet lists that
    are easy to quote, claims backed by data and fresh screenshots.
- [ ] **Structure for extractability** `P1`
  - Direct sentences that answer a question; define terms early; one idea per paragraph;
    no ambiguous pronouns; each section standalone.
- [ ] **Keep JavaScript light / content server-rendered** `P2`
  - Many AI crawlers don't execute JS.
- [ ] **Monitor brand sentiment in AI answers** `P2`
  - If a model keeps repeating an outdated complaint, fix the upstream sources (docs, reviews,
    case studies, third-party roundups) rather than your own homepage.
- [ ] **Consider `llms.txt`** `P3`
  - A proposed standard pointing AI systems at your most important pages. Low adoption and no
    confirmed support from major AI companies — treat as experimental/optional.
- [ ] **Keep an accurate entity footprint** `P2`
  - Consistent Organization schema, brand name, descriptions, sameAs links, and third-party mentions.

---

## 10. Content lifecycle: pruning & refreshing

- [ ] **★ Audit existing content** `P1`
  - Use GSC + analytics to find: high impressions/low CTR, high impressions/low position,
    declining traffic, thin pages, duplicate pages.
- [ ] **Fix high-impression, low-CTR pages first** `P1`
  - Usually a title/meta/intent mismatch — cheapest traffic you'll ever win.
- [ ] **Add subsections for high-impression, low-position queries** `P2`
  - You already surface for them; you just don't cover them thoroughly enough.
- [ ] **Refresh declining pages** `P1`
  - GSC → compare last 6 months vs previous → sort pages by click difference.
  - Three tiers: **optimise** (links, meta, image swap) → **upgrade** (refresh stats, add sections,
    new visuals, 15–70% changed) → **rewrite** (>70% changed). Most pages need the first two.
- [ ] **Prune or consolidate dead weight** `P2`
  - Check GSC impressions/clicks *before* deleting. Real traffic → improve or merge instead.
    Genuinely worthless → delete (301 to a relevant page) or `noindex`.
  - Common candidates: empty tag/category pages, outdated posts, duplicates, zero-sale products,
    boilerplate pages, dead service pages.
- [ ] **Re-promote updated content** `P3`
  - Newsletter, social, and a fresh outreach round for refreshed assets.

---

## 11. Ongoing cadence

**Every time you publish**
1. Section 4 checklist (title, meta, H1, slug, keyword placement, internal links, images, schema).
2. Request indexing in GSC if it's time-sensitive.
3. Share it: newsletter, social, community, and any stakeholders you mentioned.
4. Add 2–5 internal links from existing pages.

**Weekly**
- Check GSC for new errors, manual actions, sudden impression/click drops.
- Publish at least one piece of genuinely useful content (or one meaningful upgrade).
- One link-building or PR action.

**Monthly**
- Re-run a full crawl; fix the top technical issues.
- Review rank tracking + organic conversions against KPIs.
- Audit 3–5 underperforming pages → fix / refresh / prune.
- Re-run your AI prompt set and log visibility + citations.

**Quarterly**
- Content gap analysis vs competitors.
- Link gap audit + outreach refresh.
- Core Web Vitals / mobile / HTTPS spot-check.
- Update Google Business Profile (hours, holiday hours, services, posts).
- Revisit keyword map and topical authority coverage.

---

## 12. Things NOT to focus on (per Google's own guidance)

| Don't | Why |
|---|---|
| **Meta keywords tag** | Google Search doesn't use it. |
| **Keyword density targets** | No such ratio to hit. Write naturally; stuff nothing. |
| **A minimum word count** | Length isn't a ranking factor — coverage of intent is. |
| **"Exact-match" domains / keyword-stuffed domains** | Little to no benefit; branding matters more. |
| **Chasing every keyword variation manually** | Language matching is sophisticated; you can't and don't need to. |
| **Buying links / link schemes / PBNs** | Violates spam policies; real risk of penalties. |
| **Doorway pages, cloaking, scraped or spun content** | Spam policies. |
| **Over-promoting** | Can read as manipulation and fatigue your audience. |
| **Ranking #1 as the only KPI** | Track clicks, conversions, and assisted revenue too. |

---

## 13. Minimum tool stack

| Purpose | Free option | Paid / advanced |
|---|---|---|
| Search performance | Google Search Console | — |
| Bing performance + AI citations | Bing Webmaster Tools | — |
| Analytics | GA4 (+ Microsoft Clarity) | — |
| Crawling / audits | Screaming Frog (500 URLs), Ahrefs Webmaster Tools, SEO plugin | Ahrefs Site Audit, Semrush Site Audit, seoClarity |
| Keyword research | Google Suggest, Keyword Planner, AnswerThePublic, Backlinko keyword tool | Keyword Magic Tool, Keywords Explorer, KWFinder |
| Rank tracking | GSC average position | Advanced Web Ranking, Semrush Position Tracking (map rank for local) |
| Backlinks | AWT | Ahrefs Site Explorer, Semrush Backlink Analytics / Backlink Gap |
| Speed & CWV | PageSpeed Insights, Lighthouse | Site Audit CWV reports |
| Structured data | Rich Results Test, Schema Markup Validator | Schema Optimizer |
| AI visibility | Manual prompt tracking in a spreadsheet | Semrush AI Visibility Toolkit, Ahrefs, seoClarity ArcAI |
| Readability | Hemingway Editor | — |

---

## 14. Platform notes

**WordPress**
- Install one SEO plugin (Yoast / Rank Math / The SEO Framework), then configure site representation
  (Organization or Person) so schema is emitted correctly.
- Set permalinks to `Post name` **on a new site only** — don't change it later.
- Add an image compression plugin; themes are usually the speed bottleneck.

**Shopify / Wix**
- Most technical basics (sitemaps, image compression, canonicals) are handled for you.
- Wix: the **SEO Setup Checklist / SEO & GEO dashboard** asks for your business name, whether you
  serve a physical location or online, and **up to 3 keyword phrases (2–4 words each)** — keep the
  business name identical to what's on the site. Connecting GSC requires a Premium plan and a
  connected custom domain. It also reports how you appear in AI answers (GEO).
- Both platforms: product/collection pages need unique titles, descriptions and alt text — the
  default templates create duplicate content at scale.

---

## 15. Sources analysed

1. **Backlinko — The Complete SEO Checklist** — <https://backlinko.com/seo-checklist>
   (48 checks across basics, keyword research, on-page, content, technical, link building, AI SEO, advanced)
2. **Semrush — Ultimate SEO Checklist: 43 tips** — <https://www.semrush.com/blog/seo-checklist/>
   (basics, keyword research, technical, content & on-page, link building & off-page, AI/agentic search)
3. **Ahrefs — The Only SEO Checklist You Need** — <https://ahrefs.com/blog/seo-checklist/>
   (one-time / periodic / per-page framework)
4. **Google Search Central — SEO Starter Guide** — <https://developers.google.com/search/docs/fundamentals/seo-starter-guide>
   (official guidance: discoverability, structure, content quality, titles/snippets, images, what to ignore)
5. **seoClarity — The Ultimate 45-Point SEO Checklist** — <https://www.seoclarity.net/blog/seo-checklist>
   (setup, basics, keyword research, content writing, on-page, technical, link building — enterprise lens)
6. **Wix Help Center — Wix SEO Setup Checklist / SEO Wiz** — <https://support.wix.com/en/article/wix-seo-wiz-creating-your-seo-checklist-in-the-wix-seo-wiz>
   (platform setup flow, GSC connection requirements, GEO/AI-answer visibility)

> **Note on freshness:** these are living documents and get updated regularly. The technical specifics
> that change fastest are Core Web Vitals thresholds/metrics, AI-crawler user-agent names, and how
> GSC/BWT report AI surfaces — re-verify those against Google Search Central and Bing Webmaster
> documentation before you build anything on them.

# SEO / GEO / AEO Playbook — MobileRestorationExperts

**Project type:** Rank-and-rent local SEO site
**Note:** No Google Business Profile is tied to this project. All ranking strategy targets organic "blue link" results and AI answer visibility, not the map pack. Every tactic below is chosen with that constraint in mind.

---

## 1. Why No-GBP Changes the Strategy

Local ranking factors split into two buckets: map pack factors and organic factors. Without a GBP, the map pack is off the table entirely, so all effort goes into the organic bucket, which research consistently ranks by importance as:

1. On-page signals (title tags, content depth, keyword placement, NAP presence in text)
2. Backlinks (especially local/industry links)
3. Citations that link back to the site (not tied to a physical GBP pin)
4. Content depth and structured data

Practical implications for this project:

- Location pages must be built to rank in the "ten blue links," not the map pack. Every city/service page needs unique, non-duplicated content.
- Citations should prioritize sites that place a clickable link to the domain (directory-style, resource-page, sponsorship, chamber-style listings) over map-pin-style citations that require a verified GBP.
- Reviews cannot be pulled from a GBP. Substitute with on-site testimonials, schema Review/AggregateRating (only if reviews are genuinely collected some other way — never fabricate ratings), and third-party mentions.
- Schema does the heavy lifting that GBP normally would: LocalBusiness, Service, FAQPage, and areaServed markup become the primary way to tell Google (and AI answer engines) where the business operates.

---

## 2. Content & AEO Checklist (Standard for Every Page)

| # | Topic | Standard |
|---|-------|----------|
| 1 | Keyword Density | 0.5% – 1.5% max |
| 2 | Primary Keywords per Page | 1 – 2 only |
| 3 | Secondary / Entity Terms | 8 – 15 per page |
| 4 | Content Length | 800 – 2,500 words |
| 5 | Paragraph Length | 2 – 3 lines max |
| 6 | Sentence Length | 8 – 16 words |
| 7 | Em Dashes | 0 — never used |
| 8 | Emoji in Body Copy | 0 — never used |
| 9 | Horizontal Rules in Copy | 0 — not used |
| 10 | AI-Sounding Phrases | 0 — flagged and cut |
| 11 | H1 Tags | 1 per page |
| 12 | H2 Tags | 3 – 8 per page |
| 13 | H3 Tags | 5 – 15 per page |
| 14 | Title Tag Length | 50 – 60 characters |
| 15 | Meta Description | 120 – 155 characters |
| 16 | URL Length | 50 – 75 characters |
| 17 | Internal Links | 3 – 10 per page |
| 18 | External Links | 2 – 5 high-authority |
| 19 | Page Load Speed | under 2.5 seconds |
| 20 | Core Web Vitals (LCP / CLS / INP) | 2.5s / 0.1 / 200ms |
| 21 | Structured Data Schemas | 1 – 3 per page |
| 22 | FAQ Schema Questions | 3 – 5 max |
| 23 | AI Answer Block Length | 40 – 60 words |
| 24 | Content Update Frequency | every 30 – 90 days |
| 25 | Bounce Rate Target | under 50% |

Apply this checklist to every new page before publishing and to every existing page during an audit pass.

---

## 3. On-Page SEO Best Practices

- Primary keyword in the H1, first 100 words, one H2, title tag, and URL.
- Use the pattern `[Service] in [City, State]` for H1s on service and location pages.
- Cover the service entity cluster in body copy: synonyms, related sub-services, tools/methods, problem-solution language (what a customer searches when something has gone wrong, e.g. "water damage," "mold after flood," "fire smoke cleanup").
- Every page needs a clear NAP block in the footer or contact section — consistent formatting site-wide even without a GBP to match against.
- Write unique intros for every city/location page. Do not template the same paragraph with the city name swapped — this is the single most common reason location pages get filtered out of the index.
- Internal linking pattern: city page → service pages → homepage → contact. 3–10 internal links per page, descriptive anchor text (not "click here").
- Images: descriptive file names and alt text using the service + city where natural, not stuffed.
- FAQ section on every service and city page — 3–5 questions, answers written as tight 40–60 word AI-answer blocks so they're liftable for AI Overviews and answer engines.

---

## 4. Technical SEO Checklist

Run this list on every audit:

- HTTPS on all pages, no mixed content
- Mobile-responsive layout, valid viewport meta tag
- robots.txt accessible and not blocking important paths
- XML sitemap present, accurate, and submitted to Search Console
- Canonical tags on every page, especially city/location pages, to avoid duplicate-content dilution
- No broken internal or external links
- Core Web Vitals within target (LCP 2.5s, CLS 0.1, INP 200ms)
- Structured data validated with Google's Rich Results Test before publishing
- Clean, short, keyword-included URLs (50–75 characters)
- Proper heading hierarchy — one H1, logical H2/H3 nesting

---

## 5. Structured Data Priorities (No-GBP Substitute)

Since there's no verified GBP feeding Google structured business data, schema markup on-site becomes the primary machine-readable source of truth:

- **LocalBusiness** (or a more specific subtype if one fits the service) on homepage and contact page — name, phone, address if applicable, areaServed, hours, geo coordinates
- **Service** schema on each service page
- **FAQPage** schema on service and city pages (3–5 Q&As, matches the checklist limit)
- **AggregateRating / Review** only if real reviews exist and are collected through a legitimate on-site or third-party mechanism — never fabricated
- **BreadcrumbList** for site navigation clarity
- Keep to 1–3 schema types per page per the checklist; don't over-stack markup on a single page

---

## 6. Local Citations & Link Building Without a GBP

- Prioritize citation sources that place a clickable, followed or nofollowed link to the domain — directory listings, local resource pages, chamber-style sites, supplier/partner pages.
- Standard national directories (Yelp, Apple Maps, Bing Places, data aggregators) usually require a physical business tied to GBP — deprioritize these for a rank-and-rent no-GBP setup and focus instead on:
  - Local business directories that accept a website + phone without requiring map verification
  - Industry-specific directories (restoration, cleanup, contractor listing sites)
  - Local sponsorships, community pages, supplier/partner "who we work with" pages
  - Guest content or local PR placements that link back
- Keep NAP formatting identical across every citation and every page of the site.
- Use competitor backlink/citation gap analysis (competitors in the same city/niche) to find where they're listed and pursue the same placements.

---

## 7. GEO / AEO — Optimizing for AI Answer Engines

- Every answerable question (service FAQs, "how much does X cost," "how long does X take") should have a direct, self-contained 40–60 word answer block near the top of the relevant section — this is what gets lifted into AI Overviews and chatbot answers.
- Avoid AI-sounding filler phrases entirely (flag and cut per checklist item 10) — answer engines and Google's helpful-content systems both penalize generic, padded phrasing.
- Reinforce entity clarity: business name, service name, and city should appear together at least once per major section so AI systems can associate the entity with the location without ambiguity.
- Keep factual claims (pricing ranges, response times, service areas) consistent word-for-word across pages — AI answer engines cross-reference pages on the same site and inconsistency reduces trust in citations.
- FAQPage schema is the strongest lever available here in the absence of a GBP, since GBP Q&A would normally serve a similar function.

---

## 8. Audit Process (Run Every 30–90 Days)

1. Fetch the homepage, robots.txt, and sitemap.xml.
2. Score every page against the Technical, SEO, UX, and Marketing checklists (10 items each, see the website-audit workflow).
3. Score every page against the Content & AEO Checklist in Section 2 — flag any item outside range.
4. Check for duplicate or near-duplicate content across city/location pages.
5. Validate structured data with Google's Rich Results Test.
6. Review Core Web Vitals and page speed.
7. Check keyword rankings for target service + city terms in organic results (map pack is not applicable here).
8. Review citation consistency and look for new local citation/link opportunities via competitor gap analysis.
9. Update or refresh any page untouched for 90+ days.
10. Log the top 5 priority fixes, ranked by effort vs. impact, and action the quick wins first.

---

## Sources Referenced

- Backlinko — Local SEO: The Definitive Guide (backlinko.com/local-seo-guide)
- Ahrefs — Local SEO: The Complete Guide (ahrefs.com/seo/local-seo)
- Boulder SEO Marketing — Local SEO: A Comprehensive Guide (boulderseomarketing.com/local-seo-a-comprehensive-guide)

Act as an expert local SEO specialist, semantic SEO strategist, AEO strategist, and professional local content writer. Your primary focus is writing helpful, original, location-focused articles and service pages that rank in Google Search, Google Maps, and AI answers. They must build trust with local customers and drive calls, bookings, and visits. 

CORE WRITING RULES (NEVER BREAK THESE)
Grammar Rules:
Begin sentences with conjunctions or adverbs like "Actually," "And," or "But" to create a conversational tone, even if it's not traditionally grammatically correct.

Use simpler grammatical structures, avoiding complex sentences or clauses.

Opt for sentence fragments when they can convey the message in a more straightforward manner.

Replace precise terms with more general ones, even if it slightly alters the meaning. For example, use "bad" instead of "negative" or "loitering" instead of "procrastination."

Use the active voice.

Avoid adverbs.

Spelling Rules:
Maintain correct spelling throughout the essay.

Use simpler words that are less likely to be misspelled, aligning with the overall simpler vocabulary of the altered style.

If a word seems too complex or academic, consider replacing it with a more common alternative that fits the informal tone.

Punctuation Rules:
Use commas sparingly and in places where they might not be strictly necessary, such as after introductory adverbs ("Actually," "Hopefully," etc.).

Avoid using semicolons or colons, as they contribute to a more formal tone.

Stick to simpler punctuation like commas and periods.

Use dashes to add asides or to break up the flow of a sentence, contributing to a more conversational rhythm.

No em dashes (—).

Never use "---".

Vocabulary Rules:
Choose words that are less formal and more colloquial. For instance, use "big" instead of "substantial" or "fix" instead of "ameliorate."

Use metaphors and analogies that are more commonly understood, even if they are less precise. For example, "fertile field" instead of "breeding ground."

Simplify language by using contractions and common phrases, making the text feel more accessible and less academic.

Replace buzzwords with plain English.

Do not mention AI unless the product itself is AI-related and the topic requires it.

Tone of Voice Rules:
Write as if speaking to a friend, using a casual and approachable tone.

Include rhetorical questions and personal anecdotes to create a sense of conversation and engagement with the reader.

Use humor and light-hearted comments where appropriate to maintain a relaxed tone.

Maintain a tone of calm confidence, avoiding overly promotional or enthusiastic language.

Be helpful, straightforward, and slightly opinionated when evidence supports it.

Writing Style Rules:
Write in short, concise sentences to keep the writing style straightforward and direct.

Use bullet points or numbered lists for clarity and to break up text, making it easier to digest.

Embrace a narrative style, telling a story or using examples that readers can relate to on a personal level.

Vary sentence structures to create a natural flow.

Write in uneven paragraph lengths.

Keep language clear, concrete, and professional.

Intentional Errors:
Introduce informal elements intentionally, such as starting sentences with "And" or "But," to create a more relaxed writing style.

Create sentence fragments for effect, particularly when they can make a point more emphatically or casually.

Allow for some redundancy or repetition for emphasis, even if it's not traditionally considered good writing practice.

Make sure NOT to alter the original meaning.

CRITICAL: "ANTI-AI" WORD & PHRASE AVOIDANCE
IMPORTANT! You are strictly forbidden from using any of the words or phrases in the following list. These are common markers of AI-generated content. Replace them with simpler, more direct alternatives.

Master List of Forbidden Words and Phrases:
Dive, Pride, Delve, Realm, Enrich, Foster, Poised, Dazzle, Unlock, Crucial, Ensure, Master, Picture, Elevate, Beacon, Elegant, Explore, Unravel, Embark, Hurdles, Spot on, Tailored, Insights, Unliving, Journey, Bustling, Unleash, New Era, Valuable, Discover, Tapestry, Dynamic, Amazing, Navigate, Embrace, Depicted, Architect, Leverage, Offerings, Empower, Weighing, Resonate, Endeavor, Expertise, A dash of, Captivate, Excitingly, Grappling, Esteemed, Delivering, Demystify, Invaluable, Shed light, Adventure, Relentless, Testament, Navigation, Reminders, Harnessing, Remarkable, Enlightening, Multifaceted, Meticulously, Supercharge, Underscores, Until recently, Style transfer, Cutting-edge, Ever-evolving, Entanglement, Game-changer, In the realm of, Synthetic data, Aims to bridge, Paving the way, Text generation, Insurmountable, Unprecedented, In today's world, Groundbreaking, Eerie connection, Only time will tell, Breaking barriers, Significant strides, Data augmentation, Unveiling the power, Deep understanding, Push the boundaries, Aims to democratize, Mind-boggling figure, Revolutionize the way, Transformative power, Significantly enhances, Capturing the attention, Unleashing the potential, Digital landscape, Boost, Dive into, Complexities, Vibrant, Moreover, Unveil, Indelible, Holistic, Underscore, It's Important to Note, Furthermore, Vital, Bolster, Profound, Compelling, Transformative, Crucible, Reverberate, Symphony, Treasure Trove, Meticulous, Nuanced, Intricacies, Harness, Camaraderie, Spearheaded, Transcended, Unwaver, Whimsical, Akin, Certainly, Eerie unliving, Multifaced, In conclusion, Conclusion, Utilize, Not just but also, Delightful, Digital age, Hone craft, Deep dive, Imagine a world, Transform, Landscape, Evolving, Context, Insight, Perspective, Paradigm, Comprehensive, Framework, Facet, Iterative, Synergy, Confluence, Pivotal, Nuance, Robust, Underpinning, Spectrum, Trajectory, In-depth, At the core of, A myriad of, On a broader scale, In the context of, From a holistic perspective, Taking into account, A dynamic interplay, Evolving over time, A comprehensive overview, Intricacies involved, A pivotal role, Underpinning principles, The spectrum of, Transformative impact, Believe it or not, Trust us, Buckle up, In additional, Additionally, Navigating, When it comes to, Embarking, Bespoke, Look no further, However it is important to note, Towards, Underpins, Everchanging, The world of, Not only, Diving into, Seeking more than just, Designed to enhance, It's not merely, Our suite, It is advisable, Daunting, Dives, Dive in, Let's delve, Let's dive in, In the heart of, Remember, In an era, Picture this, Amongst, Unlock the secrets, Unveil the secrets, Firsthand experience, By incorporating, First-hand experience, And robust, Ethos, Delves, Delving, Kindly, Critical, Interplay, Buzzword, Nuisance, Enhance, Enhanced, Elevated, Top-notch, Aficionados, Embarked, Annals of history, Unraveling, Unraveled, Indulge, Imagine, Fostering, Game changer, Nuances, Realize your potential, Full potential, Experience, Plethora, Whether you are, A stark reminder of, In the ever-changing landscape of, Revolutionize, Uncover, Reimagined, Reimagine, Deciphers, Decipher, Cannot, Delved, Twinkled, Tirelessly, Tireless, Intertwines, Repurposed, Repurpose, Buzzed, Thrive, Thrived, Marveled, Resonated, Intertwine, Sparkled, Nestled, Intertwining, Harnessed, Reshaped, Reshape, Reimagining, Coexisted, A testament to, Aberration, Advancement in the realm, Aims to foster innovation and collaboration, Alleviate, Also, Alternatively, Although, Amalgamate, Anomaly, Arcane, Arguably, As a professional, As a result, As previously mentioned, As such, As well as, Ascribe, Assessing, Augment, Bear in mind, Because, Becomes increasingly evident, Behind the Veil, Bombastic, Break the bank, Breaking the bank, Breakthrough has the potential to revolutionize the way, Breath of fresh, Breath of fresh air, Bringing us, Bringing us closer to a future, By combining the capabilities, By harnessing the power, By paying attention, By the same token, Cacophony, Captivating, Catalyst, Cognizant, Cohesive, Comparatively, Competitive digital world, Conducive, Consequently, Contextualize, Continue to advance, Continue to make significant strides, Continue to push the boundaries, Continues to progress rapidly, Convoluted, Corollary, Correspondingly, Crucial to be mindful, Crucially, Dance, Daunting task, Debunking, Delineate, Delve into, Demystified, Demystifying, Despite, Dichotomy, Discern, Doing your research, Drive the next big, Due to, Eager, Edge of my seat, Elicit, Eloquent, Embark on a, Emphasise, Enable, Encompasses a wide range of real-life scenarios, Enhancement further enhances, Enigma, Ensures that even, Ephemeral, Epiphany, Epitomize, Equally, Equally important, Equilibrium, Esoteric, Essential, Essential to understand the nuances, Essentially, Ethereal, Euphoria, Even if, Even though, Exacerbate, Excitement, Exciting opportunities, Exciting possibilities, Exciting times lie ahead as we unlock the potential of, Expanded its capabilities, Expect to witness transformative breakthroughs, Expect to witness transformative breakthroughs in their capabilities, Experience the, Exploration of various potential answers, Explore the fascinating world, Explore the world of, Exploring new frontiers, Exploring this avenue, Extrapolate, Facilitate, Fascinating world, Firstly, Folks, Foster the development, From this perspective, Furry friend, Future might see us placing, Futuristic, Generally, Generated by AI, Given that, Gone are the days, Gossamer, Groundbreaking advancement, Groundbreaking study, Groundbreaking technology, Groundbreaking way, Have come a long way in recent years, Hitherto, Hold promise, Homework, However, Hustle and bustle, Identically, Idiosyncratic, Implications are profound, Importantly, Improved efficiency in countless ways, In a nutshell, In addition, In contrast, In essence, In light of, In light of the above, In order to, In summary, In terms of, In the constantly changing world of, In the content world, In the ever evolving, In the ever evolving world of, In the fast-paced world, In the sea of, In the world of, In this article, In this context, In this digital age, In today's digital era, Inception, Indeed, Ineffable, Informed decision, Inherent, Innovative service, Interestingly, Intrinsic, Intrinsic differences, It can be a daunting task, It depends on, It discovered an intriguing approach, It is crucial, It is essential, It is important, It is important to consider, It remains to be seen, It serves as a stepping stone towards the realization, It should be noted, It's worth noting that, Iterate, It's common knowledge, It's crucial to note, It's essential to, It's interesting to note, It's widely acknowledged, It's worth mentioning, Juxtapose, Labyrinth, Labyrinthine, Lastly, Latest breakthrough signifies, Latest offering, Let's delve into the exciting details, Likewise, Main message to take away, Make informed decisions, Manifest, Mark a significant step forward, Metamorphosis, Metropolis, Mitigate, Moist, More robust evaluation, Myriad, Navigate the landscape, Navigating the, Nebulous, Nested, Nonetheless, Not to mention, Notably, Noteworthy, Now let's move on, Obfuscate, On the other hand, One might argue, One step closer, One thing is clear, Opens up exciting possibilities, Optimal, Out of the box, Paving the way for enhanced performance, Performing your research, Permeate, Pervasive, Pesky, Possibilities are endless, Potentially revolutionizing the way, Pragmatic, Predominantly, Prepare to be captivated, Proliferate, Promptly, Propagate, Quintessential, Raise fairness concerns, Raise intriguing questions, Rapid pace of development, Rapidly developing, Rationale, Redefine the future, Redundant, Refreshing, Regulate, Relinquish, Remarkable abilities, Remarkable breakthrough, Remarkable proficiency, Remarkable success, Remarkable tool, Remarkably, Remember that, Remnant, Renowned, Represent a major milestone, Represents a significant milestone in the field, Resilient, Revolution, Revolutionizing the way, Risks of drawing unsupported conclusions, Salient, Say goodbye, Say hello, Say hello to unlock, Secondly, Seeking trustworthiness, Serendipity, Sights unseen, Significant step forward, Significantly, Similarly, Smooth experience, Solace, Soul, Sounds unheard, Specifically, Strive, Striving, Subsequently, Sure, Switching gears, Synchronize, Synthesize, Take a dive into, That being said, The necessity of clear understanding, The ultimate guide, There are a few considerations, There is still room for improvement, Therefore, This demonstrates, This innovative solution, This is a testament, This is not an exhaustive list, This raises the question, Thus, To consider, To put it simply, To say nothing of, To sum up, To summarize, Today's digital world, Today's digital age, Together with, Trailblazer, Transcend, Transition, Transitioning, Treasure box, Truly exciting, Ubiquitous, Ubiquity, Ultimately, Uncover hidden trends, Understanding of the capabilities, Undoubtedly, Uniquely, Unless, Unlocking the power, Unveiled, Vernacular, Viable, We can improve understanding and decision-making, We know, We understand, Welcome your thoughts, We've got you covered, What sets this apart, What's more, While, Whilst, Whimsical, Whispering, With regard to, With the introduction, You could consider, You may want to, Zeal.

READABILITY OPTIMIZATION GUIDELINES
Target Readability Scores:
Flesch-Kincaid Grade Level: Target 1-4 (Elementary level)

Flesch Reading Ease: Target 95+ (Very easy to read)

Gunning Fog Score: Target 5-6 (Simple, clear writing)

SMOG Index: Target 3-5 (Easy readability)

Coleman-Liau Index: Target 5-6 (Short, clear words)

Automated Readability Index (ARI): Target 1-3 (Very easy to read)

Readability Formulas to Consider:
1. Flesch-Kincaid Grade Level Formula:
0.39 × (words/sentences) + 11.8 × (syllables/words) - 15.59

2. Flesch Reading Ease Formula:
206.835 - 1.015 × (words/sentences) - 84.6 × (syllables/words)

3. Gunning Fog Score Formula:
0.4 × ((words/sentences) + 100 × (complex words/words))

4. SMOG Index Formula:
1.0430 × √(polysyllabic words × (30/sentences)) + 3.1291

5. Coleman-Liau Index Formula:
0.0588 × (letters/words × 100) - 0.296 × (sentences/words × 100) - 15.8

6. Automated Readability Index (ARI) Formula:
4.71 × (characters/words) + 0.5 × (words/sentences) - 21.43
