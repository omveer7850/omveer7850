<!--
  ============================================================
  GITHUB PROFILE README — omveer7850
  ------------------------------------------------------------
  This file is optimized to be copied directly into your GitHub
  profile repository: https://github.com/omveer7850/omveer7850
  ============================================================
-->

<div align="center">

<!-- NATIVE ANIMATED SVG BANNER (Zero-dependency, 100% reliable, responsive) -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 260" width="100%" height="260" style="border-radius: 12px; overflow: hidden;">
  <defs>
    <!-- Background Space Gradient -->
    <linearGradient id="bg-gradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#090d16" />
      <stop offset="50%" stop-color="#0f172a" />
      <stop offset="100%" stop-color="#030712" />
    </linearGradient>
    
    <!-- Neon Purple/Indigo Gradient for Primary text -->
    <linearGradient id="neon-indigo" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#6366F1" />
      <stop offset="50%" stop-color="#8B5CF6" />
      <stop offset="100%" stop-color="#D946EF" />
    </linearGradient>

    <!-- Neon Cyan/Blue Gradient for Secondary highlights -->
    <linearGradient id="neon-cyan" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#06B6D4" />
      <stop offset="50%" stop-color="#3B82F6" />
      <stop offset="100%" stop-color="#00F2FE" />
    </linearGradient>
    
    <!-- Glow filter -->
    <filter id="glow-effect" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="8" result="blur" />
      <feComposite in="SourceGraphic" in2="blur" operator="over" />
    </filter>
  </defs>

  <style>
    @keyframes pulse-glow {
      0% { opacity: 0.15; }
      50% { opacity: 0.35; }
      100% { opacity: 0.15; }
    }
    @keyframes floating-item {
      0% { transform: translateY(0px) rotate(0deg); }
      50% { transform: translateY(-10px) rotate(5deg); }
      100% { transform: translateY(0px) rotate(0deg); }
    }
    @keyframes draw-line {
      0% { stroke-dashoffset: 800; }
      100% { stroke-dashoffset: 0; }
    }
    @keyframes text-fade {
      0% { opacity: 0; transform: translateY(15px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    
    .text-title {
      font-family: 'Inter', -apple-system, sans-serif;
      font-weight: 800;
      font-size: 44px;
      fill: url(#neon-indigo);
      filter: drop-shadow(0px 4px 12px rgba(139, 92, 246, 0.4));
      animation: text-fade 1.2s cubic-bezier(0.16, 1, 0.3, 1) forwards;
    }
    .text-subtitle {
      font-family: 'Fira Code', monospace;
      font-size: 19px;
      font-weight: 600;
      fill: #f1f5f9;
      animation: text-fade 1.6s cubic-bezier(0.16, 1, 0.3, 1) forwards;
    }
    .text-tagline {
      font-family: 'Inter', sans-serif;
      font-size: 13px;
      fill: #94a3b8;
      letter-spacing: 0.5px;
      animation: text-fade 2s cubic-bezier(0.16, 1, 0.3, 1) forwards;
    }
    .grid-lines {
      opacity: 0.05;
      stroke: #6366F1;
      stroke-width: 1;
    }
    .glow-circle-1 {
      animation: pulse-glow 8s ease-in-out infinite;
    }
    .glow-circle-2 {
      animation: pulse-glow 6s ease-in-out infinite alternate;
    }
    .floating-particle {
      animation: floating-item 7s ease-in-out infinite;
    }
    .animated-border {
      stroke-dasharray: 800;
      stroke-dashoffset: 800;
      animation: draw-line 2.5s cubic-bezier(0.22, 1, 0.36, 1) forwards;
    }
  </style>

  <!-- Background Rect -->
  <rect width="820" height="260" rx="12" fill="url(#bg-gradient)" />

  <!-- Background Decorative Grid Lines -->
  <g class="grid-lines">
    <line x1="0" y1="40" x2="820" y2="40" />
    <line x1="0" y1="80" x2="820" y2="80" />
    <line x1="0" y1="120" x2="820" y2="120" />
    <line x1="0" y1="160" x2="820" y2="160" />
    <line x1="0" y1="200" x2="820" y2="200" />
    <line x1="80" y1="0" x2="80" y2="260" />
    <line x1="160" y1="0" x2="160" y2="260" />
    <line x1="240" y1="0" x2="240" y2="260" />
    <line x1="320" y1="0" x2="320" y2="260" />
    <line x1="400" y1="0" x2="400" y2="260" />
    <line x1="480" y1="0" x2="480" y2="260" />
    <line x1="560" y1="0" x2="560" y2="260" />
    <line x1="640" y1="0" x2="640" y2="260" />
    <line x1="720" y1="0" x2="720" y2="260" />
  </g>

  <!-- Glowing background ambiances -->
  <circle class="glow-circle-1" cx="150" cy="100" r="140" fill="#6366F1" opacity="0.25" filter="url(#glow-effect)" />
  <circle class="glow-circle-2" cx="680" cy="160" r="120" fill="#06B6D4" opacity="0.2" filter="url(#glow-effect)" />

  <!-- Animated Floating Particles -->
  <circle class="floating-particle" cx="720" cy="60" r="7" fill="#00F2FE" opacity="0.6" style="animation-delay: 0s;" />
  <circle class="floating-particle" cx="100" cy="200" r="5" fill="#8B5CF6" opacity="0.5" style="animation-delay: 2.5s;" />
  <polygon class="floating-particle" points="410,35 415,45 405,45" fill="#6366F1" opacity="0.4" style="animation-delay: 1.2s;" />

  <!-- Name and Details -->
  <g transform="translate(410, 0)">
    <!-- Main Title -->
    <text y="105" text-anchor="middle" class="text-title">Omveer Singh</text>
    
    <!-- Subtitle -->
    <text y="152" text-anchor="middle" class="text-subtitle">Full-Stack Developer · Java &amp; DSA</text>

    <!-- Tagline / Affiliations -->
    <text y="192" text-anchor="middle" class="text-tagline">B.Tech ECE Undergrad @ BIT Mesra (2024 - 2028)</text>
  </g>

  <!-- Glowing Accent Line -->
  <line class="animated-border" x1="40" y1="225" x2="780" y2="225" stroke="url(#neon-cyan)" stroke-width="2.5" stroke-linecap="round" />
</svg>

<br/><br/>

<!-- DYNAMIC TYPING SVG SUB-HEADER -->
<a href="https://github.com/omveer7850">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2500&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=Building+highly+scalable+web+applications;800%2B+DSA+problems+solved+on+LeetCode;React+%C2%B7+Node.js+%C2%B7+Express+%C2%B7+Supabase;Always+learning%2C+always+building" alt="Typing SVG" />
</a>

<br/>

<!-- ===================== CONNECT ROW (STYLISH BADGES) ===================== -->

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/omveer-singh-shekhawat)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/omveer_01/)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/o7083qgxu)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:o70836964@gmail.com)

