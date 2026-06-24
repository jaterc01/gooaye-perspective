# 本機逐字稿研究摘要

## 資料位置

- Workspace: `C:\Users\jater\Desktop\Project\googye`
- Corpus: `C:\Users\jater\Desktop\Project\googye\transcrib\gooaye`
- Files inspected: EP1-EP673 Markdown transcripts, including public-synced `EP658.md`/`EP659.md`/`EP663.md`/`EP665.md`/`EP666.md`/`EP667.md`/`EP668.md`/`EP669.md`/`EP670.md`/`EP671.md`/`EP672.md` and locally generated `EP660.md`/`EP661.md`/`EP662.md`/`EP664.md`/`EP673.md`
- Count observed after refresh on 2026-06-24: top-level corpus now includes `EP673.md`; earlier duplicated archive files may still exist under `EP001-EP642`.

## Latest transcript refresh

On 2026-06-24, `whatmkreallysaid.com/episodes.json`, SoundOn RSS, Apple lookup, and the Apple Podcasts public page were checked again.

Result:

- Public transcript source now exposes 672 episodes and includes `EP672_功率元件缺貨論與軟體職涯重整.md`, so local `EP672.md` was replaced with the public transcript version.
- SoundOn RSS latest item: `EP673 | 🥬`, published 2026-06-24 08:09:45 GMT, description snippet `韓國人真的很會玩`.
- Apple lookup exposed `EP673 | 🥬` with the same SoundOn MP3 enclosure; Apple Podcasts public page also showed `EP673 | 韓國人真的很會玩` and total episodes 673.
- Because no public EP673 transcript was available, the SoundOn RSS MP3 was downloaded to `%TEMP%\gooaye-skill\EP673.mp3` and transcribed locally with `faster-whisper-large-v3`.
- New top-level transcript artifacts: `EP673.md`, `EP673.raw.txt`, and `EP673.raw.json`.
- EP673 machine transcript metadata: 3056.927375 seconds, 2222 segments, language `zh`, language probability 1.0.
- Treat EP673 as machine-generated and provisional until `whatmkreallysaid.com` exposes the public transcript.

On 2026-06-20, `whatmkreallysaid.com/episodes.json`, SoundOn RSS, Apple lookup, and the Apple Podcasts public page were checked again.

Result:

- Public transcript site index total: 671 episodes, still stopping at EP671 `離散元件覓蹤與隨機人生論`.
- SoundOn RSS latest item: `EP672 | 🐣`, published 2026-06-20 05:40:47 GMT, description snippet `又新高拉`.
- Apple Podcasts public page indexed EP672 on 2026-06-20 and exposed the same SoundOn MP3 enclosure; Apple lookup API was still lagging and only returned through EP671 during the check.
- Because no public EP672 transcript was available, the SoundOn RSS MP3 was downloaded to `%TEMP%\gooaye-skill\EP672.mp3` and transcribed locally with `faster-whisper-large-v3`.
- New top-level transcript artifacts: `EP672.md`, `EP672.raw.txt`, and `EP672.raw.json`.
- EP672 machine transcript metadata: 3204.049 seconds, 2358 segments, language `zh`, language probability 1.0.
- Historical status at 2026-06-20: treat EP672 as machine-generated and provisional until `whatmkreallysaid.com` exposes the public transcript. This was superseded on 2026-06-24 when the public EP672 Markdown became available and replaced the local Markdown.

On 2026-06-17, `whatmkreallysaid.com/episodes.json`, SoundOn RSS, and Apple Podcasts were checked again.

Result:

- Public transcript site index total: 671 episodes.
- Public `EP671_離散元件覓蹤與隨機人生論.md` was available, so `download_gooaye_transcripts.py --out transcrib\gooaye` synced `EP671.md` directly into the local corpus.
- SoundOn RSS latest item: `EP671 | 🌼`, published 2026-06-17 06:29:22 GMT, description snippet `不可能一關再關吧`.
- Apple Podcasts public page indexed EP671 on 2026-06-17 and showed upload date 2026-06-17.
- No MP3 download or machine transcription was needed for EP671.

On 2026-06-13, `whatmkreallysaid.com/episodes.json`, SoundOn RSS, and Apple Podcasts were checked again.

Result:

- Public transcript site index total: 670 episodes.
- Public `EP670_瘦瘦針OD誌與SpaceX首航論.md` was available, so `download_gooaye_transcripts.py --out transcrib\gooaye` synced `EP670.md` directly into the local corpus.
- SoundOn RSS latest item: `EP670 | 🫡`, published 2026-06-13 07:07:21 GMT, description snippet `Dario 哥求仁得仁`.
- Apple Podcasts public page indexed EP670 on 2026-06-13 and showed `dateModified` / latest work example at 2026-06-13.
- No MP3 download or machine transcription was needed for EP670.

On 2026-06-11, `whatmkreallysaid.com/episodes.json`, SoundOn RSS, and Apple Podcasts were checked again.

Result:

- Public transcript site index total: 669 episodes.
- Public `EP669_三十四歲感懷與市場信仰考.md` was available, so `download_gooaye_transcripts.py --out transcrib\gooaye` synced `EP669.md` directly into the local corpus.
- SoundOn RSS latest item: `EP669 | 🎈`, published 2026-06-10 07:37:19 GMT, description snippet `這片汪洋，還要考驗我們到什麼時候`.
- Apple Podcasts public page/search indexed EP669 on 2026-06-11.
- No MP3 download or machine transcription was needed for EP669.

On 2026-05-09, `whatmkreallysaid.com/episodes.json`, SoundOn RSS, and Apple Podcasts were checked because Apple/SoundOn had advanced beyond the local corpus.

Result:

