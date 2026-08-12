
# ═══════════════════════════════════════════════════════════════════════════════
# SVG 2: NEON PULSE CIRCUIT BOARD
# ═══════════════════════════════════════════════════════════════════════════════
circuit_svg = '''<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 250" width="100%">
  <defs>
    <linearGradient id="neonGrad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00FFD1"/>
      <stop offset="50%" style="stop-color:#00B4D8"/>
      <stop offset="100%" style="stop-color:#0077B6"/>
    </linearGradient>
    <linearGradient id="neonGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#FF006E"/>
      <stop offset="50%" style="stop-color:#FB5607"/>
      <stop offset="100%" style="stop-color:#FFBE0B"/>
    </linearGradient>
    <filter id="neonGlow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="neonGlow2">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <rect width="1200" height="250" fill="#0D1117" rx="15"/>
  
  <!-- Circuit Lines -->
  <path d="M50,125 L200,125 L200,50 L350,50" fill="none" stroke="url(#neonGrad1)" stroke-width="3" filter="url(#neonGlow)" opacity="0.8">
    <animate attributeName="stroke-dasharray" values="0,1000;1000,0" dur="3s" repeatCount="indefinite"/>
  </path>
  
  <path d="M50,125 L200,125 L200,200 L350,200" fill="none" stroke="url(#neonGrad1)" stroke-width="3" filter="url(#neonGlow)" opacity="0.8">
    <animate attributeName="stroke-dasharray" values="0,1000;1000,0" dur="3.5s" repeatCount="indefinite"/>
  </path>
  
  <path d="M350,50 L500,50 L500,125 L650,125" fill="none" stroke="url(#neonGrad2)" stroke-width="3" filter="url(#neonGlow)" opacity="0.8">
    <animate attributeName="stroke-dasharray" values="0,1000;1000,0" dur="4s" repeatCount="indefinite"/>
  </path>
  
  <path d="M350,200 L500,200 L500,125 L650,125" fill="none" stroke="url(#neonGrad2)" stroke-width="3" filter="url(#neonGlow)" opacity="0.8">
    <animate attributeName="stroke-dasharray" values="0,1000;1000,0" dur="4.5s" repeatCount="indefinite"/>
  </path>
  
  <path d="M650,125 L800,125 L800,50 L950,50" fill="none" stroke="url(#neonGrad1)" stroke-width="3" filter="url(#neonGlow)" opacity="0.8">
    <animate attributeName="stroke-dasharray" values="0,1000;1000,0" dur="3.2s" repeatCount="indefinite"/>
  </path>
  
  <path d="M650,125 L800,125 L800,200 L950,200" fill="none" stroke="url(#neonGrad1)" stroke-width="3" filter="url(#neonGlow)" opacity="0.8">
    <animate attributeName="stroke-dasharray" values="0,1000;1000,0" dur="3.8s" repeatCount="indefinite"/>
  </path>
  
  <path d="M950,50 L1100,50 L1100,125 L1150,125" fill="none" stroke="url(#neonGrad2)" stroke-width="3" filter="url(#neonGlow)" opacity="0.8">
    <animate attributeName="stroke-dasharray" values="0,1000;1000,0" dur="4.2s" repeatCount="indefinite"/>
  </path>
  
  <path d="M950,200 L1100,200 L1100,125 L1150,125" fill="none" stroke="url(#neonGrad2)" stroke-width="3" filter="url(#neonGlow)" opacity="0.8">
    <animate attributeName="stroke-dasharray" values="0,1000;1000,0" dur="4.8s" repeatCount="indefinite"/>
  </path>
  
  <!-- Circuit Nodes -->
  <circle cx="200" cy="125" r="12" fill="#0D1117" stroke="#00FFD1" stroke-width="3" filter="url(#neonGlow2)">
    <animate attributeName="r" values="12;16;12" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="stroke-width" values="3;5;3" dur="2s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="350" cy="50" r="10" fill="#0D1117" stroke="#00B4D8" stroke-width="3" filter="url(#neonGlow2)">
    <animate attributeName="r" values="10;14;10" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="350" cy="200" r="10" fill="#0D1117" stroke="#00B4D8" stroke-width="3" filter="url(#neonGlow2)">
    <animate attributeName="r" values="10;14;10" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="500" cy="125" r="12" fill="#0D1117" stroke="#FF006E" stroke-width="3" filter="url(#neonGlow2)">
    <animate attributeName="r" values="12;16;12" dur="1.8s" repeatCount="indefinite"/>
    <animate attributeName="stroke-width" values="3;5;3" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="650" cy="125" r="12" fill="#0D1117" stroke="#FB5607" stroke-width="3" filter="url(#neonGlow2)">
    <animate attributeName="r" values="12;16;12" dur="2.2s" repeatCount="indefinite"/>
    <animate attributeName="stroke-width" values="3;5;3" dur="2.2s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="800" cy="50" r="10" fill="#0D1117" stroke="#00FFD1" stroke-width="3" filter="url(#neonGlow2)">
    <animate attributeName="r" values="10;14;10" dur="2.4s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="800" cy="200" r="10" fill="#0D1117" stroke="#00FFD1" stroke-width="3" filter="url(#neonGlow2)">
    <animate attributeName="r" values="10;14;10" dur="2.6s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="950" cy="50" r="10" fill="#0D1117" stroke="#FFBE0B" stroke-width="3" filter="url(#neonGlow2)">
    <animate attributeName="r" values="10;14;10" dur="2.1s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="950" cy="200" r="10" fill="#0D1117" stroke="#FFBE0B" stroke-width="3" filter="url(#neonGlow2)">
    <animate attributeName="r" values="10;14;10" dur="2.3s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Data Packets Flowing -->
  <circle cx="0" cy="125" r="5" fill="#00FFD1" filter="url(#neonGlow2)">
    <animate attributeName="cx" values="50;1150" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="5s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="0" cy="50" r="4" fill="#FF006E" filter="url(#neonGlow2)">
    <animate attributeName="cx" values="350;1150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="4s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="0" cy="200" r="4" fill="#FFBE0B" filter="url(#neonGlow2)">
    <animate attributeName="cx" values="350;1150" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="4.5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Title -->
  <text x="600" y="30" text-anchor="middle" fill="#00FFD1" font-family="Orbitron, monospace" font-size="22" font-weight="bold" filter="url(#neonGlow)">
    DATA PROCESSING CIRCUITS
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
  </text>
</svg>'''