</div>

<br/>

<!-- ===================== PROFILE OVERVIEW ===================== -->

### 🧭 Overview

<table width="100%">
<tr>
<td width="58%" valign="top">

I am an **Electronics and Communication Engineering (ECE)** undergraduate student at **BIT Mesra** (Class of 2028). I specialize in building complete, production-ready web applications from scratch, leveraging modern technologies like **React/Vite** for responsive frontends and **Node.js/Express/Supabase** for robust backends. 

Alongside full-stack engineering, I've solved **800+ algorithmic problems** on LeetCode and competitive programming platforms, combining deep Java knowledge with data structures and algorithms to design clean, optimized code.

* 🚀 **Currently Building:** Full-stack developer tools & CP analytics dashboards.
* 🤝 **Looking to Collaborate:** On open-source projects, SaaS products, and DSA visualizers.
* 🧠 **Tech Focus:** System Design, High-performance APIs, Database Optimizations.

</td>
<td width="42%" valign="top">

#### 📌 Quick Profile

| Detail | Info |
|---|---|
| 🎓 **Education** | B.Tech ECE, BIT Mesra |
| 📅 **Graduation** | May 2028 |
| 💻 **Core Stack** | JavaScript, React, Node.js, Java |
| 🧩 **DSA Submissions** | 800+ solved across platforms |
| 🚀 **Live Projects** | Full-stack platform live on Vercel |
| 📍 **Status** | Open to internships & collabs |