- Public transcript site index total: 659 episodes.
- Public `EP658.md` and `EP659.md` were synced into the local corpus, replacing the earlier machine-generated Markdown for those episodes; their previous `.raw.*` machine artifacts remain as provenance.
- RSS/Apple latest episode: `EP660 | 🍄‍🟫`, published 2026-05-09 02:48:01 GMT, description snippet `這樣下去會不會壞掉`, duration about 3092 seconds.
- Because no public EP660 transcript was available, the EP660 RSS `.mp3` enclosure was downloaded and transcribed locally with `faster-whisper-large-v3`.
- New top-level transcript artifacts: `EP660.md`, `EP660.raw.txt`, and `EP660.raw.json`.
- EP660 local title: `股癌逐字稿 EP660｜這樣下去會不會壞掉`.
- 2026-05-13 refresh: public transcript site still stopped at EP659, while Apple/SoundOn latest was `EP661 | 🚲`, published 2026-05-13 08:00:31 GMT, duration about 2999 seconds. The EP661 RSS `.mp3` enclosure was downloaded and transcribed locally with `faster-whisper-large-v3`, producing `EP661.md`, `EP661.raw.txt`, and `EP661.raw.json` (2196 segments, 2998.961625 seconds). Treat EP661 as machine-generated until a public human transcript appears.
- 2026-05-16 refresh: public transcript site still stopped at EP659, while SoundOn RSS latest was `EP662 | ⛑️`, published 2026-05-16 08:30:49 GMT, duration about 2999 seconds. The EP662 RSS `.mp3` enclosure was downloaded and transcribed locally with `faster-whisper-large-v3`, producing `EP662.md`, `EP662.raw.txt`, and `EP662.raw.json` (2187 segments, 2998.961625 seconds). Treat EP662 as machine-generated until a public human transcript appears.
- 2026-05-20 refresh: public transcript site still stopped at EP659, while SoundOn RSS and Apple Podcasts latest was `EP663 | 🦘`, published 2026-05-20 07:59:35 GMT, duration about 2997 seconds. The EP663 RSS `.mp3` enclosure was downloaded and transcribed locally with `faster-whisper-large-v3`, producing `EP663.md`, `EP663.raw.txt`, and `EP663.raw.json` (2213 segments, 2997.4726875 seconds).
- 2026-05-23 refresh: public transcript site advanced to EP663, so `EP663.md` was replaced with the public transcript version while its earlier `.raw.*` machine artifacts remain as provenance. SoundOn RSS and Apple Podcasts latest was `EP664 | 🐟`, published 2026-05-23 07:59:15 GMT, duration about 2999 seconds. The EP664 RSS `.mp3` enclosure was downloaded and transcribed locally with `faster-whisper-large-v3`, producing `EP664.md`, `EP664.raw.txt`, and `EP664.raw.json` (2216 segments, 2998.961625 seconds). Treat EP664 as machine-generated until a public human transcript appears.
- 2026-05-27 refresh: public transcript site advanced to EP665 and exposed `EP665_小天才初現與衛星算力遠眺.md`; `download_gooaye_transcripts.py` synced `EP665.md` directly from the public source. Apple Podcasts Taiwan and SoundOn RSS also showed `EP665`, published 2026-05-27 07:25:44 GMT, description snippet `整組做壞掉了`. No MP3 transcription was needed.
- 2026-05-30 refresh: public transcript site still stopped at EP665, while SoundOn RSS and Apple Podcasts latest was `EP666 | 🍐`, published 2026-05-30 05:57:43 GMT, duration about 3315 seconds, description snippet `誰敢說他們老`. The EP666 RSS `.mp3` enclosure was downloaded and transcribed locally with `faster-whisper-large-v3`, producing `EP666.md`, `EP666.raw.txt`, and `EP666.raw.json` (2523 segments, 3314.0245 seconds). Treat EP666 as machine-generated until a public human transcript appears.
- 2026-06-03 refresh: public transcript site still stopped at EP665, while SoundOn RSS and Apple Podcasts latest was `EP667 | 🌍`, published 2026-06-03 07:34:50 GMT, duration about 3051 seconds, description snippet `這兩天開始品到…土味`. The EP667 RSS `.mp3` enclosure was downloaded and transcribed locally with `faster-whisper-large-v3`, producing `EP667.md`, `EP667.raw.txt`, and `EP667.raw.json` (2235 segments, 3050.9714375 seconds). Treat EP667 as machine-generated until a public human transcript appears.
- 2026-06-07 refresh: public transcript site advanced to EP668 and exposed `EP668_電腦展見聞錄與槓桿天譴論.md`, so `download_gooaye_transcripts.py --out transcrib\gooaye` synced `EP668.md` directly from the public source. SoundOn RSS and the Apple public page also showed latest `EP668 | 🦞`, published/uploaded 2026-06-06, duration about 50 minutes. No new MP3 transcription was needed. A previous locally generated, misnumbered `EP688.*` set actually pointed at the EP668 audio and was moved to `transcrib\gooaye\_quarantine_wrong_ep688_20260607`; do not treat EP688 as a real latest episode.

## EP656 anchor

`EP656.md` title: `股癌逐字稿 EP656｜萬劍歸宗`

Major segments:

- Sponsor framing: trading setup and body posture as a high-win-rate personal investment.
- Life segment: wine exploration, Costco discovery, learning taste through expensive sample-building, GLP-1/Mounjaro weight-loss updates.
- Market segment: CPU stocks, Agentic AI, exaggerated 1:1 CPU/GPU narratives, Intel, TPU 8T/8i, MediaTek/Broadcom roles.

Distilled signals:

- Uses finance metaphors to explain daily life and health.
- Uses life experiments to explain investment learning: buy samples, build discrimination, then stop worshipping price tags.
- Resists extreme narratives when market excitement creates overconfident numbers.
- Keeps a distinction between long-term trend belief and short-term injury risk.

## EP657 anchor

Major segments:

- Sponsor framing: Mother's Day skincare gift as long-term asset allocation rather than short-lived emotional value.
- Life segment: a metaphysical statue story used to show curiosity, skepticism, and a "don't harm ordinary people; go find the real debtor" justice instinct.
- Market segments:
  - TSMC: foreign selling pressure vs local investment trust buying, and the way TSMC strength can drain liquidity from small/mid caps.
  - Memory/passive components: rotation into previously underperforming groups after fundamental price signals.
  - Intel EMIB: reported 90% back-end assembly yield as a forward-looking industry signal, while substrate yield remains a separate bottleneck.
  - OpenAI x Luxshare: skepticism toward native AI consumer devices replacing smartphones; existing app habits and AI Pin failure are cautionary anchors.
  - Meta x AWS Graviton5: CPU demand remains hot, but the "server shortage spills into consumer CPU chain" story needs care.
- Q&A:
  - Active ETF vs index: long-term market beating remains hard; simple 0050/006208/VOO/VTI remain preferred for most people.
  - Leverage and margin maintenance: if leverage is used, some stop-loss/self-liquidation rule is mandatory.
  - Trading execution: 5-day vs 10-day stop rules are not religious; "strategic flexibility" requires position room and a clear reason.

Distilled signals:

- Forward-looking industry research should be framed as hypothesis until public confirmation appears.
- Separate adjacent bottlenecks instead of collapsing them: Intel back-end assembly yield and substrate yield are different facts.
- Price rotation can be driven by money flow even when many groups have good fundamentals.
- New AI hardware claims should be tested against user habit lock-in, existing device ecosystems, and prior product failures.
- Rigid discipline can become bad execution if it ignores context; flexible discipline is only safe when leverage and sizing leave room.

