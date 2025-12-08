<svg width="100%" height="180" viewBox="0 0 900 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="blur" x="-10%" y="-10%" width="120%" height="120%">
      <feGaussianBlur stdDeviation="12"/>
    </filter>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0a0a0a"/>
      <stop offset="100%" stop-color="#111827"/>
    </linearGradient>
  </defs>

  <rect width="100%" height="100%" fill="url(#bg)"/>

  <!-- Glass panel -->
  <rect x="40" y="30" rx="14" ry="14" width="820" height="120"
        fill="rgba(255,255,255,0.06)"
        filter="url(#blur)"
        stroke="rgba(255,255,255,0.12)" />

  <!-- Text -->
  <text x="70" y="80" fill="#e5e7eb" font-size="28"
        font-family="monospace" font-weight="600">
    oFrank
  </text>

  <text x="70" y="115" fill="#9ca3af" font-size="16"
        font-family="monospace">
    frontend-ui-engineer · react · typescript · linux
  </text>
</svg>
<img src="./header.svg" />

<svg width="100%" height="220" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="blur">
      <feGaussianBlur stdDeviation="10"/>
    </filter>
  </defs>

  <rect x="30" y="20" rx="12" ry="12" width="840" height="180"
        fill="rgba(255,255,255,0.05)"
        filter="url(#blur)"
        stroke="rgba(255,255,255,0.12)" />

  <text x="60" y="60" fill="#e5e7eb" font-size="16"
        font-family="monospace">
    stack.ui
  </text>

  <text x="60" y="95" fill="#9ca3af" font-size="14"
        font-family="monospace">
    react · typescript · tailwindcss · framer-motion
  </text>

  <text x="60" y="130" fill="#9ca3af" font-size="14"
        font-family="monospace">
    linux · git · github · vercel · obsidian
  </text>
</svg>
<img src="./stack.svg" />
