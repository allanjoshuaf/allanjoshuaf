# Hey, I'm Al 👋

Network & Infrastructure Engineer - VPN, encrypted tunneling, routing and DNS.
I build, break and debug real infrastructure. Not tutorial environments.

## What I work on

- **Secure tunneling & traffic interference resistance** ; VLESS + XTLS-Vision + Reality,
  steal-oneself architecture, Caddy masquerade, sing-box client/server,
  AmneziaWG, automated deployment via NSSM
- **Routing & DNS integrity** ; TUN routing, FakeIP DNS, DNS-over-HTTPS, leak prevention, per-application routing,
  ruleset-based traffic engineering, policy routing, traffic segmentation
- **Embedded & home-lab networking** ; OpenWrt SNAPSHOT (qualcommax/ipq60xx, kernel 6.12),
  Asus Merlin, GL.iNet AX1800, dual-router topology, firewall and tunnel routing
- **Diagnostics & analysis** ; SNI filtering, TCP reset timing, TTL behavior, malformed TLS probes,
  WebRTC leaks, DNS resolver behavior, TLS handshake analysis, routing conflicts
- **Infrastructure tooling** ; Python network probes, JSON reporting, Caddy native APIs, 
  static diagnostic frontends, Windows services, Linux deployment, production log analysis

## Stack

```
Networking      TCP/IP · DNS · TLS · SNI · HTTP/2 · WebRTC · TUN · Routing
Security        Traffic analysis · Leak detection · TLS fingerprinting · Path validation
Tunneling       sing-box · VLESS · XTLS-Vision · Reality · WireGuard · AmneziaWG
Infrastructure  OpenWrt · Caddy · Linux · Windows · NSSM · Static hosting
Development     Python · JavaScript · HTML/CSS · JSON · REST-style APIs
Diagnostics     Wireshark-ready output · RTT analysis · DNS probes · Header inspection
```

## Repositories worth exploring

- [`dpi-probe`](https://github.com/allanjoshuaf/dpi-probe) -
  Python toolkit for detecting traffic interference on the local network path.
  
  **Signals tested:** SNI filtering, TCP reset timing, TTL anomalies, malformed TLS behavior, HTTP response injection.  
  **Output:** JSON reports with per-signal confidence scoring, median/p95 timing, variance, and consistency rates.  
  **Why it matters:** separates raw network observations from interpretation instead of pretending timing data is proof.

- [`singbox-configs`](https://github.com/allanjoshuaf/singbox-configs) - 
  Production-grade secure tunneling setup with VLESS, XTLS-Vision, Reality, and steal-oneself architecture.
  
  **Includes:** sing-box client/server configs, Caddy fallback, FakeIP DNS, TUN routing, DoH, IPv6 rejection, NSSM service deployment.  
  **Focus:** TLS consistency, DNS integrity, leak prevention, and routing reliability under restrictive network conditions.

- [`netDiag`](https://github.com/allanjoshuaf/netDiag) - 
  Deploy-ready browser-based diagnostics frontend for Reality / steal-oneself deployments.

  **Checks:** IP/ASN visibility, WebRTC leaks, DNS resolver behavior, TLS/HTTP properties, request headers, latency, privacy score.  
  **Stack:** HTML, CSS, Vanilla JS, Caddy native API endpoints. Zero npm, zero framework, zero analytics, no external calls on page load.

---

## Additional Background

Formal training in full-stack web and mobile development.  
Backend exposure: Node.js, Express, REST APIs, PostgreSQL, MongoDB, SQLite.

I use this mainly to build network tooling, diagnostic frontends, APIs, dashboards, and deployment utilities.

*Building reliable infrastructure under real-world constraints.*
