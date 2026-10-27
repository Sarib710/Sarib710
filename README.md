<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 380" width="100%" height="100%">
  <defs>
    <!-- Background Gradient -->
    <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#080a0c" />
      <stop offset="50%" stop-color="#0d0f12" />
      <stop offset="100%" stop-color="#050607" />
    </linearGradient>

    <!-- Subtle Radial Glow -->
    <radialGradient id="halo" cx="50%" cy="45%" r="65%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.05" />
      <stop offset="60%" stop-color="#12151a" stop-opacity="0.0" />
    </radialGradient>

    <!-- Grid Pattern -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <line x1="0" y1="0" x2="40" y2="0" stroke="#ffffff" stroke-opacity="0.02" stroke-width="1" />
      <line x1="0" y1="0" x2="0" y2="40" stroke="#ffffff" stroke-opacity="0.02" stroke-width="1" />
    </pattern>
  </defs>

  <style>
    .wordmark {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Cinzel", "Bodoni MT", "Didot", "Times New Roman", serif;
      font-weight: 300;
      letter-spacing: 0.38em;
      fill: #f0f2f5;
    }
    .subtext {
      font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "Inter", "Segoe UI", sans-serif;
      font-weight: 400;
      letter-spacing: 0.42em;
      font-size: 11px;
      fill: #8b929a;
      text-transform: uppercase;
    }
    .mono {
      font-family: "SF Mono", "JetBrains Mono", "Fira Code", Menlo, monospace;
      font-size: 9px;
      letter-spacing: 0.16em;
      fill: #525964;
    }
    .accent-ring {
      fill: none;
      stroke: #ffffff;
      stroke-opacity: 0.04;
    }
  </style>

  <!-- Backdrop -->
  <rect width="1200" height="380" fill="url(#bg-grad)" />
  <rect width="1200" height="380" fill="url(#halo)" />
  <rect width="1200" height="380" fill="url(#grid)" />

  <!-- Outer Frame -->
  <rect x="24" y="24" width="1152" height="332" fill="none" stroke="#ffffff" stroke-opacity="0.08" stroke-width="1" />

  <!-- Atmospheric Orbital Geometry -->
  <circle cx="600" cy="190" r="140" class="accent-ring" stroke-dasharray="2 6" />
  <circle cx="600" cy="190" r="170" class="accent-ring" stroke-opacity="0.025" />
  <circle cx="600" cy="190" r="210" class="accent-ring" stroke-dasharray="1 10" />

  <!-- Crop Corner Marks (Editorial / Viewfinder Camera Style) -->
  <path d="M 40 54 L 40 40 L 54 40" fill="none" stroke="#7e8590" stroke-width="1.2" />
  <path d="M 1160 54 L 1160 40 L 1146 40" fill="none" stroke="#7e8590" stroke-width="1.2" />
  <path d="M 40 326 L 40 340 L 54 340" fill="none" stroke="#7e8590" stroke-width="1.2" />
  <path d="M 1160 326 L 1160 340 L 1146 340" fill="none" stroke="#7e8590" stroke-width="1.2" />

  <!-- Top Metadata Line -->
  <text x="50" y="58" class="mono">INDEX // EDTR-01</text>
  <text x="600" y="58" class="mono" text-anchor="middle">MONOCHROME SYSTEM / GRAPHITE EDITION</text>
  <text x="1150" y="58" class="mono" text-anchor="end">2026 ARCHIVE</text>

  <!-- Center Wordmark and Subtitle -->
  <text x="605" y="195" font-size="64" class="wordmark" text-anchor="middle">sarib</text>
  <line x1="480" y1="222" x2="720" y2="222" stroke="#ffffff" stroke-opacity="0.12" stroke-width="1" />
  <text x="603" y="244" class="subtext" text-anchor="middle">editorial mind. digital craft.</text>

  <!-- Bottom Coordinates & Readouts -->
  <text x="50" y="328" class="mono">FRAME RATE // 24.000 FPS</text>
  <text x="600" y="328" class="mono" text-anchor="middle">LATENCY // NULL</text>
  <text x="1150" y="328" class="mono" text-anchor="end">STATUS // OPERATIONAL</text>
</svg>
<div align="center">

<img src="./assets/banner.svg" alt="sarib — editorial mind. digital craft." width="100%" />

<br />
</div>

---

### `01` // PROFILE

Operating at the intersection of visual rhythm and technical execution. 

I treat software development with an editor's discipline—stripping out noise, refining cadences, and engineering clean systems. Whether sequencing frames, tuning automated microservices, or building responsive web interfaces, the focus remains constant: restrained aesthetics, intentional hierarchy, and uncompromising craftsmanship.

---

### `02` // DISCIPLINES & EXPLORATION
---

### `03` // SELECTED WORK

A selection of technical repositories and experimental digital builds.

<table>
  <thead>
    <tr>
      <th width="45%" align="left">REPOSITORY</th>
      <th width="25%" align="left">CATEGORY</th>
      <th width="30%" align="left">ARCHITECTURE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/Sarib710/discord-bot-core">
          <b>discord-bot-core</b>
        </a><br />
        <sub>Modular event-driven automation engine for private communities.</sub>
      </td>
      <td><code>AUTOMATION</code></td>
      <td>TypeScript / Node.js</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/Sarib710/editorial-web">
          <b>editorial-web</b>
        </a><br />
        <sub>High-contrast, low-latency minimalist portfolio template for creators.</sub>
      </td>
      <td><code>INTERFACE</code></td>
      <td>Next.js / Tailwind CSS</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/Sarib710/creative-scripts">
          <b>creative-scripts</b>
        </a><br />
        <sub>CLI utilities for batch media processing, transcoding, and sorting.</sub>
      </td>
      <td><code>TOOLING</code></td>
      <td>Python / FFmpeg</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/Sarib710/lab-experiments">
          <b>lab-experiments</b>
        </a><br />
        <sub>Archived experiments exploring canvas shaders, micro-interactions, and AI APIs.</sub>
      </td>
      <td><code>EXPERIMENTAL</code></td>
      <td>Modern Web APIs</td>
    </tr>
  </tbody>
</table>

> *Note: Replace repository links above with your specific public repository names as projects are published.*

---

### `04` // SYSTEM METRICS

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sarib710&theme=transparent&hide_border=false&border_color=21262d&title_color=f0f6fc&text_color=8b949e&icon_color=7d8590&bg_color=00000000&show_icons=true&count_private=true" alt="sarib GitHub Statistics" height="150" />
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sarib710&theme=transparent&hide_border=false&border_color=21262d&title_color=f0f6fc&text_color=8b949e&bg_color=00000000&layout=compact" alt="sarib Top Languages" height="150" />

</div>

---

### `05` // CURRENT TERMINAL

```console
$ sarib --status --verbose
[ACTIVE EXPERIMENT]  Exploring zero-bloat web architecture & local LLM workflows
[REVISION FOCUS]     Deepening visual rhythm, sound-to-cut synchronization, and grain grading
[READING / INTAKE]   Typography manuals, archival cinema notes, and systems design principles
[CURRENT LOCALE]     UTC+06:00

designed by sarib © 2026
