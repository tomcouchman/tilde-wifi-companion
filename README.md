<p align="center">
  <img src="assets/tilde-app-icon.png" alt="TILDE_ app icon, a green wave on a near-black square" width="112" />
</p>

<h1 align="center">TILDE_</h1>
<p align="center"><strong>Quietly watching your connection.</strong></p>
<p align="center">
  An Android Wi-Fi companion designed to turn connection-security signals into understandable guidance.
</p>
<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.tildecompanion.app"><strong>View on Google Play</strong></a>
  &nbsp;·&nbsp;
  <a href="https://tomcouchman.github.io/tilde.html">Portfolio case study</a>
  &nbsp;·&nbsp;
  <a href="https://moondocks.github.io/privacy.html">Privacy policy</a>
</p>

---

## The problem

People connect to Wi-Fi in cafés, hotels, airports and other unfamiliar places without always knowing what the connection means for their security. Technical network information is useful, but it can be difficult to interpret and easy to overstate.

**TILDE_ focuses on awareness rather than alarm:** explain what Android reports, surface meaningful changes, and help people make more informed decisions.

## What the app does

- **Connection awareness** — presents available Wi-Fi security information in plain language.
- **Guardian** — watches for meaningful network changes when enabled and explains what deserves attention.
- **Trusted networks** — lets users recognise familiar networks using Home, Work and custom profiles.
- **VPN awareness** — reports whether Android indicates an active VPN; it does not provide VPN connectivity.
- **Connection Health** — turns network checks and status information into readable context.
- **History** — lets users review useful connection changes and alerts.
- **Optional TILDE_+** — offers additional features without changing the app's security boundaries.

## Inside TILDE_

These are screenshots from the public Google Play listing (images are served by Google Play).

<table>
  <tr>
    <td align="center"><img src="https://play-lh.googleusercontent.com/fJJeyTyxQmGim2fFkr9JLdq6YKpOrtJ8nCMrD5XkA5vNYBhOkeSkCpn4jRwyYDR_VS-CxntU6L462lozGhbuqw=w526-h296" alt="Google Play screenshot: Connection awareness" width="270" /></td>
<td align="center"><img src="https://play-lh.googleusercontent.com/mWKHr4RNnr4PExPCHnNr9Yod_mr2VtP6WpZp0SH6RI71jMNypPOvzoX0f4Yj032zVGmhQuy4TKOQRBWiHVE1EQ=w526-h296" alt="Google Play screenshot: Guardian monitoring" width="270" /></td>
<td align="center"><img src="https://play-lh.googleusercontent.com/z7wJzmaaWFBOnw4npT_fTZKimhtuD4pi_M_3Tk1makg533LkypwNmax1V9hunBjMa2dBTuyJ-OVHOs9oBr0kAvE=w526-h296" alt="Google Play screenshot: Trusted networks" width="270" /></td>
  </tr>
  <tr>
    <td align="center"><img src="https://play-lh.googleusercontent.com/O3U-fM3_U2ko9rBKb7-XELGZ9cQfgL90KcD9hsgddu8U6bTlA8FvdJ1OylnNrYG50KE1uGEE_K5Rm2VKrdeNvg=w526-h296" alt="Google Play screenshot: History" width="270" /></td>
<td align="center"><img src="https://play-lh.googleusercontent.com/r63lkOMOthkdLYszGlJhQzOrwC8TEVAQosjg3oj2ZUxZ-zIqsBXi2aG_6qrnGrRIrggmNCHG13JDu7M_mGK2=w526-h296" alt="Google Play screenshot: Connection health" width="270" /></td>
<td align="center"><img src="https://play-lh.googleusercontent.com/XhQ-0v4ZUk0Sg4F10WhWt5lB1nBowdXWMmR9KRjzm67e_SDpLpWIhO58dv5RVpBjQ4uWsgSvCGQnUYoD450Qkg=w526-h296" alt="Google Play screenshot: Guardian details" width="270" /></td>
  </tr>
</table>

[Explore all screenshots on Google Play](https://play.google.com/store/apps/details?id=com.tildecompanion.app)

## My contribution and development approach

I **conceived TILDE_ and led its development direction**: deciding its purpose, prioritising security and usability goals, shaping features and interface behaviour, testing Android builds, identifying problems, iterating on revisions, and taking the product through Google Play release preparation and publication.

**Implementation disclosure:** I used AI coding tools to produce and revise much of the Flutter/Dart and Kotlin implementation. I am **not claiming to have personally written that code** or to have professional proficiency in those languages. My role centred on product direction, security reasoning, testing, validation and release decisions.

**Technology used by the app:** Android · Flutter/Dart · Kotlin. These are application technologies, **not a list of programming languages I claim to know**.

## Security decisions and boundaries

| Decision | Why it matters |
| --- | --- |
| Explain signals rather than promise safety | A Wi-Fi security indicator cannot establish that a network is safe. |
| Treat “trusted” as familiar, not verified secure | The user recognises the network; the app does not certify it. |
| Report Android VPN status | TILDE_ can provide context but is **not** a VPN. |
| Keep sensitive network history on-device by design | Reduces unnecessary transfer of network details to the developer. |
| Explain platform limitations | Android exposes some network information only when the relevant permissions and APIs allow it. |

TILDE_ is **not** antivirus software, a firewall, a VPN or a guarantee against threats on public Wi-Fi. It is a companion for interpreting available information and making informed choices.

## What this project demonstrates

This project complements my defensive-security work, particularly **[HomeSOC Log Analyzer](https://github.com/tomcouchman/homesoc-log-analyzer)**. HomeSOC focuses on rule-based analysis of authentication logs; TILDE_ focuses on communicating network/security context to everyday users. Together they represent different parts of my cybersecurity learning: interpretation, caution about claims, testing and clear communication.

## Project links

- [Google Play — TILDE_](https://play.google.com/store/apps/details?id=com.tildecompanion.app)
- [Portfolio — TILDE_ case study](https://tomcouchman.github.io/tilde.html)
- [Moon Docks — app information and privacy](https://moondocks.github.io/)
- [Personal cybersecurity portfolio](https://tomcouchman.github.io/)

---

<sub>This repository is a **public project showcase**, not the application source code. Product implementation, private configuration, signing materials and internal build files are not published here.</sub>
