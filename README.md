<div align="center">

<br/>
<img src="https://readme-typing-svg.demolab.com?font=Syne&weight=800&size=46&duration=3000&pause=1000&color=FFFFFF&center=true&vCenter=true&width=860&height=90&lines=SANKET+BHARADWAJ" alt="Sanket Bharadwaj"/>

<img src="https://readme-typing-svg.demolab.com?font=DM+Mono&weight=400&size=13&duration=4000&pause=800&color=555555&center=true&vCenter=true&width=600&height=28&lines=Systems+Engineer+%C2%B7+Product+Builder+%C2%B7+Algorithm+Enthusiast;From+the+interface+to+the+hardware+register.;Depth+over+hype.+Execution+over+ideas." alt="Subtitle"/>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=flat-square&logo=vercel&logoColor=white&labelColor=0d0d0d)](https://sanketbharadwaj.vercel.app)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%23000000.svg?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=0d0d0d)](https://www.linkedin.com/in/sanket-bharadwaj-a041b6311)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-%23000000.svg?style=flat-square&logo=github&logoColor=white&labelColor=0d0d0d)](https://github.com/Sanket-Bharadwaj)

</div>

<br/>

---

I work at every layer of the stack — not as a framing device, but as a practice.

Written a programming language in C. Shipped production SaaS with real users. Wired microcontrollers to the web. Built a browser OS in vanilla JS. When I hit an abstraction, my instinct isn't to accept it — it's to go through it.

> *Performance isn't negotiable. UX isn't optional. Everything else is negotiable.*

---

## Work

<br/>

### VYOM — Core Language & Runtime &nbsp;&nbsp;`C`

A complete programming language built from scratch in C — including lexer, parser, execution engine, scoped runtime, fixed-size arrays (1D & 2D), strict type enforcement, and deterministic memory handling.

No LLVM.  
No garbage collector.  
No hidden runtime.  
No magic.

Manual memory management. Explicit semantics. Predictable execution.

Vyom Core is designed around one principle:

> What you write is exactly what runs.

---

#### Runtime Guarantees

- Strict typing (no silent coercion)
- Bounds-checked arrays (1D & 2D, row-major layout)
- Immutable strings
- Loop-scoped execution frames
- No shadowing ambiguity
- Deterministic cleanup (`exit()` guarantees memory release)

---

#### Why Vyom Exists

This project was built to deeply understand:

- Parsing discipline and ambiguity control  
- Expression evaluation pipelines  
- Scope resolution and call-frame design  
- Runtime safety without a garbage collector  
- Memory layout decisions and cache behavior  
- How minimal languages scale without collapsing into complexity  

Vyom Core v1.0 is frozen and stable.  
The semantics will not change.

Future layers (Std, tooling, ecosystem) build **on top**, never inside.

---
### Get VYOM

Learn more about the language, download the latest build, or explore the source code.

<div align="center">

[![Visit Website](https://img.shields.io/badge/Explore-Website-0d0d0d?style=flat-square&logo=vercel&logoColor=white)](https://getvyom.vercel.app)
[![Download Windows Build](https://img.shields.io/badge/Download-Windows_Build-0d0d0d?style=flat-square&logo=windows&logoColor=0078D6)](https://github.com/Sanket-Bharadwaj/VYOM/releases/download/v1.0.0/Vyom-1.0-Windows.zip)
[![View Repository](https://img.shields.io/badge/View-Source_Code-0d0d0d?style=flat-square&logo=github&logoColor=white)](https://github.com/Sanket-Bharadwaj/VYOM)

</div>



`v1.0 — Core Hardened Release` · `Strict • Minimal • Honest`

---

<br/>

### WANDROUS — Offline-First Travel Platform &nbsp;&nbsp;`React · TypeScript · Vite`

Full offline capability via service workers and PWA architecture. i18n across 6+ languages. Zero backend. Zero runtime network dependency. Edge deployed.

Designed under a hard constraint: assume no network. That forces clear separation between what truly requires a server and what is habitually outsourced to one. Architecture becomes intentional instead of convenient.

`offline-first` &nbsp;·&nbsp; `6+ languages` &nbsp;·&nbsp; [→ Live](https://wandrous.vercel.app)

<br/>

---

### PORTOS — Browser OS &nbsp;&nbsp;`Vanilla JS · CSS3`

Window management system, virtual file structure, drag interactions, and consistent 60fps rendering — built without frameworks or abstractions.

An exercise in pushing the DOM to its limits: measuring cost, controlling repaint/reflow behavior, and finding the performance ceiling before reaching for libraries.

`zero dependencies` &nbsp;·&nbsp; `60fps` &nbsp;·&nbsp; [→ Live](https://portos-new.vercel.app)

---

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,python,javascript,typescript,react,vite,tailwind,flask,mongodb,docker,linux,arduino,raspberrypi,opencv,pytorch,git,vercel&theme=dark&perline=9"/>

<br/><br/>

<table>
<thead>
<tr>
<th></th>
<th>Core (Built With)</th>
<th>Working Knowledge</th>
<th>Currently Exploring</th>
</tr>
</thead>

<tbody>

<tr>
<td><strong>Languages</strong></td>
<td>C · Python</td>
<td>JavaScript · TypeScript</td>
<td>C++</td>
</tr>

<tr>
<td><strong>Frontend</strong></td>
<td>React · Vite · Tailwind</td>
<td>PWA Architecture · DOM Performance</td>
<td>Advanced Rendering Techniques</td>
</tr>

<tr>
<td><strong>Backend</strong></td>
<td>Flask · REST APIs · MongoDB</td>
<td>Schema Design · Auth Systems</td>
<td>API Architecture Patterns</td>
</tr>

<tr>
<td><strong>Systems / Infra</strong></td>
<td>Linux · Docker · Git</td>
<td>Environment Setup · Networking Basics</td>
<td>Self-hosting · Service Orchestration</td>
</tr>

<tr>
<td><strong>Embedded</strong></td>
<td>ESP32 · Arduino · Raspberry Pi</td>
<td>Hardware Interfacing</td>
<td>Firmware Development</td>
</tr>

<tr>
<td><strong>Computer Science</strong></td>
<td>Lexers · Parsers · AST Execution</td>
<td>DSA · Algorithm Implementation</td>
<td>Distributed Systems Concepts</td>
</tr>

</tbody>
</table>

</div>

---

## Principles

```
Simplicity beats cleverness     —     If it needs explaining, it isn't done.
Robustness beats speed          —     Reliability is the base layer, not a feature.
Clarity beats abstraction       —     Code should explain itself.
Users beat theory               —     Software that fails production isn't software.
Depth beats hype                —     Build systems, not experiments.
Execution beats ideas           —     Shipping is the only metric that compounds.
```

> *"Every decision compounds. Build accordingly."*

---

## Current

```
Vyom v1.0          →   stdlib design · error handling · docs
DSA → Systems      →   implementing structures from scratch, not memorizing them
Linux              →   service networking · env tuning · workflow automation
CLI Tooling        →   gaps I keep hitting that shouldn't exist
```

---

<div align="center">

Open to conversations on &nbsp;`systems design` · `algorithms` · `infrastructure` · `performance` · `developer tools`

<br/>

[![Email](https://img.shields.io/badge/Email-0d0d0d?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:sanketbharadwaj@example.com)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d0d0d?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/sanket-bharadwaj-a041b6311)&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-0d0d0d?style=flat-square&logo=vercel&logoColor=white)](https://sanketbharadwaj.vercel.app)

<br/>

<sub>`Bhubaneswar, India · Updated February 2026`</sub>

</div>

---
