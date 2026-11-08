<div align="center">

<a href="https://github.com/SebasLoadJs">
  <img width="100%" src="./assets/sebas-banner.svg" alt="SEBAS — Software / Systems / Sound" />
</a>

<br/><br/>

### 𝚂𝚎𝚋𝚊𝚜 &nbsp; / &nbsp; Software Developer

<sub>PARAGUAY &nbsp; · &nbsp; JAVASCRIPT / TYPESCRIPT &nbsp; · &nbsp; INDEPENDENT PROJECTS</sub>

<br/><br/>

<a href="https://SebasLoadJs.github.io/"><img src="https://img.shields.io/badge/01-EXPLORE_PORTFOLIO-2876ad?style=for-the-badge&labelColor=101923" alt="Explore portfolio"/></a>
<a href="https://github.com/SebasLoadJs?tab=repositories"><img src="https://img.shields.io/badge/02-SOURCE_CODE-314a63?style=for-the-badge&labelColor=101923" alt="Repositories"/></a>
<a href="https://github.com/SebasLoadJs/NyxLink"><img src="https://img.shields.io/badge/03-NYXLINK-465e7e?style=for-the-badge&labelColor=101923" alt="NyxLink"/></a>

</div>

<br/>

<img width="100%" src="./assets/section-about.svg" alt="01 / Profile"/>

<table>
<tr>
<td width="55%" valign="top">

## Hey, I'm Sebas.

I develop software and explore the engineering behind **Discord applications, audio infrastructure, APIs and automation**.

My current interests include modular architecture, maintainable code, developer experience, and understanding how individual components behave together in a larger system.

I'm based in **Paraguay**. Most of my work is published through GitHub repositories, with projects that are continually evolving.

**I prefer showing actual repositories rather than claiming unverified production metrics.**

</td>
<td width="45%" valign="top">

### `developer.config.ts`

```ts
export const developer = {
  name: "Sebas",
  location: "Paraguay",
  interests: [
    "systems",
    "audio infrastructure",
    "APIs",
    "automation",
  ],
  process: [
    "research",
    "build",
    "test",
    "refine",
  ],
} as const;
```

</td>
</tr>
</table>

<br/>

<img width="100%" src="./assets/section-work.svg" alt="02 / Selected work"/>

<div align="center">

### SELECTED REPOSITORIES

<sub>FOUR PROJECTS / DIFFERENT PROBLEMS / REAL SOURCE CODE</sub>

</div>

<br/>

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/SebasLoadJs/NyxLink"><img src="./assets/nyxlink-card.svg" width="100%" alt="NyxLink" /></a>

**01 — NyxLink**

An audio-client project for Discord bots, exploring **Lavalink**, **NodeLink**, playback management and node communication.

<sub>TypeScript · Audio · Library development</sub>