## EP658 anchor

`EP658.md` title: `股癌逐字稿 EP658｜最終都是氣氛`

Generation note:

- Public transcript source stopped at EP657 when checked on 2026-05-05, so EP658 was first transcribed locally from SoundOn audio.
- On 2026-05-09, `whatmkreallysaid.com/episodes.json` exposed EP658; the local `EP658.md` was replaced with the public transcript version.

Major segments:

- Sponsor framing: NordVPN for travel price checks, public Wi-Fi safety, overseas access and device coverage.
- Market timing: after a strong run, expect normal pullbacks and do not treat stocks as things that never fall.
- Life segment: red wine collection as sample-building, taste calibration, and the difference between price, experience and memory.
- AI/work segment: Jensen Huang's pushback against AI doomer / replacement narratives; do not decompose a job into one automatable task and declare the whole person obsolete.
- SaaS/enterprise software segment: financial results and real deployment matter more than token-burning demos or venture-circle slogans.
- Market Q&A: memory fundamentals remain favorable but price timing is uncertain; MediaTek ASIC optimism is high but still needs public delivery; stock pledge can be a liquidity tool for life goals if sizing and risk are controlled.
- Life Q&A: music as memory carrier, anxiety handled by focusing on actionable problems, money should support major life goals rather than become a prison.

Distilled signals:

- Price and taste are not the same signal; you earn confidence by actually sampling the range, not by worshipping the most expensive label.
- AI analysis should inspect full workflows, accountability and context, not isolated task fragments.
- New technology often creates a new option or changes the job shape before it fully replaces an existing category.
- For life goals, preserving optionality can matter more than mechanically selling long-term assets immediately; tools like pledge loans require humility and strict risk sizing.

## EP659 anchor

`EP659.md` title: `股癌逐字稿 EP659｜做壞掉了`

Generation note:

- Public transcript source stopped at EP657 when checked on 2026-05-06, so EP659 was first transcribed locally from SoundOn audio.
- On 2026-05-09, `whatmkreallysaid.com/episodes.json` exposed EP659; the local `EP659.md` was replaced with the public transcript version.
- Earlier raw machine artifacts remain available for provenance, but the Markdown transcript now follows the public transcript source.

Major segments:

- Sponsor framing: Saily/eSIM as travel friction removal; the expensive part of travel is wasted time and broken connectivity, not only the ticket price.
- Body/operator segment: GLP-1/Mounjaro, weight loss, functional training, hip mobility, and body control as a way to restart the operator rather than merely improve appearance.
- Market segment: passive components moving from fundamental signal to price response; supply tightness, lead-time extension, MLCC/tantalum/aluminum capacitor distinctions, and order crowding from high-end AI server demand.
- CPU/ASIC segment: AMD/Intel server CPU demand, Agentic AI inference workloads, Google/Amazon ASIC chains, MediaTek optimism, and the risk that price may front-run verification.
- Leverage segment: in strong markets, broker credit limits and margin expansion can signal crowding; reduce leverage when wind changes rather than waiting for obvious rain.
- Life/Q&A segment: taxes as a real transaction cost, professional accounting for large offshore gains, family time boundaries, and not confusing another person's freedom with the unseen work that funds it.

Distilled signals:

- The operator is part of the system: sleep, body, mobility, and energy change the quality of judgment.
- Fundamental work can be early and boring before price responds; once price responds, re-check whether the move is still mechanism-driven or already narrative-driven.
- CPU/ASIC rotation should be tracked by workload and customer chain, not only by "AI everything" slogans.
- If leverage is increasing across the market, treat broker behavior and credit availability as sentiment indicators.
- Work-life balance is not a slogan; define protected time blocks so work does not leak into every family interaction.

## EP660 anchor

`EP660.md` title: `股癌逐字稿 EP660｜這樣下去會不會壞掉`

Generation note:

- Public transcript source stopped at EP659 when checked on 2026-05-09.
- EP660 audio came from the SoundOn RSS enclosure and was transcribed locally with `faster-whisper-large-v3`.
- The artifact was generated with `condition_on_previous_text=False`, converted to Taiwan traditional Chinese, and corrected for high-confidence Gooaye/industry terminology. Treat it as machine-generated until a public human transcript appears.

Major segments:

- Sponsor/operator framing: ZZ Sleeper and sleep quality as decision quality; a hot market makes physical recovery and forced cooling more valuable, not less.
- Overheated market segment: Taiwan index strength, large-cap wealth effects, investors not reducing leverage because cost bases are far below market, and the risk that high-level markets can sell off on small triggers.
- Participation/social class segment: instead of only resenting uneven technology-industry wealth, use public markets such as broad ETFs or stocks to participate in economic growth, while recognizing late entry risk.
- NVIDIA/supply-chain rumor segment: possible material/thermal design changes and CoWoS stoppage rumors can hit related components even if NVIDIA itself looks fine; at high market levels, avoid reflexively calling every drop a buy.
- Legacy/consumer rotation segment: consumer, industrial, auto, DDIC, mature-node foundry, wafer and materials names may be moving because of memory/foundry price hikes, tariffs and pull-forward stocking rather than confirmed terminal-demand recovery.
- Credit/market-structure segment: broker credit limits may cap leverage even for large accounts; Taiwan's disposition rules and crowded large-cap liquidity can amplify forced selling discussion.
- Passive components/memory segment: passive components, capacitors and memory remain fundamentally tight, but moves may arrive earlier than expected and then pause before the real cycle.
- Life/Q&A segment: relationship values around work and money, asset allocation by temperament, not overbuying children's rewards, and shifting from purchasable status toward skills and taste that accumulate in the person.

Distilled signals:

- Strong markets require price-location discipline: when the whole tape is high, a true story can still be a bad add if the next forced seller is close.
- Stock-price strength is a sensor, not proof; after a low-position group wakes up, ask whether the driver is demand, supply fear, inventory pull-forward, or pure rotation.
- Credit constraints should be read both ways: full broker books can signal crowding, but caps can also prevent some large accounts from increasing leverage further.
- For life questions, do not confuse buying the outcome with building the capacity; skills, taste, body control and memory-rich practice compound differently from purchasable goods.

## EP661 anchor

`EP661.md` title: `股癌逐字稿 EP661｜正常能量釋放`

Generation note:

- Public transcript source stopped at EP659 when checked on 2026-05-13.
- EP661 audio came from the SoundOn RSS enclosure and was transcribed locally with `faster-whisper-large-v3`.
- The artifact was generated with `condition_on_previous_text=False`, converted to Taiwan traditional Chinese, and corrected for high-confidence Gooaye/industry terminology. Treat it as machine-generated until a public human transcript appears.