with open('/mnt/agents/output/svg_assets/circuit.svg', 'w', encoding='utf-8') as f:
    f.write(circuit_svg)

# ═══════════════════════════════════════════════════════════════════════════════
# SVG 3: DATA DNA HELIX
# ═══════════════════════════════════════════════════════════════════════════════
dna_svg = '''<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%">
  <defs>
    <linearGradient id="dnaGrad1" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#00FFD1"/>
      <stop offset="100%" style="stop-color:#0077B6"/>
    </linearGradient>
    <linearGradient id="dnaGrad2" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#FF006E"/>
      <stop offset="100%" style="stop-color:#8338EC"/>
    </linearGradient>
    <filter id="dnaGlow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <rect width="1200" height="300" fill="#0D1117" rx="15"/>
  
  <!-- DNA Strand 1 -->
  <path d="M100,150 Q200,50 300,150 Q400,250 500,150 Q600,50 700,150 Q800,250 900,150 Q1000,50 1100,150" 
        fill="none" stroke="url(#dnaGrad1)" stroke-width="4" filter="url(#dnaGlow)" opacity="0.9">
    <animate attributeName="d" 
             values="M100,150 Q200,50 300,150 Q400,250 500,150 Q600,50 700,150 Q800,250 900,150 Q1000,50 1100,150;
                     M100,150 Q200,250 300,150 Q400,50 500,150 Q600,250 700,150 Q800,50 900,150 Q1000,250 1100,150;
                     M100,150 Q200,50 300,150 Q400,250 500,150 Q600,50 700,150 Q800,250 900,150 Q1000,50 1100,150" 
             dur="4s" repeatCount="indefinite"/>
  </path>
  
  <!-- DNA Strand 2 -->
  <path d="M100,150 Q200,250 300,150 Q400,50 500,150 Q600,250 700,150 Q800,50 900,150 Q1000,250 1100,150" 
        fill="none" stroke="url(#dnaGrad2)" stroke-width="4" filter="url(#dnaGlow)" opacity="0.9">
    <animate attributeName="d" 
             values="M100,150 Q200,250 300,150 Q400,50 500,150 Q600,250 700,150 Q800,50 900,150 Q1000,250 1100,150;
                     M100,150 Q200,50 300,150 Q400,250 500,150 Q600,50 700,150 Q800,250 900,150 Q1000,50 1100,150;
                     M100,150 Q200,250 300,150 Q400,50 500,150 Q600,250 700,150 Q800,50 900,150 Q1000,250 1100,150" 
             dur="4s" repeatCount="indefinite"/>
  </path>
  
  <!-- Connecting Bars -->
  <line x1="200" y1="100" x2="200" y2="200" stroke="#00FFD1" stroke-width="2" filter="url(#dnaGlow)" opacity="0.6">
    <animate attributeName="y1" values="100;200;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="200;100;200" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <line x1="300" y1="150" x2="300" y2="150" stroke="#FF006E" stroke-width="2" filter="url(#dnaGlow)" opacity="0.6">
    <animate attributeName="y1" values="150;150;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="150;150;150" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <line x1="400" y1="200" x2="400" y2="100" stroke="#00B4D8" stroke-width="2" filter="url(#dnaGlow)" opacity="0.6">
    <animate attributeName="y1" values="200;100;200" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="100;200;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <line x1="500" y1="150" x2="500" y2="150" stroke="#8338EC" stroke-width="2" filter="url(#dnaGlow)" opacity="0.6">
    <animate attributeName="y1" values="150;150;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="150;150;150" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <line x1="600" y1="100" x2="600" y2="200" stroke="#00FFD1" stroke-width="2" filter="url(#dnaGlow)" opacity="0.6">
    <animate attributeName="y1" values="100;200;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="200;100;200" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <line x1="700" y1="150" x2="700" y2="150" stroke="#FF006E" stroke-width="2" filter="url(#dnaGlow)" opacity="0.6">
    <animate attributeName="y1" values="150;150;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="150;150;150" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <line x1="800" y1="200" x2="800" y2="100" stroke="#00B4D8" stroke-width="2" filter="url(#dnaGlow)" opacity="0.6">
    <animate attributeName="y1" values="200;100;200" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="100;200;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <line x1="900" y1="150" x2="900" y2="150" stroke="#8338EC" stroke-width="2" filter="url(#dnaGlow)" opacity="0.6">
    <animate attributeName="y1" values="150;150;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="150;150;150" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <line x1="1000" y1="100" x2="1000" y2="200" stroke="#00FFD1" stroke-width="2" filter="url(#dnaGlow)" opacity="0.6">
    <animate attributeName="y1" values="100;200;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="200;100;200" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <!-- Data Nodes on DNA -->
  <circle cx="200" cy="150" r="8" fill="#00FFD1" filter="url(#dnaGlow)">
    <animate attributeName="cy" values="150;150;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="r" values="8;12;8" dur="2s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="400" cy="150" r="8" fill="#FF006E" filter="url(#dnaGlow)">
    <animate attributeName="cy" values="150;150;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="r" values="8;12;8" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="600" cy="150" r="8" fill="#00B4D8" filter="url(#dnaGlow)">
    <animate attributeName="cy" values="150;150;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="r" values="8;12;8" dur="2.2s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="800" cy="150" r="8" fill="#8338EC" filter="url(#dnaGlow)">
    <animate attributeName="cy" values="150;150;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="r" values="8;12;8" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="1000" cy="150" r="8" fill="#00FFD1" filter="url(#dnaGlow)">
    <animate attributeName="cy" values="150;150;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="r" values="8;12;8" dur="2.4s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Title -->
  <text x="600" y="280" text-anchor="middle" fill="#00FFD1" font-family="Orbitron, monospace" font-size="20" font-weight="bold" filter="url(#dnaGlow)">
    DATA DNA — STRUCTURED INSIGHTS
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
  </text>
  
  <text x="600" y="30" text-anchor="middle" fill="#00B4D8" font-family="monospace" font-size="14">
    Double Helix of Data & Intelligence
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite"/>
  </text>
</svg>'''

