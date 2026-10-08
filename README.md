<!-- ╔═══════════════════════════════════════════════════════════════╗ -->
<!-- ║  starter2157 · GitHub Profile README                          ║ -->
<!-- ╚═══════════════════════════════════════════════════════════════╝ -->

<div align="center">

<!-- ── Banner ─────────────────────────────────────────────── -->
<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:6d28d9,50:2563eb,100:06b6d4&height=200&section=header&text=STARTER&fontColor=ffffff&fontSize=72&fontAlignY=36&desc=Computer%20Engineering%20%C2%B7%20Chulalongkorn%20University&descAlignY=58&descSize=18&animation=fadeIn"
  alt="STARTER banner"
/>

<!-- ── Typing tagline ─────────────────────────────────────── -->
<a href="https://github.com/starter2157">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=2563EB&center=true&vCenter=true&width=650&lines=Computer+Vision+%C2%B7+AI+/+ML+%C2%B7+Biomedical+Tech;Full-Stack+Web+%C2%B7+Bioinformatics+RAG;Python+%C2%B7+TypeScript+%C2%B7+Java+%C2%B7+C%2B%2B;"
    alt="Typing tagline"
  />
</a>

<br/>

</div>

---

## 👋 About Me

```ts
const starter = {
  name:        "STARTER",
  base:        "Thailand 🇹🇭",
  role:        "Computer Engineering @ Chulalongkorn University",
  focus:       ["Computer Vision", "AI / ML", "Biomedical Tech", "Full-Stack Web"],
  languages:   ["Python", "TypeScript", "Java", "C++"],
  currently:   [
    "HKTutor — tutor-booking platform (Next.js + NestJS)",
    "BioProt — dual-retrieval RAG for protein function",
    "Jaw-motion tracking for digital orthodontics"
  ]
};
```