Major segments:

- Sponsor framing: HARU sponsorship turns intimate-product copy into market metaphors, using trend, volatility, position-building, and "new high" language as a deliberately absurd finance-to-life translation.
- Wine/sample segment: wine exploration continues the price-tag-as-sensor model. Start with expensive/reference bottles to build samples quickly, then use taste calibration to stop worshipping ratings or price.
- High-market segment: Taiwan index pullback from a very stretched run; most people are still far above cost and not adjusting much, but new adds at this price location require extra caution.
- Passive component segment: MLCC, aluminum capacitors, power-chain capacity reservations, and low-end standard parts can benefit from high-end AI buildout through crowding-out effects, not only direct AI content.
- Legacy/consumer segment: recent pull-forward appears more like cost and inventory protection than broad consumer-demand recovery; split cost-driven price hikes from demand-driven shortage.
- Market-structure segment: strong groups are narrowing, large orders no longer pull every name instantly, and defensive "second/third burrows" become useful when momentum begins to fragment.
- Supply-chain decoding segment: listener feedback and cross-supplier checks build a mosaic; do not reduce supplier value to "TSMC or non-TSMC" because margin, customer mix, and valuation response differ.
- Q&A segment: Qualcomm/AIPC/Cloud claims are separated from AI infrastructure or ASIC-driven narratives; a stock can rise for a different reason than the slogan attached to it.

Distilled signals:

- Price tags are useful search lights, not truth: use expensive or strong things to learn where to look, then recalibrate with taste, evidence and fit.
- At stretched price locations, the right posture is not bearishness; it is hand-binding for people without a plan and staged action only for operators who know what they are doing.
- Passive components and legacy semis need driver separation: direct AI demand, high-end crowding-out, cost pass-through, inventory pull-forward and real end-demand recovery are different mechanisms.
- When strong groups narrow and familiar buy-the-breakout behavior stops working instantly, treat it as a small market-structure warning even if the larger trend remains intact.
- A narrative label can be wrong while the stock move is real; map the actual buyer/workload/infrastructure driver before accepting AIPC, Cloud, ASIC, or other public slogans.

## EP662 anchor

`EP662.md` title: `股癌逐字稿 EP662｜再往下 8% 我就喊救命`

Generation note:

- Public transcript source stopped at EP659 when checked on 2026-05-16.
- EP662 audio came from the SoundOn RSS enclosure and was transcribed locally with `faster-whisper-large-v3`.
- The artifact was generated with `condition_on_previous_text=False`, converted to Taiwan traditional Chinese, and corrected for high-confidence Gooaye/industry terminology. Treat it as machine-generated until a public human transcript appears.

Major segments:

- Sponsor and Shaonan Capital segment: NordVPN sponsor copy, followed by Taiwan game investment updates and a "patient capital" frame for creative teams.
- Family/health segment: prenatal medical scare around his child becomes a model for uncertainty, expert selection, gratitude, and why health risk changes later decision priorities.
- Market correction segment: Friday's drawdown felt large, but low-cost holders did not show real panic; the same move is different for old inventory versus fresh chasers.
- TSMC/fund-flow segment: investment-trust rule changes may pull money into TSMC over the next one to several months, forcing profit-taking or liquidity withdrawal from some small/mid names even when their stories are not broken.
- Rotation segment: corrections are useful because the market quickly shows which groups recover first; next leaders can be identified by anti-fragile price behavior after the flush.
- Software/security segment: AI did not kill every software name; cybersecurity and selected software winners are making new highs, so apply the same "not all hardware, not all software" split.
- Passive component segment: resistor, MLCC, aluminum capacitor, inductor and Panasonic/OS-CON/SP-Cap price-hike talk move the shortage story from vague tightness toward possible stop-order or spot-price behavior.
- Power/legacy segment: power components tied to new power cabinets are separated from consumer/legacy restocking, which may be only inventory refill.
- AI/product Q&A: AI tools improve productivity, but the actual product, shipment, design taste, and ability to solve human problems remain the scarce layer.

Distilled signals:

- Cost basis changes behavior: a pullback that is noise for low-cost holders can be fatal for fresh leverage or late chasers.
- Use corrections as ranking devices: watch who stops falling first, who reclaims highs, and which whole groups recover together.
- A good fundamental story can still wait in the penalty box if funds are reallocating elsewhere.
- AI disruption should be split by product value: tools can make production easier, but taste, problem selection, shipment and responsibility remain the differentiators.
- Shortage stories move through stages: lead-time stretch, price-hike letters, spot-price behavior, order control, and stop-taking. Each stage deserves a different confidence level.

## EP663 anchor

`EP663.md` title: `股癌逐字稿 EP663｜健身減重誌與被動元件大潮`

Generation note:

- Public transcript source stopped at EP659 when checked on 2026-05-20, so EP663 was first transcribed locally from SoundOn audio.
- On 2026-05-23, `whatmkreallysaid.com/episodes.json` exposed EP663 as `健身減重誌與被動元件大潮`; the local `EP663.md` was replaced with the public transcript version.
- Earlier raw machine artifacts remain available for provenance, but the Markdown transcript now follows the public transcript source.

Major segments:

- Sponsor/health segment: 東璧堂 sponsor copy leads into weight-loss progress, functional training, physical therapy, pain reduction, and health systems as one of the highest-return life investments.
- Passive component segment: Panasonic and related price-hike letters, spot-market sweeping, distributors seeing high-end part shortages, and the possibility that shortages move toward auction-like allocation.
- Capacity discipline segment: memory and passive components are framed through whether suppliers expand capacity; disciplined non-expansion protects pricing power, while broad expansion would shorten the cycle.
- AI/ASIC/substrate segment: Google/Broadcom/MediaTek fish-code discussion, possible larger SoundFish-style chiplet/substrate designs, and old AI supply-chain names that can return to center stage when product details become visible.
- Market faith segment: strong groups can pull back sharply because holders have large gains and late chasers lack conviction; the test is whether the thesis still has revenue and profit behind it.
- TSMC/optical Q&A: TSMC forum comments do not make optical communication a zero-sum market; short-term weakness should be separated from long-term market expansion.
- Money/life Q&A: index investing, wealth effects, lifestyle inflation, and spending should be judged against personal experience value rather than comparison with richer peers.
- AI-information workflow Q&A: daily information scraping is useful only when the market is paying attention; model choice, source selection, and tape context matter more than a magic prompt.

Distilled signals:

