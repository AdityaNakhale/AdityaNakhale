<div align="center">

  <!-- ==================== 3D GLASSMORPHIC PROFILE HERO CARD ==================== -->
  <svg width="100%" height="340" viewBox="0 0 850 340" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- 3D Gradients -->
      <linearGradient id="bgGrad" x1="0" y1="0" x2="850" y2="340" gradientUnits="userSpaceOnUse">
        <stop offset="0%" stop-color="#0f172a" />
        <stop offset="45%" stop-color="#1e1b4b" />
        <stop offset="100%" stop-color="#090d16" />
      </linearGradient>
      
      <linearGradient id="borderGrad" x1="0" y1="0" x2="850" y2="340" gradientUnits="userSpaceOnUse">
        <stop offset="0%" stop-color="#818cf8" stop-opacity="0.8" />
        <stop offset="35%" stop-color="#c084fc" stop-opacity="0.3" />
        <stop offset="70%" stop-color="#38bdf8" stop-opacity="0.2" />
        <stop offset="100%" stop-color="#4f46e5" stop-opacity="0.7" />
      </linearGradient>

      <linearGradient id="avatarGlow" x1="0" y1="0" x2="160" y2="160" gradientUnits="userSpaceOnUse">
        <stop offset="0%" stop-color="#6366f1" />
        <stop offset="50%" stop-color="#a855f7" />
        <stop offset="100%" stop-color="#06b6d4" />
      </linearGradient>

      <linearGradient id="chipBg" x1="0" y1="0" x2="200" y2="40" gradientUnits="userSpaceOnUse">
        <stop offset="0%" stop-color="#312e81" stop-opacity="0.6" />
        <stop offset="100%" stop-color="#1e1b4b" stop-opacity="0.8" />
      </linearGradient>

      <!-- 3D Ambient Blur Spheres -->
      <radialGradient id="sphere1" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(700, 60) scale(180)">
        <stop offset="0%" stop-color="#6366f1" stop-opacity="0.4" />
        <stop offset="100%" stop-color="#6366f1" stop-opacity="0" />
      </radialGradient>
      <radialGradient id="sphere2" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(100, 270) scale(150)">
        <stop offset="0%" stop-color="#ec4899" stop-opacity="0.25" />
        <stop offset="100%" stop-color="#ec4899" stop-opacity="0" />
      </radialGradient>

      <!-- 3D Isometric Drop Shadow -->
      <filter id="cardShadow" x="-30" y="-20" width="910" height="390" filterUnits="userSpaceOnUse">
        <feDropShadow dx="0" dy="18" stdDeviation="22" flood-color="#000000" flood-opacity="0.65" />
        <feDropShadow dx="0" dy="4" stdDeviation="6" flood-color="#6366f1" flood-opacity="0.25" />
      </filter>
      
      <filter id="avatarShadow" x="-20" y="-10" width="200" height="200" filterUnits="userSpaceOnUse">
        <feDropShadow dx="0" dy="10" stdDeviation="12" flood-color="#4f46e5" flood-opacity="0.5" />
      </filter>

      <!-- Circular Avatar Clip -->
      <clipPath id="avatarClip">
        <circle cx="115" cy="140" r="62" />
      </clipPath>
    </defs>

    <g filter="url(#cardShadow)">
      <!-- Main Card Surface -->
      <rect x="15" y="15" width="820" height="300" rx="24" fill="url(#bgGrad)" />
      <!-- Ambient 3D Glow Spheres behind content -->
      <circle cx="700" cy="60" r="180" fill="url(#sphere1)" />
      <circle cx="100" cy="270" r="150" fill="url(#sphere2)" />
      
      <!-- Card Glossy Stroke -->
      <rect x="15" y="15" width="820" height="300" rx="24" stroke="url(#borderGrad)" stroke-width="1.8" />
    </g>

    <!-- Isometric Decorative Geometric Lines (Top Right) -->
    <g opacity="0.15" stroke="#ffffff" stroke-width="1">
      <line x1="680" y1="20" x2="810" y2="150" />
      <line x1="720" y1="20" x2="820" y2="120" />
      <line x1="640" y1="20" x2="800" y2="180" />
      <circle cx="760" cy="70" r="40" stroke="#818cf8" stroke-width="1.5" fill="none" />
      <circle cx="760" cy="70" r="70" stroke="#c084fc" stroke-width="1" stroke-dasharray="4 4" fill="none" />
    </g>

    <!-- 3D Floating Avatar Frame -->
    <g filter="url(#avatarShadow)">
      <circle cx="115" cy="140" r="66" fill="url(#avatarGlow)" />
      <circle cx="115" cy="140" r="63" fill="#0f172a" />
      <image href="https://github.com/AdityaNakhale.png" x="53" y="78" width="124" height="124" clip-path="url(#avatarClip)" preserveAspectRatio="xMidYMid slice" />
    </g>

    <!-- Online / Available Radar Pulse Badge -->
    <circle cx="162" cy="188" r="10" fill="#0f172a" />
    <circle cx="162" cy="188" r="7" fill="#22c55e" />
    <circle cx="162" cy="188" r="11" fill="none" stroke="#22c55e" stroke-width="1.5" opacity="0.6">
      <animate attributeName="r" values="7;15;7" dur="2.2s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.8;0;0.8" dur="2.2s" repeatCount="indefinite" />
    </circle>

    <!-- Left Column: Name & Micro Badges -->
    <text x="115" y="235" text-anchor="middle" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="800" font-size="20" fill="#ffffff">Aditya Nakhale</text>
    <text x="115" y="258" text-anchor="middle" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="500" font-size="12" fill="#94a3b8">📍 Amravati, India</text>

    <!-- Vertical 3D Divider -->
    <line x1="220" y1="45" x2="220" y2="285" stroke="#334155" stroke-width="1.2" stroke-dasharray="4 3" opacity="0.6" />

    <!-- Right Column Content -->
    <!-- Role Heading -->
    <text x="250" y="65" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="700" font-size="13" fill="#818cf8" letter-spacing="1.5">SOFTWARE &amp; BACKEND DEVELOPER</text>
    <text x="250" y="98" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="800" font-size="25" fill="#f8fafc">Designing Robust APIs &amp; Scalable Systems</text>

    <!-- Quick Attributes / Highlights -->
    <g font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="13" fill="#cbd5e1">
      <!-- Item 1 -->
      <circle cx="256" cy="130" r="4" fill="#6366f1" />
      <text x="272" y="134"><tspan font-weight="700" fill="#ffffff">BCA Batch 2026</tspan> • Sant Gadge Baba Amravati University</text>
      
      <!-- Item 2 -->
      <circle cx="256" cy="158" r="4" fill="#a855f7" />
      <text x="272" y="162"><tspan font-weight="700" fill="#ffffff">Ex-Backend Intern</tspan> @ JK Innovative Pvt. Ltd. (Cut Latency 30%)</text>
      
      <!-- Item 3 -->
      <circle cx="256" cy="186" r="4" fill="#38bdf8" />
      <text x="272" y="190"><tspan font-weight="700" fill="#ffffff">Core Focus:</tspan> Java, Spring Boot, Node.js, Nest.js &amp; PostgreSQL</text>
    </g>

    <!-- 3D Pill Metrics across Bottom Right -->
    <g transform="translate(250, 222)">
      <!-- Metric 1 -->
      <rect x="0" y="0" width="165" height="52" rx="12" fill="url(#chipBg)" stroke="#4338ca" stroke-width="1.2" />
      <text x="14" y="24" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="800" font-size="16" fill="#38bdf8">99.9% Uptime</text>
      <text x="14" y="41" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="500" font-size="11" fill="#94a3b8">1,000+ Active Users</text>

      <!-- Metric 2 -->
      <rect x="180" y="0" width="165" height="52" rx="12" fill="url(#chipBg)" stroke="#7e22ce" stroke-width="1.2" />
      <text x="194" y="24" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="800" font-size="16" fill="#c084fc">-30% Latency</text>
      <text x="194" y="41" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="500" font-size="11" fill="#94a3b8">Prisma ORM Layer</text>

      <!-- Metric 3 -->
      <rect x="360" y="0" width="180" height="52" rx="12" fill="url(#chipBg)" stroke="#0e7490" stroke-width="1.2" />
      <text x="374" y="24" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="800" font-size="16" fill="#2dd4bf">1st Prize Winner</text>
      <text x="374" y="41" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-weight="500" font-size="11" fill="#94a3b8">College Coding Contest</text>
    </g>
  </svg>

  <!-- Interactive / Typist Subtitle -->
  <a href="https://github.com/AdityaNakhale">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=818CF8&center=true&vCenter=true&width=650&lines=Java+%7C+Spring+Boot+%7C+Node.js+%7C+Nest.js+%7C+Next.js;Building+Scalable+Full-Stack+Platforms;Turning+Complex+Logic+Into+Clean+APIs" alt="Typing SVG" />
  </a>

  <!-- Quick Action Badges -->
  <p align="center">
    <a href="https://linkedin.com/in/aditya-nakhale-a63b67319">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    &nbsp;
    <a href="mailto:adityanakhale0@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    &nbsp;
    <a href="https://skills.google/public_profiles/64a46582">
      <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Google Cloud" />
    </a>
  </p>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=AdityaNakhale&label=Profile%20Views&color=6366f1&style=flat-square" alt="Profile Views" />
  </p>

