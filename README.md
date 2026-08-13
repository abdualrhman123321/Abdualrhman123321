
<div align="center">
<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    EXCLUSIVE HERO DESIGN                      ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<svg viewBox="0 0 900 500" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <!-- Gradients -->
    <linearGradient id="screenGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a1a;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#0d1b3e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#1a0a2e;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="glowGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f0ff;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#00f0ff;stop-opacity:0.3" />
      <stop offset="100%" style="stop-color:#00f0ff;stop-opacity:0" />
    </linearGradient>
    <linearGradient id="deskGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#1a1a2e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0f0f1a;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="neonGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feFlood flood-color="#00f0ff" result="color"/>
      <feComposite in="color" in2="blur" operator="in" result="shadow"/>
      <feMerge>
        <feMergeNode in="shadow"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <!-- Background -->
  <rect width="900" height="500" fill="#050510" rx="20"/>
  <!-- Stars -->
  <circle cx="50" cy="40" r="1.5" fill="#fff" opacity="0.8">
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="80" r="1" fill="#fff" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="800" cy="50" r="2" fill="#00f0ff" opacity="0.5">
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="850" cy="120" r="1.5" fill="#fff" opacity="0.7">
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="100" cy="150" r="1" fill="#00f0ff" opacity="0.4">
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="5s" repeatCount="indefinite"/>
  </circle>
  <!-- Desk -->
  <rect x="50" y="350" width="800" height="120" fill="url(#deskGrad)" rx="10"/>
  <rect x="50" y="350" width="800" height="3" fill="#00f0ff" opacity="0.5" filter="url(#glow)"/>
  <!-- Monitor Stand -->
  <rect x="400" y="280" width="100" height="70" fill="#1a1a2e" rx="5"/>
  <rect x="370" y="340" width="160" height="15" fill="#0a0a15" rx="5"/>
  <!-- Monitor Frame -->
  <rect x="150" y="80" width="600" height="200" fill="#0a0a15" rx="15" stroke="#00f0ff" stroke-width="2" filter="url(#neonGlow)"/>
  <rect x="160" y="90" width="580" height="180" fill="url(#screenGrad)" rx="10"/>
  <!-- Screen Content - Code Lines -->
  <g opacity="0.8">
    <rect x="180" y="110" width="120" height="8" fill="#00f0ff" rx="2" opacity="0.8">
      <animate attributeName="width" values="120;180;120" dur="4s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="125" width="200" height="6" fill="#7b2ff7" rx="2" opacity="0.7">
      <animate attributeName="width" values="200;280;200" dur="3s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="138" width="160" height="6" fill="#00f0ff" rx="2" opacity="0.6">
      <animate attributeName="width" values="160;220;160" dur="3.5s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="151" width="250" height="6" fill="#ff6b6b" rx="2" opacity="0.7">
      <animate attributeName="width" values="250;300;250" dur="4.5s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="164" width="100" height="6" fill="#00f0ff" rx="2" opacity="0.5">
      <animate attributeName="width" values="100;150;100" dur="2.5s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="177" width="180" height="6" fill="#7b2ff7" rx="2" opacity="0.6">
      <animate attributeName="width" values="180;240;180" dur="3.2s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="190" width="140" height="6" fill="#00f0ff" rx="2" opacity="0.8">
      <animate attributeName="width" values="140;200;140" dur="3.8s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="203" width="220" height="6" fill="#ffd93d" rx="2" opacity="0.6">
      <animate attributeName="width" values="220;280;220" dur="4s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="216" width="90" height="6" fill="#00f0ff" rx="2" opacity="0.5">
      <animate attributeName="width" values="90;140;90" dur="2.8s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="229" width="170" height="6" fill="#7b2ff7" rx="2" opacity="0.7">
      <animate attributeName="width" values="170;230;170" dur="3.6s" repeatCount="indefinite"/>
    </rect>
    <rect x="180" y="242" width="130" height="6" fill="#00f0ff" rx="2" opacity="0.6">
      <animate attributeName="width" values="130;190;130" dur="3.3s" repeatCount="indefinite"/>
    </rect>
  </g>
  <!-- Chart on Screen -->
  <g transform="translate(450, 120)">
    <rect x="0" y="0" width="120" height="80" fill="none" stroke="#00f0ff" stroke-width="1" opacity="0.5" rx="5"/>
    <polyline points="10,70 30,50 50,55 70,30 90,35 110,15" fill="none" stroke="#00f0ff" stroke-width="2" filter="url(#glow)">
      <animate attributeName="points" values="10,70 30,50 50,55 70,30 90,35 110,15;10,70 30,40 50,60 70,25 90,40 110,10;10,70 30,50 50,55 70,30 90,35 110,15" dur="5s" repeatCount="indefinite"/>
    </polyline>
    <circle cx="110" cy="15" r="4" fill="#00f0ff" filter="url(#glow)">
      <animate attributeName="cy" values="15;10;15" dur="5s" repeatCount="indefinite"/>
    </circle>
    <text x="60" y="95" text-anchor="middle" fill="#00f0ff" font-family="monospace" font-size="10" opacity="0.8">ANALYTICS</text>
  </g>
  <!-- Character - Data Analyst sitting -->
  <!-- Body -->
  <ellipse cx="250" cy="320" rx="35" ry="45" fill="#1a1a3e" stroke="#00f0ff" stroke-width="1.5" filter="url(#neonGlow)"/>
  <!-- Head -->
  <circle cx="250" cy="260" r="30" fill="#1a1a3e" stroke="#00f0ff" stroke-width="1.5" filter="url(#neonGlow)"/>
  <!-- Eyes -->
  <ellipse cx="240" cy="255" rx="5" ry="7" fill="#00f0ff">
    <animate attributeName="ry" values="7;1;7" dur="4s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="260" cy="255" rx="5" ry="7" fill="#00f0ff">
    <animate attributeName="ry" values="7;1;7" dur="4s" repeatCount="indefinite"/>
  </ellipse>
  <!-- Smile -->
  <path d="M 240 270 Q 250 278 260 270" fill="none" stroke="#00f0ff" stroke-width="1.5" opacity="0.8"/>
  <!-- Hair -->
  <path d="M 220 250 Q 250 200 280 250" fill="none" stroke="#7b2ff7" stroke-width="2" opacity="0.8"/>
  <path d="M 225 245 Q 250 210 275 245" fill="none" stroke="#00f0ff" stroke-width="1.5" opacity="0.6"/>
  <!-- Arms typing -->
  <line x1="220" y1="310" x2="180" y2="340" stroke="#00f0ff" stroke-width="2" opacity="0.7">
    <animate attributeName="x2" values="180;185;180" dur="0.3s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="340;335;340" dur="0.3s" repeatCount="indefinite"/>
  </line>
  <line x1="280" y1="310" x2="320" y2="340" stroke="#00f0ff" stroke-width="2" opacity="0.7">
    <animate attributeName="x2" values="320;315;320" dur="0.3s" repeatCount="indefinite" begin="0.15s"/>
    <animate attributeName="y2" values="340;335;340" dur="0.3s" repeatCount="indefinite" begin="0.15s"/>
  </line>
  <!-- Hands -->
  <circle cx="180" cy="340" r="6" fill="#00f0ff" opacity="0.8">
    <animate attributeName="cx" values="180;185;180" dur="0.3s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="340;335;340" dur="0.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="320" cy="340" r="6" fill="#00f0ff" opacity="0.8">
    <animate attributeName="cx" values="320;315;320" dur="0.3s" repeatCount="indefinite" begin="0.15s"/>
    <animate attributeName="cy" values="340;335;340" dur="0.3s" repeatCount="indefinite" begin="0.15s"/>
  </circle>
  <!-- Keyboard -->
  <rect x="160" y="355" width="180" height="15" fill="#0a0a15" rx="3" stroke="#00f0ff" stroke-width="1" opacity="0.8"/>
  <g fill="#00f0ff" opacity="0.4">
    <rect x="170" y="358" width="8" height="8" rx="1"/>
    <rect x="182" y="358" width="8" height="8" rx="1"/>
    <rect x="194" y="358" width="8" height="8" rx="1"/>
    <rect x="206" y="358" width="8" height="8" rx="1"/>
    <rect x="218" y="358" width="8" height="8" rx="1"/>
    <rect x="230" y="358" width="8" height="8" rx="1"/>
    <rect x="242" y="358" width="8" height="8" rx="1"/>
    <rect x="254" y="358" width="8" height="8" rx="1"/>
    <rect x="266" y="358" width="8" height="8" rx="1"/>
    <rect x="278" y="358" width="8" height="8" rx="1"/>
    <rect x="290" y="358" width="8" height="8" rx="1"/>
    <rect x="302" y="358" width="8" height="8" rx="1"/>
    <rect x="314" y="358" width="8" height="8" rx="1"/>
    <rect x="326" y="358" width="8" height="8" rx="1"/>
  </g>
  <!-- Mouse -->
  <ellipse cx="370" cy="362" rx="12" ry="18" fill="#0a0a15" stroke="#00f0ff" stroke-width="1" opacity="0.8"/>
  <line x1="370" y1="355" x2="370" y2="365" stroke="#00f0ff" stroke-width="1" opacity="0.5"/>
  <!-- Coffee Cup -->
  <rect x="420" y="340" width="20" height="25" fill="#0a0a15" stroke="#00f0ff" stroke-width="1" rx="3" opacity="0.8"/>
  <path d="M 440 348 Q 450 348 450 355 Q 450 362 440 362" fill="none" stroke="#00f0ff" stroke-width="1.5" opacity="0.6"/>
  <!-- Steam -->
  <path d="M 425 335 Q 430 325 425 315" fill="none" stroke="#00f0ff" stroke-width="1" opacity="0.4">
    <animate attributeName="d" values="M 425 335 Q 430 325 425 315;M 425 335 Q 420 325 425 315;M 425 335 Q 430 325 425 315" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="3s" repeatCount="indefinite"/>
  </path>
  <path d="M 435 335 Q 440 325 435 315" fill="none" stroke="#00f0ff" stroke-width="1" opacity="0.3">
    <animate attributeName="d" values="M 435 335 Q 440 325 435 315;M 435 335 Q 430 325 435 315;M 435 335 Q 440 325 435 315" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.05;0.3" dur="3.5s" repeatCount="indefinite"/>
  </path>
  <!-- Title Text -->