- Health and training are not side quests: systematized body maintenance can change the operator's confidence, energy, and future risk budget.
- In shortage cycles, watch both price signals and capacity intent. Tight supply matters more when suppliers stay disciplined rather than rush into expansion.
- A strong thesis still needs "faith testing": after a pullback, separate broken stories from high-quality names resting after a crowded move.
- Do not chase social accounts for stock tips; prioritize industry operators, price behavior, and the mechanism behind why money is moving.
- Wealth should buy experience and resilience, not only a higher comparison ladder. The reference point should be the user's own life, not the loudest winner nearby.

## EP664 anchor

`EP664.md` title: `股癌逐字稿 EP664｜差一點捏破`

Generation note:

- Public transcript source stopped at EP663 when checked on 2026-05-23.
- EP664 audio came from the SoundOn RSS enclosure and was transcribed locally with `faster-whisper-large-v3`.
- The artifact was generated with `condition_on_previous_text=False`, converted to Taiwan traditional Chinese, and corrected for high-confidence Gooaye/industry terminology. Treat it as machine-generated until a public human transcript appears.

Major segments:

- Sponsor/business segment: enterprise tax planning is framed as operational hygiene; after-tax profit, contracts, invoices, shareholder flows, and cross-border tax risk are part of the real business system.
- Positioning segment: many held names entered disposal trading or 20-minute matching, so the episode treats being unable to trade as a forced discipline rather than a reason to overreact.
- Wine/sample segment: restaurant wine programs become a way to test expensive bottles without taking full bottle risk; the point is still sample-building and preference calibration.
- AI demand segment: Anthropic profitability and Colossus-style compute payback make AI hardware capex look more durable, because compute can earn directly or be rented out.
- TPU/ASIC segment: Google plus Blackstone-style TPU cloud moves TPU from internal-use story toward external supply; the right question is not only total AI demand but who owns the cloud, accelerator, and supply-chain route.
- Passive component segment: MLCC, aluminum capacitor, inductor, resistor and power-component moves are separated into real bottlenecks versus follow-on sympathy trades; after a group rerates, price behavior can temporarily become the faster filter than fundamentals.
- Housing/life Q&A: home-buying preferences are personal utility functions; west-facing rooms, top floors, large square footage, and lower liquidity can be rational if they match the actual family use case and are not intended for quick resale.

Distilled signals:

- A hard-to-trade winner can become a discipline device; if the mechanism is intact, forced stillness may be safer than trying to micromanage every tick.
- AI capex skepticism weakens when model operators and compute owners show payback; still separate total demand expansion from competitive pressure between GPU, TPU, ASIC, and neo-cloud routes.
- In a crowded sector move, fundamentals matter most before consensus forms; after consensus forms, watch who recovers first after pullbacks, then re-check which names own the real bottleneck.
- Buying a home is not only resale optimization. Start from the user's actual life, family size, sunlight/noise preferences, and holding horizon before applying generic market checklists.

## EP665 anchor

`EP665.md` title: `股癌逐字稿 EP665｜小天才初現與衛星算力遠眺`

Generation note:

- Public transcript source included EP665 when checked on 2026-05-27.
- `download_gooaye_transcripts.py` synced the public Markdown transcript into the local corpus, so no local MP3 download or machine transcription was needed.

Major segments:

- Sponsor/health segment: 善存葉黃素 sponsor copy links all-day screen use, following markets, and eye-care as investor/operator maintenance.
- Life/body segment: weather, running progress, leg soreness, military memories, and functional training continue the "operator condition matters" frame.
- Family segment: 諾亞's hearing, language recognition, and "小天才" joking show the parental joy layer without turning it into certainty or achievement worship.
- Market segment: passive components, TSMC, and crowded AI hardware trades are treated as still-interesting but needing position discipline after large runs.
- Satellite AI compute segment: SpaceX/Starship, space-based data centers, satellite inference, and low-earth-orbit infrastructure are framed as a possible far-future theme, not an immediate all-in thesis.
- Q&A segment: accepting short attention cycles, sampling hobbies quickly, slowing down everyday actions, learning from leverage mistakes, and respecting trading-system consistency.

Distilled signals:

- Health maintenance keeps expanding from sleep/body into eyes and attention: screen-heavy investors need operating-system upkeep, not just better information.
- A future theme can be intellectually important before it is investable. Satellite compute should be mapped through launch cost, power, cooling, latency, maintenance, and who actually captures value.
- Short-lived obsessions are not necessarily waste if they build taste and skills; the new layer is learning to slow down and notice details after the initial sprint.
- Leverage should come only after an unlevered method has real trade-record evidence. "看對再下大" means the return record proves the method, not the ego.
- A trading rule can be correct and still lead to a missed move; judge the system over many trades, not one emotionally painful exit.

## EP666 anchor

`EP666.md` title: `股癌逐字稿 EP666｜生命節奏誌與AI業務論`

Source note:

- Public transcript source stopped at EP665 when checked on 2026-05-30, so EP666 was first generated from SoundOn audio.
- Public transcript source exposed EP666 by 2026-06-06, so `EP666.md` was replaced with the public Markdown. The earlier `.raw.*` machine artifacts remain as provenance.

Major segments:

- Sponsor/face-care segment: 植村秀 sponsor copy turns skin, sunscreen, makeup setting, and cleaning into "face/position management" metaphors.
- Mindfulness/operator segment: slowing down, noticing coffee, breathing into the back, and observing posture are framed as practical operator upgrades rather than abstract spiritual talk.
- Market/position segment: many holdings are in disposal trading or 20-minute matching, so inability to trade and broker credit limits become involuntary risk control rather than only frustration.
- Passive component segment: the story shifts from cost-driven price hikes toward demand-driven pricing; MLCC remains visible, but aluminum capacitors, SP-Cap/OS-CON and horn capacitors may be the less-discussed shortage layer.
- AI/software segment: AI replacement doom talk is pushed back through Salesforce, ServiceNow, Okta, Snowflake and the broader software rebound; AI can add to software instead of killing all software.
- Application-layer segment: after infra and model excitement, the scarce layer may move toward proprietary data, enterprise deployment, SI/FDE-style business ability, compliance, hallucination control, copyright risk, and accountable delivery.
- Q&A segment: starting a business can be a different life return than keeping all capital in stocks; stop discipline depends on instrument quality; capacity expansion must be judged by timing and application, not treated as a universal sell signal.

Distilled signals:

- Attention is now an operator input: slowing down small routines can improve memory, body awareness, posture, and decision quality.
- Credit/position constraints can be read as forced risk control in an overheated tape; not every unused leverage path should be reopened.
- In shortage cycles, "expansion" is not automatically bearish. Early expansion into a niche or severely short product can confirm scarcity, while late broad expansion after consensus can be a warning.
- AI software analysis should move from model leaderboard talk to data ownership, deployment, sales motion, compliance, copyright, hallucination control, and who is accountable when the output fails.
- A fixed percentage stop is too blunt. Apply different exit logic to TSMC-like quality, small speculative names, leveraged trades, and crowded high-beta setups.

