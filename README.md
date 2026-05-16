# Hey, I'm Al 👋

Network & Infrastructure Engineer - VPN, encrypted tunneling, routing and DNS.
I build, break and debug real infrastructure. Not tutorial environments.

## What I work on

- **Encrypted tunneling & DPI evasion** ; VLESS + XTLS-Vision + Reality,
  steal-oneself architecture, Caddy masquerade, sing-box client/server,
  AmneziaWG, automated deployment via NSSM
- **Routing & DNS** ; FakeIP, DNS-over-HTTPS, per-application routing,
  ruleset-based traffic engineering, policy routing, traffic segmentation
- **Embedded networking** ; OpenWrt SNAPSHOT (qualcommax/ipq60xx, kernel 6.12),
  dual-router setup (Asus Merlin + GL.iNet AX1800)
- **Diagnostics & analysis** ; protocol-level troubleshooting, DNS behavior,
  TLS handshake analysis, routing conflicts, production log analysis
- **Development** ; Node.js, Express, REST APIs, PostgreSQL, MongoDB, SQLite

## Stack

```
Infrastructure  OpenWrt · Asus Merlin · Sing-box · Caddy · NSSM
Protocols       VLESS · XTLS-Vision · Reality · AmneziaWG · WireGuard · DoH
Networking      Policy routing · Traffic segmentation · DNS · TLS · DPI evasion
Backend         Node.js · Express · REST API
Databases       PostgreSQL · MySQL · MongoDB · SQLite
OS              OpenWrt · Windows
```

## Repositories worth exploring

- [`singbox-configs`](https://github.com/allanjoshuaf/singbox-configs) - 
  VLESS + XTLS-Vision + Reality + steal-oneself - server/client configs, 
  Caddy masquerade, FakeIP DNS. Deployed and tested under active DPI censorship..

- [`netDiag`](https://github.com/allanjoshuaf/netDiag) - 
  Browser-based diagnostic toolkit to verify proxy and VPN setups ;
  WebRTC leak, DNS probe, TLS check, privacy score. Built as a
  camouflage site template for VLESS Reality / steal_oneself deployments.
  Zero frameworks. Caddy backend.

---

## Open Source

**[SagerNet/sing-box](https://github.com/SagerNet/sing-box/pull/4121)** - PR open · 33.6k ★  
Implemented fix for a Zip Slip path traversal vulnerability in `downloadZIP()`.  
Path containment validation via `filepath.Clean` + regression test - ref. issue #4117.

*Building reliable infrastructure under real-world constraints.*
