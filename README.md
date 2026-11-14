<div align="center">

<img src="assets/banner.svg" alt="subnetcalc" width="100%">

<p>
  <a href="https://cyberloop-dev.github.io/subnetcalc/"><img alt="Live demo" src="https://img.shields.io/badge/live%20demo-open-0891b2?style=for-the-badge"></a>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge">
  <img alt="Dependencies" src="https://img.shields.io/badge/dependencies-zero-818cf8?style=for-the-badge">
</p>

**A subnet calculator that shows its work: IPv4, IPv6, binary view and one-click splitting.**

</div>

---

## ✨ Features

- 🧮 Network, netmask, wildcard, broadcast, host range and usable host count
- 🌐 Full **IPv6** support (compression, expanded form, first and last address)
- 🔢 **Binary view** with network bits and host bits color-coded, so the math is visible
- ✂️ **Split** any network into smaller subnets and copy each one with a click
- 🏷️ Address type: private, loopback, link-local, CGNAT, multicast, documentation, public
- ↔️ Accepts `192.168.1.10/24` **or** `10.0.0.0/255.255.255.0`
- 🔒 100% in your browser, one HTML file, BigInt-based so large IPv6 ranges are exact

## 🚀 Quick start

Open the [live demo](https://cyberloop-dev.github.io/subnetcalc/), or:

```bash
git clone https://github.com/CyberLoop-dev/subnetcalc.git
cd subnetcalc
open index.html
```

## 🧪 Try these

| Input | What you learn |
|---|---|
| `192.168.1.10/24` | The classic: 254 usable hosts |
| `10.0.0.0/255.255.254.0` | A dotted mask works too: that is a /23 |
| `203.0.113.4/31` | Point-to-point links (RFC 3021) |
| `2001:db8::/32` | IPv6 with an exact count of addresses |

## ⚖️ Notes

- IPv6 has no broadcast address, so the tool shows first and last address instead.
- When splitting, it lists the first 256 subnets and tells you the total.

## 📄 License

MIT
