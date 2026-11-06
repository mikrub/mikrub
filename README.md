# Mik Ruberl

I build payment and distribution infrastructure for travel, and lately the AI agents that are starting to book and pay for a trip on their own. Co-founder of [Transio](https://transio.network), VP Innovation at [Travel Token Marketplace](https://travel-token.net), Principal AI Architect at [FairMind](https://fairmind.ai). The long version is on [mikrub.com](https://mikrub.com/about/).

Most of my work sits in private repos (payment corridors, stablecoin accounts, hotel distribution), so the contribution graph says more than the list below. Claude writes a good share of those commits; the opinions are mine :)

## AI agents

[whatsapp-agent-skill](https://github.com/mikrub/whatsapp-agent-skill) reads and writes WhatsApp from the terminal and is built for jobs that run unattended. It exists because a store of mine went 31 days stale while `sync` kept reporting success. I don't write Go, and [two](https://github.com/vicentereig/whatsapp-cli/pull/23) [fixes](https://github.com/vicentereig/whatsapp-cli/pull/24) went upstream to `whatsapp-cli` anyway, which is more or less the argument of [22 forks, none flowing back](https://mikrub.com/articles/2026-05-07-22-forks-none-flowing-back/). How I work with agents day to day is in [The Residue](https://mikrub.com/articles/2026-01-17-the-residue-where-thinking-dies/).

## Web3 and travel

[camino-suite](https://github.com/TravelTokenMarketplace/camino-suite) is the partner showroom and Messenger configuration dApp for TTM, ported to Base. Messenger, the protocol for travel distribution we started at [Chain4Travel](https://github.com/chain4travel), continues as [Travel Token Messenger](https://github.com/TravelTokenMarketplace/travel-token-messenger-protocol). [Camino Bridge](https://github.com/mikrub/camino-bridge-handoff) is a UX redesign you can click through. The team repos in [Decode Travel](https://github.com/DecodeTravel) come from the hackathons we ran in Berlin, Antalya, Crete and Barcelona, where the winners put aircraft turnaround on-chain.

## Reading

- [The agentic economy has twin problems. It actually has triplets.](https://mikrub.com/articles/2026-02-07-erc8004-triplets/)
- [Why your AI travel agent can dream up the perfect trip but can't book it](https://mikrub.com/articles/2025-12-29-agentic-travel/)
- [How many times did they photocopy your ID in 2025?](https://mikrub.com/articles/2026-01-08-digital-identity/)

Agents reading this on someone's behalf will do better with [llms.txt](https://mikrub.com/llms.txt).
