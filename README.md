# oxylabs pricing: Every Plan, Per-GB Rate and Hidden Cost, Plus a Cheaper Option That Starts at $15

Type "oxylabs pricing" into a search bar and you'll meet three different numbers before you reach anything you can buy. The nav dropdown advertises residential "from $2.50/GB." The pricing hero says "from $6/GB." The plan cards say $30 for 5GB. All three are real, and none of them answer the question you actually have: what will this cost *my* project?

Oxylabs sells a lot more than one product, and each one is billed differently — per GB, per IP, per 1,000 scraping results, or per credit. Here's the whole grid, where the pricing gets sharp, and what a much cheaper provider charges for the same traffic.

## The numbers, in one place

If you only remember four lines, make them these:

- **Residential proxies** are billed per GB, with self-serve plans from $30/month (5GB) to $2,500/month (1TB).
- **Datacenter proxies** start at $2.25 per IP per month, with a three-IP minimum.
- **ISP (static residential) proxies** start at $1.60 per IP, in 10-IP blocks.
- **Web Scraper API** starts at $49/month, billed per 1,000 successful results.

Everything below is the detail behind those four lines.

## Oxylabs residential pricing: four tiers and one painful gap

Residential is the product most people are comparing, and the self-serve structure is simple enough:

| Plan | Traffic | Monthly price | Effective rate |
| --- | --- | --- | --- |
| Starter | 5GB | $30 | $6.00/GB |
| Basic | 20GB | $100 | $5.00/GB |
| Advanced | 125GB | $500 | $4.00/GB |
| Corporate | 1TB | $2,500 | $2.50/GB |

Notice the jump. Between 20GB and 125GB there is nothing — a gap that's widely flagged in third-party breakdowns and one of the most common complaints about Oxylabs pricing. If your project uses 50GB a month, your options are to buy the $500 tier and leave 75GB on the table, or buy the $100 tier and top up mid-cycle. Neither is elegant.