</div>

---

### 💫 About Me

* 🎓 **BCA Graduate (Batch 2026)** with focused hands-on experience designing REST APIs, MVC services, and production full-stack systems[cite: 1].
* 💼 **Ex-Backend Developer Intern** at **JK Innovative Pvt. Ltd.**, building production APIs, cutting database latency by 30%, and maintaining 99.9% uptime for 1,000+ users[cite: 1].
* ⚙️ Strong foundational background in **Object-Oriented Programming (OOP)**, **MVC Architecture**, and **Database Performance Tuning**[cite: 1].
* ☁️ Active participant in the **Google Cloud Arcade** program[cite: 1].
* 🏆 **1st Prize Winner** at a College-Level Coding Competition[cite: 1].

---

### 🛠️ Tech Stack & Arsenal

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=java,spring,nodejs,nestjs,nextjs,postgres,mysql,prisma,c,cpp,js,html,css,git,github,vscode" alt="Tech Stack Icons" />
  </a>
</div>

<br />

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | Java, JavaScript, C, C++, SQL, HTML5, CSS3[cite: 1] |
| **Backend Frameworks** | Spring Boot, Node.js, Nest.js, Java Servlets, JSP, Thymeleaf[cite: 1] |
| **Databases & ORM** | PostgreSQL, MySQL, Prisma ORM, Spring Data JPA / Hibernate[cite: 1] |
| **Web & Architecture** | REST APIs, HTTP, MVC Architecture, Object-Oriented Design[cite: 1] |
| **APIs & Tools** | Git, GitHub, VS Code, Apache NetBeans, Google Maps APIs, Dropbox APIs[cite: 1] |

