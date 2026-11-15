# Awesome-Event-Management-Ticketing

## Top Event Management & Ticketing Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Ticket Sales, Attendee Check-in & Self-Hosted Event Platforms*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Event Management & Ticketing**. These tools help organizers sell tickets, manage attendees, and run events—covering everything from polished SaaS suites with marketing automation to open-source platforms you can self-host with zero platform fees.

**Examples** include Eventbrite, Cvent, Bizzabo, Whova, Pretix, Hi.Events, and Attendize (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted event ticketing, open-source attendee management, and community-driven event platforms—ideal for organizers seeking data sovereignty and avoiding per-ticket platform fees. The open-source landscape is genuinely functional: **Pretix** is the battle-tested standard with ISO 27001 certification and unlimited ticket volume on the free Community Edition [citation:3][citation:14], **Hi.Events** provides a modern multi-tenant platform with white-label pages and a commercial license option [citation:4][citation:10], and **Attendize** offers a Laravel-based solution with a web-based QR scanner for door management [citation:5].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Eventbrite](https://www.eventbrite.com/)** | The consumer-standard event marketplace with discovery network effects. Free events are free to publish; paid tickets incur per-ticket fees. | Free for free events; paid events charged per-ticket (varies by region) | **Free**: unlimited free events; paid tickets incur platform fees |
| **[Cvent](https://www.cvent.com/)** | Enterprise event management and hospitality cloud. Covers registration, venue sourcing, mobile apps, and attendee analytics. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Bizzabo](https://www.bizzabo.com/)** | Event experience OS combining registration, networking, and content management. Positioned for professional event teams. | Quote-only | No free tier; demo via sales |
| **[Whova](https://whova.com/)** | Event management app with agenda, networking, and attendee engagement features. Popular for conferences and trade shows. | Quote-only | No free tier; demo via sales |
| **[Hopin](https://hopin.com/)** | Virtual and hybrid event platform with sessions, networking, and exhibition halls. | Quote-only | No free tier; demo via sales |
| **[Splash](https://splashthat.com/)** | Event marketing platform focused on branded event pages and RSVP management. Positioned for corporate events and brand experiences. | Quote-only | Free trial available |
| **[vFairs](https://www.vfairs.com/)** | Virtual event platform with 3D exhibition halls and networking features. | Quote-only | No free tier; demo via sales |
| **[Airmeet](https://www.airmeet.com/)** | Virtual and hybrid event platform with networking lounges and interactive sessions. | Free tier available; paid plans via sales | **Free**: limited features for small events |
| **[Accelevents](https://www.accelevents.com/)** | Event management platform with registration, ticketing, and virtual event capabilities. | Quote-only | Free trial available |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Pretix](https://github.com/pretix/pretix)** | [![Stars](https://img.shields.io/github/stars/pretix/pretix?style=social&color=white)](https://github.com/pretix/pretix/stargazers) | **The most mature open-source ticketing platform with unlimited ticket volume on the free Community Edition.** **AGPLv3 with additional terms**, developed by German company rami.io. **ISO 27001 certified** for privacy and security [citation:14]. **Community Edition: free forever with unlimited orders and administrative users**—no platform fees, no ticket volume caps [citation:3]. Features: ticket sales with customizable event pages, quotas, payment processing, invoicing, check-in management, REST API, and plugin support [citation:9]. **Enterprise tiers available** for proprietary plugins and larger scale [citation:3]. **Best for organizers wanting a battle-tested, self-hosted platform** with proven reliability and no per-ticket fees. |
| **[Hi.Events](https://github.com/HiEventsDev/Hi.Events)** | [![Stars](https://img.shields.io/github/stars/HiEventsDev/Hi.Events?style=social&color=white)](https://github.com/HiEventsDev/Hi.Events/stargazers) | **The most modern open-source event management platform with multi-tenant support.** **AGPL-3.0 with additional terms** requiring a "Powered by Hi.Events" notice on the free self-hosted version; **commercial licenses from €249/year** remove branding [citation:10]. **PHP/Laravel + React + PostgreSQL** stack. **Docker all-in-one deployment** or one-click templates for DigitalOcean, Render, Railway [citation:10]. Features: paid/free/donation/tiered pricing, add-ons, hidden tickets, waitlists, **direct Stripe integration** (funds go to your account), tax handling, invoices, **phone-camera check-in**, attendee messaging, reports, **REST API and webhooks**, and **multi-tenant isolation** for agencies managing multiple clients [citation:4][citation:10]. **Best for organizers wanting a modern, feature-rich platform** with white-label options and active development. |
| **[Attendize](https://github.com/Attendize/Attendize)** | [![Stars](https://img.shields.io/github/stars/Attendize/Attendize?style=social&color=white)](https://github.com/Attendize/Attendize/stargazers) | **A mature Laravel-based ticketing platform with a web-based QR scanner for door management.** **Attribution Assurance License**; white-label licenses available [citation:5]. **~4,173 stars and 1,219 forks** on GitHub [citation:11]. Features: mobile-friendly event pages, unlimited organizers/events, multiple currencies, customizable tickets with QR codes, **affiliate tracking**, widget support for embedding into existing websites, **Stripe/PayPal/Coinbase payment gateways**, offline payments, partial/full refunds, attendee messaging, data export to XLS/CSV, and a **browser-based QR code scanner** for check-in [citation:5]. **Requires PHP 7.1.3+ and MySQL 5.7+** on LAMP/LEMP [citation:5]. **Best for organizers already on Laravel/PHP** wanting a proven ticketing solution with white-label options. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[FOSSASIA Eventyay](https://github.com/fossasia/eventyay)** | [![Stars](https://img.shields.io/github/stars/fossasia/eventyay?style=social&color=white)](https://github.com/fossasia/eventyay/stargazers) | **Open-source event management, ticketing, check-ins, talks/schedules, video, interpretations, and badges.** **2,000+ stars** [citation:12]. Positioned for conferences and community events with a comprehensive feature set beyond basic ticketing. **Best for conference organizers** wanting an integrated platform covering talks, schedules, and video alongside tickets. |
| **[LibreEvent](https://github.com/janishutz/libreevent)** | [![Stars](https://img.shields.io/github/stars/janishutz/libreevent?style=social&color=white)](https://github.com/janishutz/libreevent/stargazers) | **Fully featured, free and open-source self-hosted event management and ticket sales solution.** **Requires only Node.js 16+ and npm**—any CPU from the last 10 years, any OS that runs Node.js. Optional MySQL support. **Volunteer-developed** with planned features . **Best for small organizers** wanting a lightweight self-hosted option with minimal infrastructure requirements. |

**Frameworks for building custom systems**: Choose **Pretix** for a battle-tested platform with unlimited free tickets and ISO 27001 certification [citation:3][citation:14], **Hi.Events** for a modern multi-tenant platform with white-label pages and Docker deployment [citation:4][citation:10], or **Attendize** for a Laravel-based solution with a built-in QR scanner and affiliate tracking [citation:5] —all without per-ticket platform fees that eat into event revenue.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Event platforms handle attendee PII, payment information, and potentially GDPR-sensitive data; enforce encryption at rest and in transit, PCI DSS compliance for payments, and data retention policies.
- **Open-source event ticketing has different trade-offs across leading projects.** **Pretix's Community Edition is genuinely unlimited**—free forever with no ticket volume caps [citation:3], and the platform is **ISO 27001 certified** [citation:14]. **Hi.Events requires keeping a "Powered by" notice** on the free self-hosted version—commercial licenses start at **€249/year** to remove branding [citation:10]. **Attendize uses an Attribution Assurance License** with white-label options available [citation:5]. **Payment processing is separate** from platform fees—Hi.Events and Attendize both integrate Stripe directly, meaning you pay only Stripe's standard rates (2.9% + 30¢) and the platform takes **zero cut** [citation:4]. **Validate whether you need unlimited free ticketing (Pretix), modern white-label features (Hi.Events), or Laravel-based customization (Attendize)** before committing.

---

**Made for event organizers, conference teams, and organizations building ticketing infrastructure.**  
Let's make event management and ticketing more open, fee-free, and attendee-friendly.
