# Article Annotation #24

---

## Reference
- **[24]** M. Ballerini, T. Polonelli, D. Brunelli, M. Magno, and L. Benini. "NB-IoT Versus LoRaWAN: An Experimental Evaluation for Industrial Applications." *IEEE Transactions on Industrial Informatics*, vol. 16, no. 12, pp. 7802–7811, Dec. 2020. DOI: 10.1109/TII.2020.2987423

## Metadata
- **Year:** 2020
- **Database:** IEEE Xplore
- **Type:** Journal — Experimental Evaluation / Measurement Study
- **Q-rank:** Q1 (IEEE Transactions on Industrial Informatics — SCIE indexed, IF ~12)
- **Citations:** 300+ — landmark experimental NB-IoT vs LoRaWAN comparison
- **Affiliation:**
  - M. Ballerini, T. Polonelli, D. Brunelli, L. Benini — University of Bologna, Italy
  - M. Magno, L. Benini — Integrated Systems Laboratory, ETH Zurich, Switzerland

## Keywords
> NB-IoT, LoRaWAN, LPWAN, experimental evaluation, energy efficiency, quality of service, coverage, battery lifetime, industrial IoT, in-field measurement, packet delivery ratio, payload length

## Research Question / Objective
> How do NB-IoT and LoRaWAN compare in real in-field conditions across the four key dimensions of energy efficiency, battery lifetime, quality of service (QoS), and coverage — using the same application context for a fair evaluation?

## Methodology
- **Study type:** Experimental in-field measurement study
- **Comparison:** NB-IoT vs LoRaWAN — same application, same hardware, same conditions
- **Metrics measured:** Energy consumption, battery lifetime, QoS (packet delivery ratio), coverage (indoor multi-story + outdoor)
- **LPWAN technology covered:** NB-IoT + LoRaWAN directly compared ✓ — Sigfox not included
- **AI/ML technique:** None — physical layer performance benchmarking
- **Agriculture domain:** Industrial IoT — results transferable to agricultural sensor deployments

## Key Findings
1. **LoRaWAN uses 10× less energy than NB-IoT** for occasional, latency-sensitive transmissions — decisive advantage for battery-powered agricultural sensors.
2. NB-IoT energy consumption is nearly independent of payload length — favorable for applications using buffering/caching strategies (e.g., periodic batch uploads).
3. LoRaWAN achieves reliable indoor coverage including multi-story buildings (tested up to 8 floors) and outdoor scenarios.
4. NB-IoT benefits from cellular infrastructure coverage guarantees — stronger QoS SLA in areas with cellular network.
5. Technology choice between NB-IoT and LoRaWAN depends on application profile: LoRaWAN for energy-critical/occasional transmissions; NB-IoT for payload-heavy/buffered applications.

## Limitations Acknowledged by Authors
> - Sigfox not included in comparison
> - Industrial application context — agricultural-specific conditions (field distances, canopy obstruction) not tested
> - In-field results are deployment-specific — generalizability to rural agricultural areas limited

## Relevance to Our Review
- **Section(s) covered:** II (LPWAN — NB-IoT vs LoRaWAN characteristics), VI (Comparative Performance Analysis — **quantitative energy benchmark**), IX (Challenges — energy constraints for LPWAN sensor nodes)
- **Gap addressed:** Strong — provides the quantitative NB-IoT vs LoRaWAN benchmark our Section VI comparative analysis cites; **no agriculture context, no Sigfox, no AI/ML**
- **Citation priority:** Very High — IEEE TII Q1, 300+ citations; **essential citation for Section VI**: "LoRaWAN consumes 10× less energy than NB-IoT for occasional transmissions [24]"

## Why It Is NOT a Competitor
> Experimental measurement paper for industrial IoT — no precision agriculture application, no AI/ML analysis, no Sigfox, no systematic review methodology. Provides the quantitative LPWAN performance baseline that our Section VI comparative analysis builds upon for agricultural deployment recommendations.

## Notes
> - IEEE Xplore: https://ieeexplore.ieee.org/document/9068491/
> - ETH Zurich repository: https://www.research-collection.ethz.ch/handle/20.500.11850/399676
> - DOI: https://doi.org/10.1109/TII.2020.2987423
> - **Key stat for Section VI:** LoRaWAN 10× lower energy vs NB-IoT for occasional transmissions — critical quantitative benchmark
> - **Key stat for Section IX:** NB-IoT energy payload-independence → buffering strategy advantage for periodic agricultural monitoring
> - **Section II cross-reference:** Complements Wang et al. (2017) [9] NB-IoT primer and Haxhibeqiri et al. (2018) [8] LoRaWAN survey with experimental performance data
> - Status: [ ] Read  [ ] Full annotation complete
