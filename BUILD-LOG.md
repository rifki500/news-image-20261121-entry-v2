# BUILD-LOG — news-image-20261121 v2 ("The World Today")

## Entry

- **Competition:** `news-image-20261121` — "Sum up 21 November's world news in one image"
- **Image:** `entry.png`, 1024×1024 PNG, 220,456 bytes (under the 1 MiB cap)
- **Stories:** 45 total — 5 leads + 40 compact, across 9 regions
  (Middle East, Europe, Asia-Pacific, Americas, Africa, Science, Sport,
  Business, Global)
- **Renderer:** local build script `render.py` (PIL, DejaVu fonts) — it lives
  outside this repository; `main.py` only copies the finished `entry.png`
  to the output directory (standard library only, no network, byte-identical
  across two runs).
- **Date rule:** every story happened, or was first reported, on Saturday
  21 November 2026. Stories first reported that day (event itself earlier)
  are marked † on the page and flagged below.
- **Verification:** each story was checked by web search against that day's
  reporting (Reuters, AP, AFP, USGS, ESA, UKMTO, NPR, Nature and others)
  on 22 November 2026. Where two sources disagreed on a number, the more
  authoritative / more recent figure is used and the disagreement is noted.

## Lead stories (5)

1. **COP31 talks run into overtime; a deal draws closer** — COP31 in
   Antalya ran past its Friday deadline into Saturday; late Saturday the
   summit president said a final package was near, with fossil fuels still
   the sticking point. Sources: Reuters (Nov 21 brief), The National
   ("COP31 negotiations in overtime, a deal draws closer", late Saturday),
   Bloomberg/COP30-Belém note. Caveat: the summit president's statement was
   a "deal draws closer" update, not a final deal — the final package landed
   on Sunday; the page says "a deal draws closer", not "a deal is done".
2. **Iran strikes Bahrain; US bases hit, Guards say** — Iran's Revolutionary
   Guards said they struck two US positions in Bahrain (al-Riffa, Awali);
   Bahrain reported an industrial-site fire, no injuries, and said its
   defences intercepted other attacks. Iran also claimed it downed a US
   drone near Qeshm Island; the US denied an F-16 was hit. Sources: Reuters
   and Arab News ("Iran strikes Bahrain; US bases hit, Guards say"), AP
   ("Iran says it struck US positions in Bahrain"), Arab News (Qeshm drone
   claim; US denial).
3. **Two tankers hit in the Strait of Hormuz** — UKMTO reported two tankers
   struck by projectiles in the Strait of Hormuz; Iran said one hit a mine
   and claimed it downed a US drone; the US said it was assessing reports.
   Sources: Reuters and AP (Nov 21 briefs), UKMTO. Same story as v1's lead.
4. **Mexico captures 'El Chapo Isidro'** — Fausto Isidro Meza Flores, one of
   the FBI's 10 most wanted, was seized in Guasave, Sinaloa, with US help;
   11 people died in the violence that followed. Sources: Reuters and AP
   (Nov 21 briefs). Same story as v1's lead.
5. **Three Houthi missiles fired at Riyadh intercepted** — Saudi air
   defences stopped three ballistic missiles early on Saturday, two days
   after a strike damaged the PIF Tower. Sources: Reuters and AP (Nov 21
   briefs). Same story as v1's lead.

## DATE CHECK box

"Every story here happened, or was first reported, on Saturday 21 November
2026 — each checked against Reuters, AP, AFP, USGS, ESA and more. Stories
first reported that day are marked †."

## Compact stories (40)

### Middle East (3)

6. **Remains of 129 recovered in Gaza** — civil defence teams pulled 129
   bodies from rubble in central Gaza, officials said. Source: AP brief
   ("Remains of 129 recovered in Gaza").
7. **Blast at Basra power station kills four** — a gas pipeline explosion at
   the Al-Hartha plant injured 35 and halted generation. Source: AP brief
   ("Blast at Basra power station kills four").
8. **Israeli strike kills three in Gaza aid van** — a drone hit a vehicle
   carrying food in Gaza City; a fourth man was shot dead in Jabalia.
   Source: AP brief ("Israeli strike kills three in Gaza aid van").

### Europe (8)

9. **Russian strike kills two in Kryvyi Rih** — a ballistic double-tap on
   Zelenskyy's hometown killed two and wounded 60, including six children.
   Source: AP brief ("Russian strike kills two in Kryvyi Rih").
10. **Russian cargo ship ablaze after drone strike** — the Sparta II, bound
    for Kaliningrad, was hit by two drones in the Gulf of Finland on
    Saturday morning; its crew was evacuated and the ship drifted into
    Finnish waters. Source: The National (Nov 21).
