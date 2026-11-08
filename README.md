# Hi, I'm Antonio Martínez Alemán 👋

**Computer Engineering student at the [University of La Laguna](https://www.ull.es)** (Tenerife, Spain).
I like knowing how things work underneath, from logic gates and assembly up to operating systems and cryptography,
and I like shipping real products: right now a **production forecasting platform** with machine learning, a serverless
back end and a native iOS app.

- 🌊 Building and running a **production ocean & weather forecasting platform** for the Canary Islands (private repo, demo on request)
- 🧠 **Applied machine learning** validated against real measurements: buoys, weather stations, tide gauges
- 📱 **iOS development** with Xcode: Capacitor app, SwiftUI/WidgetKit widget, push notifications (APNs)
- ☁️ **Serverless & edge**: Cloudflare Pages, Workers, KV and D1 (SQLite), CI/CD with GitHub Actions
- 🔐 Background in **applied cryptography**, systems and network security
- 📫 Reach me at **tony.martinezaleman@gmail.com**

---

## 🚀 Featured: ocean & weather forecasting platform *(private, in production)*

A surf and ocean forecasting product for the 8 Canary Islands (100+ locations), live on web and iPhone.

- **Multi-model forecasts corrected in real time** with offshore buoys, coastal weather stations and tide gauges: wave error in southern Tenerife **46 → 16 cm**, 1–24 h wave error **−27 %**, live wind correction **−61 %** now-cast error, tide times **28 → 2 min**.
- **Machine learning in production**: gradient-boosting buoy model with **conformal prediction intervals** (p10–p90 covers 80 % of measurements), trained in Python, exported to JSON and evaluated in JavaScript at the edge with exact parity; monthly automated retraining.
- **~50 reproducible experiments** with written reports, including the ones that failed (e.g. a model that only learned to imitate the physics model, or terrain-based wind sheltering that did not hold up across 57 stations). Only what beats real measurements ships.
- **Serverless architecture**: per-region computation to fit edge CPU limits, KV caching, D1 for accounts and alerts, scheduled workers with e-mail monitoring, strict CSP and rate limiting.
- **Native iOS app** (Capacitor 8 + SwiftUI widget, XcodeGen): works **offline** from the beach, home and lock-screen widgets, native notifications sent over HTTP/2, over-the-air updates.
- **Product details**: user accounts (magic link / one-time code), custom alerts, user-created spots with a coastline-analysis wizard, bilingual (ES/EN), WCAG 2.1 AA (0 axe violations), ~200 automated tests.

`Python` `scikit-learn` `pandas` `xarray` `JavaScript` `Cloudflare Workers / KV / D1` `SQL` `Swift / SwiftUI` `Xcode` `Capacitor` `GitHub Actions`

---

## 🛠️ Tech stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%20%2F%20CSS-E34F26?style=flat-square&logo=html5&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-848484?style=flat-square)
![MIPS Assembly](https://img.shields.io/badge/MIPS%20Assembly-6E4C13?style=flat-square)
![Prolog](https://img.shields.io/badge/Prolog-E61B23?style=flat-square)

**Machine learning & data**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![xarray](https://img.shields.io/badge/xarray%20·%20NetCDF%20·%20GRIB-2C7FB8?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Cloud, web & mobile**
![Cloudflare](https://img.shields.io/badge/Cloudflare%20Workers%20·%20KV%20·%20D1-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Tools**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Make](https://img.shields.io/badge/Make-427819?style=flat-square&logo=gnu&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

---

## 🎓 University projects

| Project | What it is | Stack |
|---------|-----------|-------|
| 🔐 [**Computer Systems Security**](https://github.com/AntonioMartinezAleman/Seguridad-en-Sistemas-Informaticos) | From-scratch implementations of **AES (+CBC), ChaCha20, SNOW 3G, RSA, digital signatures, elliptic-curve crypto, Diffie-Hellman** and a **BB84** quantum key distribution simulation | C++, Python |
| 🐧 [**Operating Systems**](https://github.com/AntonioMartinezAleman/Sistemas-Operativos) | `netcp`, a UDP file-transfer tool built on POSIX sockets and signals, and `scdebug`, a Bash wrapper around `strace` for tracing system calls | C++, Bash |
| 🤖 [**Artificial Intelligence**](https://github.com/AntonioMartinezAleman/Inteligencia-Artificial) | BFS/DFS graph search, **A\*** maze solver, Prolog knowledge bases and **k-means** clustering on Iris | C++, Prolog, Python |
| 🔤 [**Computability & Algorithms**](https://github.com/AntonioMartinezAleman/Computabilidad-y-Algoritmia) | **Finite automata simulator**, CFG to **Chomsky Normal Form** converter and a regex-based code analyzer | C++ |
| 🧮 [**Advanced Algorithms & Data Structures**](https://github.com/AntonioMartinezAleman/Algoritmos-y-Estructuras-de-datos-Avanzada) | Arbitrary-precision arithmetic, generic **hash tables** and a templated **sorting** library | C++ (templates, OOP) |
| 🖥️ [**Computer Structure**](https://github.com/AntonioMartinezAleman/Estructura-de-Computadores) | A 4-bit **ALU** and a **single-cycle microcontroller** designed in hardware description language | Verilog |

<details>
<summary>More coursework</summary>

- ⚙️ [Computer Principles](https://github.com/AntonioMartinezAleman/Principios-de-Computadores): MIPS assembly programming
- 💻 [Basic Computing](https://github.com/AntonioMartinezAleman/Informatica-Basica): C++ fundamentals and Linux

</details>
