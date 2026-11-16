# Vultr vs Hetzner: why the starting price is $2, $3.50 or $6, which plans are actually in stock, and who wins at 1, 4, 8 and 16 GB of RAM (full Vultr plan table)

Hetzner is cheaper at equal memory at 2 GB and above, and at 4 GB and up it isn't close. A price check on 12 November 2026 put its cheapest orderable plan at $5.97 a month against $6.00 at Vultr, with Hetzner 10% to 33% below Vultr at 2, 4, 8 and 16 GB of RAM. The word "orderable" is doing a lot of work in that sentence: Hetzner's cheapest lines, CX and CAX, were showing as unavailable at the same check, which pushes you onto CPX and dedicated CCX plans at prices well above the one you clicked on.

Vultr wins where Hetzner has nothing to sell: 30-plus locations against 6, managed Kubernetes and managed databases, GPU instances, and 4 GB machines whose random disk throughput measured several times higher than Hetzner's cheapest equivalent.

> **Running a web app, API or bot near your users:** Vultr's Cloud Compute 2 vCPU / 4 GB at $20/mo is the safest default, and the High Performance version at $24/mo has newer CPUs. 👉 [Check Vultr's current plan pricing](https://bit.ly/VuLtr)
> **Running a memory-heavy backend in Germany, Finland or the US:** Hetzner CPX or CCX, after you confirm the plan is in stock and add the extra IPv4 charge.

## Every Vultr plan with a price attached

Vultr sells six families, and the cheap one is not the one most sites should buy. Cloud Compute (the vc2 line) is the budget tier on older shared CPUs. High Performance and High Frequency run newer AMD and Intel silicon with NVMe. CPU Optimized and Optimized Cloud Compute trade memory for dedicated or near-dedicated cores. VX1 is the newest generation, and Bare Metal is exactly what it sounds like.

Prices below are monthly list prices collected on 12 November 2026. Vultr's pricing page carries more sizes than any third-party tracker follows, and the per-region price can differ, so treat the table as the shape of the lineup rather than a quote.

| Plan | vCPU / RAM | Monthly | Order |
| --- | --- | --- | --- |
| Cloud Compute vc2-1c-0.5gb | 1 / 512 MB | $3.50 | [Start here](https://bit.ly/VuLtr) |
| Cloud Compute vc2-1c-1gb | 1 / 1 GB | $5.00 | [Start here](https://bit.ly/VuLtr) |
| Cloud Compute Regular 2 GB | 1 / 2 GB | $10.00 | [Start here](https://bit.ly/VuLtr) |
| Cloud Compute vc2-2c-2gb | 2 / 2 GB | $15.00 | [Start here](https://bit.ly/VuLtr) |
| Cloud Compute vc2-2c-4gb | 2 / 4 GB | $20.00 | [Start here](https://bit.ly/VuLtr) |
| Cloud Compute vc2-4c-8gb | 4 / 8 GB | $40.00 | [Start here](https://bit.ly/VuLtr) |
| Cloud Compute vc2-16c-64gb | 16 / 64 GB | $320.00 | [Start here](https://bit.ly/VuLtr) |
| High Performance AMD 1 vCPU / 1 GB | 1 / 1 GB | $6.00 | [Start here](https://bit.ly/VuLtr) |
| High Performance 1 vCPU / 2 GB | 1 / 2 GB | $12.00 | [Start here](https://bit.ly/VuLtr) |
| High Frequency 1 vCPU / 2 GB | 1 / 2 GB | $12.00 | [Start here](https://bit.ly/VuLtr) |
| High Performance AMD 2 vCPU / 2 GB | 2 / 2 GB | $18.00 | [Start here](https://bit.ly/VuLtr) |
| High Performance 2 vCPU / 4 GB | 2 / 4 GB | $24.00 | [Start here](https://bit.ly/VuLtr) |
| High Frequency vhf-3c-8gb | 3 / 8 GB | $48.00 | [Start here](https://bit.ly/VuLtr) |
| High Performance 4 vCPU / 8 GB | 4 / 8 GB | $48.00 | [Start here](https://bit.ly/VuLtr) |
| High Performance AMD 4 vCPU / 12 GB | 4 / 12 GB | $72.00 | [Start here](https://bit.ly/VuLtr) |
| High Performance AMD 8 vCPU / 16 GB | 8 / 16 GB | $96.00 | [Start here](https://bit.ly/VuLtr) |
| High Performance vhp-12c-24gb-intel | 12 / 24 GB | $144.00 | [Start here](https://bit.ly/VuLtr) |
| CPU Optimized 1-2-25 | 1 / 2 GB | $28.00 | [Start here](https://bit.ly/VuLtr) |
| CPU Optimized voc-g-1c-4gb-30s | 1 / 4 GB | $30.00 | [Start here](https://bit.ly/VuLtr) |
| CPU Optimized 2-4-50 | 2 / 4 GB | $40.00 | [Start here](https://bit.ly/VuLtr) |
| CPU Optimized voc-c-32c-64gb-500s-amd | 32 / 64 GB | $640.00 | [Start here](https://bit.ly/VuLtr) |
| VX1 GP 2C 8G 50S | 2 / 8 GB | $48.80 | [Start here](https://bit.ly/VuLtr) |
| VX1 GP 2C 8G 120S | 2 / 8 GB | $55.48 | [Start here](https://bit.ly/VuLtr) |
| VX1 GP 4C 16G 240S | 4 / 16 GB | $110.16 | [Start here](https://bit.ly/VuLtr) |
| VX1 48C 192G | 48 / 192 GB | $1,051.20 | [Start here](https://bit.ly/VuLtr) |
| Bare Metal | From $120.00 | — | [Start here](https://bit.ly/VuLtr) |

Local SSD runs from 10 GB on the 512 MB plan to 1.3 TB on the 16 vCPU / 64 GB Cloud Compute plan. Vultr's own product page quotes the 2 vCPU / 4 GB Cloud Compute instance at $20.00 a month with 80 GB of local SSD and 3 TB of bandwidth in Chicago, which is the one row above I can tie directly to the vendor.

## Why one article says $2 and another says $6

Four starting prices circulate, and each answers a different question. None of them is wrong in its own terms, which is why the comparison never resolves on its own.

| Number you've seen | Where it comes from | Why it isn't what you'll pay |
| --- | --- | --- |
| $2.00 / $2.50 | A comparison page dated January 2026 | The page itself warns that pricing changes often and some data may be outdated, and Hetzner repriced in June 2026 |
| $3.50 | Vultr's cheapest Cloud Compute plan | It's 512 MB, and it does include IPv4 |
| $5.97 / $6.00 | Cheapest orderable 1 GB plan at the 12 November 2026 check | Hetzner's figure excludes IPv4, and that CPX plan may be out of stock |
| $6.08 | Hetzner CPX 02 plus a public IPv4 | Different RAM tier, so not a like-for-like comparison with $3.50 |

**The June 2026 repricing is the biggest single reason older numbers are wrong.** Hetzner raised cloud prices on 15 June 2026 at 8 AM CEST for new orders and for rescales of existing servers. Its own price-adjustment page lists CPX22 moving from $9.49 to $22.99 a month in Germany and Finland, CPX32 from $15.99 to $41.99, CCX13 from $18.49 to $50.49 and CX23 from $4.99 to $6.49, all before IPv4 and VAT. In the US locations the CPX line roughly tripled, with CPX21 going from $13.99 to $37.49. Only the CX and CAX lines moved by a quarter to a third. Any comparison written before mid-2026 understates Hetzner by a wide margin on exactly the plans it recommended.

**IPv4 flips the small end.** Vultr includes a public IPv4 address. Hetzner bills it separately. Add it and Hetzner's entry point lands at $6.08 a month while Vultr's smallest instance sits at $3.50, so the "Hetzner is cheaper" headline reverses on the cheapest tier and only holds once you're buying 1 GB of RAM or more.

**The cheapest Hetzner plans are also the ones sold out.** CX and CAX are cost-optimized lines built on hardware Hetzner buys opportunistically. Its documentation describes them as limited offerings whose availability depends on hardware supply and can take several weeks to restock. A stock count taken in November found 76% of Hetzner's tracked plans orderable against 95% at Vultr. That's why one comparison switched its whole Hetzner side to CPX and CCX: the cheap plans weren't buyable.

One tracker also notes a separate low-price tier with the note that it's offered only while supply lasts. If a plan page shows a price you can't add to cart, that's the mechanism.

## Same RAM, head to head

Prices and scores below come from third-party benchmark runs and price checks. Hetzner quotes per region in euros and dollars, IPv4 and VAT excluded, so your invoice won't match to the cent.

| RAM tier | Hetzner | Vultr | Benchmark score | 4K random write IOPS |
| --- | --- | --- | --- | --- |
| 1 GB | CPX 02, $6.08 | Cloud Compute vc2-1c-1gb, $5.00 | 118 vs 99 | 807 vs 4,027 |
| 4 GB | CX 23, $6.64 | Cloud Compute vc2-2c-4gb, $20.00 | 82 vs 125 | 1,161 vs 10,789 |
| 8 GB | CX 33, $9.96 | Cloud Compute vc2-4c-8gb, $40.00 | 129 vs 119 | 1,261 vs 5,364 |
| 16 GB | CAX31 (ARM), $23.81 | High Performance vhp-8c-16gb-amd, $96.00 | 203 vs 166 | 1,207 vs 1,281 |

The 4 GB row is the one that decides it for most people. Vultr's vc2-2c-4gb costs three times what Hetzner asks for CX 23, and in return you get roughly nine times the 4K random write throughput, more than double the raw CPU score and 613 Laravel requests per second against 241. On a database-backed app the disk number is the one you feel.

At 1 GB the gap goes the other way. Vultr's $5.00 instance is cheaper than Hetzner's $6.08 and writes random 4K blocks five times faster, but downloads at 1,677 Mbit/s against 7,115 Mbit/s on Hetzner's side, and Hetzner's composite score is higher. For a low-traffic site either works; for a seedbox or a mirror, Hetzner's network wins outright.

At 8 GB, Hetzner's CX 33 scores higher overall at a quarter of the price while Vultr's machine has the faster raw CPU (17,113 vs 12,616 MIPS) and the faster disk (5,364 vs 1,261 IOPS). That's a genuine trade, not a pricing accident.

The 16 GB row is Hetzner's best argument in the whole table: CAX31 is an ARM instance with 8 vCPU, 42,432 MIPS and 1,671 requests per second for $23.81. Nothing Vultr sells at that size comes close on composite score. The condition is that your stack has to build and run on aarch64, and CAX is one of the lines that shows up out of stock.

👉 [Compare the Vultr plans in this table](https://bit.ly/VuLtr)

## Cheaper per gigabyte, more expensive per core

The two providers win on different denominators, which explains a lot of the arguing online.

Hetzner's median price per GB of RAM is $6.29 against Vultr's $9.00, about 30% less, and its cheapest RAM works out to $3.77/GB against $6.00/GB. On the per-vCPU measure it reverses: Vultr's median is $12.75 per vCPU against Hetzner's $16.43.

So if your workload is memory-bound (caches, JVM heaps, Postgres with a big shared buffer, containers packed several to a host), Hetzner's lineup is built for you. If it's core-bound (encoding, scraping at concurrency, build agents), Vultr's per-core pricing is lower and its per-core throughput measured higher in most of the matched tiers.

One tracker reports a much wider spread, $1.04/GB against $4.38/GB, which comes from measuring the single cheapest plan rather than the median. Different method, four times the difference. Anyone quoting a per-gigabyte figure without saying which plan they used is telling you very little.

👉 [See what Vultr charges per vCPU across its families](https://bit.ly/VuLtr)

## Stability and provisioning speed

Tests across multiple servers of the same plan type put Hetzner's consistency score at 71 and Vultr's at 63, where anything above 65 counts as stable. That measures how much performance varies between two servers of the same plan, and Hetzner's tighter spread is consistent with its more uniform hardware mix.

Provisioning: Hetzner's median was 32 seconds, Vultr's 60 seconds with a mean of 77. Read that with the sample sizes in view, because Hetzner's figure comes from 2 servers and Vultr's from 12. Two servers is not a benchmark, it's an anecdote.

CPU models seen in the runs: Hetzner on AMD EPYC Milan and Intel Xeon Skylake; Vultr on AMD EPYC Milan, Rome and Turin plus Intel Broadwell, Skylake and Cascade Lake. The wider Vultr spread means the machine you get depends more on the region and the day.

The test methodology behind these numbers: web response and throughput, Geekbench 6 single and multi-core, Sysbench random and sequential disk I/O, memory, 10-thread network transfers of at least 10 seconds with three runs and the fastest kept, plus a 24-hour CPU endurance run measuring the coefficient of variation.

## Location beats brand

Vultr advertises 30 locations across 6 continents; trackers count 32 to 33 cities in 20 countries. Hetzner runs 6: Falkenstein, Nuremberg, Helsinki, Ashburn, Hillsboro and Singapore.

The two providers share exactly one city, Singapore. If your users or your data have to be somewhere specific, that overlap is usually the whole decision.

Measured latency from the nearest available data center to major exchange APIs, in milliseconds:

| Exchange | Hetzner | Vultr |
| --- | --- | --- |
| Bybit | 6.6 (Singapore) | 9.5 (Singapore) |
| Binance | 74.3 (Singapore) | 3.9 (Tokyo) |
| Coinbase | 59.0 (Ashburn) | 33.3 (Chicago) |
| Deribit | 32.5 (Falkenstein) | 12.3 (London) |

Those numbers measure distance to a data center, not provider quality. Hetzner's 6.6 ms to Bybit comes from being in Singapore, and Vultr's 3.9 ms to Binance comes from being in Tokyo. Put a Hetzner server in Ashburn and the Coinbase figure moves; put a Vultr server in Frankfurt and half of these rows change. Pick the city first, then the vendor that sells it. Vultr sells 32 cities Hetzner doesn't, including Tokyo, London, Amsterdam, Sydney, Mumbai, São Paulo and Toronto.

## What each one has that the other doesn't

**Vultr only:** Managed Kubernetes, Managed PostgreSQL at $15.00/month, Managed Redis at $15.00/month, GPU instances, and payment in cryptocurrency. If you want a managed database cluster without hiring for it, Hetzner has no product to sell you at any price.

**Hetzner only:** ARM instances (CAX), invoice billing, phone support during German business hours, and a much cheaper object store. Hetzner's S3-compatible object storage runs $7.19/TB per month against $18.43/TB at Vultr, which matters if you're storing backups or media at volume.

**Both:** hourly billing with a monthly cap, backups and snapshots, block storage, load balancers, DDoS protection, SSH key management, NVMe storage. Hetzner's block storage is listed at $0.06/GB/month and its load balancer at $7.75/month.

**Included traffic:** Hetzner ships 500 GB to 60 TB depending on the plan; Vultr ships 2 TB to 12 TB.

Plan ranges differ more than the marketing suggests. One tracker following 16 Vultr plans caps out at 24 GB RAM and 12 vCPU; another lists a 48 vCPU / 192 GB VX1 instance at $1,051.20 and a 32 vCPU / 64 GB CPU Optimized plan at $640. Hetzner's ceiling of 192 GB and 48 vCPU is real, but "Vultr has no big machines" is a limit of the comparison table, not of Vultr.

👉 [Look at Vultr's managed database and Kubernetes options](https://bit.ly/VuLtr)

## What reviewers actually say, and how much to trust it

G2's 2026 comparison gives Hetzner higher marks on meeting requirements (9.4/10), setup (9.3) and support (8.6); Vultr scores higher on ease of use (9.1 against 8.3) and roughly ties on product direction at 8.1 for both.

The sample sizes make those numbers less solid than they look. Hetzner's ratings rest on 7 to 12 responses per question. Vultr's rest on 146 to 234. A single unhappy reviewer moves Hetzner's support score by nearly a point. G2's own summary says reviewers found Vultr easier to use while Hetzner was easier to set up and administer, and that reviewers preferred doing business with Hetzner overall, but that conclusion is drawn from a Hetzner sample one-twentieth the size.

The complaint tags are more useful than the scores. Hetzner reviewers tag it "affordable" three times and "poor customer support" twice. Vultr reviewers tag it "ease of use" eleven times, "affordable" eight, "poor customer support" five and "payment issues" three. Read those as the shape of the risk: Vultr's billing system generates complaints that Hetzner's doesn't, and both have support that people complain about.

## FAQ

**Is Hetzner really cheaper than Vultr?**
At 2 GB of RAM and above, yes, by 10% to 33% at the 12 November 2026 check. At the entry level it depends on IPv4: a 1 GB Hetzner plan at $5.97 plus a separately billed IPv4 lands close to Vultr's $6.00 all-in, and Vultr's actual cheapest instance at $3.50 undercuts both.

**What does Vultr's cheapest plan get me?**
$3.50 a month buys 1 vCPU, 512 MB of RAM, 10 GB of local SSD and an included IPv4 address. That's enough for a static site, a proxy or a small bot. It is not enough to run a database-backed web app, so budget $20 for the 2 vCPU / 4 GB Cloud Compute plan if that's the goal.

**Do prices jump on renewal?**
Neither provider runs a first-year discount that expires. Both bill hourly and cap at the monthly price, so the list price is the list price in month twelve. What does change is the list itself: Hetzner moved CPX and CCX prices up sharply on 15 June 2026 for new orders and rescales, and existing servers on legacy pricing can switch to current pricing when you resize or make certain changes.

**Do both have a data center in Singapore?**
Yes, and it's the only city they share. Hetzner also has Falkenstein, Nuremberg, Helsinki, Ashburn and Hillsboro. Vultr covers those regions through Frankfurt, Tokyo, Seoul, Sydney, Mumbai and about 27 other cities.

**Which one if I need managed Postgres or Kubernetes?**
Vultr, and there's no second option here. Hetzner sells unmanaged cloud servers only, so the database and the control plane are yours to run.

## Which one to order

Match the plan to the workload and the map, in that order.

- **Static site, proxy, small bot, or a test box:** the $3.50 to $6 tier on whichever provider has a city near your users. The price difference is a rounding error next to latency.
- **A database-backed app at 2 to 16 GB in Europe or the US:** Hetzner CPX or CCX. Check the plan is orderable before you plan around it, and add the IPv4 cost to whatever number you're comparing.
- **ARM workloads that can be rebuilt for aarch64:** Hetzner CAX, if it's in stock. The 16 GB CAX31 at $23.81 outperformed Vultr's $96 machine on the composite score.
- **Managed Kubernetes, managed Postgres or Redis, a GPU, or a city outside Hetzner's six:** Vultr. Nothing else on this list replaces those.
- **Latency-critical trading bot:** pick the exchange-adjacent city first. Vultr wins Tokyo, London and Chicago; Hetzner's Singapore and Ashburn presence covers Bybit, OKX and Coinbase reasonably well at the small end.

Two things to confirm before you enter a card number. Whether the price you're looking at includes a public IPv4 address, since Hetzner bills it separately and that's a 2% to 70% swing depending on the plan. And whether the specific plan is in stock, because Hetzner's cheapest tiers come and go with hardware supply and a sold-out CX plan will quietly cost you three times more when you're forced onto CPX.

👉 [See Vultr's live plan list and pick a region before you commit](https://bit.ly/VuLtr)
