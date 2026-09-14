<div align="center">

# 💫 Berk Elmalı
### 💻 Computer Engineer · Systems & Low-Level · Security & Network Architect · Open Source Contributor

[![Profile Views](https://komarev.com/ghpvc/?username=berkelmali&label=Profile%20Views&color=0ea5e9&style=for-the-badge)](https://github.com/berkelmali)
[![GitHub Followers](https://img.shields.io/github/followers/berkelmali?style=for-the-badge&color=6366f1&logo=github)](https://github.com/berkelmali)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/berkelmali)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:berk9elmali9@gmail.com)

<br/>

> *"Turning complex low-level concepts, operating systems, and network protocols into elegant, secure, and resilient software."*

</div>

---

## 🏆 Open Source Highlights & Upstream Contributions

<div align="center">

### ⚔️ [OpenFrontIO](https://github.com/openfrontio/OpenFrontIO)  Online Browser RTS Game Engine
**19+ Merged Pull Requests** directly into the upstream core game engine, server architecture, and client rendering pipeline.

[![Merged PRs](https://img.shields.io/badge/Merged%20PRs-19%2B-22c55e?style=for-the-badge&logo=git&logoColor=white)](https://github.com/openfrontio/OpenFrontIO/pulls?q=is%3Apr+author%3Aberkelmali+is%3Amerged)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/openfrontio/OpenFrontIO)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://github.com/openfrontio/OpenFrontIO)
[![WebSocket](https://img.shields.io/badge/WebSocket-Realtime-orange?style=for-the-badge)](https://github.com/openfrontio/OpenFrontIO)

</div>

| Category | Key Merged Works & Innovations | PR Links |
|:---|:---|:---:|
| 🛡️ **Security & Reliability** | **Desync DoS Vulnerability Patch**: Resolved critical state desynchronization via strict majority consensus logic. Fixed WebSocket teardown crashes and protected IPC broadcast streams against connection drops. | [#3956](https://github.com/openfrontio/OpenFrontIO/pull/3956) · [#3936](https://github.com/openfrontio/OpenFrontIO/pull/3936) · [#3939](https://github.com/openfrontio/OpenFrontIO/pull/3939) |
| 🚀 **Core Game Logic & Math** | **In-flight MIRV & Warhead Cancellation**: Dynamic tactical intercept cancellation upon diplomatic alliance acceptance. Implemented converge-until-stable algorithms for `handleDeadDefender` cascades and recalculated trade ship spawn matrices per roll level. | [#5054](https://github.com/openfrontio/OpenFrontIO/pull/5054) · [#5015](https://github.com/openfrontio/OpenFrontIO/pull/5015) · [#4890](https://github.com/openfrontio/OpenFrontIO/pull/4890) · [#3940](https://github.com/openfrontio/OpenFrontIO/pull/3940) |
| 🎨 **Client & Rendering** | **Real-Time Dynamic Coastline Engine**: Synchronized ocean color shifts with instant coastline shader recalculations. Resolved ship visual hostility states and enforced player privacy with strict Anonymous Name propagation in tactical event logs. | [#5107](https://github.com/openfrontio/OpenFrontIO/pull/5107) · [#4377](https://github.com/openfrontio/OpenFrontIO/pull/4377) · [#4017](https://github.com/openfrontio/OpenFrontIO/pull/4017) |
| ⚙️ **Game Rules & AI** | Fixed defensive post tile capture mechanics (demolish on capture vs ownership transfer flaw) and patched bot self-invasion loops. | [#4016](https://github.com/openfrontio/OpenFrontIO/pull/4016) · [#4014](https://github.com/openfrontio/OpenFrontIO/pull/4014) |

---

## 🌟 Flagship Projects & Latest Versions

<table>
<tr>
<td width="50%" valign="top">

### 🖥️ [BotOS Core](https://github.com/berkelmali/BotOS) `v0.3.0`
*Custom 64-bit Linux Operating System Platform & Window Manager*

[![Version](https://img.shields.io/badge/Release-v0.3.0-a855f7?style=flat-square&logo=git)](https://github.com/berkelmali/BotOS)
[![Kernel](https://img.shields.io/badge/Kernel-Linux%20LTS-eab308?style=flat-square&logo=linux)](https://github.com/berkelmali/BotOS)
[![Stars](https://img.shields.io/github/stars/berkelmali/BotOS?style=flat-square&color=3b82f6)](https://github.com/berkelmali/BotOS)

- **Micro-Window Environment (`BotDesk`)**: Tailored X11-based compositor and display environment with zero bloated desktop dependencies.
- **`PyBridge` Runtime Architecture**: Dynamic shell REPL C-to-Python runtime integration bridge (`!` prefix execution, inline evaluation).
- **Custom SDK (`BotUI`)**: Anti-aliased FreeType font rendering, hardware event dispatching, Terminal RPG subsystem, and visual package manager (`BotPkg`).

```
C11 · Python 3.10+ · Linux Kernel · X11 · FreeType · CMake · QEMU
```

</td>
<td width="50%" valign="top">

### ⚡ [Discord-DNS](https://github.com/berkelmali/Discord-DNS) `v3.6`
*Native WinDivert DPI Bypass & Encrypted DNS Orchestration Engine*

[![Version](https://img.shields.io/badge/Release-v3.6-0ea5e9?style=flat-square&logo=github)](https://github.com/berkelmali/Discord-DNS/releases)
[![Build](https://img.shields.io/badge/WinDivert-2.2-green?style=flat-square)](https://github.com/berkelmali/Discord-DNS)
[![Stars](https://img.shields.io/github/stars/berkelmali/Discord-DNS?style=flat-square&color=3b82f6)](https://github.com/berkelmali/Discord-DNS)

- **Native DPI Bypass Engine**: Fully standalone (no GoodbyeDPI dependency); built-in packet surgery for IPv4/IPv6, TCP window sizing, and TLS ClientHello SNI fragmentation.
- **Layered Diagnostics**: Multi-tier network obstacle diagnosis (`dns_hijack`, `sni_rst`, `sni_timeout`, `tcp_blocked`).
- **Resilient DoH Proxy**: Integrated 127.0.0.1:53 DNS-over-HTTPS resolver with automated multi-provider latency benchmarking and watchdog failover.

```
Python · WinDivert 2.2 · Ctypes · Network Packet Surgery · DoH · CustomTkinter
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [NotificationKeeper](https://github.com/berkelmali/NotificationKeeper) `v1.0.0`
*Zero-Cloud Android Vault with Heuristic Recall Detection & Code Shredding*

[![Version](https://img.shields.io/badge/Release-v1.0.0-emerald?style=flat-square&logo=android)](https://github.com/berkelmali/NotificationKeeper)
[![Room DB](https://img.shields.io/badge/Database-Room%20v7-blueviolet?style=flat-square)](https://github.com/berkelmali/NotificationKeeper)
[![Stars](https://img.shields.io/github/stars/berkelmali/NotificationKeeper?style=flat-square&color=3b82f6)](https://github.com/berkelmali/NotificationKeeper)

- **Military-Grade Security**: AES-256-CBC vault backups derived with PBKDF2-HMAC-SHA256 (120,000 iterations), combined with native Android BiometricPrompt auth.
- **Recall Radar™**: Heuristic detection engine flagging silently retracted and deleted push notifications in real time.
- **Code Shredder**: Auto-destruct background worker destroying ephemeral OTP/2FA verification tokens once expired.

```
Flutter · Dart · Kotlin Native Bridge · Android Jetpack WorkManager · Room DB · AES-256
```

</td>
<td width="50%" valign="top">

### 🌙 [Lunaris](https://github.com/berkelmali/Lunaris) `v3.0`
*Deterministic Ephemeris & 17-Layer ML Engine for Celestial Prediction*

[![Version](https://img.shields.io/badge/Release-v3.0-f59e0b?style=flat-square&logo=javascript)](https://github.com/berkelmali/Lunaris)
[![Mobile](https://img.shields.io/badge/Mobile-Capacitor%20(iOS%20%2B%20Android)-blue?style=flat-square&logo=capacitor)](https://github.com/berkelmali/Lunaris)
[![Stars](https://img.shields.io/github/stars/berkelmali/Lunaris?style=flat-square&color=3b82f6)](https://github.com/berkelmali/Lunaris)

- **Pure JS ML Architecture (v3.0)**: 3-layer Multi-Layer Perceptron (MLP) with Leaky ReLU, natal attention vectors, and spatial cosine similarity with zero external dependencies.
- **Astronomical Precision**: Keplerian planetary orbits, lunar perturbation modeling (evection, variation), and Gaussian aspect orbs ($\exp(-\Delta\theta^2 / 2\sigma^2)$).
- **Cross-Platform**: Capacitor-powered Android & iOS deployment with haptic feedback and safe-area optimization.

```
Vanilla JavaScript · Machine Learning · Astronomical Ephemeris · Capacitor · Firebase
```

</td>
</tr>
</table>

### 🎮 Additional Highlights
- 🧠 **[Unity-AI-Dialogue-Tool](https://github.com/berkelmali/Unity-AI-Dialogue-Tool)** `v1.0`: Custom Unity Editor extension for asynchronous AI-powered procedural NPC dialogue generation with strict JSON schema serialization. *(C# · Unity Editor API)*
- 🃏 **[ERS-Multiplayer-game](https://github.com/berkelmali/ERS-Multiplayer-game)**: Real-time multiplayer card engine with low-latency event synchronization and state reconciliation. *(JavaScript · WebSockets)*
- 🗄️ **[SQL_FPDMS](https://github.com/berkelmali/SQL_FPDMS)** & **[SQL_University_DBMS](https://github.com/berkelmali/SQL_University_DBMS)**: Relational database architecture, normalized schemas, and high-performance transactional procedures. *(PostgreSQL / T-SQL)*

---

## 🛠️ Technical Arsenal

<div align="center">

### Core & Systems Programming
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

### Web & Fullstack Engineering
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Low-Level, Security & Systems
![Linux Kernel](https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![QEMU](https://img.shields.io/badge/QEMU-FF6600?style=for-the-badge&logo=qemu&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-06B6D4?style=for-the-badge&logo=cmake&logoColor=white)
![Network / DPI](https://img.shields.io/badge/Network-DPI%20%26%20Packets-purple?style=for-the-badge)
![Cryptography](https://img.shields.io/badge/Crypto-AES--256%20%2F%20PBKDF2-blueviolet?style=for-the-badge)
![Unity](https://img.shields.io/badge/Unity_Engine-101010?style=for-the-badge&logo=unity&logoColor=white)

### DevOps & Data
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

</div>

---

## 📊 GitHub Analytics & Activity

<div align="center">

<!-- Official & Highly Reliable Contribution Graph -->
### 📅 Contribution Graph
<img src="https://ghchart.rshah.org/0ea5e9/berkelmali" alt="Berk's GitHub Contribution Graph" width="100%" />

<br/><br/>

<!-- Verified Active GitHub Stats & Top Languages -->
<img src="https://github-stats-extended.vercel.app/api?username=berkelmali&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Berk's GitHub Stats" width="49%" />
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=berkelmali&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="47%" />

<br/><br/>

<!-- Active Demolab Streak Stats -->
<img src="https://streak-stats.demolab.com/?user=berkelmali&theme=tokyonight&hide_border=true" alt="Berk's GitHub Streak" />

</div>

---

<div align="center">

📫 **Let's connect and build something extraordinary!**  
[LinkedIn](https://linkedin.com/in/berkelmali) · [Email](mailto:berk9elmali9@gmail.com) · [GitHub](https://github.com/berkelmali)

<br/>

*Designed & maintained with care by [@berkelmali](https://github.com/berkelmali)*

</div>
