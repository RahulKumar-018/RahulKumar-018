<!--
  ┌─────────────────────────────────────────────────────────┐
  │  RAHUL KUMAR — GitHub Profile README                    │
  │  Design: Premium Dark · Indigo Accent · Verified Only  │
  │  Built: 2026-09-27 · github.com/RahulKumar-018         │
  └─────────────────────────────────────────────────────────┘
-->

<!-- ════════════════════════════════════════════════════════
     HERO
     ════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="860" height="200" viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="heroBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   style="stop-color:#060810"/>
      <stop offset="50%"  style="stop-color:#0a0d1a"/>
      <stop offset="100%" style="stop-color:#060810"/>
    </linearGradient>
    <!-- Indigo accent glow -->
    <linearGradient id="accentLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   style="stop-color:#6366f1;stop-opacity:0"/>
      <stop offset="30%"  style="stop-color:#6366f1;stop-opacity:0.8"/>
      <stop offset="70%"  style="stop-color:#8b5cf6;stop-opacity:0.8"/>
      <stop offset="100%" style="stop-color:#8b5cf6;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   style="stop-color:#e6edf3"/>
      <stop offset="60%"  style="stop-color:#e6edf3"/>
      <stop offset="100%" style="stop-color:#8b949e"/>
    </linearGradient>
    <!-- Subtle grid pattern -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#6366f1" stroke-width="0.15" stroke-opacity="0.3"/>
    </pattern>
    <!-- Glow filter -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softGlow" x="-10%" y="-10%" width="120%" height="120%">
      <feGaussianBlur stdDeviation="1.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Base -->
  <rect width="860" height="200" rx="14" fill="url(#heroBg)"/>
  <!-- Grid overlay -->
  <rect width="860" height="200" rx="14" fill="url(#grid)" opacity="0.4"/>
  <!-- Top indigo accent line -->
  <rect x="80" y="0" width="700" height="2" rx="1" fill="url(#accentLine)">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
  </rect>
  <!-- Bottom accent line -->
  <rect x="80" y="198" width="700" height="2" rx="1" fill="url(#accentLine)">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" begin="1.5s" repeatCount="indefinite"/>
  </rect>
  <!-- Left dot -->
  <circle cx="40" cy="100" r="3" fill="#6366f1" opacity="0.6">
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
  <!-- Right dot -->
  <circle cx="820" cy="100" r="3" fill="#8b5cf6" opacity="0.6">
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="2s" begin="1s" repeatCount="indefinite"/>
  </circle>

  <!-- Terminal prompt line -->
  <text x="430" y="62" text-anchor="middle"
        font-family="'JetBrains Mono','Fira Code','Courier New',monospace"
        font-size="11" fill="#6366f1" opacity="0.7" filter="url(#softGlow)">▸ rahul@github:~$  whoami</text>

  <!-- Main name -->
  <text x="430" y="112" text-anchor="middle"
        font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif"
        font-size="54" font-weight="700" letter-spacing="-1"
        fill="url(#titleGrad)" filter="url(#softGlow)">Rahul Kumar</text>

  <!-- Role line with dots -->
  <text x="430" y="145" text-anchor="middle"
        font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif"
        font-size="13" fill="#8b949e" letter-spacing="1.5">
    <tspan fill="#6366f1">Software Developer</tspan>
    <tspan fill="#30363d">  ·  </tspan>
    <tspan>Full Stack</tspan>
    <tspan fill="#30363d">  ·  </tspan>
    <tspan>AI / ML</tspan>
  </text>

  <!-- Degree line -->
  <text x="430" y="170" text-anchor="middle"
        font-family="'JetBrains Mono','Fira Code',monospace"
        font-size="10" fill="#484f58" letter-spacing="0.5">B.Tech CSE (AI &amp; ML)  ·  Shivalik College of Engineering  ·  Dehradun</text>

  <!-- Corner brackets - premium detail -->
  <text x="18" y="24" font-family="monospace" font-size="14" fill="#6366f1" opacity="0.4">┌</text>
  <text x="834" y="24" font-family="monospace" font-size="14" fill="#6366f1" opacity="0.4">┐</text>
  <text x="18" y="195" font-family="monospace" font-size="14" fill="#6366f1" opacity="0.4">└</text>
  <text x="834" y="195" font-family="monospace" font-size="14" fill="#6366f1" opacity="0.4">┘</text>
