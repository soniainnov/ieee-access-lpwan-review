# Article Annotation #08

---

## Reference
- **[8]** J. Haxhibeqiri, E. De Poorter, I. Moerman, and J. Hoebeke. "A Survey of LoRaWAN for IoT: From Technology to Application." *Sensors*, vol. 18, no. 11, article 3995, MDPI, Nov. 2018. DOI: 10.3390/s18113995

## Metadata
- **Year:** 2018
- **Database:** MDPI (PubMed Central / Open Access)
- **Type:** Journal — Systematic Literature Review
- **Q-rank:** Q1 (Sensors, MDPI — SCIE indexed)
- **Citations:** 1,000+ — highly cited LoRaWAN survey
- **Affiliation:** IDLab, Department of Information Technology, Ghent University–IMEC, 9052 Ghent, Belgium

## Keywords
> LoRaWAN, LoRa, IoT, LPWAN, physical layer, network layer, security, reliability, SWOT analysis

## Research Question / Objective
> What is the state of the art in LoRaWAN technology from physical and network layer perspectives, what improvements have been proposed, and what are the remaining challenges?

## Methodology
- **Study type:** Structured literature review
- **Databases searched:** Google Scholar, IEEE Xplore
- **Date range:** 2015–September 2018
- **Papers identified:** ~2,000 (Google Scholar); 162 (IEEE Xplore — 18 journal, rest conference)
- **LPWAN technology covered:** LoRaWAN only
- **AI/ML technique:** Minimal — k-nearest neighbors for fingerprinting localization only
- **Agriculture domain:** Mentioned (underground water monitoring, soil monitoring) — not the focus

## Key Findings
1. LoRaWAN provides low-power, low-data-rate communication over wide areas; outdoor coverage up to ~15 km (SF12).
2. Outdoor reliability at 2 km: **95.5% packet reception ratio**; indoor coverage effective within 60 m with <2% packet loss.
3. Mobility significantly degrades performance: 45% packet loss at 0.4 miles/15 mph vs. <2% stationary.
4. Security vulnerabilities identified: replay attacks, eavesdropping, bit-flipping, counter overflow (LoRaWAN v1.0).
5. SWOT analysis provided covering all LoRaWAN stack layers.

## Limitations Acknowledged by Authors
> - Review period snapshot (2015–2018) — rapidly evolving technology
> - Mostly simulation-based scalability assessments (limited large-scale testbeds)
> - Primarily single-gateway deployment setups in reviewed literature

## Relevance to Our Review
- **Section(s) covered:** II (LPWAN Fundamentals — LoRaWAN deep dive), IX (Challenges — security)
- **Gap addressed:** Foundational LoRaWAN reference — no comparative LPWAN analysis, minimal AI/ML, agriculture only peripheral
- **Citation priority:** **Essential** — must cite in Section II (LoRaWAN subsection)

## Why It Is NOT a Competitor
> LoRaWAN-only scope (no NB-IoT, no Sigfox comparison). AI/ML is absent. Agriculture only briefly mentioned. Covers 2015–2018 only — our review extends to 2025 and adds the AI/ML + precision agriculture systematic dimension.

## Notes
> - MDPI Open Access: https://www.mdpi.com/1424-8220/18/11/3995
> - PubMed Central (free): https://pmc.ncbi.nlm.nih.gov/articles/PMC6264067/
> - ResearchGate: https://www.researchgate.net/publication/329006988
> - Status: [ ] Read  [ ] Full annotation complete
