# Article Annotation #19

---

## Reference
- **[19]** P. K. Kashyap, S. Kumar, A. Jaiswal, M. Prasad, and A. H. Gandomi. "Towards Precision Agriculture: IoT-Enabled Intelligent Irrigation Systems Using Deep Learning Neural Network." *IEEE Sensors Journal*, vol. 21, no. 16, pp. 17479–17491, Aug. 2021. DOI: 10.1109/JSEN.2021.3069266

## Metadata
- **Year:** 2021
- **Database:** IEEE Xplore
- **Type:** Journal — System Design + Experimental Study
- **Q-rank:** Q1 (IEEE Sensors Journal — SCIE indexed)
- **Citations:** 400+ — highly cited DL+IoT irrigation paper
- **Affiliation:** National Institute of Technology (NIT), India; University of Technology Sydney (UTS), Australia (A. H. Gandomi)

## Keywords
> IoT, deep learning, LSTM, RNN, irrigation, soil moisture prediction, precision agriculture, DLiSA, water savings, neural network, meteorological data

## Research Question / Objective
> Can a deep LSTM RNN-based IoT system (DLiSA) accurately predict next-day volumetric soil water content and enable intelligent, feedback-controlled irrigation scheduling for precision agriculture?

## Methodology
- **Study type:** System design + experimental evaluation
- **Model:** Two-layer deep LSTM RNN (one-step training procedure)
- **Training data:** 1.5 years of meteorological and hydrological data
- **Prediction target:** Next-day volumetric soil water content
- **LPWAN technology covered:** Not specifically addressed — IoT connectivity treated generally
- **AI/ML technique:** Deep learning — LSTM RNN (time-series prediction)
- **Agriculture domain:** Precision irrigation / water management

## Key Findings
1. Deep LSTM RNN accurately predicts next-day soil moisture from meteorological + hydrological time-series data.
2. DLiSA system achieves **23–43% water savings** vs. conventional irrigation — significant quantitative result.
3. Feedback-integrated system adapts to weather conditions of any region/period — generalizable architecture.
4. Two-layer LSTM outperforms single-layer and traditional ML models for soil moisture time-series prediction.
5. IoT sensor feedback loop enables closed-loop irrigation scheduling without human intervention.

## Limitations Acknowledged by Authors
> - IoT wireless connectivity (LPWAN) not analyzed — general IoT assumed
> - Tested in specific geographic/climate conditions — regional generalizability to verify
> - No real-time edge deployment — cloud-based processing

## Relevance to Our Review
- **Section(s) covered:** III (AI/ML — LSTM for time-series IoT data), V (Applications — irrigation), VIII (AI Use Cases — intelligent irrigation scheduling)
- **Gap addressed:** Direct — LSTM + IoT for precision irrigation; **missing LPWAN layer** (which LPWAN protocol delivers the sensor data?)
- **Citation priority:** High — IEEE Sensors Journal Q1; key reference for LSTM in agricultural IoT; cite in Sections III and V

## Why It Is NOT a Competitor
> System design paper focused on LSTM model for soil moisture prediction — no LPWAN technology comparison, no systematic review, no LoRaWAN/NB-IoT/Sigfox analysis. Our review provides the missing wireless LPWAN transmission layer that would deliver sensor data to this type of DL system.

## Notes
> - IEEE Xplore: https://ieeexplore.ieee.org/document/9388691/
> - ResearchGate: https://www.researchgate.net/publication/350475817
> - **Key stat for Section V:** 23–43% water savings with LSTM-based intelligent irrigation
> - Status: [ ] Read  [ ] Full annotation complete