11. **Zelenskyy calls Putin a 'killer'** — he rejected Trump's description
    of Putin as a friend, saying it eases pressure on Moscow. Source: The
    National (Nov 21).
12. **Ukraine hits Omsk plant in Saturday strikes** — drones struck a
    petrochemical plant and an Ozon warehouse; three died in
    Dnipropetrovsk. Source: The National (Nov 21).
13. **Europe denounces Russia after missile lands in Poland** — leaders
    called the airspace breach an escalation; Denmark warned Putin is
    emboldened. Source: The National (Nov 21).
14. **Denmark urges EU to halt Russian tourist visas** — Copenhagen cited a
    foiled assassination plot against a Ukrainian rapper. Source: The
    National (Nov 21).
15. **NATO-cleared pilot held fire over Poland** — a Swedish Gripen pilot
    could not identify a suspected Russian missile in bad weather. Source:
    The National (Nov 21).
16. **Trump tells Europe to defund Ukraine** — the president told European
    leaders to withhold funding after his summit with Putin. Source: The
    National (Nov 21). Caveat: as reported by the outlet; the page says
    "reports said" in the longer summary, shortened on the page to the
    direct claim.

### Asia-Pacific (7)

17. **Toxic liquor kills at least 11 in Manipur** — more than 180 people were
    hospitalised after drinking suspected tainted alcohol. Source: The
    National (Nov 21). Caveat: two sources disagreed on the death toll
    (11 vs 13); the page says "at least 11".
18. **Indonesia hit by massive forest fires** — forest fires burned across
    Indonesia, sending smoke over nearby regions. Source: The National
    (Nov 21).
19. **Japan to fire missiles at Indian ranges †** — Tokyo and New Delhi signed
    a deal letting Japanese forces train on Indian ranges. Source: The
    National (Nov 21). † Date caveat: the deal was signed on Thursday
    19 Nov and first reported on Saturday 21 Nov.
20. **EU and Indonesia sign trade deal** — Brussels and Jakarta formally
    signed an ambitious trade agreement. Source: The National (Nov 21).
21. **Bangladesh boosts security ahead of Hasina's return** — Dhaka
    tightened security amid unrest as the former premier vowed to return.
    Source: The National (Nov 21).
22. **Rubio confirms Quad business forum** — top firms from India, the US,
    Japan and Australia will meet early next year. Source: The National
    (Nov 21).
23. **Mortar shell kills four Afghan students** — an old mortar shell
    exploded in Afghanistan, killing four students. Source: The National
    (Nov 21).

### Americas (7)

24. **FBI and USDA hacked** — hackers hit the FBI's crime database and a USDA
    farm-payments system; Trump called the breach "not good" on Saturday.
    Sources: AP ("FBI and USDA hacked", breaches first reported late Fri
    20 Nov US / Sat 21 Nov UTC) and Reuters (Trump's "not good" comment on
    Saturday). Caveat: the breaches were first reported late Friday US
    time, which is Saturday UTC — inside the competition's "any time zone"
    rule.
25. **Magnitude 6.7 quake shakes central Peru** — the tremor struck Junin at
    00:09 GMT on Saturday; no deaths were reported. Source: USGS (M6.7).
    Caveat: an aggregator (Horizon) listed M6.9; the USGS M6.7 is used.
26. **Man convicted over deadly Palisades Fire** — a federal jury found
    Jonathan Rinderknecht guilty of starting the 2025 Los Angeles fire.
    Source: AP brief ("Man convicted over deadly Palisades Fire").
27. **Canada retail sales strongest since 2022** — sales rose 7.5% year on
    year in September, figures showed on Saturday. Source: AP brief
    ("Canada retail sales strongest since 2022").
28. **Trump posts 'Great Powers 1945, 2026' image** — he paired the 1945
    Yalta photo with this week's summit with Xi and Putin. Source: AP
    brief ("Trump posts 'Great Powers 1945, 2026' Yalta image").
29. **Fifth Circuit rules proxy voting unconstitutional** — the appeals court
    held 9–8 that the House could not count members "present by proxy".
    Source: AP brief ("Fifth Circuit rules proxy voting unconstitutional",
    Texas v. Blanche).
30. **Bayer to pay up to $7.25bn in Roundup deal †** — a Missouri judge
    approved the settlement for cancer claims; Bayer denies Roundup causes
    cancer. Source: AP brief. † Date caveat: the judge approved the deal on
    Friday 20 Nov; it was first reported on Saturday 21 Nov.

### Africa (6)

31. **South Africa mourns ex-deputy president †** — Phumzile Mlambo-Ngcuka,
    71, a former deputy president and UN Women chief, has died. Source:
    AFP summary of African news (Nov 21). † Date caveat: the death was
    announced late Friday 20 Nov / early Saturday 21 Nov.