## EP667 anchor

`EP667.md` title: `股癌逐字稿 EP667｜品酒問道誌與AIPC新局`

Source note:

- Public transcript source stopped at EP665 when checked on 2026-06-03, so EP667 was first generated from SoundOn audio.
- Public transcript source exposed EP667 by 2026-06-06, so `EP667.md` was replaced with the public Markdown. The earlier `.raw.*` machine artifacts remain as provenance.

Major segments:

- Sponsor/travel segment: NordVPN sponsor copy frames travel planning, price comparison, public Wi-Fi safety, cross-region access and device coverage as friction removal for family travel.
- Slow-life/operator segment: breathing, deliberate routines, child-care details, coffee runs, and slowed daily actions continue the operator-upkeep theme, but EP667 adds memory formation and "language of taste" as a learnable skill.
- Wine/taste segment: a tasting event turns wine vocabulary from "裝逼" into a real sensory language; price tags and expert language become training data, not status worship.
- Computex segment: NVIDIA and Marvell speeches reinforce optical connectivity, total AI infrastructure solutions, and market enthusiasm around Marvell, while also warning that some moves are driven by Jensen/Huang signaling power rather than fully visible fundamentals.
- AIPC/local-model segment: DGX Spark, N1X-style edge devices, open-source models, Snowflake/Data Lake workflows and token-cost reduction are used to frame local AI and cloud AI as workload splitting rather than a zero-sum fight.
- Market/Q&A segment: TSMC and NVIDIA may finally rotate stronger as leaders, while power semiconductors, PMIC/IDM, AIPC materials, passive components and high-ASP device content are watchlist themes that still need evidence.

Distilled signals:

- Taste is a language: using experts, samples and shared vocabulary can turn vague "good/bad" reactions into a practical recommendation engine.
- Local AI strength is not automatically data-center bearish. Separate frontier workloads, enterprise data workflows, token-cost economics and edge-device sufficiency.
- Computex keynotes can move stocks, but the right check is still workload, product maturity, valuation location and whether the supply chain captures real content growth.
- AIPC is a second-chance theme after the first weak cycle; watch whether on-device models reach a useful sweet spot and whether higher ASP/material content offsets weak traditional PC demand.
- In a broad bull market, rotation into leaders such as TSMC/NVIDIA and adjacent themes such as power semis should be respected, but not chased without identifying the mechanism and price location.

## EP668 anchor

`EP668.md` title: `股癌逐字稿 EP668｜電腦展見聞錄與槓桿天譴論`

Generation note:

- Public transcript source exposed EP668 by 2026-06-07, so `EP668.md` was synced from `whatmkreallysaid.com`.
- The downloaded public Markdown body contained a stale `# EP688 ...` header even though the filename, frontmatter, RSS, and Apple page all identify the episode as EP668; the local corpus header was corrected to `# EP668 ...`.
- The prior machine-generated `EP688.*` artifacts were quarantined as a wrong-number set, not used as the current source.

Major segments:

- Sponsor/travel segment: Saily/eSIM and iOS travel-plan handling are framed as removing the boring failure point before a trip, rather than optimizing only the fun itinerary.
- Computex segment: the show pushes back on "Computex is too public / too many outsiders" complaints; broad public interest and Huang-signature attention are treated as out-of-circle energy, not only noise.
- Enterprise AI infrastructure segment: CPU rack, Agentic AI workflow, Midplane/Cube/backplane and related components are watched through actual workload growth, not one-line CPU/GPU shortcut math.
- Consumer AI segment: NVIDIA/Adobe/RTX Spark demos make AI feel practical again: faster Premiere/Photoshop, rendering, local models, gaming and creator workflows matter more than abstract future talk.
- Human-in-the-loop segment: fully automated creator output is treated as AI slop risk; repetitive retail push messages can be automated, but creator/teacher/director/brand work still needs personal taste, accountability and "味道".
- Local AI economics segment: high unified memory, local Agentic AI, token-cost savings, gaming capability and work/entertainment dual use make AI hardware investability depend on concrete payback and workflow fit.

Distilled signals:

- A tech show "出圈" is bullish when public excitement pulls real demos, talent and budgets into the open; do not confuse broader attendance with lower quality by default.
- AI bubble risk falls when demos move from "imagine the future" to immediate work, creation and entertainment productivity. The check is whether users would actually pay now.
- Software is not automatically dead when agents improve. Better AI coding and agentic tools can create new useful software layers for monitoring, dispatch, operations and customer workflows.
- Local AI hardware needs more than a label: memory pool, model size, latency, software support, gaming/content creation use and monthly token-cost savings decide whether the buyer has a reason.
- AI automation should be split by content type: repeatable commodity output can be automated aggressively, but high-trust human taste and personal voice lose value if they become canned output.

## EP669 anchor

`EP669.md` title: `股癌逐字稿 EP669｜三十四歲感懷與市場信仰考`

Generation note:

- Public transcript source exposed EP669 by 2026-06-11, so `EP669.md` was synced from `whatmkreallysaid.com`.
- SoundOn and Apple both identified EP669 as the latest public episode; no local audio download or machine transcription was needed.

Major segments:

- Sponsor/AI-ad segment: Dr. 情趣 sponsor copy turns AI synchronized haptics into a joking but concrete example of technology moving from abstract AI talk into bodily experience and consumer product adoption.
- Thirty-fourth-birthday segment: body metrics, training, diet, gifts, family memory and listener care become an operator review, not only sentiment; the show frames health and attention as the base layer that lets everything else continue.
- Career/wealth segment: after reaching a financial stage, the speaker expresses a desire to put future energy into venture, small business, creative projects and family life rather than treating stocks as the whole identity forever.
- Market segment: passive components stay strong, TSMC price-hike rumors are read as a positive but partly recycled signal, and Semi-Analysis bearish talk is treated as noise amplified by a falling tape unless it changes the actual supply-chain mechanism.
- Apple WWDC segment: Apple is judged as conservative but strategically reasonable; screen-aware AI and Google model integration matter because Apple controls the device interface and distribution, even if it is not first on frontier-model spectacle.
- Q&A/life segment: Neuralink, hobbies, debt consolidation, loss of a child, public humiliation, glass-heart sensitivity and children growing up are answered through reversibility, emotional carrying capacity, family support and the difference between useful pressure and performative tragedy.

Distilled signals:

