
readme_content = '''<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║         EXCLUSIVE WHITE THEME - ANIMATED HERO                 ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<svg viewBox="0 0 900 520" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <!-- Soft Gradients for White Theme -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#f8f9ff;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#eef2ff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#e0e7ff;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="screenLight" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f0f4ff;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#2563eb;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#7c3aed;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="glowBlue" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#2563eb;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#2563eb;stop-opacity:0.15" />
      <stop offset="100%" style="stop-color:#2563eb;stop-opacity:0" />
    </linearGradient>
    <filter id="softShadow" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="4" stdDeviation="8" flood-color="#2563eb" flood-opacity="0.1"/>
    </filter>
    <filter id="glowEffect">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- White Background -->
  <rect width="900" height="520" fill="url(#bgGrad)" rx="20"/>

  <!-- Floating Orbs (Background Decoration) -->
  <circle cx="80" cy="100" r="40" fill="#2563eb" opacity="0.08">
    <animate attributeName="cy" values="100;80;100" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="r" values="40;45;40" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="820" cy="150" r="60" fill="#7c3aed" opacity="0.06">
    <animate attributeName="cy" values="150;130;150" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="r" values="60;65;60" dur="7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="400" r="30" fill="#2563eb" opacity="0.07">
    <animate attributeName="cy" values="400;380;400" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="350" r="50" fill="#7c3aed" opacity="0.05">
    <animate attributeName="cy" values="350;330;350" dur="8s" repeatCount="indefinite"/>
  </circle>

  <!-- Desk Surface -->
  <rect x="100" y="380" width="700" height="8" fill="#d1d5ff" rx="4" opacity="0.5"/>
  <rect x="100" y="388" width="700" height="80" fill="#e8ecff" rx="0" opacity="0.3"/>

  <!-- Monitor Stand -->
  <rect x="420" y="320" width="60" height="60" fill="#c7d2fe" rx="6" filter="url(#softShadow)"/>
  <rect x="400" y="370" width="100" height="12" fill="#a5b4fc" rx="6" filter="url(#softShadow)"/>

  <!-- Monitor Frame -->
  <rect x="250" y="120" width="400" height="200" fill="#ffffff" rx="16" filter="url(#softShadow)" stroke="#c7d2fe" stroke-width="2"/>
  <rect x="260" y="130" width="380" height="180" fill="url(#screenLight)" rx="12"/>

  <!-- Screen Glow Effect -->
  <rect x="260" y="130" width="380" height="180" fill="url(#glowBlue)" rx="12" opacity="0.5">
    <animate attributeName="opacity" values="0.5;0.8;0.5" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- Screen Content - Animated Code Lines -->
  <g>
    <!-- Line 1 -->
    <rect x="280" y="150" width="8" height="10" fill="#2563eb" rx="2"/>
    <rect x="295" y="152" width="140" height="6" fill="#3b82f6" rx="3" opacity="0.9">
      <animate attributeName="width" values="140;180;140" dur="3s" repeatCount="indefinite"/>
    </rect>

    <!-- Line 2 -->
    <rect x="280" y="170" width="8" height="10" fill="#7c3aed" rx="2"/>
    <rect x="295" y="172" width="200" height="6" fill="#8b5cf6" rx="3" opacity="0.8">
      <animate attributeName="width" values="200;240;200" dur="3.5s" repeatCount="indefinite"/>
    </rect>

    <!-- Line 3 -->
    <rect x="280" y="190" width="8" height="10" fill="#2563eb" rx="2"/>
    <rect x="295" y="192" width="100" height="6" fill="#60a5fa" rx="3" opacity="0.7">
      <animate attributeName="width" values="100;140;100" dur="2.8s" repeatCount="indefinite"/>
    </rect>

    <!-- Line 4 -->
    <rect x="280" y="210" width="8" height="10" fill="#7c3aed" rx="2"/>
    <rect x="295" y="212" width="180" height="6" fill="#a78bfa" rx="3" opacity="0.8">
      <animate attributeName="width" values="180;220;180" dur="4s" repeatCount="indefinite"/>
    </rect>

    <!-- Line 5 -->
    <rect x="280" y="230" width="8" height="10" fill="#2563eb" rx="2"/>
    <rect x="295" y="232" width="160" height="6" fill="#3b82f6" rx="3" opacity="0.9">
      <animate attributeName="width" values="160;200;160" dur="3.2s" repeatCount="indefinite"/>
    </rect>

    <!-- Line 6 -->
    <rect x="280" y="250" width="8" height="10" fill="#7c3aed" rx="2"/>
    <rect x="295" y="252" width="120" height="6" fill="#8b5cf6" rx="3" opacity="0.7">
      <animate attributeName="width" values="120;160;120" dur="2.5s" repeatCount="indefinite"/>
    </rect>

    <!-- Line 7 -->
    <rect x="280" y="270" width="8" height="10" fill="#2563eb" rx="2"/>
    <rect x="295" y="272" width="220" height="6" fill="#60a5fa" rx="3" opacity="0.8">
      <animate attributeName="width" values="220;260;220" dur="3.8s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- Chart on Screen -->
  <g transform="translate(520, 150)">
    <rect x="0" y="0" width="100" height="70" fill="none" stroke="#c7d2fe" stroke-width="1.5" rx="8"/>
    <!-- Animated Chart Line -->
    <polyline points="10,60 25,45 40,50 55,30 70,35 85,15 95,20" fill="none" stroke="url(#accentGrad)" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" filter="url(#glowEffect)">
      <animate attributeName="points" values="10,60 25,45 40,50 55,30 70,35 85,15 95,20;10,60 25,40 40,55 55,25 70,40 85,10 95,25;10,60 25,45 40,50 55,30 70,35 85,15 95,20" dur="4s" repeatCount="indefinite"/>
    </polyline>
    <!-- Data Points -->
    <circle cx="85" cy="15" r="4" fill="#2563eb" filter="url(#glowEffect)">
      <animate attributeName="cy" values="15;10;15" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="r" values="4;5;4" dur="4s" repeatCount="indefinite"/>
    </circle>
    <text x="50" y="88" text-anchor="middle" fill="#2563eb" font-family="monospace" font-size="9" font-weight="bold" opacity="0.8">ANALYTICS</text>
  </g>

  <!-- Animated Cursor on Screen -->
  <rect x="520" y="272" width="3" height="14" fill="#2563eb" rx="1">
    <animate attributeName="opacity" values="1;0;1" dur="0.6s" repeatCount="indefinite"/>
  </rect>

  <!-- Character - Data Analyst -->
  <!-- Chair Back -->
  <rect x="130" y="280" width="50" height="100" fill="#c7d2fe" rx="12" opacity="0.6"/>
  <rect x="135" y="285" width="40" height="90" fill="#a5b4fc" rx="10" opacity="0.4"/>

  <!-- Body -->
  <ellipse cx="155" cy="340" rx="30" ry="38" fill="#2563eb" opacity="0.9" filter="url(#softShadow)"/>
  <ellipse cx="155" cy="340" rx="25" ry="33" fill="#3b82f6" opacity="0.8"/>

  <!-- Head -->
  <circle cx="155" cy="290" r="26" fill="#1e3a8a" filter="url(#softShadow)"/>
  <circle cx="155" cy="290" r="22" fill="#2563eb" opacity="0.9"/>

  <!-- Eyes (Animated Blinking) -->
  <ellipse cx="146" cy="286" rx="4" ry="5" fill="#ffffff">
    <animate attributeName="ry" values="5;0.5;5" dur="4s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="164" cy="286" rx="4" ry="5" fill="#ffffff">
    <animate attributeName="ry" values="5;0.5;5" dur="4s" repeatCount="indefinite"/>
  </ellipse>
  <!-- Pupils -->
  <circle cx="146" cy="286" r="2" fill="#1e3a8a">
    <animate attributeName="r" values="2;0;2" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="164" cy="286" r="2" fill="#1e3a8a">
    <animate attributeName="r" values="2;0;2" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- Smile -->
  <path d="M 145 298 Q 155 305 165 298" fill="none" stroke="#ffffff" stroke-width="1.5" opacity="0.9"/>

  <!-- Hair -->
  <path d="M 130 280 Q 155 245 180 280" fill="none" stroke="#1e3a8a" stroke-width="3" opacity="0.8"/>
  <path d="M 135 275 Q 155 250 175 275" fill="none" stroke="#2563eb" stroke-width="2" opacity="0.6"/>

  <!-- Left Arm (Typing Animation) -->
  <line x1="130" y1="330" x2="100" y2="365" stroke="#1e3a8a" stroke-width="3" stroke-linecap="round">
    <animate attributeName="x2" values="100;105;100" dur="0.25s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="365;360;365" dur="0.25s" repeatCount="indefinite"/>
  </line>
  <!-- Right Arm (Typing Animation - offset) -->
  <line x1="180" y1="330" x2="210" y2="365" stroke="#1e3a8a" stroke-width="3" stroke-linecap="round">
    <animate attributeName="x2" values="210;205;210" dur="0.25s" repeatCount="indefinite" begin="0.12s"/>
    <animate attributeName="y2" values="365;360;365" dur="0.25s" repeatCount="indefinite" begin="0.12s"/>
  </line>

  <!-- Hands -->
  <circle cx="100" cy="365" r="5" fill="#2563eb" filter="url(#glowEffect)">
    <animate attributeName="cx" values="100;105;100" dur="0.25s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="365;360;365" dur="0.25s" repeatCount="indefinite"/>
  </circle>
  <circle cx="210" cy="365" r="5" fill="#2563eb" filter="url(#glowEffect)">
    <animate attributeName="cx" values="210;205;210" dur="0.25s" repeatCount="indefinite" begin="0.12s"/>
    <animate attributeName="cy" values="365;360;365" dur="0.25s" repeatCount="indefinite" begin="0.12s"/>
  </circle>

  <!-- Keyboard -->
  <rect x="90" y="375" width="140" height="18" fill="#ffffff" rx="4" filter="url(#softShadow)" stroke="#c7d2fe" stroke-width="1"/>
  <g fill="#2563eb" opacity="0.3">
    <rect x="98" y="379" width="8" height="10" rx="2"/>
    <rect x="110" y="379" width="8" height="10" rx="2"/>
    <rect x="122" y="379" width="8" height="10" rx="2"/>
    <rect x="134" y="379" width="8" height="10" rx="2"/>
    <rect x="146" y="379" width="8" height="10" rx="2"/>
    <rect x="158" y="379" width="8" height="10" rx="2"/>
    <rect x="170" y="379" width="8" height="10" rx="2"/>
    <rect x="182" y="379" width="8" height="10" rx="2"/>
    <rect x="194" y="379" width="8" height="10" rx="2"/>
    <rect x="206" y="379" width="8" height="10" rx="2"/>
    <rect x="218" y="379" width="8" height="10" rx="2"/>
  </g>

  <!-- Mouse -->
  <ellipse cx="250" cy="384" rx="10" ry="14" fill="#ffffff" filter="url(#softShadow)" stroke="#c7d2fe" stroke-width="1"/>
  <line x1="250" y1="378" x2="250" y2="388" stroke="#c7d2fe" stroke-width="1" opacity="0.6"/>

  <!-- Coffee Cup -->
  <rect x="280" y="355" width="18" height="24" fill="#ffffff" rx="4" filter="url(#softShadow)" stroke="#c7d2fe" stroke-width="1"/>
  <path d="M 298 362 Q 306 362 306 368 Q 306 374 298 374" fill="none" stroke="#c7d2fe" stroke-width="1.5" opacity="0.7"/>
  <!-- Animated Steam -->
  <path d="M 285 350 Q 290 340 285 330" fill="none" stroke="#a5b4fc" stroke-width="1.5" opacity="0.5">
    <animate attributeName="d" values="M 285 350 Q 290 340 285 330;M 285 350 Q 280 340 285 330;M 285 350 Q 290 340 285 330" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="3s" repeatCount="indefinite"/>
  </path>
  <path d="M 293 350 Q 298 340 293 330" fill="none" stroke="#c7d2fe" stroke-width="1.5" opacity="0.4">
    <animate attributeName="d" values="M 293 350 Q 298 340 293 330;M 293 350 Q 288 340 293 330;M 293 350 Q 298 340 293 330" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.05;0.4" dur="3.5s" repeatCount="indefinite"/>
  </path>

  <!-- Plant Decoration -->
  <rect x="680" y="360" width="20" height="28" fill="#ffffff" rx="4" filter="url(#softShadow)" stroke="#c7d2fe" stroke-width="1"/>
  <ellipse cx="690" cy="355" rx="15" ry="20" fill="#22c55e" opacity="0.7"/>
  <ellipse cx="690" cy="355" rx="10" ry="15" fill="#4ade80" opacity="0.5"/>

  <!-- Floating Data Icons -->
  <!-- Excel Icon -->
  <g transform="translate(720, 200)">
    <rect x="0" y="0" width="30" height="30" fill="#ffffff" rx="6" filter="url(#softShadow)" stroke="#22c55e" stroke-width="1.5"/>
    <text x="15" y="20" text-anchor="middle" fill="#22c55e" font-family="Arial" font-size="12" font-weight="bold">X</text>
    <animateTransform attributeName="transform" type="translate" values="720,200;720,190;720,200" dur="4s" repeatCount="indefinite"/>
  </g>

  <!-- SQL Icon -->
  <g transform="translate(760, 240)">
    <rect x="0" y="0" width="30" height="30" fill="#ffffff" rx="6" filter="url(#softShadow)" stroke="#2563eb" stroke-width="1.5"/>
    <text x="15" y="20" text-anchor="middle" fill="#2563eb" font-family="Arial" font-size="10" font-weight="bold">SQL</text>
    <animateTransform attributeName="transform" type="translate" values="760,240;760,230;760,240" dur="5s" repeatCount="indefinite"/>
  </g>

  <!-- Python Icon -->
  <g transform="translate(700, 260)">
    <rect x="0" y="0" width="30" height="30" fill="#ffffff" rx="6" filter="url(#softShadow)" stroke="#7c3aed" stroke-width="1.5"/>
    <text x="15" y="20" text-anchor="middle" fill="#7c3aed" font-family="Arial" font-size="10" font-weight="bold">Py</text>
    <animateTransform attributeName="transform" type="translate" values="700,260;700,250;700,260" dur="3.5s" repeatCount="indefinite"/>
  </g>

  <!-- Power BI Icon -->
  <g transform="translate(740, 280)">
    <rect x="0" y="0" width="30" height="30" fill="#ffffff" rx="6" filter="url(#softShadow)" stroke="#f59e0b" stroke-width="1.5"/>
    <text x="15" y="20" text-anchor="middle" fill="#f59e0b" font-family="Arial" font-size="8" font-weight="bold">BI</text>
    <animateTransform attributeName="transform" type="translate" values="740,280;740,270;740,280" dur="4.5s" repeatCount="indefinite"/>
  </g>

  <!-- Title -->
  <text x="450" y="460" text-anchor="middle" fill="url(#accentGrad)" font-family="'Segoe UI', Arial, sans-serif" font-size="36" font-weight="800" filter="url(#glowEffect)">DATA ANALYST</text>
  <text x="450" y="490" text-anchor="middle" fill="#4b5563" font-family="'Segoe UI', Arial, sans-serif" font-size="16" font-weight="500">Excel · Power BI · SQL · Python · Pandas · Matplotlib</text>
  <text x="450" y="510" text-anchor="middle" fill="#6b7280" font-family="'Segoe UI', Arial, sans-serif" font-size="13">Transforming Complex Data Into Clear Insights</text>

  <!-- Animated Cursor -->
  <rect x="690" y="502" width="3" height="14" fill="#2563eb" rx="1">
    <animate attributeName="opacity" values="1;0;1" dur="0.7s" repeatCount="indefinite"/>
  </rect>
</svg>

<br>

<!-- Status Badges -->
<p>
  <img src="https://img.shields.io/badge/🟢-Available%20for%20Hire-22c55e?style=for-the-badge&labelColor=ffffff&color=22c55e" />
  <img src="https://img.shields.io/badge/📍-Open%20Worldwide-2563eb?style=for-the-badge&labelColor=ffffff&color=2563eb" />
  <img src="https://img.shields.io/badge/💼-Data%20Analyst-7c3aed?style=for-the-badge&labelColor=ffffff&color=7c3aed" />
</p>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    ABOUT ME SECTION                           ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

## <img src="https://img.shields.io/badge/👤-ABOUT%20ME-2563eb?style=flat-square&labelColor=ffffff" height="32" />

</div>

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║   🎓 IT Graduate passionate about Data Analysis & Business Intelligence      ║
║                                                                              ║
║   💡 I transform complex data into clear insights and interactive            ║
║      dashboards using Excel, Power BI, and SQL                               ║
║                                                                              ║
║   🚀 Dedicated to uncovering hidden patterns and driving data-driven         ║
║      decisions for business growth                                           ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    EXPERTISE SECTION                          ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

## <img src="https://img.shields.io/badge/🎯-EXPERTISE-7c3aed?style=flat-square&labelColor=ffffff" height="32" />

</div>

<div align="center">

| 💼 **Area** | 📝 **What I Do** |
|:-----------:|:----------------|
| 📥 **Data Collection** | Gathering structured & unstructured data from multiple sources |
| 🧹 **Data Cleaning** | Handling missing values, duplicates, outliers & inconsistencies |
| 🔎 **Data Research & Mining** | Extracting valuable patterns & insights from raw datasets |
| 📊 **Data Analysis** | Statistical analysis, trend identification & hypothesis testing |
| 📈 **Dashboards** | Building interactive BI dashboards with real-time KPIs |
| 📑 **Reporting** | Creating automated reports with actionable recommendations |
| 🎨 **Data Visualization** | Crafting compelling charts, graphs & visual storytelling |
| 💼 **Business Insights** | Delivering strategic recommendations for decision makers |

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    TOOLS SECTION                              ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

## <img src="https://img.shields.io/badge/🛠️-TOOLS%20&%20TECHNOLOGIES-f59e0b?style=flat-square&labelColor=ffffff" height="32" />

</div>

<div align="center">

### 📊 **Data Analysis & Business Intelligence**
<p>
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/Excel%20Advanced-1D6F42?style=for-the-badge&logo=microsoft-excel&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/Power%20Query-2B579A?style=for-the-badge&logo=microsoft&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=dax&logoColor=black&labelColor=ffffff" />
</p>

### 🗄️ **Databases & Query Languages**
<p>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white&labelColor=ffffff" />
</p>

### 🐍 **Programming & Analytics**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white&labelColor=ffffff" />
</p>

### 🛠️ **Development & Productivity**
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white&labelColor=ffffff" />
  <img src="https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white&labelColor=ffffff" />
</p>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    WORKFLOW SECTION                           ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

## <img src="https://img.shields.io/badge/🔄-MY%20WORKFLOW-2563eb?style=flat-square&labelColor=ffffff" height="32" />

</div>

<div align="center">

```
    ┌─────────────┐         ┌─────────────┐         ┌─────────────┐         ┌─────────────┐
    │             │         │             │         │             │         │             │
    │  📥 COLLECT │   →    │  🧹 CLEAN   │   →    │  🔍 ANALYZE │   →    │  📊 VISUALIZE│
    │             │         │             │         │             │         │             │
    │ Data Sources│         │ Remove Nulls│         │ Statistics  │         │ Dashboards  │
    │ APIs · DBs  │         │ Duplicates  │         │ Trends      │         │ Reports     │
    │ Files · Web │         │ Formatting  │         │ Patterns    │         │ Charts      │
    └─────────────┘         └─────────────┘         └─────────────┘         └─────────────┘
                                                                                  │
                                                                                  ▼
                                                                       ┌─────────────┐
                                                                       │             │
                                                                       │  🎯 INSIGHTS │
                                                                       │             │
                                                                       │  Decisions   │
                                                                       │  Strategy    │
                                                                       │  Growth      │
                                                                       └─────────────┘
```

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    CONTACT SECTION                            ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

## <img src="https://img.shields.io/badge/📬-LET'S%20CONNECT!-7c3aed?style=flat-square&labelColor=ffffff" height="32" />

</div>

<div align="center">

### 📇 **Contact Information**

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│  📧  Email:        your.email@example.com                           │
│                                                                     │
│  📱  Phone:        +966 50 123 4567                                 │
│                                                                     │
│  💼  LinkedIn:     linkedin.com/in/yourprofile                      │
│                                                                     │
│  🌐  Location:     Open to opportunities worldwide                  │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

<br>

### 🔗 **Connect With Me**

<p>
  <a href="mailto:your.email@example.com">
    <img src="https://img.shields.io/badge/Send%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=ffffff" height="42" />
  </a>
  &nbsp;&nbsp;
  <a href="https://wa.me/966501234567">
    <img src="https://img.shields.io/badge/WhatsApp%20Me-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=ffffff" height="42" />
  </a>
  &nbsp;&nbsp;
  <a href="https://linkedin.com/in/yourprofile">
    <img src="https://img.shields.io/badge/LinkedIn%20Profile-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=ffffff" height="42" />
  </a>
</p>

<br>

### 🌟 **Open to Data Analyst opportunities worldwide!**

<img src="https://img.shields.io/badge/🌍-Available%20Worldwide-22c55e?style=for-the-badge&labelColor=ffffff&color=22c55e" height="35" />

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    FOOTER SECTION                             ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,50:7c3aed,100:f59e0b&height=100&section=footer&text=Thank%20You%20For%20Visiting!&fontSize=22&fontColor=ffffff&animation=fadeIn&fontAlignY=70" width="100%"/>

<br>

<p>
  <img src="https://komarev.com/ghpvc/?username=yourusername&label=Profile%20Views&color=2563eb&style=flat-square" alt="Profile Views" />
  &nbsp;
  <img src="https://img.shields.io/badge/Made%20with%20❤️%20by-Data%20Analyst-2563eb?style=flat-square&labelColor=ffffff" />
  &nbsp;
  <img src="https://img.shields.io/badge/Open%20to%20Work-Yes!-22c55e?style=flat-square&labelColor=ffffff" />
</p>

</div>
racters")
