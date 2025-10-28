<!-- ===================================================== -->
<!-- JEROME ANDREW K — TERMINAL MOTION (SVG ANIMATED, NO GIFs) -->
<!-- Ultra-compact. True SVG animations: matrix columns, glowing text, blinking cursor -->
<!-- Copy this file into your repo as README.md -->
<!-- ===================================================== -->

<div align="center">

<!-- SVG Terminal Animation: black background, green matrix columns, neon title, blinking cursor -->
<!-- This uses inline SVG and SMIL animations (widely supported). No GIFs. -->
<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="280" viewBox="0 0 1200 280" preserveAspectRatio="xMidYMid meet" style="max-width:100%;background:#000;border-radius:8px;">
  <defs>
    <linearGradient id="g1" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0%" stop-color="#00ff99" stop-opacity="0.95"/>
      <stop offset="100%" stop-color="#006633" stop-opacity="0.25"/>
    </linearGradient>

    <filter id="neon">
      <feGaussianBlur stdDeviation="3.5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <style type="text/css"><![CDATA[
      .matrixChar { font-family: 'Courier New', monospace; font-size: 16px; fill: #00ff99; opacity: 0.9; }
      .title { font-family: 'Fira Code', monospace; font-size:42px; fill: #00ff99; filter: url(#neon); }
      .subtitle { font-family: 'Fira Code', monospace; font-size:16px; fill:#9affc9; opacity:0.9; }
      .cursor { fill:#00ff99; }
    ]]></style>
  </defs>

  <!-- background -->
  <rect x="0" y="0" width="1200" height="280" fill="#000" />

  <!-- matrix columns: we'll create repeating text elements animated to fall -->
  <!-- columns are spaced every 28px across the width -->
  <!-- each column has several characters that translate down in a loop -->
  <g id="matrix" transform="translate(40,20)">

    <g>
    <text class="matrixChar" x="0" y="0">B</text>
    <text class="matrixChar" x="0" y="20">Y</text>
    <text class="matrixChar" x="0" y="40">F</text>
    <text class="matrixChar" x="0" y="60">4</text>
    <text class="matrixChar" x="0" y="80">2</text>
    <text class="matrixChar" x="0" y="100">4</text>
    <text class="matrixChar" x="0" y="120">F</text>
    <text class="matrixChar" x="0" y="140">2</text>
    <text class="matrixChar" x="0" y="160">8</text>
    <text class="matrixChar" x="0" y="180">C</text>
    <text class="matrixChar" x="0" y="200">1</text>
    <text class="matrixChar" x="0" y="220">A</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="5.62s" repeatCount="indefinite" begin="-1.48s" />
    </g>
    <g>
    <text class="matrixChar" x="32" y="0">X</text>
    <text class="matrixChar" x="32" y="20">5</text>
    <text class="matrixChar" x="32" y="40">E</text>
    <text class="matrixChar" x="32" y="60">3</text>
    <text class="matrixChar" x="32" y="80">X</text>
    <text class="matrixChar" x="32" y="100">4</text>
    <text class="matrixChar" x="32" y="120">C</text>
    <text class="matrixChar" x="32" y="140">8</text>
    <text class="matrixChar" x="32" y="160">6</text>
    <text class="matrixChar" x="32" y="180">5</text>
    <text class="matrixChar" x="32" y="200">3</text>
    <text class="matrixChar" x="32" y="220">A</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.47s" repeatCount="indefinite" begin="-5.77s" />
    </g>
    <g>
    <text class="matrixChar" x="64" y="0">F</text>
    <text class="matrixChar" x="64" y="20">4</text>
    <text class="matrixChar" x="64" y="40">3</text>
    <text class="matrixChar" x="64" y="60">9</text>
    <text class="matrixChar" x="64" y="80">6</text>
    <text class="matrixChar" x="64" y="100">X</text>
    <text class="matrixChar" x="64" y="120">8</text>
    <text class="matrixChar" x="64" y="140">D</text>
    <text class="matrixChar" x="64" y="160">7</text>
    <text class="matrixChar" x="64" y="180">8</text>
    <text class="matrixChar" x="64" y="200">X</text>
    <text class="matrixChar" x="64" y="220">Z</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="4.97s" repeatCount="indefinite" begin="-2.79s" />
    </g>
    <g>
    <text class="matrixChar" x="96" y="0">2</text>
    <text class="matrixChar" x="96" y="20">F</text>
    <text class="matrixChar" x="96" y="40">5</text>
    <text class="matrixChar" x="96" y="60">A</text>
    <text class="matrixChar" x="96" y="80">F</text>
    <text class="matrixChar" x="96" y="100">9</text>
    <text class="matrixChar" x="96" y="120">4</text>
    <text class="matrixChar" x="96" y="140">6</text>
    <text class="matrixChar" x="96" y="160">7</text>
    <text class="matrixChar" x="96" y="180">8</text>
    <text class="matrixChar" x="96" y="200">2</text>
    <text class="matrixChar" x="96" y="220">Z</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="6.76s" repeatCount="indefinite" begin="-1.63s" />
    </g>
    <g>
    <text class="matrixChar" x="128" y="0">8</text>
    <text class="matrixChar" x="128" y="20">6</text>
    <text class="matrixChar" x="128" y="40">E</text>
    <text class="matrixChar" x="128" y="60">X</text>
    <text class="matrixChar" x="128" y="80">0</text>
    <text class="matrixChar" x="128" y="100">7</text>
    <text class="matrixChar" x="128" y="120">9</text>
    <text class="matrixChar" x="128" y="140">E</text>
    <text class="matrixChar" x="128" y="160">9</text>
    <text class="matrixChar" x="128" y="180">E</text>
    <text class="matrixChar" x="128" y="200">C</text>
    <text class="matrixChar" x="128" y="220">Z</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="5.66s" repeatCount="indefinite" begin="-1.47s" />
    </g>
    <g>
    <text class="matrixChar" x="160" y="0">1</text>
    <text class="matrixChar" x="160" y="20">A</text>
    <text class="matrixChar" x="160" y="40">A</text>
    <text class="matrixChar" x="160" y="60">2</text>
    <text class="matrixChar" x="160" y="80">8</text>
    <text class="matrixChar" x="160" y="100">9</text>
    <text class="matrixChar" x="160" y="120">0</text>
    <text class="matrixChar" x="160" y="140">E</text>
    <text class="matrixChar" x="160" y="160">Y</text>
    <text class="matrixChar" x="160" y="180">E</text>
    <text class="matrixChar" x="160" y="200">1</text>
    <text class="matrixChar" x="160" y="220">F</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.12s" repeatCount="indefinite" begin="-1.62s" />
    </g>
    <g>
    <text class="matrixChar" x="192" y="0">F</text>
    <text class="matrixChar" x="192" y="20">7</text>
    <text class="matrixChar" x="192" y="40">B</text>
    <text class="matrixChar" x="192" y="60">Z</text>
    <text class="matrixChar" x="192" y="80">6</text>
    <text class="matrixChar" x="192" y="100">0</text>
    <text class="matrixChar" x="192" y="120">A</text>
    <text class="matrixChar" x="192" y="140">5</text>
    <text class="matrixChar" x="192" y="160">3</text>
    <text class="matrixChar" x="192" y="180">B</text>
    <text class="matrixChar" x="192" y="200">7</text>
    <text class="matrixChar" x="192" y="220">6</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.84s" repeatCount="indefinite" begin="-0.09s" />
    </g>
    <g>
    <text class="matrixChar" x="224" y="0">1</text>
    <text class="matrixChar" x="224" y="20">8</text>
    <text class="matrixChar" x="224" y="40">A</text>
    <text class="matrixChar" x="224" y="60">1</text>
    <text class="matrixChar" x="224" y="80">C</text>
    <text class="matrixChar" x="224" y="100">Y</text>
    <text class="matrixChar" x="224" y="120">Y</text>
    <text class="matrixChar" x="224" y="140">Y</text>
    <text class="matrixChar" x="224" y="160">D</text>
    <text class="matrixChar" x="224" y="180">0</text>
    <text class="matrixChar" x="224" y="200">9</text>
    <text class="matrixChar" x="224" y="220">1</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="5.71s" repeatCount="indefinite" begin="-2.99s" />
    </g>
    <g>
    <text class="matrixChar" x="256" y="0">F</text>
    <text class="matrixChar" x="256" y="20">7</text>
    <text class="matrixChar" x="256" y="40">8</text>
    <text class="matrixChar" x="256" y="60">8</text>
    <text class="matrixChar" x="256" y="80">2</text>
    <text class="matrixChar" x="256" y="100">D</text>
    <text class="matrixChar" x="256" y="120">0</text>
    <text class="matrixChar" x="256" y="140">F</text>
    <text class="matrixChar" x="256" y="160">9</text>
    <text class="matrixChar" x="256" y="180">8</text>
    <text class="matrixChar" x="256" y="200">C</text>
    <text class="matrixChar" x="256" y="220">1</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.28s" repeatCount="indefinite" begin="-5.74s" />
    </g>
    <g>
    <text class="matrixChar" x="288" y="0">6</text>
    <text class="matrixChar" x="288" y="20">8</text>
    <text class="matrixChar" x="288" y="40">Y</text>
    <text class="matrixChar" x="288" y="60">8</text>
    <text class="matrixChar" x="288" y="80">D</text>
    <text class="matrixChar" x="288" y="100">3</text>
    <text class="matrixChar" x="288" y="120">Y</text>
    <text class="matrixChar" x="288" y="140">7</text>
    <text class="matrixChar" x="288" y="160">9</text>
    <text class="matrixChar" x="288" y="180">6</text>
    <text class="matrixChar" x="288" y="200">Y</text>
    <text class="matrixChar" x="288" y="220">Z</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.96s" repeatCount="indefinite" begin="-3.76s" />
    </g>
    <g>
    <text class="matrixChar" x="320" y="0">7</text>
    <text class="matrixChar" x="320" y="20">Y</text>
    <text class="matrixChar" x="320" y="40">X</text>
    <text class="matrixChar" x="320" y="60">7</text>
    <text class="matrixChar" x="320" y="80">X</text>
    <text class="matrixChar" x="320" y="100">8</text>
    <text class="matrixChar" x="320" y="120">A</text>
    <text class="matrixChar" x="320" y="140">C</text>
    <text class="matrixChar" x="320" y="160">2</text>
    <text class="matrixChar" x="320" y="180">8</text>
    <text class="matrixChar" x="320" y="200">7</text>
    <text class="matrixChar" x="320" y="220">7</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.67s" repeatCount="indefinite" begin="-4.07s" />
    </g>
    <g>
    <text class="matrixChar" x="352" y="0">9</text>
    <text class="matrixChar" x="352" y="20">7</text>
    <text class="matrixChar" x="352" y="40">9</text>
    <text class="matrixChar" x="352" y="60">6</text>
    <text class="matrixChar" x="352" y="80">9</text>
    <text class="matrixChar" x="352" y="100">A</text>
    <text class="matrixChar" x="352" y="120">4</text>
    <text class="matrixChar" x="352" y="140">C</text>
    <text class="matrixChar" x="352" y="160">3</text>
    <text class="matrixChar" x="352" y="180">8</text>
    <text class="matrixChar" x="352" y="200">5</text>
    <text class="matrixChar" x="352" y="220">E</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.09s" repeatCount="indefinite" begin="-5.97s" />
    </g>
    <g>
    <text class="matrixChar" x="384" y="0">C</text>
    <text class="matrixChar" x="384" y="20">1</text>
    <text class="matrixChar" x="384" y="40">9</text>
    <text class="matrixChar" x="384" y="60">0</text>
    <text class="matrixChar" x="384" y="80">4</text>
    <text class="matrixChar" x="384" y="100">Y</text>
    <text class="matrixChar" x="384" y="120">7</text>
    <text class="matrixChar" x="384" y="140">B</text>
    <text class="matrixChar" x="384" y="160">Y</text>
    <text class="matrixChar" x="384" y="180">2</text>
    <text class="matrixChar" x="384" y="200">4</text>
    <text class="matrixChar" x="384" y="220">2</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.76s" repeatCount="indefinite" begin="-2.48s" />
    </g>
    <g>
    <text class="matrixChar" x="416" y="0">B</text>
    <text class="matrixChar" x="416" y="20">9</text>
    <text class="matrixChar" x="416" y="40">6</text>
    <text class="matrixChar" x="416" y="60">C</text>
    <text class="matrixChar" x="416" y="80">D</text>
    <text class="matrixChar" x="416" y="100">D</text>
    <text class="matrixChar" x="416" y="120">1</text>
    <text class="matrixChar" x="416" y="140">C</text>
    <text class="matrixChar" x="416" y="160">F</text>
    <text class="matrixChar" x="416" y="180">9</text>
    <text class="matrixChar" x="416" y="200">Y</text>
    <text class="matrixChar" x="416" y="220">Z</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.58s" repeatCount="indefinite" begin="-5.1s" />
    </g>
    <g>
    <text class="matrixChar" x="448" y="0">8</text>
    <text class="matrixChar" x="448" y="20">7</text>
    <text class="matrixChar" x="448" y="40">6</text>
    <text class="matrixChar" x="448" y="60">0</text>
    <text class="matrixChar" x="448" y="80">F</text>
    <text class="matrixChar" x="448" y="100">1</text>
    <text class="matrixChar" x="448" y="120">E</text>
    <text class="matrixChar" x="448" y="140">0</text>
    <text class="matrixChar" x="448" y="160">3</text>
    <text class="matrixChar" x="448" y="180">D</text>
    <text class="matrixChar" x="448" y="200">X</text>
    <text class="matrixChar" x="448" y="220">8</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.73s" repeatCount="indefinite" begin="-2.36s" />
    </g>
    <g>
    <text class="matrixChar" x="480" y="0">9</text>
    <text class="matrixChar" x="480" y="20">7</text>
    <text class="matrixChar" x="480" y="40">F</text>
    <text class="matrixChar" x="480" y="60">A</text>
    <text class="matrixChar" x="480" y="80">4</text>
    <text class="matrixChar" x="480" y="100">1</text>
    <text class="matrixChar" x="480" y="120">5</text>
    <text class="matrixChar" x="480" y="140">A</text>
    <text class="matrixChar" x="480" y="160">Z</text>
    <text class="matrixChar" x="480" y="180">B</text>
    <text class="matrixChar" x="480" y="200">A</text>
    <text class="matrixChar" x="480" y="220">D</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="5.05s" repeatCount="indefinite" begin="-5.54s" />
    </g>
    <g>
    <text class="matrixChar" x="512" y="0">5</text>
    <text class="matrixChar" x="512" y="20">6</text>
    <text class="matrixChar" x="512" y="40">Y</text>
    <text class="matrixChar" x="512" y="60">5</text>
    <text class="matrixChar" x="512" y="80">9</text>
    <text class="matrixChar" x="512" y="100">B</text>
    <text class="matrixChar" x="512" y="120">7</text>
    <text class="matrixChar" x="512" y="140">6</text>
    <text class="matrixChar" x="512" y="160">6</text>
    <text class="matrixChar" x="512" y="180">A</text>
    <text class="matrixChar" x="512" y="200">4</text>
    <text class="matrixChar" x="512" y="220">3</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.65s" repeatCount="indefinite" begin="-4.84s" />
    </g>
    <g>
    <text class="matrixChar" x="544" y="0">6</text>
    <text class="matrixChar" x="544" y="20">6</text>
    <text class="matrixChar" x="544" y="40">Z</text>
    <text class="matrixChar" x="544" y="60">3</text>
    <text class="matrixChar" x="544" y="80">2</text>
    <text class="matrixChar" x="544" y="100">8</text>
    <text class="matrixChar" x="544" y="120">Y</text>
    <text class="matrixChar" x="544" y="140">9</text>
    <text class="matrixChar" x="544" y="160">5</text>
    <text class="matrixChar" x="544" y="180">9</text>
    <text class="matrixChar" x="544" y="200">7</text>
    <text class="matrixChar" x="544" y="220">8</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.47s" repeatCount="indefinite" begin="-0.45s" />
    </g>
    <g>
    <text class="matrixChar" x="576" y="0">B</text>
    <text class="matrixChar" x="576" y="20">0</text>
    <text class="matrixChar" x="576" y="40">C</text>
    <text class="matrixChar" x="576" y="60">0</text>
    <text class="matrixChar" x="576" y="80">7</text>
    <text class="matrixChar" x="576" y="100">9</text>
    <text class="matrixChar" x="576" y="120">8</text>
    <text class="matrixChar" x="576" y="140">D</text>
    <text class="matrixChar" x="576" y="160">E</text>
    <text class="matrixChar" x="576" y="180">4</text>
    <text class="matrixChar" x="576" y="200">9</text>
    <text class="matrixChar" x="576" y="220">2</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="5.37s" repeatCount="indefinite" begin="-0.11s" />
    </g>
    <g>
    <text class="matrixChar" x="608" y="0">X</text>
    <text class="matrixChar" x="608" y="20">1</text>
    <text class="matrixChar" x="608" y="40">4</text>
    <text class="matrixChar" x="608" y="60">A</text>
    <text class="matrixChar" x="608" y="80">0</text>
    <text class="matrixChar" x="608" y="100">2</text>
    <text class="matrixChar" x="608" y="120">X</text>
    <text class="matrixChar" x="608" y="140">3</text>
    <text class="matrixChar" x="608" y="160">3</text>
    <text class="matrixChar" x="608" y="180">7</text>
    <text class="matrixChar" x="608" y="200">F</text>
    <text class="matrixChar" x="608" y="220">0</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="5.54s" repeatCount="indefinite" begin="-0.44s" />
    </g>
    <g>
    <text class="matrixChar" x="640" y="0">4</text>
    <text class="matrixChar" x="640" y="20">9</text>
    <text class="matrixChar" x="640" y="40">Y</text>
    <text class="matrixChar" x="640" y="60">6</text>
    <text class="matrixChar" x="640" y="80">4</text>
    <text class="matrixChar" x="640" y="100">0</text>
    <text class="matrixChar" x="640" y="120">6</text>
    <text class="matrixChar" x="640" y="140">2</text>
    <text class="matrixChar" x="640" y="160">9</text>
    <text class="matrixChar" x="640" y="180">D</text>
    <text class="matrixChar" x="640" y="200">0</text>
    <text class="matrixChar" x="640" y="220">7</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="5.43s" repeatCount="indefinite" begin="-0.66s" />
    </g>
    <g>
    <text class="matrixChar" x="672" y="0">Z</text>
    <text class="matrixChar" x="672" y="20">2</text>
    <text class="matrixChar" x="672" y="40">F</text>
    <text class="matrixChar" x="672" y="60">E</text>
    <text class="matrixChar" x="672" y="80">9</text>
    <text class="matrixChar" x="672" y="100">Y</text>
    <text class="matrixChar" x="672" y="120">Z</text>
    <text class="matrixChar" x="672" y="140">B</text>
    <text class="matrixChar" x="672" y="160">C</text>
    <text class="matrixChar" x="672" y="180">A</text>
    <text class="matrixChar" x="672" y="200">9</text>
    <text class="matrixChar" x="672" y="220">D</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="4.65s" repeatCount="indefinite" begin="-4.31s" />
    </g>
    <g>
    <text class="matrixChar" x="704" y="0">0</text>
    <text class="matrixChar" x="704" y="20">0</text>
    <text class="matrixChar" x="704" y="40">0</text>
    <text class="matrixChar" x="704" y="60">F</text>
    <text class="matrixChar" x="704" y="80">X</text>
    <text class="matrixChar" x="704" y="100">8</text>
    <text class="matrixChar" x="704" y="120">7</text>
    <text class="matrixChar" x="704" y="140">8</text>
    <text class="matrixChar" x="704" y="160">A</text>
    <text class="matrixChar" x="704" y="180">1</text>
    <text class="matrixChar" x="704" y="200">9</text>
    <text class="matrixChar" x="704" y="220">C</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.68s" repeatCount="indefinite" begin="-5.41s" />
    </g>
    <g>
    <text class="matrixChar" x="736" y="0">8</text>
    <text class="matrixChar" x="736" y="20">7</text>
    <text class="matrixChar" x="736" y="40">2</text>
    <text class="matrixChar" x="736" y="60">5</text>
    <text class="matrixChar" x="736" y="80">8</text>
    <text class="matrixChar" x="736" y="100">9</text>
    <text class="matrixChar" x="736" y="120">D</text>
    <text class="matrixChar" x="736" y="140">B</text>
    <text class="matrixChar" x="736" y="160">6</text>
    <text class="matrixChar" x="736" y="180">X</text>
    <text class="matrixChar" x="736" y="200">F</text>
    <text class="matrixChar" x="736" y="220">9</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="6.57s" repeatCount="indefinite" begin="-0.53s" />
    </g>
    <g>
    <text class="matrixChar" x="768" y="0">7</text>
    <text class="matrixChar" x="768" y="20">1</text>
    <text class="matrixChar" x="768" y="40">0</text>
    <text class="matrixChar" x="768" y="60">5</text>
    <text class="matrixChar" x="768" y="80">B</text>
    <text class="matrixChar" x="768" y="100">6</text>
    <text class="matrixChar" x="768" y="120">E</text>
    <text class="matrixChar" x="768" y="140">A</text>
    <text class="matrixChar" x="768" y="160">2</text>
    <text class="matrixChar" x="768" y="180">7</text>
    <text class="matrixChar" x="768" y="200">8</text>
    <text class="matrixChar" x="768" y="220">Y</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.23s" repeatCount="indefinite" begin="-3.28s" />
    </g>
    <g>
    <text class="matrixChar" x="800" y="0">9</text>
    <text class="matrixChar" x="800" y="20">8</text>
    <text class="matrixChar" x="800" y="40">C</text>
    <text class="matrixChar" x="800" y="60">Y</text>
    <text class="matrixChar" x="800" y="80">0</text>
    <text class="matrixChar" x="800" y="100">6</text>
    <text class="matrixChar" x="800" y="120">8</text>
    <text class="matrixChar" x="800" y="140">F</text>
    <text class="matrixChar" x="800" y="160">9</text>
    <text class="matrixChar" x="800" y="180">Z</text>
    <text class="matrixChar" x="800" y="200">9</text>
    <text class="matrixChar" x="800" y="220">E</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="6.29s" repeatCount="indefinite" begin="-3.72s" />
    </g>
    <g>
    <text class="matrixChar" x="832" y="0">9</text>
    <text class="matrixChar" x="832" y="20">Z</text>
    <text class="matrixChar" x="832" y="40">4</text>
    <text class="matrixChar" x="832" y="60">B</text>
    <text class="matrixChar" x="832" y="80">D</text>
    <text class="matrixChar" x="832" y="100">7</text>
    <text class="matrixChar" x="832" y="120">Z</text>
    <text class="matrixChar" x="832" y="140">0</text>
    <text class="matrixChar" x="832" y="160">D</text>
    <text class="matrixChar" x="832" y="180">8</text>
    <text class="matrixChar" x="832" y="200">Y</text>
    <text class="matrixChar" x="832" y="220">Y</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.8s" repeatCount="indefinite" begin="-2.61s" />
    </g>
    <g>
    <text class="matrixChar" x="864" y="0">X</text>
    <text class="matrixChar" x="864" y="20">8</text>
    <text class="matrixChar" x="864" y="40">2</text>
    <text class="matrixChar" x="864" y="60">Z</text>
    <text class="matrixChar" x="864" y="80">A</text>
    <text class="matrixChar" x="864" y="100">8</text>
    <text class="matrixChar" x="864" y="120">7</text>
    <text class="matrixChar" x="864" y="140">8</text>
    <text class="matrixChar" x="864" y="160">1</text>
    <text class="matrixChar" x="864" y="180">A</text>
    <text class="matrixChar" x="864" y="200">Y</text>
    <text class="matrixChar" x="864" y="220">C</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="6.11s" repeatCount="indefinite" begin="-5.38s" />
    </g>
    <g>
    <text class="matrixChar" x="896" y="0">B</text>
    <text class="matrixChar" x="896" y="20">B</text>
    <text class="matrixChar" x="896" y="40">0</text>
    <text class="matrixChar" x="896" y="60">1</text>
    <text class="matrixChar" x="896" y="80">1</text>
    <text class="matrixChar" x="896" y="100">0</text>
    <text class="matrixChar" x="896" y="120">0</text>
    <text class="matrixChar" x="896" y="140">1</text>
    <text class="matrixChar" x="896" y="160">A</text>
    <text class="matrixChar" x="896" y="180">8</text>
    <text class="matrixChar" x="896" y="200">7</text>
    <text class="matrixChar" x="896" y="220">7</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.51s" repeatCount="indefinite" begin="-3.31s" />
    </g>
    <g>
    <text class="matrixChar" x="928" y="0">7</text>
    <text class="matrixChar" x="928" y="20">C</text>
    <text class="matrixChar" x="928" y="40">3</text>
    <text class="matrixChar" x="928" y="60">5</text>
    <text class="matrixChar" x="928" y="80">8</text>
    <text class="matrixChar" x="928" y="100">A</text>
    <text class="matrixChar" x="928" y="120">E</text>
    <text class="matrixChar" x="928" y="140">Y</text>
    <text class="matrixChar" x="928" y="160">7</text>
    <text class="matrixChar" x="928" y="180">X</text>
    <text class="matrixChar" x="928" y="200">X</text>
    <text class="matrixChar" x="928" y="220">C</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.03s" repeatCount="indefinite" begin="-4.89s" />
    </g>
    <g>
    <text class="matrixChar" x="960" y="0">D</text>
    <text class="matrixChar" x="960" y="20">9</text>
    <text class="matrixChar" x="960" y="40">C</text>
    <text class="matrixChar" x="960" y="60">4</text>
    <text class="matrixChar" x="960" y="80">8</text>
    <text class="matrixChar" x="960" y="100">E</text>
    <text class="matrixChar" x="960" y="120">3</text>
    <text class="matrixChar" x="960" y="140">D</text>
    <text class="matrixChar" x="960" y="160">0</text>
    <text class="matrixChar" x="960" y="180">3</text>
    <text class="matrixChar" x="960" y="200">B</text>
    <text class="matrixChar" x="960" y="220">5</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="6.47s" repeatCount="indefinite" begin="-3.05s" />
    </g>
    <g>
    <text class="matrixChar" x="992" y="0">F</text>
    <text class="matrixChar" x="992" y="20">2</text>
    <text class="matrixChar" x="992" y="40">8</text>
    <text class="matrixChar" x="992" y="60">5</text>
    <text class="matrixChar" x="992" y="80">E</text>
    <text class="matrixChar" x="992" y="100">4</text>
    <text class="matrixChar" x="992" y="120">9</text>
    <text class="matrixChar" x="992" y="140">8</text>
    <text class="matrixChar" x="992" y="160">8</text>
    <text class="matrixChar" x="992" y="180">9</text>
    <text class="matrixChar" x="992" y="200">Y</text>
    <text class="matrixChar" x="992" y="220">9</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="4.63s" repeatCount="indefinite" begin="-3.67s" />
    </g>
    <g>
    <text class="matrixChar" x="1024" y="0">E</text>
    <text class="matrixChar" x="1024" y="20">Z</text>
    <text class="matrixChar" x="1024" y="40">3</text>
    <text class="matrixChar" x="1024" y="60">8</text>
    <text class="matrixChar" x="1024" y="80">9</text>
    <text class="matrixChar" x="1024" y="100">2</text>
    <text class="matrixChar" x="1024" y="120">7</text>
    <text class="matrixChar" x="1024" y="140">9</text>
    <text class="matrixChar" x="1024" y="160">D</text>
    <text class="matrixChar" x="1024" y="180">9</text>
    <text class="matrixChar" x="1024" y="200">7</text>
    <text class="matrixChar" x="1024" y="220">5</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.93s" repeatCount="indefinite" begin="-5.4s" />
    </g>
    <g>
    <text class="matrixChar" x="1056" y="0">7</text>
    <text class="matrixChar" x="1056" y="20">Y</text>
    <text class="matrixChar" x="1056" y="40">7</text>
    <text class="matrixChar" x="1056" y="60">C</text>
    <text class="matrixChar" x="1056" y="80">X</text>
    <text class="matrixChar" x="1056" y="100">Z</text>
    <text class="matrixChar" x="1056" y="120">Y</text>
    <text class="matrixChar" x="1056" y="140">4</text>
    <text class="matrixChar" x="1056" y="160">6</text>
    <text class="matrixChar" x="1056" y="180">6</text>
    <text class="matrixChar" x="1056" y="200">6</text>
    <text class="matrixChar" x="1056" y="220">6</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="6.35s" repeatCount="indefinite" begin="-1.74s" />
    </g>
    <g>
    <text class="matrixChar" x="1088" y="0">9</text>
    <text class="matrixChar" x="1088" y="20">Y</text>
    <text class="matrixChar" x="1088" y="40">Z</text>
    <text class="matrixChar" x="1088" y="60">D</text>
    <text class="matrixChar" x="1088" y="80">8</text>
    <text class="matrixChar" x="1088" y="100">X</text>
    <text class="matrixChar" x="1088" y="120">9</text>
    <text class="matrixChar" x="1088" y="140">1</text>
    <text class="matrixChar" x="1088" y="160">B</text>
    <text class="matrixChar" x="1088" y="180">0</text>
    <text class="matrixChar" x="1088" y="200">E</text>
    <text class="matrixChar" x="1088" y="220">D</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="8.84s" repeatCount="indefinite" begin="-5.8s" />
    </g>
    <g>
    <text class="matrixChar" x="1120" y="0">Z</text>
    <text class="matrixChar" x="1120" y="20">X</text>
    <text class="matrixChar" x="1120" y="40">X</text>
    <text class="matrixChar" x="1120" y="60">7</text>
    <text class="matrixChar" x="1120" y="80">9</text>
    <text class="matrixChar" x="1120" y="100">8</text>
    <text class="matrixChar" x="1120" y="120">8</text>
    <text class="matrixChar" x="1120" y="140">1</text>
    <text class="matrixChar" x="1120" y="160">D</text>
    <text class="matrixChar" x="1120" y="180">3</text>
    <text class="matrixChar" x="1120" y="200">2</text>
    <text class="matrixChar" x="1120" y="220">9</text>
      <animateTransform attributeName="transform" type="translate" from="0 -360" to="0 0" dur="7.87s" repeatCount="indefinite" begin="-2.93s" />
    </g>
  </g>

  <!-- Title with neon flicker -->
  <g transform="translate(80,60)">
    <text class="title">Jerome Andrew K</text>
    <text class="subtitle" transform="translate(0,46)">Cyber-Hacker · Matrix · AI Neural</text>

    <!-- small flicker effect for title -->
    <rect x="220" y="-6" width="6" height="48" class="cursor">
      <animate attributeName="opacity" values="0;1;0;1;0" dur="1.2s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- blinking cursor after title (SVG text-based cursor for style) -->
  <g transform="translate(80,132)">
    <text class="subtitle">> </text>
    <text class="subtitle" x="20" id="typed">Penetration Tester · Exploit Dev · AI Security</text>
    <!-- emulate a blinking terminal cursor after the typed text -->
    <rect x="470" y="-14" width="8" height="18" class="cursor">
      <animate attributeName="opacity" from="1" to="0" dur="0.8s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- subtle bottom glow -->
  <rect x="0" y="250" width="1200" height="30" fill="url(#g1)" opacity="0.08"/>
</svg>

</div>

---

<!-- Minimal, highly-relevant info — short and to the point -->
<div align="center" style="background:#000;padding:14px;border-radius:6px;margin-top:12px;">
  <p style="color:#00ff99;font-family: 'Fira Code', monospace;font-size:14px;margin:6px 0;">
    <strong>&gt; Quick Glance</strong> — Python · Bash · Active Directory · Memory Forensics · CTF Writeups
  </p>

  <p style="margin:6px 0;">
    <a href="https://jerome.co.in" style="text-decoration:none"><img src="https://img.shields.io/badge/Portfolio-jerome.co.in-000?style=for-the-badge&logo=About.me&logoColor=00ff99" alt="portfolio"></a>
    <a href="https://github.com/Jery0843" style="text-decoration:none"><img src="https://img.shields.io/badge/GitHub-Jery0843-000?style=for-the-badge&logo=github&logoColor=00ff99" alt="github"></a>
    <a href="https://linkedin.com/in/jerome-andrew-k-093b2620a" style="text-decoration:none"><img src="https://img.shields.io/badge/LinkedIn-Connect-000?style=for-the-badge&logo=linkedin&logoColor=00ff99" alt="linkedin"></a>
  </p>

  <p style="color:#9affc9;font-family:'Fira Code',monospace;font-size:12px;margin:6px 0;">
    Tip: For full interactivity (WebGL / live demo) link a portfolio page — README is lightweight by design.
  </p>
</div>
