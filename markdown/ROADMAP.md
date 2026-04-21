# Roadmap
The 'de-link' hardware platform is currently a work-in-progress and self-funded project. For community confidence, I'm establishing a series of "checkpoints" which I'd hope to achieve building upon my small-scoped initial prototype. 
This is a community-driven project from day one. Whether you're interested in PCB design, firmware development, 3D printing, or just want to build one for yourself, contributions and feedback are welcome.

Watch this repository for updates, open issues with questions or ideas, and join the conversation on [Discord here](https://discord.gg/zCnKFt4Y4P).

To join the project as a supporter, please find my [Patreon here](https://www.patreon.com/cw/iandchasse) or my [Ko-Fi here](https://ko-fi.com/iandchasse). This will grant you early access to project details as detailed below.

## Current Phase: Foundation & Community Building

**Status: Ongoing!**

The initial prototype is functional and the immediate priority is building a community around the project. Everything needed to evaluate, replicate, and contribute to the current design is being made available:

- Full BOM (Bill of Materials)
- KiCad project files (schematic + PCB layout)
- Software compatible with the current hardware
- Step-by-step build guides
- PCB and schematic breakdowns with documentation
- 3D-printable enclosure files
- Working prototype demonstrations with crosspoint-reader firmware

**Goal:** Establish a base of early supporters and contributors who can provide feedback, test if they feel so inclined to build it themselves at this stage, and help shape the direction of the project.

---

## Checkpoint 1: Board v1.0 Release (Supporters)

**Status: Check in around June 2026!**

With initial community support hopefully established, the focus shifts to producing a refined v1.0 board design suitable for beta testers interested in the initial prototype.

- Finalize v1.0 board design based on prototype feedback
- Produce a batch of v1.0 PCBs
- Release Gerber files and full manufacturing data to supporters
- Refine and organize community repositories:
    - Software libraries and example projects
    - Hardware documentation and design notes
    - 3D printing guides and enclosure files
    - Screen compatibility reference (tested displays, wiring notes, driver support)

**Goal:** Deliver a reliable, well-documented v1.0 board that supporters can confidently build and develop with.

---

## Checkpoint 2: Evaluation & v2.0 Planning

**Status: Check in around August 2026!**

A checkpoint to assess community traction and plan the next hardware revision.

- Evaluate community support level and engagement
- Gather feedback from v1.0 builders on pain points, feature requests, and use cases
- Begin v2.0 board design if resources allow, targeting:
    - Smaller overall footprint (closer to generic dev-kit than fit to 4.26" screen/enclosure)
    - Same overall component set as v1.0 
    - Greater flexibility for integration with other GoodDisplay screens and enclosure designs

**Goal:** Make an informed decision on continuing to v2.0 and begin design work with feedback from v1.0 supporters

---

## Checkpoint 3: Board v2.0 Release (Supporters)

**Status: Check in around September 2026!**

Expand the platform beyond the original 4.26" display and demonstrate the full capability of the optional module system.

- Produce v2.0 board design
- Design and release 3D-printable enclosures for multiple GoodDisplay screen sizes:
    - 3.97"
    - 4.26" (same as initial prototype)
    - 7.5"
    - any others that seem fit (see [here](https://www.good-display.com/product/6/))
- Demonstrate the onboard series-LED driver with external front-light attachment
- Release all v1.0 resources (hardware files, software, documentation) to the general public — no longer limited to early supporters

**Goal:** Flesh out alternate display compatibility and reward the broader community with full access to v1.0.

---

## Checkpoint 4: v2.0 Release & Next Steps

**Status: Check in around December 2026!**

Transition the project from a community effort toward a sustainable product path.

- Release v2.0 board design and associated resources to all
- Establish an LLC for the project
- Evaluate and potentially launch a crowdfunding campaign for small production run for cohesive development kit (screen, battery, assembled board, case)
- Continue expanding display compatibility and enclosure options

**Goal:** Put the groundwork in place for production.

---

## Beyond: Long-Term Vision

- Beyond a short crowd-funded production run, I will likely not be able to sustain maintained production and I do not want to. Please see PHILOSOPHY.md.
- Expand display support if GoodDisplay releases new panels
- Grow the ecosystem of compatible enclosures, accessories, and community-built software

---

## Ongoing: Always in Progress

These efforts run in parallel with every phase above:

- **Open-source software maintenance**: bug fixes, feature development, driver support for new displays. Focus on crosspoint-reader will be first and foremost, while TRMNL will be explored. Ideally, crosspoint-reader will be the "default" platform, as its implementation on the ESP32-S3 (with PSRAM) allows for a much broader scope of that specific project.
- **Progress updates**: regular communication with the community on development status
- **Community feedback**: actively incorporating suggestions, bug reports, and feature requests into the roadmap

---
