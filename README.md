# Internetization - ISOC-Georgia
Operational and Sustainable Development Guidelines for the Broadband Network of the Tusheti Region

***

# Tusheti Community Broadband Rollout

## 📌 Project Overview
The Tusheti Connectivity Project is an open-model, community-driven wireless internet network deployed in the high-altitude, remote Tusheti region of the Greater Caucasus Mountains, Georgia. Due to harsh geographic conditions and a low population density, traditional optical networks were unfeasible. This project successfully bridged the digital divide by deploying a ruggedized, off-grid fixed wireless network to support local residents, tourism, healthcare, and educational access.

## 🏗️ Network Architecture & Topology
The network relies on a fixed wireless backbone transferring high-capacity bandwidth from urban centers to the isolated mountains.
* **Main Radio Backbone:** The main link originates in Ruispiri (Telavi region), passes through the Abano Pass, and terminates at Mount Diklo.
* **Local Distribution:** From Mount Diklo, the signal is routed to internal valleys and villages including Dochu, Koklata, Dano, and Omalo.
* **Topological Adaptation:** Initial designs were revised to move masts to the highest mountain peaks (e.g., Mt. Javakha and Mt. Makratela). This was necessary to maintain a clear line-of-sight (Fresnel zone) over evergreen forests and heavy snow accumulation. 
* **Hardware Solutions:** The network utilizes high-performance Ubiquiti Networks and MikroTik hardware. Legacy 90-degree sector antennas were replaced with Ubiquiti LBE-5AC-16-120 models to achieve up to 240-degree wide-angle coverage, reaching hidden settlements. Local repeaters were installed to serve deep gorges like Dartlo and Keselo without destroying the aesthetic landscape with cables.

## ⚡ Off-Grid Power & Environmental Resilience
Deploying infrastructure at high altitudes required extreme weatherization and customized power engineering:
* **Solar Energy Engineering:** The entire infrastructure is powered by PoE switches running on off-grid solar stations. Due to the low azimuth of the winter sun at 41-42° latitude, standard solar setups failed to charge deep-cycle batteries efficiently. The solution involved doubling the solar capacity to 200W (four 12V panels) per node.
* **Active Lightning Protection:** Local mountain rocks contain high levels of sulfides and ferrites, creating highly conductive environments that attract destructive lightning. The network is shielded using advanced active lightning protection systems manufactured by Andeli.
* **Snow-Slip Resistance:** Masts and solar mounts were heavily reinforced with specialized steel anchors and stretch marks to withstand the massive pressure of 1.5-meter deep melting snow sliding down the mountain slopes.

## 💼 Business Model & Sustainability
The project was designed around a community-centric, non-profit ISP model to ensure long-term viability:
* **Community Ownership:** The physical network and daily operations were transferred entirely to the local NGO, the **Tusheti Development Fund (TDF)**.
* **Non-Profit Reinvestment:** TDF operates the network with a strict profit cap of 10% over operational and capital expenses.
* **Sustainable Growth:** All generated income from residential and hospitality internet tariffs is legally bound to be reinvested into network maintenance, battery replacements, and expansion (such as the planned rollout to the neighboring Khevsureti region).

## 🤝 Partners & Contributors
This project was made possible through a multi-stakeholder Memorandum of Understanding:
* **Internet Society (ISOC):** Financial backing and grant support via the European Regional Office.
* **ISOC Georgia Chapter & Internet Development Initiative:** Marketing, tariff modeling, and technical training.
* **Small and Medium Telecom Operators Association of Georgia & LTD "Free Net":** Free backbone transit bandwidth (100 Mbps) and collocation space at the Ruispiri tower.
* **Tusheti Development Fund (TDF):** Local operation, maintenance, and beneficiary.
* **Konstantin Stalinsky:** Technical engineering and network design.

---
This repository contains the technical documentation, budget datasets, network topology maps, and operational guides developed throughout the Tusheti connectivity project.
