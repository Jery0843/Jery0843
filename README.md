<!-- ===================================================== -->
<!-- Jerome Andrew K — Final Terminal README (SVG animated, GitHub-safe) -->
<!-- Neon green on black terminal. Full-bleed cinematic SVG + compact info. -->
<!-- Save this file as README.md in your profile repo (github.com/Jery0843/Jery0843) -->
<!-- ===================================================== -->

<div align="center">

<!-- Full-width SVG: terminal header + animated matrix strip + blinking cursor -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" preserveAspectRatio="xMidYMid slice" width="100%" style="max-width:100%;border-radius:8px;background:#000;">
  <defs>
    <linearGradient id="neonGrad" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0%" stop-color="#00FF66" stop-opacity="0.95"/>
      <stop offset="100%" stop-color="#006633" stop-opacity="0.15"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <style><![CDATA[
      .title { font-family: 'Fira Code', 'Courier New', monospace; font-size:46px; fill:#00FF66; font-weight:700; }
      .sub { font-family: 'Fira Code', monospace; font-size:14px; fill:#9fffcf; opacity:0.95; }
      .matrix { font-family: 'Courier New', monospace; font-size:14px; fill:#00ff66; opacity:0.92; }
      .cursor { fill:#00FF66; }
      .panel { fill:#000; fill-opacity:0.0; }
    ]]></style>
  </defs>

  <!-- black rectangle backdrop -->
  <rect x="0" y="0" width="1200" height="320" fill="#000" />

  <!-- Title group with slight neon flicker animation -->
  <g transform="translate(60,48)">
    <text class="title" id="nameText">Jerome Andrew K</text>
    <text class="sub" transform="translate(0,46)">Cyber Hacker | AI Security | Forensics</text>

    <!-- subtle flicker overlay using opacity animation -->
    <rect x="360" y="-6" width="6" height="48" class="cursor">
      <animate attributeName="opacity" values="0;1;0;1;0" dur="1.6s" repeatCount="indefinite" />
    </rect>
  </g>

  <!-- matrix rain strip (multiple columns animated via translate) -->
  <g transform="translate(40,120)">

    <g>
    <text class="matrix" x="0" y="0">7</text>
    <text class="matrix" x="0" y="18">7</text>
    <text class="matrix" x="0" y="36">C</text>
    <text class="matrix" x="0" y="54">0</text>
    <text class="matrix" x="0" y="72">*</text>
    <text class="matrix" x="0" y="90">*</text>
    <text class="matrix" x="0" y="108">Z</text>
    <text class="matrix" x="0" y="126">9</text>
    <text class="matrix" x="0" y="144">E</text>
    <text class="matrix" x="0" y="162">6</text>
    <text class="matrix" x="0" y="180">8</text>
    <text class="matrix" x="0" y="198">B</text>
    <text class="matrix" x="0" y="216">0</text>
    <text class="matrix" x="0" y="234">C</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.14s" repeatCount="indefinite" begin="-2.84s" />
    </g>
    <g>
    <text class="matrix" x="32" y="0">%</text>
    <text class="matrix" x="32" y="18">@</text>
    <text class="matrix" x="32" y="36">4</text>
    <text class="matrix" x="32" y="54">2</text>
    <text class="matrix" x="32" y="72">2</text>
    <text class="matrix" x="32" y="90">Y</text>
    <text class="matrix" x="32" y="108">2</text>
    <text class="matrix" x="32" y="126">E</text>
    <text class="matrix" x="32" y="144">#</text>
    <text class="matrix" x="32" y="162">7</text>
    <text class="matrix" x="32" y="180">#</text>
    <text class="matrix" x="32" y="198">B</text>
    <text class="matrix" x="32" y="216">5</text>
    <text class="matrix" x="32" y="234">8</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.32s" repeatCount="indefinite" begin="-0.57s" />
    </g>
    <g>
    <text class="matrix" x="64" y="0">5</text>
    <text class="matrix" x="64" y="18">C</text>
    <text class="matrix" x="64" y="36">0</text>
    <text class="matrix" x="64" y="54">9</text>
    <text class="matrix" x="64" y="72">4</text>
    <text class="matrix" x="64" y="90">X</text>
    <text class="matrix" x="64" y="108">7</text>
    <text class="matrix" x="64" y="126">F</text>
    <text class="matrix" x="64" y="144">3</text>
    <text class="matrix" x="64" y="162">*</text>
    <text class="matrix" x="64" y="180">1</text>
    <text class="matrix" x="64" y="198">D</text>
    <text class="matrix" x="64" y="216">8</text>
    <text class="matrix" x="64" y="234">8</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="8.1s" repeatCount="indefinite" begin="-1.7s" />
    </g>
    <g>
    <text class="matrix" x="96" y="0">9</text>
    <text class="matrix" x="96" y="18">F</text>
    <text class="matrix" x="96" y="36">@</text>
    <text class="matrix" x="96" y="54">#</text>
    <text class="matrix" x="96" y="72">8</text>
    <text class="matrix" x="96" y="90">0</text>
    <text class="matrix" x="96" y="108">B</text>
    <text class="matrix" x="96" y="126">Z</text>
    <text class="matrix" x="96" y="144">Z</text>
    <text class="matrix" x="96" y="162">#</text>
    <text class="matrix" x="96" y="180">8</text>
    <text class="matrix" x="96" y="198">B</text>
    <text class="matrix" x="96" y="216">1</text>
    <text class="matrix" x="96" y="234">Y</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="7.2s" repeatCount="indefinite" begin="-2.31s" />
    </g>
    <g>
    <text class="matrix" x="128" y="0">D</text>
    <text class="matrix" x="128" y="18">7</text>
    <text class="matrix" x="128" y="36">E</text>
    <text class="matrix" x="128" y="54">D</text>
    <text class="matrix" x="128" y="72">6</text>
    <text class="matrix" x="128" y="90">9</text>
    <text class="matrix" x="128" y="108">%</text>
    <text class="matrix" x="128" y="126">8</text>
    <text class="matrix" x="128" y="144">E</text>
    <text class="matrix" x="128" y="162">*</text>
    <text class="matrix" x="128" y="180">6</text>
    <text class="matrix" x="128" y="198">%</text>
    <text class="matrix" x="128" y="216">0</text>
    <text class="matrix" x="128" y="234">7</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="8.1s" repeatCount="indefinite" begin="-1.57s" />
    </g>
    <g>
    <text class="matrix" x="160" y="0">B</text>
    <text class="matrix" x="160" y="18">3</text>
    <text class="matrix" x="160" y="36">%</text>
    <text class="matrix" x="160" y="54">0</text>
    <text class="matrix" x="160" y="72">E</text>
    <text class="matrix" x="160" y="90">8</text>
    <text class="matrix" x="160" y="108">0</text>
    <text class="matrix" x="160" y="126">4</text>
    <text class="matrix" x="160" y="144">*</text>
    <text class="matrix" x="160" y="162">X</text>
    <text class="matrix" x="160" y="180">2</text>
    <text class="matrix" x="160" y="198">D</text>
    <text class="matrix" x="160" y="216">6</text>
    <text class="matrix" x="160" y="234">E</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="5.29s" repeatCount="indefinite" begin="-2.08s" />
    </g>
    <g>
    <text class="matrix" x="192" y="0">3</text>
    <text class="matrix" x="192" y="18">2</text>
    <text class="matrix" x="192" y="36">7</text>
    <text class="matrix" x="192" y="54">C</text>
    <text class="matrix" x="192" y="72">A</text>
    <text class="matrix" x="192" y="90">9</text>
    <text class="matrix" x="192" y="108">*</text>
    <text class="matrix" x="192" y="126">D</text>
    <text class="matrix" x="192" y="144">B</text>
    <text class="matrix" x="192" y="162">%</text>
    <text class="matrix" x="192" y="180">0</text>
    <text class="matrix" x="192" y="198">X</text>
    <text class="matrix" x="192" y="216">#</text>
    <text class="matrix" x="192" y="234">X</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="5.85s" repeatCount="indefinite" begin="-1.99s" />
    </g>
    <g>
    <text class="matrix" x="224" y="0">F</text>
    <text class="matrix" x="224" y="18">8</text>
    <text class="matrix" x="224" y="36">C</text>
    <text class="matrix" x="224" y="54">X</text>
    <text class="matrix" x="224" y="72">0</text>
    <text class="matrix" x="224" y="90">D</text>
    <text class="matrix" x="224" y="108">5</text>
    <text class="matrix" x="224" y="126">7</text>
    <text class="matrix" x="224" y="144">1</text>
    <text class="matrix" x="224" y="162">9</text>
    <text class="matrix" x="224" y="180">E</text>
    <text class="matrix" x="224" y="198">Z</text>
    <text class="matrix" x="224" y="216">3</text>
    <text class="matrix" x="224" y="234">1</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="5.52s" repeatCount="indefinite" begin="-2.3s" />
    </g>
    <g>
    <text class="matrix" x="256" y="0">1</text>
    <text class="matrix" x="256" y="18">D</text>
    <text class="matrix" x="256" y="36">B</text>
    <text class="matrix" x="256" y="54">A</text>
    <text class="matrix" x="256" y="72">#</text>
    <text class="matrix" x="256" y="90">6</text>
    <text class="matrix" x="256" y="108">7</text>
    <text class="matrix" x="256" y="126">@</text>
    <text class="matrix" x="256" y="144">6</text>
    <text class="matrix" x="256" y="162">7</text>
    <text class="matrix" x="256" y="180">D</text>
    <text class="matrix" x="256" y="198">Z</text>
    <text class="matrix" x="256" y="216">*</text>
    <text class="matrix" x="256" y="234">2</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="4.35s" repeatCount="indefinite" begin="-2.2s" />
    </g>
    <g>
    <text class="matrix" x="288" y="0">X</text>
    <text class="matrix" x="288" y="18">7</text>
    <text class="matrix" x="288" y="36">B</text>
    <text class="matrix" x="288" y="54">*</text>
    <text class="matrix" x="288" y="72">#</text>
    <text class="matrix" x="288" y="90">0</text>
    <text class="matrix" x="288" y="108">0</text>
    <text class="matrix" x="288" y="126">#</text>
    <text class="matrix" x="288" y="144">E</text>
    <text class="matrix" x="288" y="162">Y</text>
    <text class="matrix" x="288" y="180">Y</text>
    <text class="matrix" x="288" y="198">C</text>
    <text class="matrix" x="288" y="216">5</text>
    <text class="matrix" x="288" y="234">*</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.95s" repeatCount="indefinite" begin="-0.39s" />
    </g>
    <g>
    <text class="matrix" x="320" y="0">8</text>
    <text class="matrix" x="320" y="18">9</text>
    <text class="matrix" x="320" y="36">1</text>
    <text class="matrix" x="320" y="54">6</text>
    <text class="matrix" x="320" y="72">X</text>
    <text class="matrix" x="320" y="90">7</text>
    <text class="matrix" x="320" y="108">9</text>
    <text class="matrix" x="320" y="126">Z</text>
    <text class="matrix" x="320" y="144">Z</text>
    <text class="matrix" x="320" y="162">C</text>
    <text class="matrix" x="320" y="180">C</text>
    <text class="matrix" x="320" y="198">0</text>
    <text class="matrix" x="320" y="216">D</text>
    <text class="matrix" x="320" y="234">B</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="5.19s" repeatCount="indefinite" begin="-1.1s" />
    </g>
    <g>
    <text class="matrix" x="352" y="0">7</text>
    <text class="matrix" x="352" y="18">#</text>
    <text class="matrix" x="352" y="36">Z</text>
    <text class="matrix" x="352" y="54">*</text>
    <text class="matrix" x="352" y="72">5</text>
    <text class="matrix" x="352" y="90">0</text>
    <text class="matrix" x="352" y="108">Y</text>
    <text class="matrix" x="352" y="126">@</text>
    <text class="matrix" x="352" y="144">*</text>
    <text class="matrix" x="352" y="162">%</text>
    <text class="matrix" x="352" y="180">F</text>
    <text class="matrix" x="352" y="198">6</text>
    <text class="matrix" x="352" y="216">4</text>
    <text class="matrix" x="352" y="234">%</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="7.5s" repeatCount="indefinite" begin="-1.42s" />
    </g>
    <g>
    <text class="matrix" x="384" y="0">C</text>
    <text class="matrix" x="384" y="18">%</text>
    <text class="matrix" x="384" y="36">Y</text>
    <text class="matrix" x="384" y="54">7</text>
    <text class="matrix" x="384" y="72">D</text>
    <text class="matrix" x="384" y="90">6</text>
    <text class="matrix" x="384" y="108">Z</text>
    <text class="matrix" x="384" y="126">#</text>
    <text class="matrix" x="384" y="144">2</text>
    <text class="matrix" x="384" y="162">A</text>
    <text class="matrix" x="384" y="180">6</text>
    <text class="matrix" x="384" y="198">@</text>
    <text class="matrix" x="384" y="216">#</text>
    <text class="matrix" x="384" y="234">Z</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="4.71s" repeatCount="indefinite" begin="-1.29s" />
    </g>
    <g>
    <text class="matrix" x="416" y="0">7</text>
    <text class="matrix" x="416" y="18">0</text>
    <text class="matrix" x="416" y="36">5</text>
    <text class="matrix" x="416" y="54">7</text>
    <text class="matrix" x="416" y="72">8</text>
    <text class="matrix" x="416" y="90">3</text>
    <text class="matrix" x="416" y="108">#</text>
    <text class="matrix" x="416" y="126">1</text>
    <text class="matrix" x="416" y="144">Z</text>
    <text class="matrix" x="416" y="162">%</text>
    <text class="matrix" x="416" y="180">8</text>
    <text class="matrix" x="416" y="198">Y</text>
    <text class="matrix" x="416" y="216">Y</text>
    <text class="matrix" x="416" y="234">3</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.22s" repeatCount="indefinite" begin="-2.04s" />
    </g>
    <g>
    <text class="matrix" x="448" y="0">A</text>
    <text class="matrix" x="448" y="18">5</text>
    <text class="matrix" x="448" y="36">3</text>
    <text class="matrix" x="448" y="54">@</text>
    <text class="matrix" x="448" y="72">0</text>
    <text class="matrix" x="448" y="90">9</text>
    <text class="matrix" x="448" y="108">1</text>
    <text class="matrix" x="448" y="126">Y</text>
    <text class="matrix" x="448" y="144">8</text>
    <text class="matrix" x="448" y="162">B</text>
    <text class="matrix" x="448" y="180">F</text>
    <text class="matrix" x="448" y="198">F</text>
    <text class="matrix" x="448" y="216">6</text>
    <text class="matrix" x="448" y="234">#</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.13s" repeatCount="indefinite" begin="-0.06s" />
    </g>
    <g>
    <text class="matrix" x="480" y="0">A</text>
    <text class="matrix" x="480" y="18">X</text>
    <text class="matrix" x="480" y="36">A</text>
    <text class="matrix" x="480" y="54">8</text>
    <text class="matrix" x="480" y="72">5</text>
    <text class="matrix" x="480" y="90">2</text>
    <text class="matrix" x="480" y="108">B</text>
    <text class="matrix" x="480" y="126">Z</text>
    <text class="matrix" x="480" y="144">3</text>
    <text class="matrix" x="480" y="162">F</text>
    <text class="matrix" x="480" y="180">*</text>
    <text class="matrix" x="480" y="198">A</text>
    <text class="matrix" x="480" y="216">#</text>
    <text class="matrix" x="480" y="234">B</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="7.68s" repeatCount="indefinite" begin="-0.51s" />
    </g>
    <g>
    <text class="matrix" x="512" y="0">5</text>
    <text class="matrix" x="512" y="18">@</text>
    <text class="matrix" x="512" y="36">B</text>
    <text class="matrix" x="512" y="54">0</text>
    <text class="matrix" x="512" y="72">1</text>
    <text class="matrix" x="512" y="90">4</text>
    <text class="matrix" x="512" y="108">C</text>
    <text class="matrix" x="512" y="126">2</text>
    <text class="matrix" x="512" y="144">8</text>
    <text class="matrix" x="512" y="162">@</text>
    <text class="matrix" x="512" y="180">*</text>
    <text class="matrix" x="512" y="198">8</text>
    <text class="matrix" x="512" y="216">#</text>
    <text class="matrix" x="512" y="234">3</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.41s" repeatCount="indefinite" begin="-2.86s" />
    </g>
    <g>
    <text class="matrix" x="544" y="0">F</text>
    <text class="matrix" x="544" y="18">A</text>
    <text class="matrix" x="544" y="36">*</text>
    <text class="matrix" x="544" y="54">3</text>
    <text class="matrix" x="544" y="72">D</text>
    <text class="matrix" x="544" y="90">9</text>
    <text class="matrix" x="544" y="108">%</text>
    <text class="matrix" x="544" y="126">7</text>
    <text class="matrix" x="544" y="144">D</text>
    <text class="matrix" x="544" y="162">E</text>
    <text class="matrix" x="544" y="180">E</text>
    <text class="matrix" x="544" y="198">@</text>
    <text class="matrix" x="544" y="216">#</text>
    <text class="matrix" x="544" y="234">X</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="7.85s" repeatCount="indefinite" begin="-1.58s" />
    </g>
    <g>
    <text class="matrix" x="576" y="0">A</text>
    <text class="matrix" x="576" y="18">7</text>
    <text class="matrix" x="576" y="36">Y</text>
    <text class="matrix" x="576" y="54">9</text>
    <text class="matrix" x="576" y="72">B</text>
    <text class="matrix" x="576" y="90">X</text>
    <text class="matrix" x="576" y="108">4</text>
    <text class="matrix" x="576" y="126">Y</text>
    <text class="matrix" x="576" y="144">D</text>
    <text class="matrix" x="576" y="162">9</text>
    <text class="matrix" x="576" y="180">#</text>
    <text class="matrix" x="576" y="198">7</text>
    <text class="matrix" x="576" y="216">6</text>
    <text class="matrix" x="576" y="234">0</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="4.49s" repeatCount="indefinite" begin="-1.5s" />
    </g>
    <g>
    <text class="matrix" x="608" y="0">C</text>
    <text class="matrix" x="608" y="18">4</text>
    <text class="matrix" x="608" y="36">1</text>
    <text class="matrix" x="608" y="54">5</text>
    <text class="matrix" x="608" y="72">2</text>
    <text class="matrix" x="608" y="90">*</text>
    <text class="matrix" x="608" y="108">9</text>
    <text class="matrix" x="608" y="126">8</text>
    <text class="matrix" x="608" y="144">Z</text>
    <text class="matrix" x="608" y="162">1</text>
    <text class="matrix" x="608" y="180">*</text>
    <text class="matrix" x="608" y="198">%</text>
    <text class="matrix" x="608" y="216">@</text>
    <text class="matrix" x="608" y="234">%</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="7.32s" repeatCount="indefinite" begin="-0.49s" />
    </g>
    <g>
    <text class="matrix" x="640" y="0">5</text>
    <text class="matrix" x="640" y="18">C</text>
    <text class="matrix" x="640" y="36">8</text>
    <text class="matrix" x="640" y="54">9</text>
    <text class="matrix" x="640" y="72">3</text>
    <text class="matrix" x="640" y="90">2</text>
    <text class="matrix" x="640" y="108">C</text>
    <text class="matrix" x="640" y="126">0</text>
    <text class="matrix" x="640" y="144">#</text>
    <text class="matrix" x="640" y="162">%</text>
    <text class="matrix" x="640" y="180">Y</text>
    <text class="matrix" x="640" y="198">F</text>
    <text class="matrix" x="640" y="216">F</text>
    <text class="matrix" x="640" y="234">9</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="5.58s" repeatCount="indefinite" begin="-1.91s" />
    </g>
    <g>
    <text class="matrix" x="672" y="0">%</text>
    <text class="matrix" x="672" y="18">4</text>
    <text class="matrix" x="672" y="36">C</text>
    <text class="matrix" x="672" y="54">9</text>
    <text class="matrix" x="672" y="72">@</text>
    <text class="matrix" x="672" y="90">C</text>
    <text class="matrix" x="672" y="108">Y</text>
    <text class="matrix" x="672" y="126">9</text>
    <text class="matrix" x="672" y="144">D</text>
    <text class="matrix" x="672" y="162">1</text>
    <text class="matrix" x="672" y="180">6</text>
    <text class="matrix" x="672" y="198">E</text>
    <text class="matrix" x="672" y="216">C</text>
    <text class="matrix" x="672" y="234">0</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="8.11s" repeatCount="indefinite" begin="-0.82s" />
    </g>
    <g>
    <text class="matrix" x="704" y="0">9</text>
    <text class="matrix" x="704" y="18">3</text>
    <text class="matrix" x="704" y="36">7</text>
    <text class="matrix" x="704" y="54">6</text>
    <text class="matrix" x="704" y="72">1</text>
    <text class="matrix" x="704" y="90">0</text>
    <text class="matrix" x="704" y="108">3</text>
    <text class="matrix" x="704" y="126">B</text>
    <text class="matrix" x="704" y="144">E</text>
    <text class="matrix" x="704" y="162">9</text>
    <text class="matrix" x="704" y="180">Z</text>
    <text class="matrix" x="704" y="198">9</text>
    <text class="matrix" x="704" y="216">#</text>
    <text class="matrix" x="704" y="234">8</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.03s" repeatCount="indefinite" begin="-2.85s" />
    </g>
    <g>
    <text class="matrix" x="736" y="0">7</text>
    <text class="matrix" x="736" y="18">0</text>
    <text class="matrix" x="736" y="36">7</text>
    <text class="matrix" x="736" y="54">%</text>
    <text class="matrix" x="736" y="72">0</text>
    <text class="matrix" x="736" y="90">6</text>
    <text class="matrix" x="736" y="108">9</text>
    <text class="matrix" x="736" y="126">8</text>
    <text class="matrix" x="736" y="144">2</text>
    <text class="matrix" x="736" y="162">#</text>
    <text class="matrix" x="736" y="180">D</text>
    <text class="matrix" x="736" y="198">6</text>
    <text class="matrix" x="736" y="216">4</text>
    <text class="matrix" x="736" y="234">C</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.93s" repeatCount="indefinite" begin="-1.03s" />
    </g>
    <g>
    <text class="matrix" x="768" y="0">5</text>
    <text class="matrix" x="768" y="18">7</text>
    <text class="matrix" x="768" y="36">3</text>
    <text class="matrix" x="768" y="54">D</text>
    <text class="matrix" x="768" y="72">B</text>
    <text class="matrix" x="768" y="90">7</text>
    <text class="matrix" x="768" y="108">A</text>
    <text class="matrix" x="768" y="126">4</text>
    <text class="matrix" x="768" y="144">9</text>
    <text class="matrix" x="768" y="162">0</text>
    <text class="matrix" x="768" y="180">8</text>
    <text class="matrix" x="768" y="198">8</text>
    <text class="matrix" x="768" y="216">Z</text>
    <text class="matrix" x="768" y="234">9</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.76s" repeatCount="indefinite" begin="-1.45s" />
    </g>
    <g>
    <text class="matrix" x="800" y="0">9</text>
    <text class="matrix" x="800" y="18">C</text>
    <text class="matrix" x="800" y="36">2</text>
    <text class="matrix" x="800" y="54">%</text>
    <text class="matrix" x="800" y="72">5</text>
    <text class="matrix" x="800" y="90">#</text>
    <text class="matrix" x="800" y="108">4</text>
    <text class="matrix" x="800" y="126">Y</text>
    <text class="matrix" x="800" y="144">5</text>
    <text class="matrix" x="800" y="162">5</text>
    <text class="matrix" x="800" y="180">E</text>
    <text class="matrix" x="800" y="198">Z</text>
    <text class="matrix" x="800" y="216">8</text>
    <text class="matrix" x="800" y="234">Y</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="7.02s" repeatCount="indefinite" begin="-1.75s" />
    </g>
    <g>
    <text class="matrix" x="832" y="0">#</text>
    <text class="matrix" x="832" y="18">Z</text>
    <text class="matrix" x="832" y="36">1</text>
    <text class="matrix" x="832" y="54">6</text>
    <text class="matrix" x="832" y="72">5</text>
    <text class="matrix" x="832" y="90">F</text>
    <text class="matrix" x="832" y="108">#</text>
    <text class="matrix" x="832" y="126">#</text>
    <text class="matrix" x="832" y="144">1</text>
    <text class="matrix" x="832" y="162">X</text>
    <text class="matrix" x="832" y="180">X</text>
    <text class="matrix" x="832" y="198">7</text>
    <text class="matrix" x="832" y="216">C</text>
    <text class="matrix" x="832" y="234">9</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="4.74s" repeatCount="indefinite" begin="-0.43s" />
    </g>
    <g>
    <text class="matrix" x="864" y="0">B</text>
    <text class="matrix" x="864" y="18">9</text>
    <text class="matrix" x="864" y="36">7</text>
    <text class="matrix" x="864" y="54">7</text>
    <text class="matrix" x="864" y="72">8</text>
    <text class="matrix" x="864" y="90">B</text>
    <text class="matrix" x="864" y="108">1</text>
    <text class="matrix" x="864" y="126">Y</text>
    <text class="matrix" x="864" y="144">7</text>
    <text class="matrix" x="864" y="162">2</text>
    <text class="matrix" x="864" y="180">C</text>
    <text class="matrix" x="864" y="198">X</text>
    <text class="matrix" x="864" y="216">F</text>
    <text class="matrix" x="864" y="234">7</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.91s" repeatCount="indefinite" begin="-0.01s" />
    </g>
    <g>
    <text class="matrix" x="896" y="0">8</text>
    <text class="matrix" x="896" y="18">0</text>
    <text class="matrix" x="896" y="36">A</text>
    <text class="matrix" x="896" y="54">D</text>
    <text class="matrix" x="896" y="72">D</text>
    <text class="matrix" x="896" y="90">4</text>
    <text class="matrix" x="896" y="108">E</text>
    <text class="matrix" x="896" y="126">4</text>
    <text class="matrix" x="896" y="144">Z</text>
    <text class="matrix" x="896" y="162">5</text>
    <text class="matrix" x="896" y="180">C</text>
    <text class="matrix" x="896" y="198">7</text>
    <text class="matrix" x="896" y="216">C</text>
    <text class="matrix" x="896" y="234">D</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="4.54s" repeatCount="indefinite" begin="-1.41s" />
    </g>
    <g>
    <text class="matrix" x="928" y="0">D</text>
    <text class="matrix" x="928" y="18">2</text>
    <text class="matrix" x="928" y="36">0</text>
    <text class="matrix" x="928" y="54">7</text>
    <text class="matrix" x="928" y="72">6</text>
    <text class="matrix" x="928" y="90">3</text>
    <text class="matrix" x="928" y="108">6</text>
    <text class="matrix" x="928" y="126">A</text>
    <text class="matrix" x="928" y="144">B</text>
    <text class="matrix" x="928" y="162">0</text>
    <text class="matrix" x="928" y="180">0</text>
    <text class="matrix" x="928" y="198">Y</text>
    <text class="matrix" x="928" y="216">2</text>
    <text class="matrix" x="928" y="234">X</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="5.85s" repeatCount="indefinite" begin="-1.19s" />
    </g>
    <g>
    <text class="matrix" x="960" y="0">B</text>
    <text class="matrix" x="960" y="18">#</text>
    <text class="matrix" x="960" y="36">2</text>
    <text class="matrix" x="960" y="54">#</text>
    <text class="matrix" x="960" y="72">5</text>
    <text class="matrix" x="960" y="90">8</text>
    <text class="matrix" x="960" y="108">1</text>
    <text class="matrix" x="960" y="126">Z</text>
    <text class="matrix" x="960" y="144">7</text>
    <text class="matrix" x="960" y="162">X</text>
    <text class="matrix" x="960" y="180">7</text>
    <text class="matrix" x="960" y="198">Z</text>
    <text class="matrix" x="960" y="216">7</text>
    <text class="matrix" x="960" y="234">8</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="7.59s" repeatCount="indefinite" begin="-0.6s" />
    </g>
    <g>
    <text class="matrix" x="992" y="0">C</text>
    <text class="matrix" x="992" y="18">8</text>
    <text class="matrix" x="992" y="36">7</text>
    <text class="matrix" x="992" y="54">0</text>
    <text class="matrix" x="992" y="72">X</text>
    <text class="matrix" x="992" y="90">2</text>
    <text class="matrix" x="992" y="108">B</text>
    <text class="matrix" x="992" y="126">X</text>
    <text class="matrix" x="992" y="144">B</text>
    <text class="matrix" x="992" y="162">9</text>
    <text class="matrix" x="992" y="180">0</text>
    <text class="matrix" x="992" y="198">3</text>
    <text class="matrix" x="992" y="216">X</text>
    <text class="matrix" x="992" y="234">8</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="4.91s" repeatCount="indefinite" begin="-2.68s" />
    </g>
    <g>
    <text class="matrix" x="1024" y="0">Z</text>
    <text class="matrix" x="1024" y="18">0</text>
    <text class="matrix" x="1024" y="36">5</text>
    <text class="matrix" x="1024" y="54">9</text>
    <text class="matrix" x="1024" y="72">Z</text>
    <text class="matrix" x="1024" y="90">8</text>
    <text class="matrix" x="1024" y="108">7</text>
    <text class="matrix" x="1024" y="126">F</text>
    <text class="matrix" x="1024" y="144">X</text>
    <text class="matrix" x="1024" y="162">@</text>
    <text class="matrix" x="1024" y="180">*</text>
    <text class="matrix" x="1024" y="198">Z</text>
    <text class="matrix" x="1024" y="216">7</text>
    <text class="matrix" x="1024" y="234">*</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="7.18s" repeatCount="indefinite" begin="-2.83s" />
    </g>
    <g>
    <text class="matrix" x="1056" y="0">9</text>
    <text class="matrix" x="1056" y="18">9</text>
    <text class="matrix" x="1056" y="36">0</text>
    <text class="matrix" x="1056" y="54">F</text>
    <text class="matrix" x="1056" y="72">#</text>
    <text class="matrix" x="1056" y="90">%</text>
    <text class="matrix" x="1056" y="108">*</text>
    <text class="matrix" x="1056" y="126">Z</text>
    <text class="matrix" x="1056" y="144">2</text>
    <text class="matrix" x="1056" y="162">9</text>
    <text class="matrix" x="1056" y="180">B</text>
    <text class="matrix" x="1056" y="198">4</text>
    <text class="matrix" x="1056" y="216">8</text>
    <text class="matrix" x="1056" y="234">C</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="4.33s" repeatCount="indefinite" begin="-2.45s" />
    </g>
    <g>
    <text class="matrix" x="1088" y="0">E</text>
    <text class="matrix" x="1088" y="18">8</text>
    <text class="matrix" x="1088" y="36">E</text>
    <text class="matrix" x="1088" y="54">1</text>
    <text class="matrix" x="1088" y="72">8</text>
    <text class="matrix" x="1088" y="90">7</text>
    <text class="matrix" x="1088" y="108">5</text>
    <text class="matrix" x="1088" y="126">@</text>
    <text class="matrix" x="1088" y="144">*</text>
    <text class="matrix" x="1088" y="162">9</text>
    <text class="matrix" x="1088" y="180">Y</text>
    <text class="matrix" x="1088" y="198">8</text>
    <text class="matrix" x="1088" y="216">1</text>
    <text class="matrix" x="1088" y="234">A</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="6.43s" repeatCount="indefinite" begin="-2.52s" />
    </g>
    <g>
    <text class="matrix" x="1120" y="0">5</text>
    <text class="matrix" x="1120" y="18">3</text>
    <text class="matrix" x="1120" y="36">@</text>
    <text class="matrix" x="1120" y="54">F</text>
    <text class="matrix" x="1120" y="72">0</text>
    <text class="matrix" x="1120" y="90">D</text>
    <text class="matrix" x="1120" y="108">#</text>
    <text class="matrix" x="1120" y="126">0</text>
    <text class="matrix" x="1120" y="144">8</text>
    <text class="matrix" x="1120" y="162">8</text>
    <text class="matrix" x="1120" y="180">Y</text>
    <text class="matrix" x="1120" y="198">9</text>
    <text class="matrix" x="1120" y="216">8</text>
    <text class="matrix" x="1120" y="234">3</text>
      <animateTransform attributeName="transform" type="translate" from="0 -320" to="0 0" dur="7.76s" repeatCount="indefinite" begin="-0.45s" />
    </g>
  </g>

  <!-- terminal prompt line with blinking cursor created in SVG -->
  <g transform="translate(60,260)">
    <text class="sub">&gt; </text>
    <text class="sub" id="promptText" x="20">Initializing probe · Scanning memory · Correlating signals</text>
    <rect x="520" y="-14" width="10" height="18" class="cursor">
      <animate attributeName="opacity" from="1" to="0" dur="0.8s" repeatCount="indefinite" />
    </rect>
  </g>

  <!-- small subtle neon glow at bottom -->
  <rect x="0" y="300" width="1200" height="20" fill="url(#neonGrad)" opacity="0.06"/>
</svg>

</div>

<!-- compact info under the SVG -->
<div align="center" style="background:#000;padding:10px;border-radius:6px;margin-top:10px;">
<p style="color:#00FF66;font-family: 'Fira Code', monospace;margin:6px 0;"><strong>&gt; Quick Glance</strong> — Python · Bash · Active Directory · Memory Forensics · CTF Writeups</p>
<p style="margin:6px 0;">
<a href="https://github.com/Jery0843"><img src="https://img.shields.io/badge/GitHub-Jery0843-000?style=for-the-badge&logo=github&logoColor=00FF66" alt="github"></a>
<a href="https://jerome.co.in"><img src="https://img.shields.io/badge/Portfolio-jerome.co.in-000?style=for-the-badge&logo=About.me&logoColor=00FF66" alt="portfolio"></a>
<a href="https://linkedin.com/in/jerome-andrew-k-093b2620a"><img src="https://img.shields.io/badge/LinkedIn-Connect-000?style=for-the-badge&logo=linkedin&logoColor=00FF66" alt="linkedin"></a>
</p>
</div>

<!-- small note -->
<p align="center" style="color:#9fffcf;font-family:'Fira Code',monospace;font-size:12px;margin-top:8px;">Made for Jerome Andrew K — copy into <code>Jery0843/Jery0843</code> as <code>README.md</code></p>
