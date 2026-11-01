# colocation service providers: Real Prices From $35 a Month, Five Data Center Locations Compared, and How to Pick the Right One

Most people searching for colocation service providers are trying to answer one question: where can I park my own servers without getting nickel-and-dimed? The honest answer is that pricing varies wildly by city, the advertised rate is rarely the whole story, and the add-ons — DDoS protection, rack-and-cable fees, remote hands — are where bills balloon.

One provider that keeps showing up in these searches is Sharktech, a Las Vegas-headquartered host that has been around for roughly two decades and operates data centers in Los Angeles, Las Vegas, Denver, Chicago and Amsterdam. Its headline numbers are aggressive: 1–6U colocation starting at $35/month in Chicago, 10–42U cabinets from $280/month, with 10–100Gbps connectivity, 300TB+ of monthly traffic, free setup and in-house DDoS protection folded into the base price.

That last part matters more than it sounds. A lot of colo providers charge a few hundred dollars just to rack and cable your gear, and DDoS mitigation is typically sold as an add-on priced per Gbps. Sharktech bundles both, which is one of the reasons its entry-level prices look the way they do.

## Quick picks

> **In a hurry?** Most single-server owners should start with the **1–6U plan in Chicago at $35/month** — the lowest entry price across all five locations, with 300TB of traffic and free DDoS protection included. If you need West Coast or Asia-Pacific-friendly latency, the Los Angeles 1–6U at $99/month is the pick; a full 42U cabinet runs $280–$792/month depending on the city. 👉 [Check Sharktech colocation pricing and configure your deployment](https://bit.ly/SharKtech)

One caveat before anything else: Sharktech's official colocation page doesn't publish a price list — you configure space, power and location in the ordering portal and see the full configuration cost before committing. The per-city figures below come from third-party pricing trackers compiled in 2026, so treat them as accurate starting points but confirm the final number in the portal.

## What Sharktech colocation actually costs

Colocation pricing is built from four things: space, power, bandwidth and location. Sharktech publishes two standard tiers at every location, and everything outside those tiers — partial cabinets, custom power densities, private cages, multi-rack deployments — gets a custom quote from sales.

| Location | Space | Power allowance | Network & bandwidth | Starting price | Order |
| --- | --- | --- | --- | --- | --- |
| Chicago | 1–6U | 200–1200W | 10–100Gbps, 300TB+/mo | $35/mo | [Order Chicago 1–6U](https://bit.ly/SharKtech) |
| Chicago | 10–42U | 1600–5500W | 10–100Gbps, 300TB+/mo | $280/mo | [Order Chicago cabinet](https://bit.ly/SharKtech) |
| Las Vegas | 1–6U | 200–1200W | 10–100Gbps, 300TB+/mo | $65/mo | [Order Las Vegas 1–6U](https://bit.ly/SharKtech) |
| Las Vegas | 10–42U | 1600–5500W | 10–100Gbps, 300TB+/mo | $520/mo | [Order Las Vegas cabinet](https://bit.ly/SharKtech) |
| Denver | 1–6U | 200–1200W | 10–100Gbps, 300TB+/mo | $65/mo | [Order Denver 1–6U](https://bit.ly/SharKtech) |
| Denver | 10–42U | 1600–5500W | 10–100Gbps, 300TB+/mo | $520/mo | [Order Denver cabinet](https://bit.ly/SharKtech) |
| Los Angeles | 1–6U | 200–1200W | 10–100Gbps, 300TB+/mo | $99/mo | [Order Los Angeles 1–6U](https://bit.ly/SharKtech) |
| Los Angeles | 10–42U | 1600–5500W | 10–100Gbps, 300TB+/mo | $792/mo | [Order Los Angeles cabinet](https://bit.ly/SharKtech) |
| Amsterdam | 1–6U | 200–1200W | 10–100Gbps, 300TB+/mo | $99/mo | [Order Amsterdam 1–6U](https://bit.ly/SharKtech) |
| Amsterdam | 10–42U | 1600–5500W | 10–100Gbps, 300TB+/mo | $792/mo | [Order Amsterdam cabinet](https://bit.ly/SharKtech) |

Two notes on reading that table. First, Sharktech's own product page currently lists 1–6U "starting at $79/month" and 10–42U "starting at $449/month" — those sit between the per-city numbers, so the cheapest real entry point is the third-party-listed Chicago rate, while the official figures are the safer budget baseline. Second, the published prices are the floor, not the ceiling: if your gear pulls more than 1200W in a 1–6U slot, you're into custom-quote territory.

For context, general industry guidance puts entry-level colocation for a single server with 100 Mbps of bandwidth at around $100/month, with full-rack deployments running $600/month and up depending on power and location. Even Sharktech's premium Los Angeles and Amsterdam rates at $99/month land at the low end of that range — before counting the included DDoS protection, which competitors commonly sell as a $50–$200/month add-on. The price gap is widest in Chicago, where the same 1–6U tier costs $35/month versus $99 in Los Angeles, a 65% difference; the explanation offered is that Chicago is a Sharktech stronghold with favorable power contracts that get passed through.

## What's included in the base price

Beyond space and power, every tier ships with the same network and support package:

- **10Gbps to 100Gbps connectivity** with at least 300TB of monthly bandwidth
- **Free DDoS protection** using Sharktech's in-house scrubbing — a third-party guide notes each IP gets 60Gbps of protection by default, upgradeable to 1Tbps
- **Free setup**, which at many providers means a few hundred dollars in rack-and-cable fees
- **24/7 on-site engineers**, not a remote ticket queue
- **Fully redundant power, cooling and network**, hosted in enterprise facilities operated by Equinix, CoreSite, H5 Data Centers and CrownCastle, depending on the city

The facilities detail is worth dwelling on. Your gear doesn't sit in a back room Sharktech owns outright — in Los Angeles it's in Equinix space with multiple Tier-1 10Gb/s connections from Comcast, Cogent and Zayo, and in Denver it's in the H5 Data Centers complex near the CoreSite neutral data center. For anyone who later needs a cross-connect to a specific carrier or exchange, that carrier-neutral footing matters.

## The fine print most reviews skip

This is where most comparison articles stop, and it's exactly the part that affects whether you'll be happy six months in.

**There is no refund policy.** Sharktech states it does not give refunds under any circumstances. For colocation that's a real commitment — you're typically signing up for at least a month of service you can't walk back from. Start with the smallest tier that fits and scale up; Sharktech does assist with migrations to larger deployments.

**Remote hands is a negotiated scope, not an open buffet.** On-site technicians are available 24/7 for emergencies, but ongoing hands-on work — reboots beyond emergencies, cable changes, hardware swaps — needs its scope agreed with the team in advance, and the ordering portal shows installation and remote-hands charges before you pay. If your workflow depends on frequent physical interventions, price that out first.

**Registration has an anti-fraud filter.** Sharktech runs fraud screening on new accounts; signing up with a fake name, address or contact details gets the account flagged and suspended. Use real information.

**The support assumes technical competence.** Ticket support won't teach you Linux administration from scratch, and the knowledge base is fairly basic. Colocation as a product assumes you already run your own hardware anyway, but it's worth stating plainly.

One promo worth knowing about: third-party pricing trackers report that new colocation contracts get roughly 10% off the first six months, usually without needing a coupon code — Chicago's $35 tier works out to about $31.50/month during that window. Since it's not printed on the official page, confirm it with sales before signing rather than treating it as guaranteed.

## How the five locations differ

Location is the single biggest lever on both price and performance, and the right answer depends entirely on who reaches your servers.

- **Chicago ($35/mo / $280/mo)** — the value play. If you're hosting backups, secondary replicas, internal tools or game servers for a US-central audience, coastal latency is irrelevant and the savings are real: a full year on the 1–6U tier here costs $420 versus $1,188 in Los Angeles.
- **Las Vegas ($65/mo / $520/mo)** — Nevada's lack of state income tax and cheap power feed into the pricing, and it's a practical middle-ground for West Coast coverage.
- **Denver ($65/mo / $520/mo)** — solid central-US connectivity out of the H5 Data Centers complex, and the location customers quoted most positively in public feedback.
- **Los Angeles ($99/mo / $792/mo)** — the West Coast's densest internet exchange point. If Asia-Pacific latency matters, or you need direct routes to major content networks, this is the one to pay for; a third-party guide reports China Telecom/Unicom/Mobile direct connectivity with sub-200ms latency from mainland China.
- **Amsterdam ($99/mo / $792/mo)** — Sharktech's only European node, and the obvious choice if GDPR data-residency requirements or EMEA coverage apply to you.

## How does Sharktech stack up against other colocation service providers?

Against the big retail names, the comparison usually comes down to price per watt and what's bundled. A concrete example: Netrouting, a carrier-neutral provider operating its own AS6206 backbone with 2.4 Tbps+ of capacity, offers colocation from Amsterdam, Frankfurt, Miami and Hong Kong with 99.9% uptime SLAs and 24/7/365 DDoS protection. Netrouting's footprint covers two regions Sharktech doesn't (Frankfurt, Miami, Hong Kong) and runs its own backbone, which appeals if multi-region reach or specific European/Asian metros matter more than price. Its pricing isn't publicly listed in the same per-city format, so direct dollar comparisons require getting quotes from both.

Where Sharktech wins on paper is the bundle: free setup, included in-house DDoS scrubbing, and 300TB+ of traffic at a starting price well below the typical $75–$150/month retail entry point for a single server in major US markets. Where it's behind: no refund policy at all, a smaller support organization (the company served 5,000+ clients with about 25 staff as of a 2019 review, now claiming 10,000+ businesses), and a support culture that assumes you can mostly run things yourself. There's also a gap between the company's claimed 99.9999% network uptime and some customer reports of instability — older, but it's the kind of thing worth weighing for anything mission-critical.

If you need white-glove enterprise service and will pay for it, a larger carrier-neutral provider may suit you better. If you want maximum hardware per dollar with serious DDoS protection baked in, Sharktech's numbers are hard to argue with.

## Ordering: what the process actually looks like

Sharktech's colocation isn't a one-click SKU, and knowing the flow saves a support ticket later:

1. **Choose a location** — compare the five cities against where your users, partners and network requirements sit.
2. **Specify your build** — rack units, power draw, port speed and expected growth. This is where being honest about power matters; a single 1U server typically draws 200–400W, and a loaded cabinet pulls 3–5kW, so don't lowball it.
3. **Review the full configuration** — the portal shows power, connectivity, installation and remote-hands charges before you order.
4. **Coordinate shipping** — arrange shipment and installation requirements with Sharktech *before* sending equipment. Sending gear unannounced is the classic first-timer mistake.

You can also specify bandwidth commitments, cross-connects and routing requirements during configuration. 👉 [Configure your Sharktech colocation deployment and see the full pricing](https://bit.ly/SharKtech)

## FAQ

**What fits in a 1–6U colocation plan?**
A few dense 1U servers or a small cluster of equipment, drawing up to 1200W total. Most people colocation-shopping for the first time — moving gear out of a closet or a failing office server room — land here.

**Is DDoS protection really free?**
Yes, on all colocation tiers, using Sharktech's own scrubbing infrastructure. It's the same protection stack its dedicated server and VPS customers use, where the per-IP baseline is 60Gbps by default.

**Can I get a partial cabinet or more than 5500W?**
Not from the published tiers. Partial cabinets, custom power densities, private cages and multi-rack deployments all go through a custom quote. High-density GPU racks commonly need 10–20kW, so plan for a conversation with sales.

**Is there a contract or monthly billing?**
Sharktech bills month-to-month with no setup fee on colocation; specifics beyond that come at quote time. Remember the no-refund stance when deciding how many months to prepay.

**Do I keep ownership of my hardware?**
Yes. That's the whole point of colocation — you own and manage the equipment, Sharktech provides the facility, power, cooling, network and physical security. You retain full control and can pull your gear whenever the billing term allows.

## The bottom line before you order

Three rules will get almost everyone to the right choice. Hosting backups, internal services or anything latency-tolerant → take Chicago's 1–6U at $35/month and bank the difference. Serving US users with real bandwidth demands or running revenue-bearing game servers that attract attacks → Las Vegas or Denver at $65/month, or Los Angeles at $99 if Asia-Pacific routes matter. Any EU data-residency requirement → Amsterdam, full stop. If you're beyond 6U or pushing serious power, skip the tiers entirely and get an itemized custom quote.

And one last practical check: since refunds don't exist here, pay for one month, not twelve, until you've seen how the deployment actually runs. When you're ready, 👉 [start with Sharktech's Chicago 1–6U plan at $35/month or compare all five locations](https://bit.ly/SharKtech).
