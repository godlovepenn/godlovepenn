# gpenn

### Research Interests

**AI red teaming and adversarial robustness.** I'm actively researching how AI systems fail when facing real adversaries. My current work focuses on adversarial attacks against AI coding agents, and I'm finding that the results challenge assumptions about how these systems handle adversarial input. I'm exploring how these classes of vulnerabilities will scale as frontier models take on security-critical roles like code review, vulnerability analysis, and incident response.

**AI-driven offensive security.** I'm building tools that use AI to generate and execute attack simulations. My open-source TTPForge plugin uses Claude to create structured attack procedures from natural language, and my contributions to ForgeArmory span 17+ techniques across credential theft, persistence, and data exfiltration. I'm exploring how autonomous offensive agents can help defenders map their exposure before real adversaries do.

---

### Projects

**[Attack Simulation Claude Plugin](https://github.com/godlovepenn/attack-simulation-claude)** (2025) — Open-source Claude Code plugin for TTPForge that generates YAML-format attack procedures from natural language descriptions.

**[Effect of Packing on MalConv](https://github.com/godlovepenn/effect-of-packing-on-malconv)** (2021, M.S. research) — Empirical study testing the robustness of the MalConv CNN-based malware classifier against executable packing techniques.

---

### Open Source Contributions

**[ForgeArmory](https://github.com/facebookincubator/ForgeArmory)** — Contributed 17+ attack simulation techniques across 5 merged PRs to an open-source TTP library for TTPForge.

| PR | Focus | Techniques |
|---|---|---|
| [#148](https://github.com/facebookincubator/ForgeArmory/pull/148) | macOS Chrome InfoStealer (v1–v4) | Credential extraction, keychain access, GUI input capture |
| [#150](https://github.com/facebookincubator/ForgeArmory/pull/150) | Windows Offensive TTPs | BYOVD, WMI discovery, HTML smuggling, shellcode injection, scheduled task COM |
| [#151](https://github.com/facebookincubator/ForgeArmory/pull/151) | macOS Chrome Exploitation | Extension sideloading, secure preferences hijack, token abuse |
| [#152](https://github.com/facebookincubator/ForgeArmory/pull/152) | macOS Data Exfiltration | GitHub API, webhook, rclone, curl exfil |
| [#153](https://github.com/facebookincubator/ForgeArmory/pull/153) | macOS Persistence | Cron, login item, launch agent, launch daemon |

[View all contributions →](https://github.com/facebookincubator/ForgeArmory/pulls?q=is%3Apr+author%3Agodlovepenn)