- 📓 Building the **messaging API** for **HKTutor**, a tutor-booking platform, with a ten-plus-person team (NestJS + Prisma + PostgreSQL)
- 🧬 Working on **BioProt** — a dual-retrieval RAG pipeline that combines **sequence** and **structure** evidence for protein-function research
- 🦷 Building an end-to-end **jaw-motion tracking pipeline** for digital dentistry — computer vision, 3D reconstruction, and an iOS TrueDepth capture app
- 🧊 Shipped a full **business-management system** for a family-run ice factory (Next.js + MongoDB)
- 🖨️ Designing **3D-printed fiducial markers** in Blender and validating print geometry against my own detectors
- 🌱 From my first hand-coded website to production systems tested on real clinical data

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Vision · 3D · ML**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Open3D](https://img.shields.io/badge/Open3D-2A6FDB?style=for-the-badge&logo=data:image/svg+xml;base64,&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-EA7600?style=for-the-badge&logo=blender&logoColor=white)
![ARKit](https://img.shields.io/badge/ARKit%20%C2%B7%20TrueDepth-000000?style=for-the-badge&logo=apple&logoColor=white)

**Web · Data**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## 🔨 Currently Building

<table>
  <tr>
    <td width="50%" valign="top">

### 📓 [HKTutor](https://github.com/Sitta-C/HKTutor) — Tutor-booking platform
**A full-stack marketplace where students find tutors and book lessons** — built as a pnpm monorepo by a ten-plus-person team, with a notebook-themed, Thai/English UI.

- **My part — the messaging API:** conversation endpoints, **cursor-paged** conversation lists with unread counts, message history paging, and **recipient-only read receipts**, covered by e2e tests
- **Platform:** tutor discovery, availability with overnight and multi-day slots, student booking, and role-specific dashboards
- **Auth built in-house:** Argon2id hashes, email verification, short-lived JWTs with **rotating refresh sessions** and reuse detection

`Next.js 16` · `React 19` · `Tailwind v4` · `NestJS 11` · `Prisma` · `PostgreSQL` · `Docker`

[📂 Repo](https://github.com/Sitta-C/HKTutor)

  </td>
    <td width="50%" valign="top">

### 🧬 [BioProt](https://github.com/splexmus/BioProt) — Dual-retrieval RAG for protein function
**Predicting what a protein does from two independent evidence channels** — sequence homology and 3D structure — instead of collapsing them into one score. *Early stage: Phase 1 proof of concept.*

- **Two retrievers:** a sequence branch (eggNOG / MMseqs2) and a structure branch (AlphaFold DB models searched with Foldseek)
- **Cross-modal agreement:** every candidate function is labelled `CONSENSUS`, `SEQUENCE_ONLY`, `STRUCTURE_ONLY` or `CONFLICT` — conflicts are kept as evidence, never averaged away
- **Reproducible by design:** typed evidence schemas, versioned normalization, and provenance for every run
- **Roadmap:** literature RAG, citation-verified LLM reports, and calibrated confidence

`Python` · `Pydantic` · `Typer` · `pytest` · `Bioinformatics`

[📂 Repo](https://github.com/splexmus/BioProt)

  </td>
  </tr>
</table>

---

## 🚀 Featured Projects

### 🦷 [jaw-motion](https://github.com/starter2157/jaw-motion) — Digital-orthodontics research
> **Markerless jaw-motion tracking from an iPhone + intraoral scan.** An end-to-end pipeline that reconstructs how the jaw moves — the kind of capability behind commercial systems like **Modjaw / MetiSmile** — built from scratch.

- **Computer vision:** a whole catalog of fiducial-marker detectors — HSV colour, geometric relief/curvature, an arch-unrolling **render-to-2D panorama** detector, **multi-cue fusion**, and a **sphere-fit** detector for 3D-printed dome markers
- **3D tracking:** **markerless ICP** mesh registration + **ArUco-carrier PnP** 6-DOF pose recovery → jaw motion as relative maxilla/mandible transforms
- **iOS app** (`JawTrackCapture`, Swift/SwiftUI): synchronized **RGB + TrueDepth** capture in exact pipeline format — *built and field-tested on a real iPhone*
- **Hardware:** 3D-printed dome markers designed in **Blender (via MCP)**, print geometry verified against the detector's own sphere-fit

`Python` · `OpenCV` · `Open3D` · `trimesh` · `Swift` · `TrueDepth` · `Blender`
&nbsp;&nbsp;[🔗 Live demo](https://jaw-motion.vercel.app) · [📂 Repo](https://github.com/starter2157/jaw-motion)

<table>
  <tr>
    <td width="50%" valign="top">

### 📷 [HardwareSynLab-Project](https://github.com/Sherneys/HardwareSynLab-Project) — FPGA video pipeline
**Real-time camera → VGA video processor on a Basys 3 FPGA.** Computer vision, but in hardware.

- **OV7670 camera** capture, configured over an SCCB (I²C-like) bus
- Dual-clock **dual-port BRAM** frame buffer
- **Switchable filters** — grayscale, colour inversion, channel isolation, threshold — live via board switches
- Verified with **5 Verilog testbenches** (all passing)

`Verilog` · `Basys 3` · `OV7670` · `VGA` · `Vivado`

[📂 Repo](https://github.com/Sherneys/HardwareSynLab-Project)

  </td>
    <td width="50%" valign="top">

### 🧊 [d-ice](https://github.com/starter2157/d-ice) — Dee-Ice factory ERP
A private **business-management system** for the *Dee-Ice* ice factory (Pathio, Chumphon 🇹🇭). Employees, stock, and finances in one internal tool.

- **Dashboard** with stats + low-stock alerts
- CRUD for **employees / inventory / finances**
- JWT auth, Thai Baht ฿ + Thai locale throughout

`Next.js 16` · `TypeScript` · `Tailwind v4` · `MongoDB` · `JWT`

[📂 Repo](https://github.com/starter2157/d-ice)

  </td>
  </tr>
</table>

<sub>🕰️ Earlier work: ⚽ **Goalkeeper Dive Prediction** — my DPST research (2023): pose estimation + a neural network predicting penalty-kick dive direction, 71.08% accuracy · 🎮 [Color-in-RealLife](https://github.com/starter2157/Color-in-RealLife) — a JavaFX turn-based life-sim game with JUnit-tested OOP logic</sub>

<sub>🌐 Also: [Next-js-BusinessWebsite](https://github.com/starter2157/Next-js-BusinessWebsite) — a live business site · [nextjs-pets](https://github.com/starter2157/nextjs-pets) · [express-pets](https://github.com/starter2157/express-pets) — full-stack CRUD practice · 🌟 [NewjeansWebsite](https://github.com/starter2157/NewjeansWebsite) — where it all started (my first hand-coded HTML/CSS/JS site)</sub>

---

## 🌐 Connect

<div align="center">

<a href="https://github.com/starter2157">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="mailto:starter2157@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:2563eb,100:6d28d9&height=100&section=footer" alt="footer" />

</div>
