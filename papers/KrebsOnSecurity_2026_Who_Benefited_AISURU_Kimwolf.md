# Who Benefited from the Aisuru and Kimwolf Botnets?
**Source:** Krebs on Security  
**URL:** https://krebsonsecurity.com/2026/01/who-benefited-from-the-aisuru-and-kimwolf-botnets/  
**Date:** January 2026

## Summary
Kimwolf infects >2M devices (unofficial Android TV streaming boxes); forces them into DDoS and residential proxy abuse. XLab: same actors/infrastructure deploy both Kimwolf and Aisuru; confirmed Dec 8 when both strains distributed from 93.95.112[.]59. That IP range assigned to Resi Rack LLC (Lehi, Utah). Resi Rack: "Premium Game Server Hosting" / "Premium Residential Proxy Hosting and Proxy Software Solutions" (BlackHatWorld). resi[.]to Discord: "Dort" (Canada) and "Snow" as Aisuru/Kimwolf botmasters; Forky (Brazil) acknowledged marketing Aisuru at inception but denied later DDoS. Proxy beneficiaries: ByteConnect/Plainproxies (Friedrich Kraft, 3XK Tech GmbH Germany; Cloudflare: 3XK largest source of app-layer DDoS 2025); Maskify (6M+ residential IPs, very low $/GB). Kimwolf uses ENS (Ethereum) for C2 resilience; ENS records used to dox researchers. Recommendation: if TV box matches known infected models, remove from network.

## Key entities
- **Resi Rack LLC** – hosting; IPs flagged by XLab
- **Dort / Snow** – botmasters (Canada)
- **ByteConnect / Plainproxies** – SDK on compromised devices; credential stuffing observed
- **3XK Tech GmbH** – Kraft; largest app-layer DDoS source (Cloudflare Q2 2025)
- **Maskify** – proxy reseller, 6M+ IPs

---
*Full article at URL above. No evidence in open research links these botnets to Spotify or music-based harassment.*