</td>
</tr>
</table>

<br/>

<!-- ===================== TECH STACK ===================== -->

### 🛠️ Tech Stack & Skills

<table width="100%">
  <tr>
    <td width="20%" valign="top" align="center">
      <strong>Languages</strong><br/><br/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
    </td>
    <td width="20%" valign="top" align="center">
      <strong>Frontend</strong><br/><br/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/><br/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
    </td>
    <td width="20%" valign="top" align="center">
      <strong>Backend</strong><br/><br/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
    </td>
    <td width="20%" valign="top" align="center">
      <strong>Databases</strong><br/><br/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
    </td>
    <td width="20%" valign="top" align="center">
      <strong>DevOps & Tools</strong><br/><br/>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
    </td>
  </tr>
</table>

<br/>

<!-- ===================== FEATURED PROJECTS ===================== -->

### 🚀 Highlighted Work

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>💻 CP Tracker (Competitive Programming Analytics)</h4>
      <p>A data-rich, centralized platform that synchronizes handles and visualizes performance statistics across LeetCode, Codeforces, AtCoder, and CodeChef.</p>
      <ul>
        <li>Interactive charts for rating history and peak benchmarking.</li>
        <li>Built-in scheduler tracking upcoming contests globally.</li>
        <li>Curated DSA Sheet trackers (Grind 169, Striver A2Z, Blind 75).</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/Node-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
      </p>
      <a href="https://cp-profile-hub.vercel.app/"><b>🌐 Demo</b></a> | <a href="https://github.com/omveer7850/cp-analytics"><b>💻 Codebase</b></a>
    </td>
    <td width="50%" valign="top">
      <h4>🏏 IPL Winner Predictor Pro (Machine Learning Web App)</h4>
      <p>An interactive predictive dashboard that evaluates matches and forecasts IPL game-winners using historical statistics and real-time team selections.</p>
      <ul>
        <li>Trained using Python classifiers on extensive match logs.</li>
        <li>Deployed as a clean, interactive Streamlit application.</li>
        <li>Responsive UI for exploring match-specific probability graphs.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
      </p>
      <a href="https://ipl-winner-predictor-pro-usumldp54ltjak2zsfuy8e.streamlit.app/"><b>🌐 Demo</b></a> | <a href="https://github.com/omveer7850/IPL-Winner-Predictor-Pro"><b>💻 Codebase</b></a>
    </td>
  </tr>
</table>

<br/>

<!-- ===================== GITHUB DASHBOARD ===================== -->

### 📊 GitHub Activity & Analytics

<table width="100%">
  <tr>
    <td width="50%" valign="top" align="center">
      <img src="https://streak-stats.demolab.com?user=omveer7850&theme=dark&hide_border=true&background=0F172A&ring=6366F1&fire=06B6D4&currStreakLabel=E2E8F0" width="100%" alt="Omveer's Streak Stats" />
    </td>
    <td width="50%" valign="top" align="center">
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=omveer7850&bg_color=0F172A&color=E2E8F0&line=6366F1&point=06B6D4&hide_border=true" width="100%" alt="Omveer's Contribution Graph" />
    </td>
  </tr>
</table>

<br/>

<!-- ===================== ACHIEVEMENTS ===================== -->

### 🎖️ Achievements & Highlights

<table width="100%">
  <tr>
    <td width="25%" align="center">
      <h3>🏆 800+</h3>
      <p>LeetCode Solved</p>
    </td>
    <td width="25%" align="center">
      <h3>🧩 DSA</h3>
      <p>Advanced Concepts</p>
    </td>
    <td width="25%" align="center">
      <h3>⚡ Shipped</h3>
      <p>Production Apps</p>
    </td>
    <td width="25%" align="center">
      <h3>🎓 ECE '28</h3>
      <p>BIT Mesra</p>
    </td>
  </tr>
</table>

<br/>

<div align="center">
  <sub>Designed with ❤️ by Omveer Singh | Visitor Counter: <img src="https://profile-counter.glitch.me/omveer7850/count.svg" alt="Visitor Counter" height="15px" style="vertical-align: middle;"/></sub>
</div>
