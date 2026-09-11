# PortSwigger Web Security Academy — Lab Writeups

Screenshot-backed walkthroughs of PortSwigger Web Security Academy labs, completed as part of my web-application security training. Every entry documents the objective, how the vulnerability was identified, the payload used and how exploitation was verified — written in the style of a professional finding report rather than a solution key.

> **Scope note:** all labs were completed exclusively on PortSwigger's intentionally vulnerable training environment. No production, third-party or unauthorised system was ever tested.

## Contents

| Track | Labs documented | Folder |
|---|---|---|
| Cross-Site Scripting — reflected, stored, DOM | 30 | [`Cross-Site-Scripting/`](Cross-Site-Scripting/) |
| Cross-Site Request Forgery | 1 | [`CSRF/`](CSRF/) |

XSS coverage includes context-specific bypasses (HTML attribute, JavaScript string, template literal, event handlers, SVG, canonical link), AngularJS sandbox escapes, CSP bypasses including dangling markup, and impact-chaining labs such as cookie theft, password capture and CSRF-token bypass.

## How each writeup is structured

- **Objective** — what the lab asks the analyst to achieve
- **Discovery & Analysis** — the vulnerable parameter and the root cause
- **Exploitation** — the payload and delivery method, with Burp Suite where interception was required
- **Verification** — the observed proof that the payload executed
- **Evidence** — screenshots of each successful exploit

## Tools

Burp Suite (Proxy, Repeater), browser developer tools, PortSwigger Web Security Academy lab environment.

## Status

In progress. XSS and CSRF tracks are documented; further tracks (SQL injection, access control, authentication, SSRF) will be added as they are completed.

## Related work

- [SBT-DF203 Lab 3 — SYN Flood Attack Investigation Using tshark](https://github.com/IfyTechy/SBT-DF203_Lab3_SYN-Flood-Attack-Investigation-Using-tshark)
- [SBT-DF203 Lab 2 — HTTP Analysis and Embedded Image Extraction with Wireshark](https://github.com/IfyTechy/SBT-DF203_Lab2_HTTP-Analysis-Using-Wireshark-Embedded-image-Traffic)
- [CIP-B102 Lab 3 — Data Carving with XXD, Binwalk and Scalpel](https://github.com/IfyTechy/CIP-B102_Lab3_Data-Carving-with-XXD-Binwalk-and-Scalpel)

## Author

Nebeuwa Ifeanyichukwu Raphael — digital forensics and cyber-defence trainee, International Cybersecurity and Digital Forensics Academy (ICDFA).