Pay-as-you-go exists too, but the rate is quoted inconsistently depending on where you look. One independent breakdown puts standard PAYG at $8/GB with a capped promotional rate around $4/GB; older reviews list $4/GB as the plain entry rate. Oxylabs has effectively changed this over time, and the site itself doesn't reconcile its own numbers — the navigation says $2.50/GB (that's the $2,500 tier), the hero says $6/GB (that's the $30 tier).

The residential cards do include things worth counting: unlimited concurrent sessions, three proxy users, sticky sessions that hold the same IP for up to 24 hours, free geo-targeting, and 10 whitelisted IPs. Oxylabs claims 175M+ IPs across 195 countries.

One catch hidden in the feature list: **IPv4/IPv6 selection and OS filters are inactive on Starter, Basic, and Advanced.** They only unlock on plans that come with a dedicated account manager, which in practice means Corporate. If your workflow depends on picking IPv6 exits or filtering by operating system, the $500 tier isn't optional.

## The rest of the Oxylabs price list

Residential gets the attention, but most of Oxylabs' products are priced by IP or by result, and those rates behave very differently.

| Product | Billing model | Entry price | Notes |
| --- | --- | --- | --- |
| Dedicated datacenter | Per IP, monthly | $2.25/IP (3-IP minimum = $6.75/mo) | Unlimited bandwidth under fair use, 10,000 concurrent sessions; custom pricing above 3,000 IPs |
| Shared datacenter | Per IP | First five IPs free | Cheapest entry point in the whole catalogue |
| ISP / static residential | Per IP, monthly | $1.60/IP (10–49 IPs) | $1.45 (50–99), $1.30 (100–199), $1.20 (200–499), $1.15 (500–999), $1.10 (2,000+) |
| Rotating ISP | Per GB, monthly | $340/mo for 20GB ($17/GB) | $700 for 50GB ($14/GB), $1,100 for 100GB ($11/GB), enterprise from $6,000 |
| Premium ISP | Per IP | From $3.80/IP at 1,000+ IPs | Listed as coming soon |
| Mobile proxies | Per GB | Priced above residential | Enterprise-oriented, custom pricing at the top end |
| Web Scraper API | Per 1,000 results | From $49/mo | Feature-based billing since mid-2025: different rates for Google, Amazon, JS-rendered and non-JS targets |
| AI Studio (AI-Scraper, AI-Crawler, AI-Map) | Per credit | From $12/mo for 3,000 credits | 1 request/second at entry, more at higher tiers |

Two things stand out here. First, annual billing gets you 10% off across the board, which is the only standing discount I could find on the site — there's no public coupon code doing better than that. Second, the ISP and datacenter products carry a fair usage policy that isn't obvious from the price. On ISP proxies, each IP gets 100 concurrent sessions until it has moved 50GB in a billing cycle; past that, sessions drop to 10 per IP. Buy 100 IPs expecting 10,000 concurrent sessions and you'll hit that wall at 5TB.

## Free trial, refunds, and the parts that aren't on the pricing page

The free trial is real but request-based. It isn't a checkout SKU you click — you go through the contact form or email support, and it's a one-time thing. Web Scraper API gets a more generous offer: up to 2,000 results, no time limit. AI Studio tools start with 1,000 credits.

Refunds are tighter than the trial. Self-serve plans are reported to have a three-day refund window, and pay-as-you-go data isn't refundable at all. Add a KYC step for certain ISP targets — reviews mention verification taking anything from days to weeks — and the "just try it" path has more friction than the pricing page suggests.

## Where the per-GB model stops making sense

Oxylabs pricing is built for companies that can commit to a $500 or $2,500 line item and keep it steady. Above 1TB a month, the per-GB rates get genuinely competitive with Bright Data and Decodo, and the enterprise contracts are a different conversation entirely.

Below that, the maths gets ugly fast:

- Under 50GB a month, you're paying $6/GB with no tier that fits you properly.
- If your bandwidth is unpredictable — say you scrape JS-heavy pages that vary between 2MB and 5MB each — a per-GB bill is a variable you can't budget.
- If your real problem is session stability rather than volume, you're paying for data you won't use.

That last point is the interesting one. Plenty of people searching for Oxylabs pricing aren't shopping for 500GB of traffic. They need a few hundred sticky residential IPs that don't die mid-session, or a predictable monthly cost they can plan around.

## 9Proxy: the same job, billed per IP instead of per GB

9Proxy takes a different route. It's a residential network with 20M+ IPs across 90+ countries, and it offers two billing models side by side: pay per IP with unlimited bandwidth per IP, or pay per GB. That split matters, because the two models solve different problems.

The per-IP model is for fixed sessions — account work, cart sessions, anything where the IP has to stay put. You buy a block of IPs, bandwidth is unmetered, and unused IPs never expire. The per-GB model is for high-rotation work: generate as many endpoints as you like, sticky or rotating, authenticated by username/password or IP whitelist, running straight from the dashboard without installing anything. GB plans are valid for 180 days, or indefinitely on Enterprise.

👉 [Start with a 9Proxy package and compare the per-IP rates against your Oxylabs quote](https://bit.ly/9-Proxy)

### IP-based packages (unlimited bandwidth)

| Package | Rate per IP | Total | Validity | Get started |
| --- | --- | --- | --- | --- |
| 100 IPs | $0.24 | $24 | IPs never expire | [Grab 100 IPs](https://bit.ly/9-Proxy) |
| 500 IPs | $0.144 | $72 | IPs never expire | [Grab 500 IPs](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $0.084 | $126 | IPs never expire | [Grab 1,500 IPs](https://bit.ly/9-Proxy) |
| 2,500 IPs | $0.084 | $210 | IPs never expire | [Grab 2,500 IPs](https://bit.ly/9-Proxy) |
| 5,000 IPs | $0.072 | $360 | IPs never expire | [Grab 5,000 IPs](https://bit.ly/9-Proxy) |
| 15,000 IPs | $0.048 | $720 | IPs never expire | [Grab 15,000 IPs](https://bit.ly/9-Proxy) |
| 25,000 IPs | $0.035 | $863 | IPs never expire | [Grab 25,000 IPs](https://bit.ly/9-Proxy) |
| 50,000 IPs | $0.029 | $1,438 | IPs never expire | [Grab 50,000 IPs](https://bit.ly/9-Proxy) |
| 100,000 IPs (Business) | $0.023 | $2,300 | IPs never expire | [Grab 100,000 IPs](https://bit.ly/9-Proxy) |
| 200,000 IPs (Business) | $0.021 | $4,140 | IPs never expire | [Grab 200,000 IPs](https://bit.ly/9-Proxy) |
| 500,000 IPs (Business) | $0.018 | $8,625 | IPs never expire | [Grab 500,000 IPs](https://bit.ly/9-Proxy) |

Worth knowing before you compare: 9Proxy raised IP-based and bundle prices on 1 June 2026, its first adjustment since launch. GB-based pricing was left untouched by that change, which is why the per-GB rates below still look the way they did when the product first shipped.

### GB-based packages

| Package | Rate per GB | Total | Validity | Get started |
| --- | --- | --- | --- | --- |
| 5GB | $3.00 | $15 | 180 days | [Start with 5GB](https://bit.ly/9-Proxy) |
| 50GB + 5GB bonus | $2.10 | $105 | 180 days | [Get 55GB](https://bit.ly/9-Proxy) |
| 100GB | $1.50 | $150 | 180 days | [Get 100GB](https://bit.ly/9-Proxy) |
| 200GB | $1.00 | $200 | 180 days | [Get 200GB](https://bit.ly/9-Proxy) |
| 1,000GB | $0.80 | $800 | 180 days | [Get 1TB](https://bit.ly/9-Proxy) |
| 2,000GB | $0.75 | $1,500 | 180 days | [Get 2TB](https://bit.ly/9-Proxy) |
| 10,000GB | $0.68 | On request | 180 days | [Ask about 10TB](https://bit.ly/9-Proxy) |
| Enterprise | VIP pricing | Custom | Unlimited | [See Enterprise terms](https://bit.ly/9-Proxy) |

The Enterprise tier adds team access for one owner plus up to five members, no expiry on shared bandwidth, per-member traffic controls, full activity logs, and unlimited share-code creation.

### Bundle packages

If you need both stable IPs and rotation capacity, the bundles are cheaper than buying separately.

| Bundle | What's included | Price | Get started |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5GB | $30 | [Get the Starter bundle](https://bit.ly/9-Proxy) |
| Popular | 1,500 IPs + 50GB | $180 | [Get the Popular bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500GB | $720 | [Get the Pro bundle](https://bit.ly/9-Proxy) |

Bundle traffic keeps the 180-day validity, so unused balance doesn't evaporate at the end of the month.

## Same volume, two very different invoices

This is the comparison that actually decides things. Both columns below are published pricing, no discounts applied:

| Monthly traffic | Oxylabs | 9Proxy |
| --- | --- | --- |
| 5GB | $30 (Starter) | $15 |
| 20GB | $100 (Basic) | $60 (four 5GB packs) or $105 (50+5GB pack) |
| 50GB | $500 — no 50GB tier exists, next step is 125GB | $105 (50+5GB pack) |
| 100GB | $500 (Advanced, 125GB) | $150 |
| 1TB | $2,500 (Corporate) | $800 |

At 1TB the gap narrows to roughly 3x. At 50GB it's close to 5x, mostly because Oxylabs has no tier between 20GB and 125GB. The comparison flips somewhat when you count IP pool size — 175M+ for Oxylabs against 20M+ for 9Proxy — and when you need ASN-level targeting or the compliance paperwork that comes with enterprise procurement.

## Where 9Proxy is genuinely different, and where it isn't

Honest limits, because a pricing comparison that ignores them is useless:

- **Pool size.** 175M+ versus 20M+ IPs. For most scraping and multi-account work that gap doesn't show up in the results, but for rare geographies it can.
- **IP lifetime.** Residential IPs are real people's connections, and they drop. 9Proxy's own support has said as much publicly: if you need one IP to hold for weeks, static ISP is the right product, not a rotating residential pool. That's true of Oxylabs' residential network too, but the per-IP model makes it more visible.
- **Review spread.** 9Proxy's Trustpilot pages are all over the place — one regional page scores it 4.6/5, another 2/5. Read the negative reviews for the pattern rather than trusting the average. The recurring theme is session stability on long-running tasks, which circles back to the previous point.
- **Setup.** IP-based plans require the desktop app for local port forwarding. GB-based plans don't — they run entirely from the dashboard.
- **What both do well.** HTTP/HTTPS and SOCKS5, country/city/ZIP/ISP targeting, low blacklist rates, 24/7 support.

On the operational side, 9Proxy's dashboard rebuild added a proxy generator with sticky or rotating sessions, unlimited endpoint creation, and export to .txt or .csv, plus a "Today List" feature that lets you reuse IPs from the previous 24 hours for free — the kind of thing that quietly shaves 20–30% off a scraping bill. Auto-refresh replaces dead IPs within about a minute.

## So which one do you actually need?

If your traffic is steady, high-volume, and you need enterprise compliance, ASN targeting, or someone contractually accountable when a target site changes its defences — Oxylabs is the right purchase. The 1TB rate of $2.50/GB is competitive, and the per-GB model rewards scale. Just budget the $500 tier or above to get there.

If your traffic is spiky, you're under 100GB a month, or your real constraint is how many stable IP sessions you can hold rather than how much data you can move, Oxylabs pricing is shaped wrong for the job. That's the case where a per-IP, unlimited-bandwidth model wins on both cost and predictability — and it's a $24 entry point rather than a $500 one.

👉 [Compare the full current 9Proxy pricing and pick the package that matches your volume](https://bit.ly/9-Proxy)

## Frequently asked questions

**Why does Oxylabs say "from $2.50/GB" when the cheapest plan is $6/GB?**
Because $2.50/GB is the Corporate tier at $2,500/month. The navigation dropdown and the pricing hero quote different tiers, which is why the entry price looks lower than it is until you reach the plan cards.

**Does Oxylabs have a free plan?**
No free tier is advertised on the public pricing page. There's a one-time free trial you request through support rather than a self-serve button, plus a free trial for Web Scraper API that covers up to 2,000 results with no time limit.

**Can I pay for Oxylabs monthly without committing?**
Yes — Starter through Corporate are monthly self-serve plans, and pay-as-you-go exists for residential traffic. The catch is the per-GB rate: it only drops meaningfully once you commit to the $500 or $2,500 tier.

**What's the cheapest way to start with 9Proxy?**
A 5GB GB-based package at $15, or 100 IPs at $24 if you'd rather pay per IP with unlimited bandwidth. Neither expires at the end of a billing cycle, so you can test the network without watching a countdown.
