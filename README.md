
# Hey, I'm Ruther 👋

I'm a software engineer and second-degree Computer Science student at the University of British Columbia. Before software, I studied mechanical engineering!

I'm especially interested in backend engineering, platform infrastructure, databases, and building useful products from end to end. I've worked on production software at **Procurify** and **Trulioo**, and I enjoy contributing to multidisciplinary engineering teams.

---

### 🗺️ Want a different kind of portfolio?

**[Enter Mintvale — my interactive portfolio](https://portfolio-charrmint.vercel.app/)**

Instead of a traditional résumé page, I built a small RPG-inspired village where you can create a traveler, explore my background, unlock stories, and browse a more direct **World Atlas** if you're short on time.

**Built with:** HTML, CSS, vanilla JavaScript, SVG, and a dependency-free Node.js content build.

[Source code](https://github.com/charrmint/portfolio-charrmint) · [LinkedIn](https://www.linkedin.com/in/rutherbc/)

---

## 🚀 Things I've built

### 🏋️ [RepPilot](https://github.com/charrmint/Rep-Pilot)

<sub>Next.js · React · TypeScript · Supabase/PostgreSQL · Tailwind CSS · Vitest</sub>

**[Try the live app](https://rep-pilot.vercel.app/)**

A mobile-first strength-training tracker that turns workout history into explainable, deterministic progression recommendations.

- Built reusable workout templates, set-by-set logging, training history, and strength records.
- Designed a pure double-progression engine that considers rep targets, effort, pain signals, and recent sessions to recommend increasing, maintaining, reducing, or reviewing a load.
- Used Supabase Auth, row-level security, database constraints, and transactional RPCs to isolate user data and keep workout completion consistent.

---

### 🥬 [FoodRadar](https://github.com/charrmint/FoodRadar) — BCS Hacks 2025

<sub>React · Vite · Node.js · Express · MongoDB · Google Cloud Vision API · JWT / Google OAuth</sub>

A smart-fridge proof of concept that makes it easier to track what's in your refrigerator. It supports manual inventory management and camera-assisted item recognition, using a webcam in place of an in-fridge camera for the prototype.

---

### 💼 [Job Hunting Assistant](https://github.com/charrmint/JobTrackerApp)

<sub>Java · Swing · JSON · JUnit</sub>

A desktop application built to make my own internship search less spreadsheet-heavy. Organizes opportunities by application stage, supports status changes and transitions, and provides deadline/follow-up notifications with local save and load.

---

## 🤝 Team projects & contributions

### 🚣 [NABIL — Naval Architecture & Boat Innovation Lab](https://github.com/UBC-Concrete-Canoe/nabil-app)

<sub>UBC Concrete Canoe · C++17 · Qt 6 · OpenCASCADE · VTK · CMake</sub>

A collaborative CAD-style hull-design application for naval architecture, connecting a geometric hull model to interactive 3D views.

**Highlights:**

- **Control-point interaction:** Implemented selection and movement of 3D control points using OpenCASCADE's interactive context, translating 2D mouse movements into 3D coordinates relative to the camera.
- **UI and model integration:** Connected Qt mouse events to the underlying hull model, supporting distinct selection, movement, and viewport navigation modes.

---

### 🧠 [MOSS — EEG Signal Processing Platform](https://github.com/UBCMint/fullstack-moss-app)

<sub>UBC MINT · Next.js · TypeScript · Rust · Python · WebSockets · TimescaleDB/PostgreSQL · Docker</sub>

A full-stack platform for configuring, streaming, processing, and visualizing EEG signals using a node-based pipeline editor backed by Rust services.

**Highlights:**

- **Pipeline reliability:** Reworked validation so incomplete pipelines can be edited without noisy errors, while streaming requires a valid, freshly generated configuration. Added editing safeguards during active streams and regression tests.
- **Cross-platform infrastructure:** Repaired Rust/Python Docker builds by updating Debian images, aligning embedded-Python dependencies, and addressing ARM/Linux compatibility issues in native dependencies.
- **Developer documentation:** Documented the Rust-to-Python processing bridge, processing modules, and CI workflows to make the architecture easier to understand and maintain.
- **Editor navigation:** Implemented browser/OS Back behavior that closes chart preview without discarding the user's unsaved pipeline, with state synchronized to browser history.

---

### 🌐 Launchpad — Distributed Connectivity Testing

<sub>Python · Docker · HTTP APIs · GitHub webhooks · relational database design</sub>

A distributed connectivity-testing system where remote probes execute centrally assigned test scripts and report run results and analytics.

**Highlights:**

- **Server–probe architecture:** Designed the MVP architecture and relational data model for distributed connectivity testing, using HTTP polling to retrieve test assignments and report execution results.
- **Test version management:** Designed a GitHub webhook-driven update mechanism where probes synchronize test scripts with the latest versions, tracking installed and executed commit SHAs for traceability and auditability.

*Repository not yet public.*

---

## 🧰 Tools I work with

**Languages:** Python, C#, TypeScript/JavaScript, SQL, Java, C++, Rust

**Backend & data:** .NET, ASP.NET Core, Django, FastAPI, Node.js, PostgreSQL, MySQL, MongoDB

**Frontend:** React, Next.js

**Infrastructure & testing:** AWS, Docker, GitHub Actions, GitLab CI, CircleCI, xUnit, pytest, Vitest

---

### 📬 Let's connect

[Interactive portfolio](https://portfolio-charrmint.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/rutherbc/)