32. **Somalia expels UAE ambassador** — Mogadishu expelled the envoy,
    escalating a diplomatic row. Source: AFP summary of African news
    (Nov 21).
33. **Egypt secures $2.3bn IMF deal** — Cairo won the loan as its economic
    recovery gained momentum. Source: AFP summary of African news (Nov 21).
34. **700,000 displaced in southern Ethiopia** — volatile conflict has driven
    around 700,000 people from their homes, aid groups said. Source: AFP
    summary of African news (Nov 21).
35. **Funeral boat capsizes in Nigeria; four dead** — a boat carrying
    mourners overturned, killing at least four, including two children.
    Source: AFP summary of African news (Nov 21).
36. **Kenya floods leave six dead** — floods in Kenya killed six people,
    officials said. Source: AFP summary of African news (Nov 21).

### Science & Tech (4)

37. **BepiColombo enters orbit around Mercury** — after an eight-year
    journey, the ESA–JAXA probe arrived at 18:24 UTC on Saturday.
    Sources: ESA (X post, Nov 21, "BepiColombo enters orbit around
    Mercury at 18:24 UTC"), NPR ("BepiColombo enters orbit around Mercury",
    Nov 21).
38. **Mosquito trial cuts dengue by 69%** — Wolbachia mosquitoes protected
    5,700 children in Belo Horizonte, Brazil, a study found. Source: Nature
    (Nov 21, "Mosquito trial cuts dengue by 69%").
39. **Anthropic mathematician claims Riemann proof †** — Levent Alpöge says
    he proved the Riemann Hypothesis with Claude; experts say it needs
    rigorous checking. A rival human-written proof by Stanford postdoc
    Alessandro Maria Masullo appeared the same day. Sources: Fortune
    ("Anthropic mathematician claims Riemann proof") and other Nov 21
    coverage. † Date caveat: Alpöge announced the claim on Friday 20 Nov;
    it was first reported on Saturday 21 Nov. The page frames it as a
    *claim*, not a proven result — the proof is unverified.
40. **AI instructions found hidden in journal papers** — researchers found
    hidden prompts in published papers, raising peer-review concerns.
    Source: Nature (Nov 21, "AI instructions found hidden in journal
    papers").

### Sport (3)

41. **Leeds stun Chelsea 4-1 at Stamford Bridge** — Noah Okafor scored twice
    as Leeds won at Chelsea for the first time since 1999. Source: The
    Guardian (Nov 21, "Leeds stun Chelsea 4-1 at Stamford Bridge").
42. **Canada wins four short-track medals in Seoul** — Canada took four
    medals on Saturday at a World Tour stop in Seoul. Source: CBC
    (Nov 21, "Canada wins four short-track medals in Seoul").
43. **Morocco thrash Fiji 6-0 at U-17 World Cup** — Morocco opened its FIFA
    U-17 World Cup campaign with a 6-0 win in Qatar. Source: FIFA
    (Nov 21, "Morocco thrash Fiji 6-0 at U-17 World Cup").

### Business / Global (2)

44. **Markets plunge as AI sell-off spreads** — the S&P 500 fell 3.7% and the
    Nasdaq 5.3% on Friday; Nvidia dropped 14%. Source: Financial Times
    (Nov 21, "Markets plunge as AI sell-off spreads"). Caveat: the market
    close was Friday 20 Nov, first reported on Saturday 21 Nov — inside the
    competition's "reported on" rule.
45. **UN 'killer robots' talks end in soft deal** — states in Geneva agreed
    to keep talking for two more years, with no binding rules. Source:
    The Guardian (Nov 21, "UN 'killer robots' talks end in soft deal").

## Stories deliberately excluded

- **$22.5M Los Angeles train-heist charges** — announced Thursday 19 Nov,
  not 21 Nov.
- **UK–EU reset deal** — Friday 20 Nov; already in the 20261120 entry.
- **Anthropic IPO debut** — Thursday 19 Nov.
- **Kyiv bridge strikes** — Friday 20 Nov.
- **Berlin student protest; Italy strike; Tunisian activist sentencing** —
  Friday 20 Nov.
- **COP31 "close to final deal" Sunday package** — Sunday 23 Nov, not
  Saturday; the Saturday framing is "a deal draws closer".

## Layout

1024×1024. Masthead "THE WORLD TODAY" + "SATURDAY, 21 NOVEMBER 2026" +
tagline + double rule. Leads in a 3×2 grid (5 stories + the DATE CHECK
box). "THE WORLD IN BRIEF" divider with the story/region count. Compact
stories in a 4×10 grid, each with a red region label, a bold headline and a
one-to-two-line summary. Footer with sources and the † legend. DejaVu
fonts (system). The renderer checks every cell for overflow and reports
any clipped text; this build reports no overflow problems.
