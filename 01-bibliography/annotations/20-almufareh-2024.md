# Article Annotation #20

---

## Reference
- **[20]** M. F. Almufareh, M. Humayun, Z. Ahmad, and A. Khan. "An Intelligent LoRaWAN-Based IoT Device for Monitoring and Control Solutions in Smart Farming Through Anomaly Detection Integrated With Unsupervised Machine Learning." *IEEE Access*, vol. 12, pp. 119072–119086, 2024. DOI: 10.1109/ACCESS.2024.3450587

## Metadata
- **Year:** 2024
- **Database:** IEEE Xplore (Open Access)
- **Type:** Journal — System Design + Experimental Study
- **Q-rank:** Q1 (IEEE Access — SCIE indexed) — **same target journal as our review**
- **Citations:** Early citations (2024 paper — to verify on IEEE Xplore)
- **Affiliation:** University of Roehampton, UK (Almufareh, Humayun, Ahmad, Khan)

## Keywords
> LoRaWAN, IoT, smart farming, precision agriculture, anomaly detection, Isolation Forest, unsupervised machine learning, Random Forest, linear regression, temperature monitoring, humidity monitoring, agricultural IoT

## Research Question / Objective
> Can a LoRaWAN-based IoT device integrated with unsupervised machine learning (Isolation Forest) reliably detect anomalies in agricultural sensor data (temperature, humidity) and enable intelligent monitoring and control solutions for smart farming?

## Methodology
- **Study type:** System design + experimental evaluation
- **Hardware:** Custom LoRaWAN IoT device for sensor data acquisition and transmission
- **LPWAN technology covered:** LoRaWAN explicitly ✓ — end-to-end LoRaWAN IoT architecture
- **AI/ML techniques:**
  - **Isolation Forest** — unsupervised anomaly detection on temperature/humidity data
  - **Random Forest** — predictive model for temperature variation
  - **Linear Regression** — baseline predictive model comparison
- **Agriculture domain:** Smart farming — environmental monitoring (temperature, humidity), irrigation/control decision support

## Key Findings
1. LoRaWAN IoT device successfully acquires and transmits real-time agricultural sensor data for smart farming monitoring and control.
2. Isolation Forest effectively detects anomalies in temperature and humidity sensor streams — validated on field data.
3. Random Forest outperforms Linear Regression for temperature prediction — unsupervised anomaly + supervised prediction pipeline demonstrated.
4. LoRaWAN connectivity enables farmers to access real-time readings for on-demand resource optimization.
5. Combined LoRaWAN + ML architecture provides an actionable precision farming decision-support system.

## Limitations Acknowledged by Authors
> - NB-IoT and Sigfox not compared — single LPWAN technology (LoRaWAN only)
> - Limited to temperature and humidity — broader soil/crop parameter coverage needed
> - Field validation at single-site scale

## Relevance to Our Review
- **Section(s) covered:** II (LPWAN — LoRaWAN deployment), III (AI/ML — Isolation Forest + Random Forest), V (Applications — smart farming monitoring), VIII (AI Use Cases — anomaly detection in agricultural IoT)
- **Gap addressed:** Direct — LoRaWAN + unsupervised ML for smart farming; **missing NB-IoT/Sigfox comparison, no PRISMA systematic approach**
- **Citation priority:** High — IEEE Access Q1 (same journal); 2024 most recent entry for Group D; cite in Sections II, V, and VIII

## Why It Is NOT a Competitor
> System design and experimental paper — not a systematic review. Covers LoRaWAN only with no comparative LPWAN analysis (no NB-IoT, no Sigfox) and no PRISMA methodology. Our review provides the systematic multi-LPWAN comparative framework within which this type of LoRaWAN+ML deployment fits.

## Notes
> - IEEE Xplore: https://ieeexplore.ieee.org/document/10649553/
> - DOI: https://doi.org/10.1109/ACCESS.2024.3450587
> - University of Roehampton repository: https://pure.roehampton.ac.uk/portal/en/publications/an-intelligent-lorawan-based-iot-device-for-monitoring-and-contro
> - **Published in IEEE Access** — same Q1 SCIE target journal as our review; format reference value
> - **Key ML methods for Section III:** Isolation Forest (anomaly detection) + Random Forest (prediction) on LoRaWAN sensor data
> - Status: [ ] Read  [ ] Full annotation complete