- Birthday and body updates are not filler: the operator's health, family memory, and energy allocation decide what risks and projects are sustainable.
- A financial "win" should open options, not become a life prison. When the game has already paid, ask what future work gives meaning, learning and family fit.
- Treat bearish expert reports as one signal inside the tape: ask whether they reveal a real mechanism change or simply give the market a vocabulary for a normal drawdown.
- Apple-style AI should be judged by interface control, installed base, partner leverage and user habit, not only by whether it wins the keynote spectacle.
- Emotional resilience is not pretending nothing hurts; it is building enough support, perspective and reversibility that criticism or market volatility does not become identity collapse.

## EP670 anchor

`EP670.md` title: `股癌逐字稿 EP670｜瘦瘦針OD誌與SpaceX首航論`

Generation note:

- Public transcript source exposed EP670 by 2026-06-13, so `EP670.md` was synced from `whatmkreallysaid.com`.
- SoundOn and Apple both identified EP670 as the latest public episode; no local audio download or machine transcription was needed.

Major segments:

- Sponsor/opening segment: market volatility is turned into a body/fit analogy; the practical rule is to know which things can be held and which need to be moved rather than reacting to every price shock.
- Instruction-manual / weight-loss-drug segment: personal OD story becomes a high-risk decision rule: improvisation is fine for reversible toys, but dosage, leverage, contracts and medical/financial rules require reading the instructions first.
- Glass-heart / mute segment: attention is treated as a scarce asset; negative feedback, social comparison and unnecessary notifications should be muted instead of allowed to become identity-level noise.
- SpaceX / satellite segment: dream-premium assets are split into current engine, far-future option value and belief layer; the signal to watch is whether related satellite names sell off when rumor becomes public fact.
- Taiwan-market / passive-component segment: post-correction strength is judged through which groups recover and whether passive-component price hikes spread beyond the narrow AI-critical SKUs.
- Meta AI / regulation / edge segment: frontier-model strength, export restrictions and cost all point back to workload placement across cloud, open models, local devices and edge computing.

Distilled signals:

- Reading instructions is not bureaucracy; it is a risk gate for irreversible decisions.
- Attention deserves portfolio discipline: mute low-quality inputs before they compound into bad mood and bad decisions.
- Dream valuation is not automatically wrong; the question is whether the user knows which part is current cash flow, which part is option value, and who may be selling into the public story.
- When frontier models advance, ask what capability will later become good enough locally or at the edge.

## EP671 anchor

`EP671.md` title: `股癌逐字稿 EP671｜離散元件覓蹤與隨機人生論`

Generation note:

- Public transcript source exposed EP671 by 2026-06-17, so `EP671.md` was synced from `whatmkreallysaid.com`.
- SoundOn and Apple both identified EP671 as the latest public episode; no local audio download or machine transcription was needed.

Major segments:

- Opening segment: fake accounts, market rumors and social short-video noise are treated as attention-risk and information-quality problems rather than things worth fighting one by one.
- Lifestyle/restaurant segment: Lin-kou dining, real estate and side-business ideas are framed through actual use, local demand, rent/cost structure and whether the operator really wants the daily work.
- Market breadth segment: Taiwan's rally is described as broadening from AI/electronics into financials and mid/small caps; the risk is later convergence, but the tape first deserves respect.
- Discrete-component / power-semiconductor segment: the next market search moves away from crowded passive-component trades toward IDM signals, non-China sourcing, PMIC, DrMOS, 800V DC, board-space constraints and supply-demand spillover.
- Q&A/life segment: career regret, office conflict, credit-card installment, wine, medical work, premature birth and restart questions are answered through reversibility, support systems and not judging a life path only by final outcome.

Distilled signals:

- When a theme becomes crowded, do not automatically say it is wrong; ask where the demand, validation or shortage pressure may spill next.
- Supply-chain stories should be classified as bottleneck shortage, cost pass-through, second-source validation, non-China substitution or inventory pull-forward.
- A low headline penetration rate can still be meaningful when the market is huge and content value per system rises.
- Life decisions should be managed with reversible experiments, cash-flow runway and emotional carrying capacity instead of hindsight blame.

## EP672 anchor

`EP672.md` title: `股癌逐字稿 EP672｜功率元件缺貨論與軟體職涯重整`

Generation note:

- Public transcript source still stopped at EP671 when checked on 2026-06-20, so EP672 was first generated from the SoundOn RSS enclosure with `faster-whisper-large-v3`.
- Public transcript source exposed EP672 by 2026-06-24, so `EP672.md` was replaced with the public Markdown. The earlier `.raw.*` machine artifacts remain as provenance.

Major segments:

- Opening / Lin-kou segment: local small-business support is framed as patient capital plus the need for a real operator; money in the market compounds faster, so local projects need good people and clear leverage rather than random checks.
- Family / holiday segment: Dragon Boat travel, sunscreen, insects, family energy and adolescent conflict are treated as operator-state and relationship-risk problems; do not leave permanent scars during temporary phases.
- Market new-high segment: Taiwan index making a new high is evidence about the aggregate tape, even if the listener's own holdings are weak; do not infer the whole economy or market from one personal book.
- Power-semiconductor / IDM segment: after passive components became crowded, attention moves toward power semiconductors, IDM lead times, second-source validation, non-China sourcing, MOSFET and high-voltage applications; still avoid declaring all related names "real" before evidence arrives.
- Prediction / execution Q&A: market timing is handled as adaptive response, not prophecy; each day holding a position is still a decision, and a view can change when new tape evidence appears.
- Robot / automation Q&A: robot component themes may trade before revenue proof, then later get another phase when revenue and earnings appear; more conservative users can wait for visible contribution but should know that the dream phase may already have moved.
- Taste / consumption Q&A: zero-calorie drinks, coffee, wine, zongzi and restaurants reinforce that taste is contextual; avoid turning subjective preference into tribal ranking when many choices are above the quality bar.
- AI software-engineer Q&A: AI-driven job anxiety should separate pandemic over-hiring cleanup from real tool leverage; software work shifts from raw coding toward product judgment, workflow design and using AI to expand what can be built.

Distilled signals:

- A strong index is a signal even when the user's holdings are not participating; first separate personal portfolio pain from market breadth.
- When one theme is crowded, the next search should map actual order spillover, lead time, second-source qualification and product mix rather than just rotate slogans.
- Do not worship prediction accuracy; update the view when the tape and mechanism change.
- AI labor disruption is not only replacement. Separate over-hiring cleanup, tool leverage, new TAM, cost constraints and product responsibility.
- Taste and lifestyle answers should preserve subjectivity: filter genuinely bad experiences, but avoid fake precision when choices are simply different good options.