[Explore source →](https://github.com/SebasLoadJs/NyxLink)

</td>
<td width="50%" valign="top">

<a href="https://github.com/SebasLoadJs/OBEY-YOUR-MASTER"><img src="./assets/obey-card.svg" width="100%" alt="OBEY YOUR MASTER" /></a>

**02 — OBEY YOUR MASTER**

A multipurpose Discord bot project with a wide-ranging codebase spanning music, commands, event handling, dashboard and localization.

<sub>Node.js · Discord · Modular systems</sub>

[Explore source →](https://github.com/SebasLoadJs/OBEY-YOUR-MASTER)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<br/>

<a href="https://github.com/SebasLoadJs/OguriCap-Bot"><img src="./assets/oguri-card.svg" width="100%" alt="OguriCap Bot" /></a>

**03 — OguriCap Bot**

A WhatsApp bot and automation project including plugin infrastructure, services, database-related files and frontend code.

<sub>Automation · Plugins · Web frontend</sub>

[Explore source →](https://github.com/SebasLoadJs/OguriCap-Bot)

</td>
<td width="50%" valign="top">

<br/>

<a href="https://github.com/SebasLoadJs/KONMI-BOT-"><img src="./assets/konmi-card.svg" width="100%" alt="KONMI BOT" /></a>

**04 — KONMI BOT**

A separate bot-development repository within my technical experiments.

<sub>Bots · Experiments</sub>

[Explore source →](https://github.com/SebasLoadJs/KONMI-BOT-)

</td>
</tr>
</table>

<br/>

### BEHIND THE PROJECTS

<details>
<summary><strong>↳ NyxLink / Source structure and technical focus</strong></summary>
<br/>

The repository includes real source, distribution files, examples, tests and package tooling:

```text
NyxLink/
├── src/             implementation modules
├── tests/           automated test materials
├── examples/        integration examples
├── dist/            distribution output
├── scripts/         development scripts
├── index.ts         package entry
├── package.json     dependencies and commands
└── tsconfig.json    TypeScript configuration
```

**Engineering topics:** audio client interfaces, node connection lifecycle, track handling, queue/player state, backend compatibility and error recovery.

[Read the project README](https://github.com/SebasLoadJs/NyxLink#readme) · [View source](https://github.com/SebasLoadJs/NyxLink/tree/v5.2/src) · [Explore tests](https://github.com/SebasLoadJs/NyxLink/tree/v5.2/tests)

</details>

<details>
<summary><strong>↳ OBEY / Codebase organization</strong></summary>
<br/>

OBEY is a broader Discord application than a simple music command:

```text
OBEY-YOUR-MASTER/
├── commands/        text command modules
├── slashCommands/   application commands
├── events/          event handlers
├── handlers/        shared handlers
├── dashboard/       separate web interface
├── languages/       localization resources
├── lavalink/        audio infrastructure files
├── database/        persistence layer
├── docs/            project documentation
├── test/            test materials
├── Dockerfile       container build
└── ROADMAP.md       development roadmap
```

**Engineering topics:** modularity, Discord API integration, command architecture, localization, audio playback, deployment and testing.

The presence of these modules does not imply that every planned feature is already production-ready.

[View source](https://github.com/SebasLoadJs/OBEY-YOUR-MASTER) · [Read roadmap](https://github.com/SebasLoadJs/OBEY-YOUR-MASTER/blob/master/ROADMAP.md)

</details>

<details>
<summary><strong>↳ OguriCap / Automation and services</strong></summary>
<br/>

```text
OguriCap-Bot/
├── plugins/          extensions and plugins
├── services/         backend services
├── frontend-next/    frontend application
├── database/         database files
├── lib/              shared utilities
├── test/             test materials
├── nginx/            server configuration
└── docker-compose.yml
```

**Engineering topics:** message-driven applications, extensibility, service boundaries, frontend integration and deployment.

[Explore repository](https://github.com/SebasLoadJs/OguriCap-Bot)

</details>

<br/>

<img width="100%" src="./assets/section-stack.svg" alt="03 / Technology"/>

<div align="center">

### TOOLKIT & CURRENT INTERESTS

<sub>TOOLS APPEARING IN MY WORK / NOT AN INVENTED EXPERIENCE SCORE</sub>

<br/><br/>

<img src="https://skillicons.dev/icons?i=js,ts,nodejs,git,github,docker,mongodb,postgres&theme=dark&perline=8" alt="JavaScript, TypeScript, Node.js, Git, GitHub, Docker, MongoDB, PostgreSQL" />

<br/><br/>

`discord.js` &nbsp; `Lavalink` &nbsp; `NodeLink` &nbsp; `REST APIs` &nbsp; `WebSockets`

`Node.js` &nbsp; `TypeScript` &nbsp; `Testing` &nbsp; `Software Architecture`

</div>

<br/>

### ENGINEERING APPROACH

| Area | How I think about it |
|:--|:--|
| **Architecture** | Clear boundaries, modules with responsibilities, maintainable interfaces |
| **Reliability** | Tests, failure handling, clear logging and controlled changes |
| **Developer experience** | Useful documentation, predictable configuration and understandable APIs |
| **Deployment** | Reproducible environments, environment variables and infrastructure awareness |
| **Iteration** | Research first, build deliberately, test the result, improve it |

<br/>

<img width="100%" src="./assets/section-connect.svg" alt="04 / Connect"/>

<div align="center">

## Have a project or an idea?

I'm interested in software systems, developer tooling and open-source exploration.

<br/>

<a href="https://github.com/SebasLoadJs"><img src="https://img.shields.io/badge/GITHUB-EXPLORE_REPOSITORIES-101923?style=for-the-badge&logo=github&logoColor=white" alt="Explore GitHub"/></a>
<a href="https://SebasLoadJs.github.io/"><img src="https://img.shields.io/badge/PORTFOLIO-VISIT_WEBSITE-126dab?style=for-the-badge&logo=googlechrome&logoColor=white" alt="View portfolio"/></a>

<br/><br/>

<sub>SEBAS © 2026 &nbsp; / &nbsp; SOFTWARE — SYSTEMS — SOUND</sub>

</div>
