<div align="center">

<img src="assets/pinaxa-hero.png" width="100%" alt="PINAXA personal safety app showcasing genuine Android screens" />

# PINAXA — Personal Safety for Android

**A focused, offline-oriented emergency toolkit designed for deliberate action under pressure.**

![Platform](https://img.shields.io/badge/Platform-Android-17191D?style=for-the-badge&logo=android&logoColor=white)
![Product](https://img.shields.io/badge/Product-Personal_Safety-C83039?style=for-the-badge)
![Showcase](https://img.shields.io/badge/Repository-Product_Showcase-8E4D59?style=for-the-badge)

**[Explore the screens](#the-product-in-action)** · **[Technical approach](#design-and-technical-approach)** · **[Developer](#creator)**

</div>

---

## An emergency tool with one clear purpose

In stressful situations, complex interfaces are difficult to use. **PINAXA** is a personal safety Android application organized around a prominent **PANIC** control, selectable emergency behaviors, a record of events and a protected evidence area.

The screenshots below come from the actual PINAXA application provided by its developer. This repository is a **product showcase**, not a distribution channel for an APK or source code.

## The product in action

<img src="assets/pinaxa-screens-gallery.png" width="100%" alt="Real PINAXA screens showing panic control, event timeline, contacts, evidence access, settings and a safety timer" />

| Home & panic control | Emergency timeline | Protected evidence |
|:--:|:--:|:--:|
| <img src="assets/screenshots/home.webp" width="220" alt="PINAXA panic control"/> | <img src="assets/screenshots/event-timeline.webp" width="220" alt="PINAXA emergency timeline"/> | <img src="assets/screenshots/evidence-lock.webp" width="220" alt="PINAXA evidence authentication screen"/> |

| Emergency contacts | Settings | Safety timer |
|:--:|:--:|:--:|
| <img src="assets/screenshots/emergency-contacts.webp" width="220" alt="PINAXA emergency contacts"/> | <img src="assets/screenshots/settings.webp" width="220" alt="PINAXA emergency behavior settings"/> | <img src="assets/screenshots/safety-timer.webp" width="220" alt="PINAXA safety timer selection"/> |

## Core experiences

### 01 · Panic activation

The home screen emphasizes a large emergency control with prominent status feedback. A separate **duress protection** state shows whether shake-trigger configuration is active. The app describes a deliberate, three-shake gesture for silent emergency dispatch.

### 02 · Configurable emergency behavior

The settings screen exposes options for **automatic SMS**, **automatic calls**, **audio recording during emergencies** and **shake-to-trigger stealth mode**. These are visible settings; actual delivery and recording depend on permissions, device behavior and local service availability. The existence of an option does not guarantee a message or call was delivered.

### 03 · Emergency contacts

PINAXA includes a dedicated view for saved emergency contacts, with an action to add entries. The numbers shown in screenshots are test/sample data and are not emergency-service guidance.

### 04 · Emergency event timeline

The event history displays timestamped entries including **GUARDIAN**, **PANIC** and **DURESS_TRIGGER** events, making relevant activation history easier to review after a test or incident.

### 05 · Protected evidence access

A separate **Evidence Locked** screen requires a password before opening stored material. The application screens describe audio recording and offline voice transcription, but the screenshots do not independently validate encryption, evidence integrity or transcription accuracy.

### 06 · Safety timer

A configurable safety timer offers 15-, 30- and 60-minute options plus a short test option. The timer is part of the safety workflow; the exact result when it expires should be independently tested before relying on it.

## Design and technical approach

- **Android-native interface:** high-contrast dark surfaces, prominent red emergency actions and a bottom navigation bar.
- **Intentional activation:** explicit controls and a configurable shake gesture; the in-app disclaimer says PINAXA **does not automatically detect threats via audio**.
- **Local-first focus:** the app describes its core functionality as offline-capable and user data as device-local.
- **Device features:** configured SMS, calling, microphone, motion sensors and on-device data may each require separate permissions or supported hardware.
- **Privacy-aware experience:** a password gate for evidence and locally presented privacy disclosures are included in the interface.

**Implementation transparency:** This is a visual/product overview based on app screenshots, not a completed source-code audit, penetration test, medical/safety certification or verified emergency dispatch service. Security and offline claims require testing against a distributable build.

## Product gallery

The repository includes developer-supplied screenshots in [`assets/screenshots/`](assets/screenshots/), a promotional cover, a full screen gallery, and the original PINAXA icon image. No demo interfaces are substituted for the actual screens.

## Responsible use and limitations

**PINAXA should not be the sole way to request emergency help.** Device battery level, permissions, telephony coverage, SMS availability, operating-system restrictions and app state can affect emergency workflows. Test all configured contacts and behaviors safely before real-world reliance. In an emergency, contact your local emergency services directly whenever possible.

Any audio recording, location access, or messaging must comply with applicable laws and the consent expectations of people involved.

## Product status

- **Shown here:** PINAXA v2.0 interface, as labeled in the supplied in-app About panel.
- **Availability:** private project showcase; no public download or store listing is asserted here.
- **Repository scope:** screenshots, marketing graphics and documentation only. **No application source code, passwords or user data exports.**

## Creator

**Geda Taye** — self-taught Android & web developer from Ethiopia, building native apps and digital products using a smartphone-first workflow.

Other work:

- **[NONOX](https://github.com/geda21/nonox-android)** — focus and discipline Android app, [on Google Play](https://play.google.com/store/apps/details?id=com.nonox.app)
- **[JLab](https://github.com/geda21/Jlab)** — local-first productivity workspace
- **[JABAA Shop](https://jabashop.store)** — digital learning marketplace

[**View GitHub profile**](https://github.com/geda21) · [**Connect on LinkedIn**](https://www.linkedin.com/in/geda-taye-a60b403ba)

---

**All rights reserved.** This showcase does not grant a license to redistribute PINAXA, its designs or its assets. It is not a promise of certified safety or guaranteed emergency-response performance.