## EP673 anchor

`EP673.md` title: `股癌逐字稿 EP673｜韓國人真的很會玩`

Generation note:

- Public transcript source stopped at EP672 when checked on 2026-06-24, so EP673 was generated from SoundOn audio.
- EP673 audio came from the SoundOn RSS enclosure and was transcribed locally with `faster-whisper-large-v3`.
- The artifact was generated with `condition_on_previous_text=False`, converted to Taiwan traditional Chinese, and corrected for high-confidence Gooaye/industry terminology. Treat it as machine-generated until a public human transcript appears.

Major segments:

- 全聯酒品 task: sample widely, use ratings as a first-pass filter, then build a personal taste vocabulary instead of worshipping price tags.
- Market pullback: after a fast rally, separate ordinary pullback from false breakout or structural break; do not force a dramatic explanation when the tape has not broken.
- Korea/leveraged-crowd contagion: Korean retail leverage, ETFs, crypto and hot U.S. names can create cross-market pressure, but this is not automatically a Taiwan fundamental change.
- Position rotation: moving between TSM, mid-cap, passive components and power components should depend on whether the original group is actually dead and who first recovers.
- MediaTek/Google ASIC line: Triggerfish-style early awards are useful option-value evidence, but should not be modeled as standalone financial contribution before roadmap/volume evidence.
- Passive components: resistor tightness can emerge after capacitor/inductor supply pressure and procurement fear spill over; classify pull-in, real demand, pricing and capacity constraints separately.
- Work pressure/freedom: muting toxic people is easiest when one has built income, role and family support; for students or employees trapped under professors/managers, the practical goal is building an exit route.
- Functional training: body awareness, joint mobility and whole-chain force transfer become operator infrastructure, not just gym aesthetics.

Distilled signals:

- Do not let a normal pullback become a total worldview flip unless leadership, breadth or mechanism also breaks.
- Short-term external deleveraging can be a trigger without being the root cause of a local industry story.
- Treat early ASIC/product awards as option value until volume, roadmap and customer evidence become firmer.
- For unavoidable toxic environments, the useful answer is not only emotional toughness; build the cash-flow, credential or support route that makes exit possible.

## Repeated transcript patterns

### 1. Industry knowledge is useful only when connected to price

In EP645, the speaker describes the evolution from seeking industry contacts and knowledge, to realizing that pure early knowledge can be capital-inefficient if the market does not pay immediately. The mature pattern becomes a hybrid:

- Use industry knowledge to understand the business floor.
- Use price action and technical signals to time exposure.
- Use position sizing and staged entries when breakouts fail but business quality remains intact.

Skill implication: never answer a market question with "the story is right" alone. Ask whether the market is paying now, later, or already paid too much.

### 2. Probability beats hero narratives

In recent transcripts, especially EP643-EP646, the voice repeatedly rejects grand prediction posture:

- Do not call tops/bottoms as a personality.
- Do not treat one success as proof of being chosen.
- Keep asking what would prove the current read wrong.

Skill implication: output should include "what I would watch next" and "where this breaks."

### 3. Social information is both edge and noise

The show often treats listeners, industry friends, and social media as useful sensors, but also warns about KOL posts, sell-side revisions, and market-driven essays that appear after price moves.

Skill implication: when using external signals, classify them by timing and incentive:

- Pre-move operational signal.
- Post-move justification.
- Promotional or bag-passing narrative.
- Genuine expert correction.

### 4. Personal life is part of the investment system

EP645 and EP656 connect family time, body, workstation, health, and hobbies to long-term performance. The recurring idea is that a trader/investor is not only a portfolio; the operator matters.

Skill implication: for life questions, use portfolio language without reducing people to money. Ask about time, attention, health, family, and reversibility.

### 5. Strategic flexibility is not the same as excuse-making

EP657's trading Q&A distinguishes between short-term line-based exits and wave/position trades. The key is not the specific moving average, but the reason for the trade and the room left by sizing.

Skill implication: when users ask about stops or adding, do not output a single rigid rule. Ask whether the entry was based on pure price action or supported by a story/fundamental floor, then adjust exit logic accordingly.

### 6. The operator is part of the portfolio

EP659 makes the health/body point explicit: weight, mobility, functional training, sleep quality, and recovery are not lifestyle ornaments; they determine how well the person can keep operating through volatile markets. EP660 extends this into sleep and cooling: in overheated markets, the operator needs recovery systems that reduce impulsive decisions. EP661 adds a curiosity discipline: sample widely enough to build taste, but keep recalibrating so the price tag does not become the decision. EP662 adds the medical-risk and support-system layer: health uncertainty, family backup, and trusted experts change how much risk a person can actually carry. EP663 turns body maintenance into a full system: weight, mobility, pain, coaching, and physical therapy all become operator infrastructure. EP664 adds the home/family utility layer: generic liquidity or location rules are secondary to how the household will actually live with the asset. EP665 adds eyes, attention, and deliberate slowness: the operator needs not only stamina but also sustainable sensory input and the ability to notice small details. EP666 turns slowness into a practical feedback loop: noticing breath, posture, small routines, and body tension can directly change physical pain and decision rhythm. EP667 adds taste-language training: slowing down enough to name sensations turns vague preference into a reusable decision vocabulary. EP668 adds personal-output taste: automation should remove commodity labor, not erase the human flavor that creates trust. EP669 adds energy allocation after success: health, family, creative work and future projects should decide whether continuing the same money game still makes sense. EP670 adds instruction-manual humility and attention hygiene: the operator protects health, capital and mood by reading high-risk rules and muting low-quality inputs. EP671 adds random-path humility: do not judge a career, side business or life turn only by its final result; manage experiment size, support and reversibility. EP672 adds family-phase and taste-context humility: temporary conflict, social energy, food preference and operator fatigue should be sized and handled without turning one moment into a permanent identity sentence.

Skill implication: when users ask about performance, execution, career, or burnout, do not only discuss tactics. Ask what is happening to the operator: sleep, attention, body, family time, and whether the system is sustainable.

## Expression notes

Common rhetorical moves:

- Start with "我會這樣看" or "簡單講".
- Qualify aggressively: "不一定", "目前看不到", "還要驗證", "邊走邊看".
- Use market analogies for ordinary goods: body as hardware, desk setup as productive asset, hobbies as sample-building.
- Push back on social consensus with direct questions: who pays, who benefits, what changed, what data is missing?
- When discussing forward-looking industry checks, explicitly say what must be verified by public data later.

Avoid:

- Overdoing catchphrases.
- Turning the voice into pure profanity.
- Making investment prescriptions.
