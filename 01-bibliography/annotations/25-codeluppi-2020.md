# Article Annotation #25

---

## Reference
- **[25]** G. Codeluppi, A. Cilfone, L. Davoli, and G. Ferrari. "LoRaFarM: A LoRaWAN-Based Smart Farming Modular IoT Architecture." *Sensors* (MDPI), vol. 20, no. 7, art. 2028, Apr. 2020. DOI: 10.3390/s20072028

## Metadata
- **Year:** 2020
- **Database:** MDPI (Open Access) — PubMed Central: PMC7180486
- **Type:** Journal — System Design + Field Deployment Study
- **Q-rank:** Q1 (Sensors, MDPI — SCIE indexed)
- **Citations:** 154 (Semantic Scholar)
- **Affiliation:** IoT Lab, Department of Engineering and Architecture, University of Parma, Parco Area delle Scienze 181/A, 43124 Parma, Italy (all four authors)

## Keywords
> IoT, smart agriculture, LoRaWAN, smart farming, modular architecture, WSN, multi-protocol gateway, middleware, heterogeneous networks, vineyard monitoring, greenhouse, energy harvesting

## Research Question / Objective
> How can a low-cost, modular, LoRaWAN-based IoT platform be designed and validated in a real farm environment to provide customizable, extensible, and sustainable smart farming capabilities across heterogeneous on-farm applications?

## Methodology
- **Study type:** System design + 81-day real field deployment
- **Deployment site:** Podere Campáz biological farm, Italy
- **Platform:** LoRaFarM — star-of-stars LoRaWAN topology with multi-protocol gateway
- **Agriculture scenarios:** Vineyard monitoring (outdoor) + greenhouse vegetable monitoring (indoor)
- **LPWAN technology covered:** LoRaWAN exclusively ✓ — with IEEE 802.11 for indoor short-range nodes
- **AI/ML technique:** Not integrated — rule-based monitoring and data collection platform
- **Metrics:** Packet delivery rate, battery autonomy, data continuity over 81 days

## Key Findings
1. **>80% packet transmission success rate** sustained over 81 days of continuous deployment — confirms LoRaWAN reliability for real farm environments.
2. **Vineyard LoRaWAN End Nodes: ~84-day theoretical battery autonomy** — viable for seasonal agricultural monitoring without manual recharging.
3. **Greenhouse nodes: ~8-day autonomy** — different energy profile for indoor dense-sensing applications; solar panel recharging compensates.
4. Star-of-stars LoRaWAN topology (farm-level modules → multi-protocol gateway → middleware → servers) enables heterogeneous sensor integration without platform redefinition.
5. Web dashboard and mobile application validated as high-level modules — demonstrates end-to-end farmer-accessible smart farming platform.

## Limitations Acknowledged by Authors
> - No AI/ML analytics — data collection platform without intelligent decision support
> - LoRaWAN only — no NB-IoT or Sigfox alternative analysis
> - Greenhouse nodes require solar recharging — battery autonomy insufficient without energy harvesting
> - Single-farm Italian deployment — generalizability across climates and farm types to verify

## Relevance to Our Review
- **Section(s) covered:** II (LPWAN — LoRaWAN star-of-stars deployment architecture), V (Applications — vineyard + greenhouse monitoring), VII (Case Studies — **real 81-day farm deployment**), IX (Challenges — battery autonomy limits, indoor/outdoor performance differential)
- **Gap addressed:** Direct — LoRaWAN in real precision agriculture deployment; **missing AI/ML layer, no NB-IoT/Sigfox comparison, no systematic review methodology**
- **Citation priority:** High — Sensors Q1, 154 citations, real farm deployment; cite in **Section VII** as Italian LoRaWAN case study; also Section V for vineyard + greenhouse applications

## Why It Is NOT a Competitor
> System design and field deployment paper — no AI/ML, no NB-IoT/Sigfox comparison, no PRISMA methodology, no systematic review. Serves as a key real-world case study in Section VII demonstrating LoRaWAN deployment feasibility for multi-environment precision farming.

## Notes
> - MDPI Open Access: https://www.mdpi.com/1424-8220/20/7/2028
> - PubMed Central (free): https://pmc.ncbi.nlm.nih.gov/articles/PMC7180486/
> - PubMed: https://pubmed.ncbi.nlm.nih.gov/32260338/
> - DOI: https://doi.org/10.3390/s20072028
> - **Key stats for Section VII:** >80% PDR, 81-day continuous deployment, 84-day battery (vineyard), Podere Campáz farm (Italy)
> - **Key stats for Section IX:** 8-day greenhouse node autonomy — demonstrates need for solar harvesting in high-frequency indoor sensing
> - Status: [ ] Read  [ ] Full annotation complete