---

### 💼 Work Experience

<table>
  <tr>
    <td width="75%">
      <strong>Backend Developer Intern</strong> • <em>JK Innovative Pvt. Ltd.</em>[cite: 1]<br />
      <small>Jun 2025 – Sep 2025</small>[cite: 1]
      <ul>
        <li>Architected and delivered a Node.js & PostgreSQL REST API handling ~100 daily requests for a live Career Portfolio Generator[cite: 1].</li>
        <li>Built a Prisma ORM data access layer that reduced database query latency by <strong>30%</strong>[cite: 1].</li>
        <li>Delivered a Next.js / Nest.js / MySQL application supporting <strong>1,000+ users</strong> at <strong>99.9% uptime</strong> and <strong>~200ms latency</strong>[cite: 1].</li>
        <li>Integrated Dropbox APIs alongside a 5-member engineering team for secure file management across 500+ users[cite: 1].</li>
      </ul>
    </td>
    <td width="25%" align="center" valign="middle">
      <img src="https://img.shields.io/badge/Uptime-99.9%25-brightgreen?style=flat-square" alt="Uptime" /><br /><br />
      <img src="https://img.shields.io/badge/Latency-30%25_Faster-blue?style=flat-square" alt="Latency" /><br /><br />
      <img src="https://img.shields.io/badge/Users-1%2C000%2B-orange?style=flat-square" alt="Users" />
    </td>
  </tr>
</table>

---

### 🚀 Highlighted Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🍲 Food Rescue AI</h3>
      <p align="center"><em>Smart food allocation & real-time NGO dispatch platform</em>[cite: 1]</p>
      <ul>
        <li>Built full-stack service with <strong>Spring Boot</strong>, <strong>Thymeleaf</strong>, and <strong>MySQL / PostgreSQL</strong>[cite: 1].</li>
        <li>Designed a rule-based matching engine balancing proximity, shelf life, and NGO capacity[cite: 1].</li>
        <li>Integrated <strong>Google Maps Geocoding & Distance Matrix APIs</strong> for real-time travel and distance optimization[cite: 1].</li>
        <li>Managed a 4-stage tracking workflow: <code>Pending</code> ➔ <code>Allocated</code> ➔ <code>Claimed</code> ➔ <code>Rescued</code>[cite: 1].</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring Boot" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/Google_Maps-4285F4?style=flat-square&logo=google-maps&logoColor=white" alt="Google Maps" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🎓 Career Portfolio Generator</h3>
      <p align="center"><em>Automated dynamic digital portfolio builder for students</em>[cite: 1]</p>
      <ul>
        <li>Structured strictly around <strong>MVC Architecture</strong> using <strong>Java Servlets</strong>, <strong>JSP</strong>, and <strong>MySQL</strong>[cite: 1].</li>
        <li>Engineered form handling workflows to capture credentials and render responsive templates[cite: 1].</li>
        <li>Designed session management pipelines enabling instant sharing of personal portfolio pages[cite: 1].</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
        <img src="https://img.shields.io/badge/Servlets_&_JSP-007396?style=flat-square&logo=java&logoColor=white" alt="JSP" />
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
      </p>
    </td>
  </tr>
</table>

---

### 📊 GitHub Activity & Analytics

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=AdityaNakhale&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" alt="Aditya's GitHub Stats" />
  &nbsp;
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdityaNakhale&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

<div align="center">
  <br />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AdityaNakhale&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

### 📬 Get In Touch

<p align="center">
  <a href="https://linkedin.com/in/aditya-nakhale-a63b67319">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:adityanakhale0@gmail.com">
    <img src="https://img.shields.io/badge/Email-Send_Message-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,24,36&height=80&section=footer" width="100%" alt="Footer" />
</div>