with open('/mnt/agents/output/svg_assets/dna.svg', 'w', encoding='utf-8') as f:
    f.write(dna_svg)

# ═══════════════════════════════════════════════════════════════════════════════
# SVG 4: HOLOGRAPHIC DASHBOARD GRID
# ═══════════════════════════════════════════════════════════════════════════════
holo_svg = '''<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%">
  <defs>
    <linearGradient id="holoGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00FFD1;stop-opacity:0.8"/>
      <stop offset="100%" style="stop-color:#00B4D8;stop-opacity:0.2"/>
    </linearGradient>
    <linearGradient id="holoGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#FF006E;stop-opacity:0.8"/>
      <stop offset="100%" style="stop-color:#FB5607;stop-opacity:0.2"/>
    </linearGradient>
    <filter id="holoGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <rect width="1200" height="300" fill="#0D1117" rx="15"/>
  
  <!-- Grid Background -->
  <defs>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#1a1a2e" stroke-width="0.5"/>
    </pattern>
  </defs>
  <rect width="1200" height="300" fill="url(#grid)"/>
  
  <!-- Dashboard Panel 1 -->
  <rect x="50" y="50" width="250" height="200" fill="none" stroke="url(#holoGrad1)" stroke-width="2" rx="10" filter="url(#holoGlow)">
    <animate attributeName="stroke-opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite"/>
  </rect>
  <text x="175" y="80" text-anchor="middle" fill="#00FFD1" font-family="Orbitron, monospace" font-size="16" font-weight="bold">SALES METRICS</text>
  <text x="175" y="120" text-anchor="middle" fill="#00B4D8" font-family="monospace" font-size="36" font-weight="bold" filter="url(#holoGlow)">
    $2.4M
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
  </text>
  <text x="175" y="150" text-anchor="middle" fill="#0077B6" font-family="monospace" font-size="14">+15.3% vs last month</text>
  <!-- Mini chart inside panel -->
  <polyline points="70,200 100,180 130,190 160,160 190,170 220,140 250,150 280,130" 
            fill="none" stroke="#00FFD1" stroke-width="2" filter="url(#holoGlow)">
    <animate attributeName="points" 
             values="70,200 100,180 130,190 160,160 190,170 220,140 250,150 280,130;
                     70,190 100,200 130,170 160,180 190,150 220,160 250,140 280,170;
                     70,200 100,180 130,190 160,160 190,170 220,140 250,150 280,130" 
             dur="4s" repeatCount="indefinite"/>
  </polyline>
  
  <!-- Dashboard Panel 2 -->
  <rect x="350" y="50" width="250" height="200" fill="none" stroke="url(#holoGrad2)" stroke-width="2" rx="10" filter="url(#holoGlow)">
    <animate attributeName="stroke-opacity" values="0.3;1;0.3" dur="3.5s" repeatCount="indefinite"/>
  </rect>
  <text x="475" y="80" text-anchor="middle" fill="#FF006E" font-family="Orbitron, monospace" font-size="16" font-weight="bold">USER GROWTH</text>
  <text x="475" y="120" text-anchor="middle" fill="#FB5607" font-family="monospace" font-size="36" font-weight="bold" filter="url(#holoGlow)">
    12.8K
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </text>
  <text x="475" y="150" text-anchor="middle" fill="#FFBE0B" font-family="monospace" font-size="14">+8.7% vs last month</text>
  <!-- Mini bars inside panel -->
  <rect x="370" y="180" width="20" height="40" fill="#FF006E" opacity="0.7" rx="3">
    <animate attributeName="height" values="40;60;40" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="y" values="180;160;180" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="400" y="170" width="20" height="50" fill="#FB5607" opacity="0.7" rx="3">
    <animate attributeName="height" values="50;30;50" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="y" values="170;190;170" dur="2.5s" repeatCount="indefinite"/>
  </rect>
  <rect x="430" y="160" width="20" height="60" fill="#FFBE0B" opacity="0.7" rx="3">
    <animate attributeName="height" values="60;40;60" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="y" values="160;180;160" dur="3s" repeatCount="indefinite"/>
  </rect>
  <rect x="460" y="175" width="20" height="45" fill="#FF006E" opacity="0.7" rx="3">
    <animate attributeName="height" values="45;65;45" dur="2.2s" repeatCount="indefinite"/>
    <animate attributeName="y" values="175;155;175" dur="2.2s" repeatCount="indefinite"/>
  </rect>
  <rect x="490" y="165" width="20" height="55" fill="#FB5607" opacity="0.7" rx="3">
    <animate attributeName="height" values="55;35;55" dur="2.8s" repeatCount="indefinite"/>
    <animate attributeName="y" values="165;185;165" dur="2.8s" repeatCount="indefinite"/>
  </rect>
  <rect x="520" y="155" width="20" height="65" fill="#FFBE0B" opacity="0.7" rx="3">
    <animate attributeName="height" values="65;45;65" dur="3.2s" repeatCount="indefinite"/>
    <animate attributeName="y" values="155;175;155" dur="3.2s" repeatCount="indefinite"/>
  </rect>
  <rect x="550" y="170" width="20" height="50" fill="#FF006E" opacity="0.7" rx="3">
    <animate attributeName="height" values="50;70;50" dur="2.4s" repeatCount="indefinite"/>
    <animate attributeName="y" values="170;150;170" dur="2.4s" repeatCount="indefinite"/>
  </rect>
  
  <!-- Dashboard Panel 3 -->
  <rect x="650" y="50" width="250" height="200" fill="none" stroke="url(#holoGrad1)" stroke-width="2" rx="10" filter="url(#holoGlow)">
    <animate attributeName="stroke-opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </rect>
  <text x="775" y="80" text-anchor="middle" fill="#00FFD1" font-family="Orbitron, monospace" font-size="16" font-weight="bold">CONVERSION</text>
  <text x="775" y="120" text-anchor="middle" fill="#00B4D8" font-family="monospace" font-size="36" font-weight="bold" filter="url(#holoGlow)">
    4.2%
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.2s" repeatCount="indefinite"/>
  </text>
  <text x="775" y="150" text-anchor="middle" fill="#0077B6" font-family="monospace" font-size="14">+1.2% vs last month</text>
  <!-- Mini pie chart -->
  <circle cx="775" cy="200" r="30" fill="none" stroke="#00FFD1" stroke-width="8" filter="url(#holoGlow)"
          stroke-dasharray="75,188" transform="rotate(-90 775 200)">
    <animate attributeName="stroke-dasharray" values="75,188;150,113;75,188" dur="5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Dashboard Panel 4 -->
  <rect x="950" y="50" width="200" height="200" fill="none" stroke="url(#holoGrad2)" stroke-width="2" rx="10" filter="url(#holoGlow)">
    <animate attributeName="stroke-opacity" values="0.3;1;0.3" dur="3.8s" repeatCount="indefinite"/>
  </rect>
  <text x="1050" y="80" text-anchor="middle" fill="#FF006E" font-family="Orbitron, monospace" font-size="16" font-weight="bold">RETENTION</text>
  <text x="1050" y="120" text-anchor="middle" fill="#FB5607" font-family="monospace" font-size="36" font-weight="bold" filter="url(#holoGlow)">
    89%
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.8s" repeatCount="indefinite"/>
  </text>
  <text x="1050" y="150" text-anchor="middle" fill="#FFBE0B" font-family="monospace" font-size="14">+3.5% vs last month</text>
  <!-- Mini gauge -->
  <path d="M 1000 200 A 50 50 0 0 1 1100 200" fill="none" stroke="#1a1a2e" stroke-width="8" stroke-linecap="round"/>
  <path d="M 1000 200 A 50 50 0 0 1 1100 200" fill="none" stroke="url(#holoGrad2)" stroke-width="8" stroke-linecap="round"
          stroke-dasharray="157" stroke-dashoffset="40" filter="url(#holoGlow)">
    <animate attributeName="stroke-dashoffset" values="40;20;40" dur="4s" repeatCount="indefinite"/>
  </path>
  
  <!-- Scanning Line -->
  <line x1="0" y1="0" x2="1200" y2="0" stroke="#00FFD1" stroke-width="2" opacity="0.5" filter="url(#holoGlow)">
    <animate attributeName="y1" values="0;300;0" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="0;300;0" dur="6s" repeatCount="indefinite"/>
  </line>
  
  <!-- Title -->
  <text x="600" y="30" text-anchor="middle" fill="#00FFD1" font-family="Orbitron, monospace" font-size="20" font-weight="bold" filter="url(#holoGlow)">
    LIVE HOLOGRAPHIC DASHBOARD
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
  </text>
</svg>'''

with open('/mnt/agents/output/svg_assets/holo.svg', 'w', encoding='utf-8') as f:
    f.write(holo_svg)

print("✅ SVG 2: Neon Pulse Circuit - Created!")
print("✅ SVG 3: Data DNA Helix - Created!")
print("✅ SVG 4: Holographic Dashboard - Created!")