</svg>

<!-- Typing animation — professional, restrained -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=3800&pause=1400&color=6366F1&center=true&vCenter=true&width=640&height=38&lines=Building+software+that+solves+real+problems.;95+LeetCode+problems+%E2%80%94+70-day+max+streak.;Striver+A2Z+%E2%80%94+110%2F495+problems+solved.;Oracle+OCI+Certified+%E2%80%94+Gen+AI+Professional.;Full+Stack+%E2%86%92+AI%2FML+%E2%80%94+one+commit+at+a+time." alt="Typing" />

<br/>

<!-- Social links — minimal, clean -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0A66C2)](https://linkedin.com/in/rahul-kumar-4665592a6)&nbsp;
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black&labelColor=FFA116)](https://leetcode.com/u/Rahulkumar33/)&nbsp;
[![GFG](https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=flat-square&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/rahulkufgas)&nbsp;
[![Striver](https://img.shields.io/badge/Striver%20A2Z-6366f1?style=flat-square&logo=target&logoColor=white)](https://takeuforward.org/profile/Rahul_Kumar07)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/RahulKumar-018)

</div>

<br/>

<!-- ════════════════════════════════════════════════════════
     DIVIDER
     ════════════════════════════════════════════════════════ -->
<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=2&section=header&reversal=false" width="100%"/></div>

<!-- ════════════════════════════════════════════════════════
     ABOUT
     ════════════════════════════════════════════════════════ -->

<br/>

```python
# rahul_kumar.py — who I am

class Developer:
    name       = "Rahul Kumar"
    degree     = "B.Tech CSE (AI & ML)  ·  3rd Year / 5th Sem"
    college    = "Shivalik College of Engineering, Dehradun"

    focus_now  = ["DSA (C++)", "Full Stack Development", "Software Engineering"]
    studying   = ["Striver A2Z Sheet", "LeetCode daily", "React + Backend"]
    building   = ["Projects that are practical, functional, and well-engineered"]
    direction  = "Full Stack Dev  →  ML Engineering"

    philosophy = "Understand the pattern. Build the solution. Ship it."
```

<br/>
<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=2&section=header&reversal=false" width="100%"/></div>

<!-- ════════════════════════════════════════════════════════
     TECH STACK
     ════════════════════════════════════════════════════════ -->

<br/>

<div align="center">

<h3>⚙️ Tech Stack</h3>

**Languages**<br/>
[![Skills](https://skillicons.dev/icons?i=cpp,javascript,python,html,css&theme=dark)](https://skillicons.dev)

**Tools & Environment**<br/>
[![Skills](https://skillicons.dev/icons?i=git,github,vscode,linux&theme=dark)](https://skillicons.dev)

</div>

<br/>

<div align="center">

<!-- Verified tech — flat badges, consistent style -->
![C++](https://img.shields.io/badge/C%2B%2B-primary%20language-6366f1?style=flat-square&logo=c%2B%2B&logoColor=white&labelColor=161b22)
![JavaScript](https://img.shields.io/badge/JavaScript-frontend-6366f1?style=flat-square&logo=javascript&logoColor=F7DF1E&labelColor=161b22)
![HTML/CSS](https://img.shields.io/badge/HTML%20%2F%20CSS-markup%20%26%20style-6366f1?style=flat-square&logo=html5&logoColor=E34F26&labelColor=161b22)
![Git](https://img.shields.io/badge/Git-version%20control-6366f1?style=flat-square&logo=git&logoColor=F05032&labelColor=161b22)

</div>

<br/>
<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=2&section=header&reversal=false" width="100%"/></div>

<!-- ════════════════════════════════════════════════════════
     DSA JOURNEY
     ════════════════════════════════════════════════════════ -->

<br/>

<div align="center">
<h3>📊 DSA Journey</h3>

**Roadmap:** [Striver A2Z](https://takeuforward.org/profile/Rahul_Kumar07) &nbsp;·&nbsp;
**Practice:** [LeetCode](https://leetcode.com/u/Rahulkumar33/) · [GFG](https://www.geeksforgeeks.org/profile/rahulkufgas) &nbsp;·&nbsp;
**Language:** C++

<br/>

<!-- LeetCode stats card — verified data, custom SVG -->
<svg width="540" height="160" viewBox="0 0 540 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cardBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#161b22"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="indigoBorder" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#6366f1"/>
      <stop offset="100%" style="stop-color:#8b5cf6"/>
    </linearGradient>
    <linearGradient id="totalGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#e6edf3"/>
      <stop offset="100%" style="stop-color:#c9d1d9"/>
    </linearGradient>
  </defs>
  <!-- Card -->
  <rect width="540" height="160" rx="12" fill="url(#cardBg)" stroke="#21262d" stroke-width="1"/>
  <!-- Left accent stripe -->
  <rect x="0" y="20" width="3" height="120" rx="1.5" fill="url(#indigoBorder)"/>
  <!-- LeetCode label -->
  <text x="22" y="30" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="11" fill="#6366f1" font-weight="600" letter-spacing="1">LEETCODE</text>
  <text x="516" y="30" text-anchor="end" font-family="'JetBrains Mono',monospace" font-size="10" fill="#484f58">@Rahulkumar33</text>
  <line x1="18" y1="38" x2="522" y2="38" stroke="#21262d" stroke-width="1"/>

  <!-- Total solved -->
  <text x="26" y="63" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="10" fill="#8b949e" letter-spacing="0.5">TOTAL SOLVED</text>
  <text x="26" y="96" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="42" font-weight="800" fill="url(#totalGrad)">95</text>
  <text x="88" y="96" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="14" fill="#30363d">/ 4068</text>

  <!-- Divider -->
  <line x1="150" y1="48" x2="150" y2="110" stroke="#21262d" stroke-width="1"/>

  <!-- Easy -->
  <text x="172" y="60" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="10" fill="#3fb950">● EASY</text>
  <text x="172" y="86" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="26" font-weight="700" fill="#3fb950">48</text>
  <text x="206" y="86" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="11" fill="#484f58">/ 968</text>

  <!-- Medium -->
  <text x="295" y="60" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="10" fill="#d29922">● MEDIUM</text>
  <text x="295" y="86" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="26" font-weight="700" fill="#d29922">43</text>
  <text x="331" y="86" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="11" fill="#484f58">/ 2121</text>

  <!-- Hard -->
  <text x="420" y="60" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="10" fill="#f85149">● HARD</text>
  <text x="420" y="86" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="26" font-weight="700" fill="#f85149">4</text>
  <text x="439" y="86" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="11" fill="#484f58">/ 979</text>

  <!-- Bottom stats row -->
  <line x1="18" y1="118" x2="522" y2="118" stroke="#21262d" stroke-width="1"/>
  <text x="26" y="140" font-family="'JetBrains Mono',monospace" font-size="11" fill="#8b949e">Streak <tspan fill="#e6edf3" font-weight="600">70 days 🔥</tspan></text>
  <text x="200" y="140" font-family="'JetBrains Mono',monospace" font-size="11" fill="#8b949e">Active <tspan fill="#e6edf3" font-weight="600">73 days</tspan></text>
  <text x="340" y="140" font-family="'JetBrains Mono',monospace" font-size="11" fill="#8b949e">Acceptance <tspan fill="#3fb950" font-weight="600">85.82%</tspan></text>
  <text x="26" y="156" font-family="'JetBrains Mono',monospace" font-size="10" fill="#6366f1">🏅 50 Days Badge 2026  ·  Striver A2Z: 110/495 solved</text>
</svg>

<br/><br/>

<!-- Topic Progress — verified from LeetCode tag counts -->
<svg width="560" height="300" viewBox="0 0 560 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="pb1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#4f46e5"/>
      <stop offset="100%" style="stop-color:#6366f1"/>
    </linearGradient>
    <linearGradient id="pb2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#059669"/>
      <stop offset="100%" style="stop-color:#10b981"/>
    </linearGradient>
    <linearGradient id="pb3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#7c3aed"/>
      <stop offset="100%" style="stop-color:#8b5cf6"/>
    </linearGradient>
    <linearGradient id="topicBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#161b22"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
  </defs>
  <rect width="560" height="300" rx="12" fill="url(#topicBg)" stroke="#21262d" stroke-width="1"/>
  <!-- Header -->
  <rect x="0" y="0" width="560" height="44" rx="12" fill="#161b22"/>
  <rect x="0" y="34" width="560" height="10" fill="#161b22"/>
  <rect x="0" y="0" width="560" height="3" rx="1" fill="url(#pb1)" opacity="0.7"/>
  <text x="20" y="26" font-family="-apple-system,BlinkMacSystemFont,sans-serif" font-size="12" font-weight="600" fill="#6366f1" letter-spacing="0.5">PROBLEM-SOLVING BY TOPIC</text>
  <text x="540" y="26" text-anchor="end" font-family="'JetBrains Mono',monospace" font-size="10" fill="#484f58">LeetCode tag counts</text>
  <line x1="16" y1="44" x2="544" y2="44" stroke="#21262d" stroke-width="1"/>

  <!-- Rows: label@18, bar@168, maxW=330, count@506 -->
  <text x="18" y="68" font-family="'JetBrains Mono',monospace" font-size="11.5" fill="#c9d1d9">Array</text>
  <rect x="168" y="56" width="330" height="11" rx="5.5" fill="#21262d"/>
  <rect x="168" y="56" width="330" height="11" rx="5.5" fill="url(#pb1)"/>
  <text x="506" y="68" font-family="'JetBrains Mono',monospace" font-size="10" fill="#6366f1">×74</text>

  <text x="18" y="96" font-family="'JetBrains Mono',monospace" font-size="11.5" fill="#c9d1d9">Binary Search</text>
  <rect x="168" y="84" width="330" height="11" rx="5.5" fill="#21262d"/>
  <rect x="168" y="84" width="125" height="11" rx="5.5" fill="url(#pb1)"/>
  <text x="506" y="96" font-family="'JetBrains Mono',monospace" font-size="10" fill="#6366f1">×28</text>

  <text x="18" y="124" font-family="'JetBrains Mono',monospace" font-size="11.5" fill="#c9d1d9">Two Pointers</text>
  <rect x="168" y="112" width="330" height="11" rx="5.5" fill="#21262d"/>
  <rect x="168" y="112" width="90" height="11" rx="5.5" fill="url(#pb1)"/>
  <text x="506" y="124" font-family="'JetBrains Mono',monospace" font-size="10" fill="#6366f1">×20</text>

  <text x="18" y="152" font-family="'JetBrains Mono',monospace" font-size="11.5" fill="#c9d1d9">Math</text>
  <rect x="168" y="140" width="330" height="11" rx="5.5" fill="#21262d"/>
  <rect x="168" y="140" width="80" height="11" rx="5.5" fill="url(#pb2)"/>
  <text x="506" y="152" font-family="'JetBrains Mono',monospace" font-size="10" fill="#6366f1">×18</text>

  <text x="18" y="180" font-family="'JetBrains Mono',monospace" font-size="11.5" fill="#c9d1d9">Sorting</text>
  <rect x="168" y="168" width="330" height="11" rx="5.5" fill="#21262d"/>
  <rect x="168" y="168" width="76" height="11" rx="5.5" fill="url(#pb2)"/>
  <text x="506" y="180" font-family="'JetBrains Mono',monospace" font-size="10" fill="#6366f1">×17</text>

  <text x="18" y="208" font-family="'JetBrains Mono',monospace" font-size="11.5" fill="#c9d1d9">Hash Table</text>
  <rect x="168" y="196" width="330" height="11" rx="5.5" fill="#21262d"/>
  <rect x="168" y="196" width="58" height="11" rx="5.5" fill="url(#pb2)"/>
  <text x="506" y="208" font-family="'JetBrains Mono',monospace" font-size="10" fill="#6366f1">×13</text>

  <text x="18" y="236" font-family="'JetBrains Mono',monospace" font-size="11.5" fill="#c9d1d9">Dynamic Prog.</text>
  <rect x="168" y="224" width="330" height="11" rx="5.5" fill="#21262d"/>
  <rect x="168" y="224" width="32" height="11" rx="5.5" fill="url(#pb3)"/>
  <text x="506" y="236" font-family="'JetBrains Mono',monospace" font-size="10" fill="#6366f1">×7</text>

  <text x="18" y="264" font-family="'JetBrains Mono',monospace" font-size="11.5" fill="#c9d1d9">Divide &amp; Conquer</text>
  <rect x="168" y="252" width="330" height="11" rx="5.5" fill="#21262d"/>
  <rect x="168" y="252" width="27" height="11" rx="5.5" fill="url(#pb3)"/>
  <text x="506" y="264" font-family="'JetBrains Mono',monospace" font-size="10" fill="#6366f1">×6</text>

  <text x="18" y="292" font-family="'JetBrains Mono',monospace" font-size="11.5" fill="#8b949e">Backtracking</text>
  <rect x="168" y="280" width="330" height="11" rx="5.5" fill="#21262d"/>
  <rect x="168" y="280" width="9" height="11" rx="5.5" fill="url(#pb3)"/>
  <text x="506" y="292" font-family="'JetBrains Mono',monospace" font-size="10" fill="#484f58">×1</text>
</svg>

</div>

> 💡 Pattern recognition over memorization. Understand *why* a solution works, not just *that* it works.

<details>
<summary><b>▸ Striver A2Z Roadmap — Detailed Topic Status</b></summary>

<br/>

```
COMPLETED  ✅
│
├─ Fundamentals  ──  C++ STL · Complexity Analysis · Basic Mathematics
│
├─ Arrays  ×74   ──  Traversal · Sorting · Two Pointer · Sliding Window
│                    Prefix Sum · Kadane · Hashing
│
├─ Binary Search ×28 ─  1D / 2D · Rotated Arrays · Answer-based BS
│
├─ Sorting  ──  Bubble · Selection · Insertion · Merge Sort · Quick Sort
│
└─ Strings  ──  Two-pointer techniques · Palindromes (active)

IN PROGRESS  🔄
│
├─ Strings (continuing)  ──  Sliding window · Pattern matching
│
└─ Recursion & Backtracking  ──  Subsets · Permutations

UPCOMING  ⏳
│
└─ Stack · Queue · Linked List · Trees · Graphs
   Heaps · Greedy · DP (deeper) · Tries · Segment Trees
```

</details>

<br/>
<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=2&section=header&reversal=false" width="100%"/></div>

<!-- ════════════════════════════════════════════════════════
     PROJECTS
     ════════════════════════════════════════════════════════ -->

<br/>

<div align="center">
<h3>🛠️ Projects</h3>
<sub>Verified repositories — built, committed, and active on GitHub</sub>
</div>

<br/>

<!-- Project 1: DSA-_OS -->
<table>
<tr>
<td width="100%">

**[DSA-_OS](https://github.com/RahulKumar-018/DSA-_OS)** &nbsp;&nbsp; ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Stars](https://img.shields.io/github/stars/RahulKumar-018/DSA-_OS?style=flat-square&color=6366f1&labelColor=161b22)

*Striver A2Z DSA Sheet — C++ solution archive*

My primary DSA repository. Contains C++ implementations of problems from the Striver A2Z sheet, organized by topic. Active and continuously updated as I progress through the roadmap.

- Organized by topic: Arrays → Binary Search → Sorting → Strings → (in progress)
- Clean, readable C++ code — focused on understanding patterns
- Tracking 110/495 problems completed across the A2Z sheet

[![View Repo →](https://img.shields.io/badge/View%20Repository-6366f1?style=flat-square&logo=github&logoColor=white)](https://github.com/RahulKumar-018/DSA-_OS)

</td>
</tr>
</table>

<br/>

<!-- Project 2: Ultimate-DSA-Tracker -->
<table>
<tr>
<td width="100%">

**[Ultimate-DSA-Tracker](https://github.com/RahulKumar-018/Ultimate-DSA-Tracker)** &nbsp;&nbsp; ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) ![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Stars](https://img.shields.io/github/stars/RahulKumar-018/Ultimate-DSA-Tracker?style=flat-square&color=6366f1&labelColor=161b22) ![Pages](https://img.shields.io/badge/GitHub%20Pages-live-3fb950?style=flat-square)

*Interactive DSA progress tracker — deployed on GitHub Pages*

A frontend web application for tracking Striver A2Z DSA sheet progress. Built with HTML, CSS, and vanilla JavaScript. Deployed live via GitHub Pages.

- Progress tracking UI across DSA topics
- Client-side JavaScript logic — no build tools, pure web
- Live deployment on GitHub Pages

[![View Repo →](https://img.shields.io/badge/View%20Repository-6366f1?style=flat-square&logo=github&logoColor=white)](https://github.com/RahulKumar-018/Ultimate-DSA-Tracker)&nbsp;
[![Live Demo →](https://img.shields.io/badge/Live%20Demo-3fb950?style=flat-square&logo=github&logoColor=white)](https://rahulkumar-018.github.io/Ultimate-DSA-Tracker)

</td>
</tr>
</table>

<br/>

<!-- Project 3: Problems_solved -->
<table>
<tr>
<td width="100%">

**[Problems-Solved](https://github.com/RahulKumar-018/Problems_solved)**

*NeetCode.io problem submissions archive*

A personal repository of problem solutions from NeetCode.io — supplementary practice alongside the Striver A2Z roadmap.

[![View Repo →](https://img.shields.io/badge/View%20Repository-6366f1?style=flat-square&logo=github&logoColor=white)](https://github.com/RahulKumar-018/Problems_solved)

</td>
</tr>
</table>

<br/>
<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=2&section=header&reversal=false" width="100%"/></div>

<!-- ════════════════════════════════════════════════════════
     GITHUB STATS
     ════════════════════════════════════════════════════════ -->

<br/>

<div align="center">
<h3>📈 GitHub Activity</h3>

<img height="175" src="https://github-readme-stats.vercel.app/api?username=RahulKumar-018&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=6366f1&icon_color=6366f1&text_color=8b949e&ring_color=6366f1&count_private=true&hide=prs,issues" alt="GitHub Stats" />
&nbsp;&nbsp;
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RahulKumar-018&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=6366f1&text_color=8b949e&langs_count=5" alt="Top Languages" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=RahulKumar-018&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=21262d&ring=6366f1&fire=f85149&currStreakLabel=6366f1&sideLabels=8b949e&dates=8b949e&sideNums=e6edf3&currStreakNum=e6edf3" alt="Streak" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=RahulKumar-018&bg_color=0d1117&color=6366f1&line=4f46e5&point=6366f1&area=true&area_color=4f46e5&hide_border=true" alt="Activity Graph" />

</div>

<br/>
<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=2&section=header&reversal=false" width="100%"/></div>

<!-- ════════════════════════════════════════════════════════
     CERTIFICATIONS
     ════════════════════════════════════════════════════════ -->

<br/>

<div align="center">
<h3>🏅 Certifications</h3>

<table>
<tr>
<td align="center" width="50%">

[![Oracle](https://img.shields.io/badge/Oracle%20OCI%202025-Gen%20AI%20Professional-F80000?style=flat-square&logo=oracle&logoColor=white&labelColor=1a1a1a)](https://catalog-education.oracle.com/ords/certview/sharebadge?id=3ECC7CF9CFDEC35BF789347D467CD689F53E901574AAE0911E909165CE0437BA)

`LLMs · RAG · Vector DB · LangChain · OCI GenAI`

[Verify →](https://catalog-education.oracle.com/ords/certview/sharebadge?id=3ECC7CF9CFDEC35BF789347D467CD689F53E901574AAE0911E909165CE0437BA)

</td>
<td align="center" width="50%">

[![Oracle](https://img.shields.io/badge/Oracle%20OCI%202025-AI%20Foundations-F80000?style=flat-square&logo=oracle&logoColor=white&labelColor=1a1a1a)](https://catalog-education.oracle.com/ords/certview/sharebadge?id=536B7DA1A445B06AE9B1ABEECAA2542721D3C2B9028B721D566112844367C634)

`ML · Deep Learning · NLP · Computer Vision`

[Verify →](https://catalog-education.oracle.com/ords/certview/sharebadge?id=536B7DA1A445B06AE9B1ABEECAA2542721D3C2B9028B721D566112844367C634)

</td>
</tr>
</table>

</div>

<br/>
<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=2&section=header&reversal=false" width="100%"/></div>

<!-- ════════════════════════════════════════════════════════
     ENGINEERING JOURNEY
     ════════════════════════════════════════════════════════ -->

<br/>

<div align="center">
<h3>🗺️ Engineering Journey</h3>
</div>

```
2025
 ├─ Enrolled: B.Tech CSE (AI & ML) — Shivalik College of Engineering
 └─ Certified: Oracle OCI AI Foundations + Gen AI Professional

2026  ← current
 ├─ DSA: Striver A2Z — 110/495 problems completed
 ├─ LeetCode: 95 solved · 70-day max streak · 50 Days Badge 🏅
 ├─ Built: Ultimate-DSA-Tracker (HTML/CSS/JS → GitHub Pages)
 ├─ Built: DSA-_OS (C++ solutions archive, active)
 └─ Focus: Full Stack Development + Software Engineering

→ Next: Internship-ready Software / Full Stack Developer
→ Long-term: Machine Learning Engineering
```

<br/>
<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=2&section=header&reversal=false" width="100%"/></div>

<!-- ════════════════════════════════════════════════════════
     CURRENT FOCUS
     ════════════════════════════════════════════════════════ -->

<br/>

<div align="center">

<h3>🎯 Current Focus</h3>

| | Area | Status |
|:---:|:---|:---:|
| 🔢 | **DSA** — Striver A2Z in C++, daily LeetCode | Active |
| 🌐 | **Full Stack** — React + Backend fundamentals | Learning |
| 📐 | **Software Engineering** — Clean code, Git, system thinking | Practicing |
| 🤖 | **AI / ML** — OCI certified, building foundations | Long-term |

</div>

<br/>
<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=2&section=header&reversal=false" width="100%"/></div>

<!-- ════════════════════════════════════════════════════════
     CONNECT
     ════════════════════════════════════════════════════════ -->

<br/>

<div align="center">

<h3>🤝 Connect</h3>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rahul_Kumar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-kumar-4665592a6)
[![LeetCode](https://img.shields.io/badge/LeetCode-Rahulkumar33-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Rahulkumar33/)
[![GFG](https://img.shields.io/badge/GeeksforGeeks-rahulkufgas-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/rahulkufgas)
[![Striver](https://img.shields.io/badge/Striver%20A2Z-Rahul__Kumar07-6366f1?style=for-the-badge)](https://takeuforward.org/profile/Rahul_Kumar07)

</div>

<!-- ════════════════════════════════════════════════════════
     FOOTER
     ════════════════════════════════════════════════════════ -->

<br/>

<div align="center">

<svg width="860" height="56" viewBox="0 0 860 56" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerBg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   style="stop-color:#060810"/>
      <stop offset="50%"  style="stop-color:#0a0d1a"/>
      <stop offset="100%" style="stop-color:#060810"/>
    </linearGradient>
    <linearGradient id="footerLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   style="stop-color:#6366f1;stop-opacity:0"/>
      <stop offset="30%"  style="stop-color:#6366f1;stop-opacity:0.6"/>
      <stop offset="70%"  style="stop-color:#8b5cf6;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#8b5cf6;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="860" height="56" rx="10" fill="url(#footerBg)"/>
  <rect x="80" y="0" width="700" height="1.5" rx="1" fill="url(#footerLine)"/>
  <text x="430" y="26" text-anchor="middle"
        font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif"
        font-size="12" fill="#8b949e">
    Solving problems consistently · Building things that work · Getting better every week
  </text>
  <text x="430" y="46" text-anchor="middle"
        font-family="'JetBrains Mono',monospace"
        font-size="10" fill="#484f58">github.com/RahulKumar-018 · 2026</text>
</svg>

</div>
