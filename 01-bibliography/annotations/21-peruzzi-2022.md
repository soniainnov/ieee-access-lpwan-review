# Article Annotation #21

---

## Reference
- **[21]** G. Peruzzi and A. Pozzebon. "Combining LoRaWAN and NB-IoT for Edge-to-Cloud Low Power Connectivity Leveraging on Fog Computing." *Applied Sciences*, vol. 12, no. 3, art. 1497, Jan. 2022. DOI: 10.3390/app12031497

## Metadata
- **Year:** 2022
- **Database:** MDPI (Open Access)
- **Type:** Journal — System Architecture + Experimental Validation
- **Q-rank:** Q2 (Applied Sciences, MDPI — SCIE indexed)
- **Citations:** ~50+ (to verify — 2022 paper)
- **Affiliation:** Department of Information Engineering and Mathematics, University of Siena, Italy

## Keywords
> LoRaWAN, NB-IoT, LPWAN, fog computing, edge computing, multi-protocol gateway, MQTT, IoT architecture, hybrid connectivity, edge-to-cloud, low power, peer-to-peer

## Research Question / Objective
> Can a hybrid network architecture combining LoRaWAN and NB-IoT — with multi-protocol gateways and fog computing — provide flexible, low-power, edge-to-cloud connectivity that is transparent to the underlying LPWAN technology?

## Methodology
- **Study type:** System architecture design + experimental validation
- **Architecture layers:** Sensor nodes (LoRaWAN or NB-IoT) → Multi-protocol gateway → Cloud (MQTT over NB-IoT uplink)
- **LPWAN technology covered:** LoRaWAN + NB-IoT simultaneously ✓ — hybrid comparative architecture
- **Fog computing role:** Peer-to-peer NB-IoT subnetworks enable local fog processing before cloud upload
- **AI/ML technique:** Not the primary focus — network architecture and connectivity paper
- **Agriculture domain:** Generic IoT — applicable to precision agriculture deployments

## Key Findings
1. Multi-protocol gateway successfully receives LoRaWAN packets and uploads to cloud via NB-IoT using MQTT — validated experimentally.
2. Cloud infrastructure is transparent to underlying LPWAN technology — data stored identically regardless of LoRaWAN or NB-IoT origin.
3. NB-IoT peer-to-peer subnetworks enable fog computing paradigm: local processing before cloud upload reduces latency and bandwidth.
4. Hybrid LoRaWAN + NB-IoT architecture extends coverage and flexibility beyond single-LPWAN deployments.
5. Architecture provides a blueprint for combining complementary LPWAN strengths: LoRaWAN's cost-effective unlicensed deployment + NB-IoT's cellular infrastructure reliability.

## Limitations Acknowledged by Authors
> - Sigfox not included in hybrid architecture
> - No AI/ML analytics layer — data connectivity only
> - No agriculture-specific deployment or performance validation
> - Fog computing tested in controlled conditions

## Relevance to Our Review
- **Section(s) covered:** II (LPWAN — LoRaWAN + NB-IoT hybrid architecture), VI (Comparative Analysis — LoRaWAN vs NB-IoT complementarity), X (Future Directions — hybrid LPWAN connectivity)
- **Gap addressed:** Partial — LoRaWAN + NB-IoT combined architecture; **no agriculture context, no AI/ML, no Sigfox**
- **Citation priority:** Medium — applicable to Section II and VI for hybrid LPWAN architecture discussion; supports argument for multi-LPWAN integration in precision agriculture

## Why It Is NOT a Competitor
> Network architecture paper — no systematic review, no agriculture application, no AI/ML integration, no Sigfox coverage. Provides technical reference for hybrid LoRaWAN+NB-IoT architectures that could support the multi-LPWAN AI/ML systems our review examines.

## Notes
> - MDPI Open Access: https://www.mdpi.com/2076-3417/12/3/1497
> - DOI: https://doi.org/10.3390/app12031497
> - **Key architecture insight for Section II:** Fog computing paradigm bridging LoRaWAN and NB-IoT — cite when discussing hybrid LPWAN deployments and edge intelligence
> - **Section VI relevance:** Demonstrates LoRaWAN+NB-IoT complementarity — LoRaWAN for cost-effective unlicensed sensing, NB-IoT for reliable cellular backhaul
> - Status: [ ] Read  [ ] Full annotation complete
