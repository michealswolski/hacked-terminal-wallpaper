# 🔒 Security Awareness: Hacked Terminal & QR Code Risks

> **This project is a security awareness tool.** It demonstrates how convincing fake "hacked" interfaces look, and how QR codes can be weaponised to deliver them — without the target suspecting anything. Use it to educate, train, and protect.

## 🎯 Live Demo

- **Terminal Demo**: [View Live](https://michealswolski.github.io/hacked-terminal-wallpaper/)
- **QR Code Page**: [Get QR Code](https://michealswolski.github.io/hacked-terminal-wallpaper/qr.html)

---

## 🎓 Purpose: Security Awareness Training

This project was built specifically to support **security awareness education**. It serves as a hands-on demonstration of two related social engineering threats:

1. **Fake system compromise screens** — realistic-looking terminal output that can panic or manipulate a target into taking harmful actions (calling a fake support line, entering credentials, paying a ransom).
2. **QR code phishing ("quishing")** — using innocent-looking QR codes to silently deliver malicious URLs, bypassing traditional link-scanning habits entirely.

By seeing how convincing these attacks look in practice, users, teams, and organisations are far better prepared to recognise and resist them in the real world.

---

## ⚠️ The Real Danger of QR Codes

QR codes have become a trusted part of everyday life — restaurant menus, parking meters, event check-ins, package tracking. That trust is exactly what attackers exploit.

### What is QR Code Phishing ("Quishing")?

Quishing is a phishing attack delivered via QR code instead of a traditional hyperlink. Because most people cannot read a QR code with their eyes, they have no idea where it leads before they scan it. Attackers exploit this blindness by:

- **Replacing legitimate QR codes** on posters, parking machines, restaurant tables, or package labels with malicious versions — either physically reprinted or overlaid with a sticker.
- **Embedding QR codes in phishing emails** as image attachments, bypassing email security filters that scan text-based links but typically ignore images.
- **Sharing QR codes through social media or messaging apps**, where they appear harmless and generate no URL preview warnings.
- **Placing QR codes in public spaces** (airports, cafés, conference venues) under pretexts like "Free Wi-Fi — scan to connect" or "Scan here for your receipt."

### What Can Happen When You Scan a Malicious QR Code?

Once scanned, a malicious QR code can:

- **Redirect you to a phishing page** that mimics a trusted login screen (Microsoft 365, Gmail, a banking app) and silently harvests your credentials.
- **Trigger an automatic dow