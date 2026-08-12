
import os
os.makedirs('/mnt/agents/output/svg_assets', exist_ok=True)

# ═══════════════════════════════════════════════════════════════════════════════
# SVG 1: MATRIX RAIN EFFECT WITH DATA NUMBERS
# ═══════════════════════════════════════════════════════════════════════════════
matrix_svg = '''<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%">
  <defs>
    <linearGradient id="matrixGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#00FFD1;stop-opacity:0"/>
      <stop offset="20%" style="stop-color:#00FFD1;stop-opacity:1"/>
      <stop offset="80%" style="stop-color:#00B4D8;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#0077B6;stop-opacity:0"/>
    </linearGradient>
    <filter id="matrixGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <rect width="1200" height="300" fill="#0D1117" rx="15"/>
  
  <!-- Column 1 -->
  <text x="50" y="0" fill="#00FFD1" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.8">
    <tspan x="50" dy="20">9</tspan>
    <tspan x="50" dy="20">7</tspan>
    <tspan x="50" dy="20">3</tspan>
    <tspan x="50" dy="20">1</tspan>
    <tspan x="50" dy="20">5</tspan>
    <tspan x="50" dy="20">8</tspan>
    <tspan x="50" dy="20">2</tspan>
    <tspan x="50" dy="20">0</tspan>
    <tspan x="50" dy="20">4</tspan>
    <tspan x="50" dy="20">6</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,40; 0,0" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0.3;0.8" dur="2s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 2 -->
  <text x="100" y="0" fill="#00B4D8" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.6">
    <tspan x="100" dy="20">4</tspan>
    <tspan x="100" dy="20">2</tspan>
    <tspan x="100" dy="20">8</tspan>
    <tspan x="100" dy="20">0</tspan>
    <tspan x="100" dy="20">6</tspan>
    <tspan x="100" dy="20">3</tspan>
    <tspan x="100" dy="20">9</tspan>
    <tspan x="100" dy="20">1</tspan>
    <tspan x="100" dy="20">5</tspan>
    <tspan x="100" dy="20">7</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-30; 0,0" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 3 -->
  <text x="150" y="0" fill="#0077B6" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.7">
    <tspan x="150" dy="20">1</tspan>
    <tspan x="150" dy="20">5</tspan>
    <tspan x="150" dy="20">9</tspan>
    <tspan x="150" dy="20">3</tspan>
    <tspan x="150" dy="20">7</tspan>
    <tspan x="150" dy="20">0</tspan>
    <tspan x="150" dy="20">4</tspan>
    <tspan x="150" dy="20">8</tspan>
    <tspan x="150" dy="20">2</tspan>
    <tspan x="150" dy="20">6</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,50; 0,0" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="2s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 4 -->
  <text x="200" y="0" fill="#00FFD1" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.9">
    <tspan x="200" dy="20">7</tspan>
    <tspan x="200" dy="20">3</tspan>
    <tspan x="200" dy="20">0</tspan>
    <tspan x="200" dy="20">5</tspan>
    <tspan x="200" dy="20">8</tspan>
    <tspan x="200" dy="20">2</tspan>
    <tspan x="200" dy="20">9</tspan>
    <tspan x="200" dy="20">4</tspan>
    <tspan x="200" dy="20">1</tspan>
    <tspan x="200" dy="20">6</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-40; 0,0" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.5s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 5 -->
  <text x="250" y="0" fill="#00B4D8" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.5">
    <tspan x="250" dy="20">2</tspan>
    <tspan x="250" dy="20">6</tspan>
    <tspan x="250" dy="20">4</tspan>
    <tspan x="250" dy="20">8</tspan>
    <tspan x="250" dy="20">0</tspan>
    <tspan x="250" dy="20">3</tspan>
    <tspan x="250" dy="20">7</tspan>
    <tspan x="250" dy="20">5</tspan>
    <tspan x="250" dy="20">9</tspan>
    <tspan x="250" dy="20">1</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,35; 0,0" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 6 -->
  <text x="300" y="0" fill="#0077B6" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.8">
    <tspan x="300" dy="20">5</tspan>
    <tspan x="300" dy="20">9</tspan>
    <tspan x="300" dy="20">1</tspan>
    <tspan x="300" dy="20">7</tspan>
    <tspan x="300" dy="20">3</tspan>
    <tspan x="300" dy="20">0</tspan>
    <tspan x="300" dy="20">6</tspan>
    <tspan x="300" dy="20">8</tspan>
    <tspan x="300" dy="20">4</tspan>
    <tspan x="300" dy="20">2</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-25; 0,0" dur="2.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="2.2s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 7 -->
  <text x="350" y="0" fill="#00FFD1" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.6">
    <tspan x="350" dy="20">8</tspan>
    <tspan x="350" dy="20">4</tspan>
    <tspan x="350" dy="20">0</tspan>
    <tspan x="350" dy="20">6</tspan>
    <tspan x="350" dy="20">2</tspan>
    <tspan x="350" dy="20">9</tspan>
    <tspan x="350" dy="20">5</tspan>
    <tspan x="350" dy="20">3</tspan>
    <tspan x="350" dy="20">7</tspan>
    <tspan x="350" dy="20">1</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,45; 0,0" dur="3.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="2.8s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 8 -->
  <text x="400" y="0" fill="#00B4D8" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.9">
    <tspan x="400" dy="20">3</tspan>
    <tspan x="400" dy="20">7</tspan>
    <tspan x="400" dy="20">5</tspan>
    <tspan x="400" dy="20">1</tspan>
    <tspan x="400" dy="20">9</tspan>
    <tspan x="400" dy="20">4</tspan>
    <tspan x="400" dy="20">0</tspan>
    <tspan x="400" dy="20">8</tspan>
    <tspan x="400" dy="20">6</tspan>
    <tspan x="400" dy="20">2</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-35; 0,0" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="3.5s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 9 -->
  <text x="450" y="0" fill="#0077B6" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.7">
    <tspan x="450" dy="20">6</tspan>
    <tspan x="450" dy="20">0</tspan>
    <tspan x="450" dy="20">8</tspan>
    <tspan x="450" dy="20">4</tspan>
    <tspan x="450" dy="20">2</tspan>
    <tspan x="450" dy="20">7</tspan>
    <tspan x="450" dy="20">3</tspan>
    <tspan x="450" dy="20">9</tspan>
    <tspan x="450" dy="20">5</tspan>
    <tspan x="450" dy="20">1</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,30; 0,0" dur="2.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="1.8s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 10 -->
  <text x="500" y="0" fill="#00FFD1" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.8">
    <tspan x="500" dy="20">0</tspan>
    <tspan x="500" dy="20">4</tspan>
    <tspan x="500" dy="20">6</tspan>
    <tspan x="500" dy="20">8</tspan>
    <tspan x="500" dy="20">2</tspan>
    <tspan x="500" dy="20">5</tspan>
    <tspan x="500" dy="20">1</tspan>
    <tspan x="500" dy="20">7</tspan>
    <tspan x="500" dy="20">3</tspan>
    <tspan x="500" dy="20">9</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-45; 0,0" dur="3.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 11 -->
  <text x="550" y="0" fill="#00B4D8" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.5">
    <tspan x="550" dy="20">9</tspan>
    <tspan x="550" dy="20">3</tspan>
    <tspan x="550" dy="20">1</tspan>
    <tspan x="550" dy="20">5</tspan>
    <tspan x="550" dy="20">7</tspan>
    <tspan x="550" dy="20">0</tspan>
    <tspan x="550" dy="20">4</tspan>
    <tspan x="550" dy="20">8</tspan>
    <tspan x="550" dy="20">6</tspan>
    <tspan x="550" dy="20">2</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,40; 0,0" dur="4.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.2s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 12 -->
  <text x="600" y="0" fill="#0077B6" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.9">
    <tspan x="600" dy="20">2</tspan>
    <tspan x="600" dy="20">8</tspan>
    <tspan x="600" dy="20">4</tspan>
    <tspan x="600" dy="20">0</tspan>
    <tspan x="600" dy="20">6</tspan>
    <tspan x="600" dy="20">3</tspan>
    <tspan x="600" dy="20">9</tspan>
    <tspan x="600" dy="20">5</tspan>
    <tspan x="600" dy="20">1</tspan>
    <tspan x="600" dy="20">7</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-30; 0,0" dur="2.6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 13 -->
  <text x="650" y="0" fill="#00FFD1" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.6">
    <tspan x="650" dy="20">5</tspan>
    <tspan x="650" dy="20">1</tspan>
    <tspan x="650" dy="20">7</tspan>
    <tspan x="650" dy="20">3</tspan>
    <tspan x="650" dy="20">9</tspan>
    <tspan x="650" dy="20">4</tspan>
    <tspan x="650" dy="20">0</tspan>
    <tspan x="650" dy="20">8</tspan>
    <tspan x="650" dy="20">6</tspan>
    <tspan x="650" dy="20">2</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,50; 0,0" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="2.5s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 14 -->
  <text x="700" y="0" fill="#00B4D8" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.8">
    <tspan x="700" dy="20">8</tspan>
    <tspan x="700" dy="20">6</tspan>
    <tspan x="700" dy="20">0</tspan>
    <tspan x="700" dy="20">4</tspan>
    <tspan x="700" dy="20">2</tspan>
    <tspan x="700" dy="20">7</tspan>
    <tspan x="700" dy="20">5</tspan>
    <tspan x="700" dy="20">3</tspan>
    <tspan x="700" dy="20">9</tspan>
    <tspan x="700" dy="20">1</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-40; 0,0" dur="4.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="3.8s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 15 -->
  <text x="750" y="0" fill="#0077B6" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.7">
    <tspan x="750" dy="20">1</tspan>
    <tspan x="750" dy="20">9</tspan>
    <tspan x="750" dy="20">5</tspan>
    <tspan x="750" dy="20">3</tspan>
    <tspan x="750" dy="20">7</tspan>
    <tspan x="750" dy="20">0</tspan>
    <tspan x="750" dy="20">6</tspan>
    <tspan x="750" dy="20">8</tspan>
    <tspan x="750" dy="20">4</tspan>
    <tspan x="750" dy="20">2</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,35; 0,0" dur="2.4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="1.9s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 16 -->
  <text x="800" y="0" fill="#00FFD1" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.9">
    <tspan x="800" dy="20">4</tspan>
    <tspan x="800" dy="20">0</tspan>
    <tspan x="800" dy="20">8</tspan>
    <tspan x="800" dy="20">6</tspan>
    <tspan x="800" dy="20">2</tspan>
    <tspan x="800" dy="20">5</tspan>
    <tspan x="800" dy="20">9</tspan>
    <tspan x="800" dy="20">1</tspan>
    <tspan x="800" dy="20">7</tspan>
    <tspan x="800" dy="20">3</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-50; 0,0" dur="3.6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.8s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 17 -->
  <text x="850" y="0" fill="#00B4D8" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.5">
    <tspan x="850" dy="20">7</tspan>
    <tspan x="850" dy="20">3</tspan>
    <tspan x="850" dy="20">1</tspan>
    <tspan x="850" dy="20">9</tspan>
    <tspan x="850" dy="20">5</tspan>
    <tspan x="850" dy="20">0</tspan>
    <tspan x="850" dy="20">4</tspan>
    <tspan x="850" dy="20">8</tspan>
    <tspan x="850" dy="20">6</tspan>
    <tspan x="850" dy="20">2</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,45; 0,0" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 18 -->
  <text x="900" y="0" fill="#0077B6" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.8">
    <tspan x="900" dy="20">0</tspan>
    <tspan x="900" dy="20">6</tspan>
    <tspan x="900" dy="20">4</tspan>
    <tspan x="900" dy="20">2</tspan>
    <tspan x="900" dy="20">8</tspan>
    <tspan x="900" dy="20">3</tspan>
    <tspan x="900" dy="20">7</tspan>
    <tspan x="900" dy="20">5</tspan>
    <tspan x="900" dy="20">9</tspan>
    <tspan x="900" dy="20">1</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-35; 0,0" dur="2.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="2.2s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 19 -->
  <text x="950" y="0" fill="#00FFD1" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.6">
    <tspan x="950" dy="20">3</tspan>
    <tspan x="950" dy="20">9</tspan>
    <tspan x="950" dy="20">5</tspan>
    <tspan x="950" dy="20">1</tspan>
    <tspan x="950" dy="20">7</tspan>
    <tspan x="950" dy="20">0</tspan>
    <tspan x="950" dy="20">6</tspan>
    <tspan x="950" dy="20">8</tspan>
    <tspan x="950" dy="20">4</tspan>
    <tspan x="950" dy="20">2</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,40; 0,0" dur="3.3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="2.6s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 20 -->
  <text x="1000" y="0" fill="#00B4D8" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.9">
    <tspan x="1000" dy="20">6</tspan>
    <tspan x="1000" dy="20">2</tspan>
    <tspan x="1000" dy="20">8</tspan>
    <tspan x="1000" dy="20">4</tspan>
    <tspan x="1000" dy="20">0</tspan>
    <tspan x="1000" dy="20">5</tspan>
    <tspan x="1000" dy="20">9</tspan>
    <tspan x="1000" dy="20">3</tspan>
    <tspan x="1000" dy="20">7</tspan>
    <tspan x="1000" dy="20">1</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-45; 0,0" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="3.5s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 21 -->
  <text x="1050" y="0" fill="#0077B6" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.7">
    <tspan x="1050" dy="20">9</tspan>
    <tspan x="1050" dy="20">5</tspan>
    <tspan x="1050" dy="20">3</tspan>
    <tspan x="1050" dy="20">7</tspan>
    <tspan x="1050" dy="20">1</tspan>
    <tspan x="1050" dy="20">0</tspan>
    <tspan x="1050" dy="20">4</tspan>
    <tspan x="1050" dy="20">8</tspan>
    <tspan x="1050" dy="20">6</tspan>
    <tspan x="1050" dy="20">2</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,30; 0,0" dur="2.1s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="1.7s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 22 -->
  <text x="1100" y="0" fill="#00FFD1" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.8">
    <tspan x="1100" dy="20">2</tspan>
    <tspan x="1100" dy="20">4</tspan>
    <tspan x="1100" dy="20">6</tspan>
    <tspan x="1100" dy="20">8</tspan>
    <tspan x="1100" dy="20">0</tspan>
    <tspan x="1100" dy="20">3</tspan>
    <tspan x="1100" dy="20">7</tspan>
    <tspan x="1100" dy="20">5</tspan>
    <tspan x="1100" dy="20">9</tspan>
    <tspan x="1100" dy="20">1</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-40; 0,0" dur="3.9s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="3.1s" repeatCount="indefinite"/>
  </text>
  
  <!-- Column 23 -->
  <text x="1150" y="0" fill="#00B4D8" font-family="monospace" font-size="14" filter="url(#matrixGlow)" opacity="0.5">
    <tspan x="1150" dy="20">5</tspan>
    <tspan x="1150" dy="20">7</tspan>
    <tspan x="1150" dy="20">9</tspan>
    <tspan x="1150" dy="20">1</tspan>
    <tspan x="1150" dy="20">3</tspan>
    <tspan x="1150" dy="20">0</tspan>
    <tspan x="1150" dy="20">6</tspan>
    <tspan x="1150" dy="20">8</tspan>
    <tspan x="1150" dy="20">4</tspan>
    <tspan x="1150" dy="20">2</tspan>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,50; 0,0" dur="4.3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Central Title -->
  <text x="600" y="150" text-anchor="middle" fill="#00FFD1" font-family="Orbitron, monospace" font-size="36" font-weight="bold" filter="url(#matrixGlow)">
    DATA MATRIX
    <animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" repeatCount="indefinite"/>
  </text>
  <text x="600" y="180" text-anchor="middle" fill="#00B4D8" font-family="monospace" font-size="16">
    Raw Data Flowing Through the System
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
  </text>
</svg>'''

with open('/mnt/agents/output/svg_assets/matrix.svg', 'w', encoding='utf-8') as f:
    f.write(matrix_svg)

print("✅ SVG 1: Matrix Rain Effect - Created!")
