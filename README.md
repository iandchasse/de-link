<!--
  Before committing: make sure the two images are in this repo's images/ folder as
  images/homepage.png and images/pip-pcb-render.png  (site URL is already set to https://de-link.me).
-->

<p align="center">
  <a href="https://de-link.me">
    <img src="images/homepage.png" alt="de-link — open source microreader and development kit" width="820">
  </a>
</p>

<h1 align="center">de-link</h1>

<p align="center">
  <b>open source microreader &amp; development kit</b><br>
  ESP32-S3 · any 24-pin e-paper panel · fully repairable · yours to modify
</p>

<p align="center">
  <a href="https://de-link.me"><img src="https://img.shields.io/badge/website-de--link-1053a4?style=for-the-badge" alt="Website"></a>
  <a href="https://discord.gg/zCnKFt4Y4P"><img src="https://img.shields.io/badge/discord-join-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://www.patreon.com/iandchasse"><img src="https://img.shields.io/badge/patreon-support-F96854?style=for-the-badge&logo=patreon&logoColor=white" alt="Patreon"></a>
  <a href="https://ko-fi.com/iandchasse"><img src="https://img.shields.io/badge/ko--fi-support-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white" alt="Ko-fi"></a>
</p>

---

> ## ✅ de-link is alive and in active development.
>
> This repository is the **original project hub** — it's preserved here (history, images,
> schematics, and notes all intact), but the **full, up-to-date information now lives on the website.**
>
> ### 👉 **[Visit the de-link website to learn more →](https://de-link.me)**
>
> You'll find the current specs, an interactive bill of materials, a rotatable 3D model,
> the `pre` and `pip` editions, and how to build your own.

---

## 📸 The project today

<p align="center">
  <img src="images/homepage.png" alt="de-link website homepage" width="720"><br>
  <em>The de-link homepage — <a href="https://de-link.me">de-link.me</a></em>
</p>

<p align="center">
  <img src="images/pip-pcb-render.png" alt="de-link pip PCB render" width="720"><br>
  <em>de-link <b>pip</b> (v1.0) — PCB design nearly final</em>
</p>

## 📍 Status at a glance

- ✅ **`pre`** — the first prototype: built, validated, and documented (warts and all).
- 🔷 **`pip` (v1.0)** — PCB design **nearly final**: smaller footprint, thinner profile, lower BOM cost.
- 🖥️ Runs **[Crosspoint Reader](https://crosspointreader.com)** firmware, flashable over USB-C — no locked bootloaders, no bricks.
- 🧰 Fully **3D-printable** case · **0805 / SOT-23** hand-solderable parts · fully **open BOM**.
- 🔦 Optional **frontlight** (software cool/warm) and **battery-protection** modules.
- 📦 Production files — **KiCad, gerbers, CPL, STL, firmware** — release publicly at launch.
- 🤝 Built in open collaboration with **[freeink.org](https://freeink.org)**.

> ℹ️ Some figures in this repo's older notes are out of date (for example, an early
> ~$60 cost estimate). The **live bill of materials on the website** is the source of truth.

## 🛠️ Hardware at a glance

| | |
|---|---|
| **Screen** | any 24-pin GoodDisplay SPI e-paper panel — 3.97", 4.26", 7.5" and more. swap without touching the PCB. |
| **Case** | fully 3D-printable. reprint or redesign freely — no molds, no minimums. |
| **Repair** | 0805 & SOT-23 throughout, hand-solderable. open BOM — replace the part that broke. |
| **Battery** | bring your own single-cell 3.7V LiPo with a JST 2.0 connector. |
| **Compute** | ESP32-S3 with USB-C OTG and no firmware restrictions. |
| **Storage** | 4-bit SDMMC microSD — faster than the 1-bit SPI most comparable devices use. |

## 🗂️ The de-link project on GitHub

The project is split into focused repositories. This hub points you to the right one:

| Repository | What it is |
|---|---|
| 🌐 **[de-link-site](https://github.com/iandchasse/de-link-site)** | The website — **now the main information hub. Start here.** |
| 🔧 **[de-link-pcb](https://github.com/iandchasse/de-link-pcb)** | Hardware / PCB design files. |
| 💾 **[crosspoint-reader-de-link](https://github.com/iandchasse/crosspoint-reader-de-link)** | Reader firmware — Crosspoint Reader ported to the de-link platform. |
| 📚 **[freeink-sdk](https://github.com/iandchasse/freeink-sdk)** | Hardware-independent SDK for e-paper reader firmware (fork of [Free-Ink/freeink-sdk](https://github.com/Free-Ink/freeink-sdk)). |
| 🧩 **[community-sdk-de-link](https://github.com/iandchasse/community-sdk-de-link)** | Community SDK for de-link. |
| 🧭 **de-link** *(you are here)* | The original hub — kept for history and as an index to the above. |

## 💬 Community &amp; support

- **Discord** — [join the community](https://discord.gg/zCnKFt4Y4P)
- **Patreon** — [support development](https://www.patreon.com/iandchasse)
- **Ko-fi** — [buy a coffee](https://ko-fi.com/iandchasse)
- **Mailing list** — sign up on the [website](https://de-link.me) for hardware release news

## 📄 About this repository

This repo is preserved as part of de-link's history. The original deep-dive notes,
schematics, and images remain in place (`markdown/`, `schematic/`, `images/`, `logos/`)
for anyone who wants them. For anything current — specs, BOM, build info — the
**[website](https://de-link.me)** is authoritative.

<p align="center">
  ⭐ <b>461 stars and counting</b> — thank you. Now come see where it's headed:<br>
  <a href="https://de-link.me"><b>de-link.me →</b></a>
</p>