<text x="450" y="420" text-anchor="middle" fill="#00f0ff" font-family="'Fira Code', monospace" font-size="32" font-weight="bold" filter="url(#neonGlow)">
<text x="450" y="450" text-anchor="middle" fill="#7b2ff7" font-family="'Fira Code', monospace" font-size="16" opacity="0.9">
<text x="450" y="475" text-anchor="middle" fill="#fff" font-family="'Fira Code', monospace" font-size="12" opacity="0.6">
  <!-- Animated Cursor -->
  <rect x="560" y="462" width="8" height="15" fill="#00f0ff" opacity="0.8">
    <animate attributeName="opacity" values="0.8;0;0.8" dur="0.8s" repeatCount="indefinite"/>
  </rect>
  <!-- Floating Particles -->
  <circle cx="700" cy="300" r="3" fill="#00f0ff" opacity="0.6">
    <animate attributeName="cy" values="300;280;300" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="250" r="2" fill="#7b2ff7" opacity="0.5">
    <animate attributeName="cy" values="250;230;250" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="680" cy="200" r="2.5" fill="#00f0ff" opacity="0.4">
    <animate attributeName="cy" values="200;180;200" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.05;0.4" dur="5s" repeatCount="indefinite"/>
  </circle>
</svg>

<!-- Animated Status Badges -->
<p>
  <img src="https://img.shields.io/badge/🟢-Available%20for%20Hire-00C853?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/📍-Open%20Worldwide-00F0FF?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/💼-Data%20Analyst-7B2FF7?style=for-the-badge&labelColor=0D1117" />
