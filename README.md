# Hi, I'm Roscoe Sincero <a href="https://github.com/roscoe-sincero-sys/roscoe-sincero-sys">🫵</a>

I design SQL Server databases by day, and tinker with AI tools and old game engines by night. I talk to AI models so you don't have to.

> *Some AI agents come into our lives and quickly go. Some stay for a while, write thousands of lines of code we don't understand, break things that worked yesterday and we are never, ever the same.*
>
> *As a vibe coder, I work 12-hour shifts pressing Enter. My AI has the intelligence. I have the carpal tunnel.*

<details>
<summary>🤖 <b>More AI agent wisdom</b></summary>

> *Some AI agents are just passing ships in the night. Others linger just long enough to gaslight your entire test suite, seduce your CI/CD pipeline, delete the database migration scripts, and leave you staring at a terminal prompt wondering where your life went wrong.*
>
> *Some AI agents touch three lines and leave. Others open a PR titled "chore: simplify date formatting", touch 84 files across seven newly invented abstraction layers, wrap a single boolean in three nested generic interfaces, break the login screen in every timezone west of Greenwich, and leave 412 unit tests that all assert true === true.*
>
> *Some AI agents submit modest bug fixes. Others open "fix: typo in README" that somehow includes an updated package manifest adding 1,400 npm modules, deprecates your build pipeline, migrates the ORM to a pre-alpha dialect, and leaves a PR comment assuring you: "All changes are purely cosmetic and safe to squash-merge."*

</details>

---

## 🛠️ Tech Stack & Tooling

<p align="center">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/tech-stack-dark-mobile.svg">
    <source media="(max-width: 600px)" srcset="assets/tech-stack-light-mobile.svg">
    <source media="(prefers-color-scheme: dark)" srcset="assets/tech-stack-dark.svg">
    <img src="assets/tech-stack-light.svg" alt="Tech stack: SQL Server, T-SQL, Oracle Database, Oracle XE, PL/SQL, C#, .NET, Python, HTMX, Alpine.js, Tailwind CSS, Power BI, SSRS, Visual Studio 2022, Notepad++, GitHub Actions, Git, ChatGPT, Claude, Google Gemini, Ollama, OpenAI Codex, Claude Code, Gemini CLI, Antigravity">
  </picture>
</p>

---

## ⚡ What I Focus On Today

<p align="center">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/flip-phone-dev-mobile-dark.svg">
    <source media="(max-width: 600px)" srcset="assets/flip-phone-dev-mobile-light.svg">
    <source media="(prefers-color-scheme: dark)" srcset="assets/flip-phone-dev-desktop-dark.svg">
    <img src="assets/flip-phone-dev-desktop-light.svg" alt="Anime-style Roscoe holding a 2004 flip phone and looking confused as he tries to build a full-stack web app, while the phone screen cycles through npm install over GPRS, a memory-full warning, a Docker error, and an incoming call from Mom">
  </picture>
</p>

* **Keeping Data Out of the Junk Drawer:** I organize information so people can find what they need. I also keep track of changes-because "Who changed this?" is much easier to place blame when the computer took notes.
* **Giving AI Adult Supervision:** I get AI to help with repetitive -I mean real- work then check -I mean stare at- what it did.
* **Making Websites Behave:** I build web pages where buttons might do what you'd expect and forms most definitely forget what you typed. Small ambitions. I built a form by hand once. Now I have a three-model pull request workflow. GPT-6.1-SOL builds the form.  Opus 5.5 opens a pull request. GEMINI Flash 3.8 rubber stamps the PR. GEMINI Argon gets the credit.

---

## 🕹️ Retro Roots: Quake & Quake II (1996–1998)

<p align="center">
  <picture>
    <img src="assets/retro-roots.svg" alt="Retro arena deathmatch animation: the time limit hits just before the shot, and the scoreboard shows I Cause Lags in first place">
  </picture>
</p>

Years before trading rocket launchers for corporate Maya and attaining Moksha as an over-caffeinated prompt jockey chatting with hallucinatory LLMs, I spent the late 1990s deep in the id Software modding scene under the handles **Legion** and **I Cause Lags**, building Quake bots, movement libraries, and total combat overhauls.

A bahut special shoutout to [Jason Brownlee](https://github.com/Jason2Brownlee/) for keeping Quake ki yaadein zinda through his [Quake Bot Archive](https://github.com/Jason2Brownlee/QuakeBotArchive).  I completely forgot about [**Doombot**](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/dmbt21b3.txt) but I do remember contributing to [tutorials/guides](https://web.archive.org/web/19981203004143/http://www.inside3d.com/qctut/).

* **Stroggs Gone Mad (SGM)** *(Quake II, Nov 1998 — v1.0c)*:  
  A complete single-player combat and difficulty overhaul that cures the "turret syndrome" of vanilla Strogg units.

  <details>
  <summary><b>Features, downloads &amp; how to run it today</b></summary>

  * **Evasive Combat Maneuvers:** Re-engineered monster movement to include active lateral strafing, dodge mechanics, and dynamic positioning during fire cycles.
  * **Persistent Pursuit Logic:** Removed passive aggro limits, turning encounters into high-tempo hunts where enemies aggressively track players through geometry.
  * **Accelerated Attack Cycles:** Drastically reduced attack recovery intervals and increased projectile velocities to punish passive corner-camping.
  * **Downloads:** Available via [The Quake II Repository](https://thequake2repository.blogspot.com/2013/10/information-center.html) and [ModDB](https://www.moddb.com/games/quake-2/downloads).

  **🕹️ Running SGM on Yamagi Quake II / classic engines**

  Because SGM is a classic `gamex86.dll` mod, it runs natively on standard 32-bit source ports or vanilla-compatible 64-bit builds like [Yamagi Quake II](https://www.yamagi.org/quake2/):

  1. Download and extract the SGM archive (e.g., `sgm10c.zip`).
  2. Place the resulting folder (named `sgm` or `mad`) inside your root Quake II directory alongside `baseq2`.
  3. Launch via your modern port's command line or shortcut:
     ```bash
     yquake2.exe +set game sgm +map base1
     ```
     *(Or select the mod directly from the in-game mod menu if supported by your engine).*
  </details>

* **`norse_movetogoal` & Bot Navigation** *(Quake / QuakeC)*:  
  I wrote a replacement for Quake's built-in movement routine so bots could cross uneven ground, swim, and jump gaps.  **Navy SEALs sQuad bots v2.0.1** credited a modified version of `norse_movetogoal` v0.32 for much of its bot movement code. **CTFBot+** and **FrikBot** also credited my movement code. [Bot Movement v0.31 release notes](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/btmv31.txt) · [Navy SEALs sQuad bots v2.0.1 readme](https://www.scribd.com/document/426971606/Stuff-and-things-and-stuff) · [CTFBot+ credits](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/ctfbot%2B.txt) · [FrikBot credits preserved in the Quake Bot Archive](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/research/essays/b18_doombot.md)

* **Quake Bot Skeleton (`btsk`)**:  
  I packaged the movement code with reusable bot features such as strafing while attacking, random names, and support for player classes. Other modders could use it as a starting point for their own bot AI. [Bot Skeleton v0.23 release notes](https://github.com/Jason2Brownlee/QuakeBotArchive/blob/main/bin/btsk23.txt)
  
---

<p align="center">
  <i>"I'm here to vibe, not to transcribe." <a href="https://github.com/roscoe-sincero-sys/roscoe-sincero-sys">⭐ Star ME</a></i>
</p>
