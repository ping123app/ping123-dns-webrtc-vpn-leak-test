# DNS Leak Test, WebRTC Leak Test, VPN Leak Test Checklist

[![DNS Leak Test](https://img.shields.io/badge/DNS%20Leak-Test-2563eb?style=for-the-badge)](https://ping123.app/en/dns-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=ping123-dns-webrtc-vpn-leak-test&utm_content=hero_badge)
[![WebRTC Leak Test](https://img.shields.io/badge/WebRTC%20Leak-Test-7c3aed?style=for-the-badge)](https://ping123.app/en/webrtc-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=ping123-dns-webrtc-vpn-leak-test&utm_content=hero_badge)
[![VPN Detection](https://img.shields.io/badge/VPN-Detection-16a34a?style=for-the-badge)](https://ping123.app/vpn-detection/?utm_source=github&utm_medium=repo&utm_campaign=ping123-dns-webrtc-vpn-leak-test&utm_content=hero_badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-111827?style=for-the-badge)](LICENSE)

Ping123 provides free browser-based workflows for **DNS leak test**, **WebRTC leak test**, **VPN detection**, and proxy/VPN environment checks.

Start with the DNS leak test:

https://ping123.app/en/dns-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=ping123-dns-webrtc-vpn-leak-test&utm_content=hero_cta

## Why Leak Tests Matter

Changing your visible IP address is only one part of a privacy or network check. DNS, WebRTC, browser language, time zone, and reputation signals may still reveal an unexpected route or mismatch.

Ping123 helps review:

- DNS resolver behavior
- WebRTC browser exposure
- Visible public IP address
- Proxy and VPN detection context
- IP risk and reputation signals
- Browser language and time zone coherence

## Leak Test Checklist

```text
DNS / WebRTC / VPN leak test

[ ] Public IP matches the expected VPN or proxy route
[ ] DNS resolver behavior matches the expected route
[ ] WebRTC does not expose unexpected network information
[ ] Proxy/VPN labels are understood
[ ] IP risk context is acceptable for the workflow
[ ] Browser language and time zone match the visible region
[ ] Results were re-tested after browser, VPN, proxy, extension, or DNS changes
```

## Related Ping123 Tools

| Tool | Use it for | Link |
|---|---|---|
| DNS Leak Test | Check DNS resolver behavior | https://ping123.app/en/dns-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=ping123-dns-webrtc-vpn-leak-test&utm_content=tool_table |
| WebRTC Leak Test | Check browser-side network exposure | https://ping123.app/en/webrtc-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=ping123-dns-webrtc-vpn-leak-test&utm_content=tool_table |
| VPN Detection | Review VPN detection context | https://ping123.app/vpn-detection/?utm_source=github&utm_medium=repo&utm_campaign=ping123-dns-webrtc-vpn-leak-test&utm_content=tool_table |
| What Is My IP | Confirm the visible public IP address | https://ping123.app/what-is-my-ip/?utm_source=github&utm_medium=repo&utm_campaign=ping123-dns-webrtc-vpn-leak-test&utm_content=tool_table |

## FAQ

### What is a DNS leak?

A DNS leak happens when DNS requests use an unexpected resolver path outside the intended proxy or VPN route.

### What is a WebRTC leak?

A WebRTC leak happens when browser WebRTC behavior exposes unexpected network information that may differ from the visible public IP.

### Should I retest after changing VPN servers?

Yes. Re-test DNS, WebRTC, public IP, and browser context after every VPN, proxy, DNS, browser, extension, or OS change.

## License

MIT