</p>
</div>
<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    ABOUT ME SECTION                           ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<div align="center">
<img src="https://img.shields.io/badge/👤-ABOUT%20ME-00F0FF?style=flat-square&labelColor=0D1117" height="35" />
</div>
<div align="center">
plain
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
</div>
<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    EXPERTISE SECTION                          ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<div align="center">
<img src="https://img.shields.io/badge/🎯-EXPERTISE-7B2FF7?style=flat-square&labelColor=0D1117" height="35" />
</div>
<div align="center">
جدول
💼 Area	📝 What I Do
📥 Data Collection	Gathering structured & unstructured data from multiple sources
🧹 Data Cleaning	Handling missing values, duplicates, outliers & inconsistencies
🔎 Data Research & Mining	Extracting valuable patterns & insights from raw datasets
📊 Data Analysis	Statistical analysis, trend identification & hypothesis testing
📈 Dashboards	Building interactive BI dashboards with real-time KPIs
📑 Reporting	Creating automated reports with actionable recommendations
🎨 Data Visualization	Crafting compelling charts, graphs & visual storytelling
💼 Business Insights	Delivering strategic recommendations for decision makers
</div>
<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    TOOLS SECTION                              ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<div align="center">
<img src="https://img.shields.io/badge/🛠️-TOOLS%20&%20TECHNOLOGIES-FF6B6B?style=flat-square&labelColor=0D1117" height="35" />
</div>
<div align="center">
📊 Data Analysis & Business Intelligence
<p>
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Excel%20Advanced-1D6F42?style=for-the-badge&logo=microsoft-excel&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Power%20Query-2B579A?style=for-the-badge&logo=microsoft&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=dax&logoColor=black&labelColor=0D1117" />
</p>
🗄️ Databases & Query Languages
<p>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white&labelColor=0D1117" />
</p>
🐍 Programming & Analytics
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white&labelColor=0D1117" />
</p>
🛠️ Development & Productivity
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white&labelColor=0D1117" />
</p>
</div>
<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    WORKFLOW SECTION                           ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<div align="center">
<img src="https://img.shields.io/badge/🔄-MY%20WORKFLOW-00F0FF?style=flat-square&labelColor=0D1117" height="35" />
</div>
<div align="center">
plain
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
</div>
<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    CONTACT SECTION                            ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<div align="center">
<img src="https://img.shields.io/badge/📬-LET'S%20CONNECT!-7B2FF7?style=flat-square&labelColor=0D1117" height="35" />
</div>
<div align="center">
📇 Contact Information
plain
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

🔗 Connect With Me
<p>
  <a href="mailto:your.email@example.com">
    <img src="https://img.shields.io/badge/Send%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" height="40" />
  </a>
  &nbsp;&nbsp;
  <a href="https://wa.me/966501234567">
    <img src="https://img.shields.io/badge/WhatsApp%20Me-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=0D1117" height="40" />
  </a>
  &nbsp;&nbsp;
  <a href="https://linkedin.com/in/yourprofile">
    <img src="https://img.shields.io/badge/LinkedIn%20Profile-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" height="40" />
  </a>
</p>

🌟 Open to Data Analyst opportunities worldwide!
<img src="https://img.shields.io/badge/🌍-Available%20Worldwide-00C853?style=for-the-badge&labelColor=0D1117" height="35" />
</div>
<!-- ═══════════════════════════════════════════════════════════════ -->
<!-- ║                    FOOTER SECTION                             ║ -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F0FF,50:7B2FF7,100:FF6B6B&height=120&sect
