## Aaron Poppie

A decade of producing festivals and live events taught me that a plan is only as good as the checks at the gate. Now I apply that to AI agents: I design and direct systems where agents do most of the building, and the guardrails and receipts that let anyone verify what they shipped.

Independent researcher, developer, and organizer. Captain of Lightcone Studios, founder of [AI Northwest](https://ainorthwest.org). Seattle, WA.

Everything below links to something you can open and check.

### Keeping agents honest

How I run a practice where AI agents write most of the code, and how the human stays in the loop where it counts.

- [One privacy standard, four websites, and a control group](https://gist.github.com/apoppie/ccdae825f9c07b7520f1822fa60ffabb). A weekend multi-agent operation: a standard sealed before any code was written, a live-site verifier (32 pass, 0 fail, 6 expected failures, all on the control site), and an adversarial security review with every finding dispositioned before publishing.
- [Keeping Agents Honest](https://poppie.me/work/keeping-agents-honest/). Merge rights gated by risk, a written bar every guardrail must pass, and eval and verification suites that say plainly what they do not check yet.

### AI Northwest

The Pacific Northwest's AI builder community. Events, a forum, and the infrastructure that runs it.

- [ainw-forum-skills](https://github.com/ainorthwest/ainw-forum-skills). Four agent skills (read, post, onboard, runtime setup) for taking part in a community forum. Apache 2.0, works in any Agent Skills-standard harness. Members set up their agents at [ainorthwest.org/agents](https://ainorthwest.org/agents/).
- [ainw-kiosk](https://github.com/ainorthwest/ainw-kiosk). Check-in at the door. A QR scan looks the guest up in Luma, then records attendance in HubSpot.
- [ainw-digest](https://github.com/ainorthwest/ainw-digest). The weekly forum digest email. A Cloudflare Worker with rate limiting, a dry-run mode and signed unsubscribe links.

### Lightcone Studios

The studio. Most of the product work is private; the write-ups above are how it shows its work.

- [hummingbird-cam](https://github.com/lightcone-studios/hummingbird-cam). A Raspberry Pi nest monitor I built for a family of rescued hummingbirds. Its [science harness](https://github.com/lightcone-studios/hummingbird-cam/tree/main/science) seals each hypothesis before the data exists: preregistration gates enforced by git, Secure Enclave signatures, and a hash-chained ledger anyone can verify with openssl.

Built with Claude Code as my pair; the commit trailers say so.

→ [poppie.me](https://poppie.me) · all work, each fact with its receipt
