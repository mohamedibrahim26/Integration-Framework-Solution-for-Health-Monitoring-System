# Integration Framework Solution for Health Monitoring System

An IoT-based real-time healthcare monitoring system built around an interoperability framework. Patient vitals (pulse rate, blood oxygen saturation, body temperature) are collected from market sensors, streamed in real time using the **XMPP** protocol, and made available to doctors and family members through a connected mobile and web layer. The system was tested with three real human volunteers.

**🏆 Best Paper Award** at the RAWCET 2022 conference. Certificate included in this repo: [`Best Paper Award.pdf`](Best Paper Award.pdf).

## Publication

> Usharani, S., Rajakumaran, G., Nandam, A. D., & **Ibrahim, M.** (2023). *Integration Framework Solution for Healthcare Monitoring.* Journal of Physics: Conference Series, 2471(1), 012018. IOP Publishing.
>
> DOI: [10.1088/1742-6596/2471/1/012018](https://doi.org/10.1088/1742-6596/2471/1/012018)

[Read the full paper (PDF)](Published%20Paper.pdf)

## Authors and affiliations

- **Shola Usharani** — School of Computer Science and Engineering, Vellore Institute of Technology, Chennai
- **Gayathri Rajakumaran** — School of Computer Science and Engineering, Vellore Institute of Technology, Chennai
- **Anjana Devi Nandam** — Department of Computer Science and Engineering, Koneru Lakshmaiah Education Foundation, Vijayawada
- **Mohamed Ibrahim** — School of Computer Science and Engineering, Vellore Institute of Technology, Chennai

## Why this matters

Healthcare access in rural India is uneven, and many patients cannot travel for routine vital checks. This project builds a low-cost, interoperable monitoring layer that lets care providers track patients remotely and get alerted in emergencies. The interoperability piece matters because it removes manual data transcription between systems, which is a known source of medical record errors.

## Approach

- **Sensors:** market-available sensors for pulse rate, oxygen saturation, and body temperature.
- **Communication:** the XMPP protocol for instant, interoperable IoT messaging using XML data.
- **Application layer:** mobile app for patients and family members; planned web dashboard for time-indexed history.
- **Alerting:** emergency notifications routed to the patient's doctor or caregiver based on threshold rules.
- **Evaluation:** tested on three real human volunteers under normal and emergency conditions.

## Files in this repo

- [`Published Paper.pdf`](Published%20Paper.pdf) — the full published paper (open access)
- [`Best_Paper_Award.pdf`](Best_Paper_Award.pdf) — Best Paper Award certificate from RAWCET 2022
- [`Health Monitoring Code.txt`](Health%20Monitoring%20Code.txt) — source code

## License

The paper is published under the Creative Commons Attribution 3.0 licence by IOP Publishing. Any redistribution of the paper must keep attribution to the authors, the title of the work, the journal citation, and the DOI.
