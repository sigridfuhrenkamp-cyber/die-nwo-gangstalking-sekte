# Lumen Disrupts AISURU and Kimwolf Botnet by Blocking Over 550 C2 Servers
**Source:** Security Affairs  
**URL:** https://securityaffairs.com/186918/cyber-crime/lumen-disrupts-aisuru-and-kimwolf-botnet-by-blocking-over-550-c2-servers.html  
**Date:** January 15, 2026  
**Author:** Pierluigi Paganini

## Summary
Lumen’s Black Lotus Labs disrupted over 550 command-and-control servers linked to the AISURU and Kimwolf botnet, used for DDoS attacks and proxy abuse. Aisuru acts as DDoS-for-hire; avoids government/military targets but broadband providers faced attacks exceeding 1.5 Tb/sec from infected customer devices. Capabilities: UDP/TCP/GRE floods, credential stuffing, AI-driven scraping, spamming, phishing. Kimwolf: Android botnet linked to Aisuru, >1.8M devices, >1.7B DDoS commands (Nov 19–22); targets TV boxes; DNS over TLS, elliptic curve auth, EtherHiding. Lumen saw bot traffic surge 50K→200K daily (Sept 2025); null-routed 550+ C2 nodes over four months; Canadian IPs and proxy infrastructure identified; shared with law enforcement.

## Technical details (AISURU/Kimwolf)
- TurboMirai family; multi-use: DDoS, credential stuffing, AI scraping, spam, phishing
- Kimwolf: NDK-compiled, DDoS + proxy + reverse shell + file management; Stack XOR encryption; naming "niggabox + v[number]"
- ~2.7M IPs observed on one C2 over three days; 550+ servers null-routed by Lumen

---
*Saved for research archive. No public evidence links this IoT/DDoS botnet to music streaming or psychological warfare; see ChatGPT follow-up in research notes.*
