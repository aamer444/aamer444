<div align="center">

<img src="assets/motion/hero.svg" width="100%" alt="Mohammad Aamer — Backend Engineer, Node.js, TypeScript, NestJS. 5+ years experience." />

<br/><br/>

<a href="https://github.com/aamer444"><img src="https://img.shields.io/badge/GitHub-0f172a?style=for-the-badge&logo=github&logoColor=67e8f9&labelColor=1e1b4b" alt="GitHub" /></a>
<a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/LinkedIn-0f172a?style=for-the-badge&logo=linkedin&logoColor=67e8f9&labelColor=1e1b4b" alt="LinkedIn" /></a>
<a href="https://github.com/aamer444?tab=followers"><img src="https://img.shields.io/github/followers/aamer444?style=for-the-badge&logo=github&logoColor=67e8f9&labelColor=1e1b4b&color=0f172a&label=Followers" alt="GitHub followers" /></a>
<a href="https://github.com/aamer444"><img src="https://komarev.com/ghpvc/?username=aamer444&color=1e1b4b&style=for-the-badge&label=Profile+Views&labelColor=0f172a" alt="Profile views" /></a>

</div>

<br/>

## 🪐 About

<table>
<tr>
<td valign="top" width="55%">

**Backend Engineer** with **5+ years** building production systems in **Node.js and TypeScript**. I design REST and real-time APIs, authentication and **role-based access control**, microservices and third-party integrations — with clean data models on **MySQL, PostgreSQL, MongoDB and Redis**.

I care about the boring parts that keep systems alive: input validation, guards, caching, error handling and docs that a new teammate can actually follow. Lately I've also been shipping **desktop and web front-ends** (Tauri, React) when a product needs the whole slice, not just the API.

I build with **AI-assisted workflows** — Claude Code, Codex, Copilot, Cursor — to move faster without lowering the bar on reviews and tests.

<img src="https://img.shields.io/badge/Role-Backend_Engineer-0f172a?style=flat-square&labelColor=1e1b4b" alt="Backend Engineer" />
<img src="https://img.shields.io/badge/Based_in-Mumbai,_India-0f172a?style=flat-square&labelColor=1e1b4b" alt="Mumbai, India" />
<img src="https://img.shields.io/badge/Open_to-Backend_roles-0f172a?style=flat-square&labelColor=1e1b4b" alt="Open to backend roles" />

</td>
<td valign="top" width="45%">

```ts
const aamer = {
  role:       "Backend Engineer",
  experience: "5+ years",
  location:   "Mumbai, India",
  core:       ["Node.js", "TypeScript", "NestJS", "Express"],
  data:       ["MySQL", "PostgreSQL", "MongoDB", "Redis"],
  strengths:  ["REST & WebSocket APIs", "Auth & RBAC",
               "Microservices", "3rd-party integrations"],
  also:       ["React", "Tauri", "Docker", "AWS"],
  aiTools:    ["Claude Code", "Codex", "Copilot", "Cursor"],
  learning:   "Java + DSA",
};
```

</td>
</tr>
</table>

> [!TIP]
> **Ship small, ship safe.** Typed DTOs, guarded routes, cached reads and a Swagger page on every service — so the API explains itself before anyone asks.

<br/>

## 📊 At a Glance

<div align="center">

<img src="assets/motion/metrics.svg" width="100%" alt="5+ years experience, Node.js and TypeScript core stack, 4 public projects, backend-first and full-stack ready" />

</div>

<br/>

<img src="assets/motion/divider.svg" width="100%" alt="" />

## 🧩 What I Do

<table>
<tr>
<td valign="top" width="33%">

### ⚙️ API Engineering
Fast, documented, versioned APIs.

- REST &amp; WebSocket (Socket.io)
- NestJS modules &amp; Express
- DTO validation &amp; pipes
- Swagger / OpenAPI docs

</td>
<td valign="top" width="33%">

### 🔐 Auth &amp; Access
Security as a default, not a patch.

- JWT + Passport strategies
- Role / permission (RBAC) guards
- Redis-backed sessions
- bcrypt &amp; least privilege

</td>
<td valign="top" width="34%">

### 🔄 Data &amp; Integrations
Moving data between real systems.

- TypeORM on MySQL / Postgres
- Caching with Redis
- OCR &amp; document pipelines
- Accounting (TallyPrime) XML sync

</td>
</tr>
</table>

<br/>

## 🛰️ How I Build APIs

<img src="assets/motion/api-flow.svg" width="100%" alt="Animated request lifecycle: a client request passes through NestJS or Express, a JWT and RBAC guard, validation and the service layer, which reads Redis cache or MySQL/PostgreSQL before responding; events are pushed over Socket.io" />

<details>
<summary><b>Layer by layer</b></summary>

<br/>

| Layer | What I put there |
|---|---|
| **Controller** | Thin routes, versioned paths, Swagger decorators so docs never drift |
| **Guards** | JWT auth, role and permission checks, rate limits on sensitive routes |
| **Validation** | `class-validator` DTOs and pipes — bad input never reaches the service |
| **Service** | Business rules, transactions, idempotent writes, clear domain errors |
| **Cache** | Redis for sessions, hot reads and short-lived tokens |
| **Persistence** | TypeORM entities and migrations on MySQL / PostgreSQL, indexes on real query paths |
| **Real-time** | Socket.io gateways for live dashboards and notifications |

</details>

<br/>

<img src="assets/motion/divider.svg" width="100%" alt="" />

## 🚀 Featured Projects

<table>
<tr>
<td valign="top" width="50%">

### 🧾 [tally-helper](https://github.com/aamer444/tally-helper)
Desktop app that turns **Excel registers, supplier PDF bills and bank statements** into reviewed **TallyPrime vouchers** — replacing a mix of paid tools with one flow.

`Tauri 2` `React` `TypeScript` `SQLite` `pnpm monorepo` `Rust`

</td>
<td valign="top" width="50%">

### 🔐 [rbac_backend](https://github.com/aamer444/rbac_backend)
Role-based access control platform: users, roles, permissions, sessions and a dashboard API with live updates.

`NestJS 11` `JWT` `Passport` `TypeORM` `MySQL` `Redis` `Socket.io` `Swagger`

</td>
</tr>
<tr>
<td valign="top" width="50%">

### 🏭 [esper_home](https://github.com/aamer444/esper_home)
Marketing site for **Esper Radiators &amp; Products** — product catalogue, SEO, scroll animations and enquiry forms.

`React 19` `TypeScript` `Vite` `Tailwind CSS 4` `React Hook Form`

</td>
<td valign="top" width="50%">

### 📄 [TEST_DLP](https://github.com/aamer444/TEST_DLP)
OCR document-processing API — accepts uploads or base64 images/PDFs, validates type and size, extracts data with Redis-backed caching.

`Node.js` `Express` `OCR` `Redis`

</td>
</tr>
</table>

<details>
<summary><b>🧾 Inside tally-helper</b></summary>

<br/>

<img src="assets/motion/tally-flow.svg" width="100%" alt="Animated tally-helper pipeline: Excel registers, PDF bills and bank statements are parsed, mapped to ledgers, reviewed, and pushed as XML vouchers into TallyPrime" />

| Package | Responsibility |
|---|---|
| `packages/importers` | Excel / CSV / bank PDF / GSTR-2B parsing |
| `packages/mapping-engine` | Rules, learned mappings, fuzzy ledger matching |
| `packages/domain` | Canonical models, GST and money handling |
| `packages/tally-client` | XML builders, transport and response parser |
| `packages/sync` | AlterID-based incremental mirror of Tally |
| `packages/storage` | SQLite schema, migrations, repositories |
| `tools/tally-mock` | Fake Tally server on `:9900` for tests |

</details>

<br/>

## 🛠️ Technology Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=nodejs,ts,js,nestjs,express,java,react,tailwind,vite&perline=9" alt="Node.js, TypeScript, JavaScript, NestJS, Express, Java, React, Tailwind, Vite" />
<br/>
<img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,redis,sqlite,docker,aws,linux,rust&perline=9" alt="MySQL, PostgreSQL, MongoDB, Redis, SQLite, Docker, AWS, Linux, Rust" />
<br/>
<img src="https://skillicons.dev/icons?i=git,github,gitlab,githubactions,postman,vscode,pnpm,npm&perline=9" alt="Git, GitHub, GitLab, GitHub Actions, Postman, VS Code, pnpm, npm" />

</div>

<br/>

<table>
<tr>
<td valign="top" width="50%">

**⚙️ Backend**

![Node.js](https://img.shields.io/badge/Node.js-0f172a?style=flat-square&logo=nodedotjs&logoColor=67e8f9&labelColor=1e1b4b)
![TypeScript](https://img.shields.io/badge/TypeScript-0f172a?style=flat-square&logo=typescript&logoColor=67e8f9&labelColor=1e1b4b)
![NestJS](https://img.shields.io/badge/NestJS-0f172a?style=flat-square&logo=nestjs&logoColor=67e8f9&labelColor=1e1b4b)
![Express](https://img.shields.io/badge/Express-0f172a?style=flat-square&logo=express&logoColor=67e8f9&labelColor=1e1b4b)
![Socket.io](https://img.shields.io/badge/Socket.io-0f172a?style=flat-square&logo=socketdotio&logoColor=67e8f9&labelColor=1e1b4b)
![Swagger](https://img.shields.io/badge/Swagger-0f172a?style=flat-square&logo=swagger&logoColor=67e8f9&labelColor=1e1b4b)
![JWT](https://img.shields.io/badge/JWT-0f172a?style=flat-square&logo=jsonwebtokens&logoColor=67e8f9&labelColor=1e1b4b)
![Java](https://img.shields.io/badge/Java_(learning)-0f172a?style=flat-square&logo=openjdk&logoColor=67e8f9&labelColor=1e1b4b)

**🗄️ Data**

![MySQL](https://img.shields.io/badge/MySQL-0f172a?style=flat-square&logo=mysql&logoColor=67e8f9&labelColor=1e1b4b)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0f172a?style=flat-square&logo=postgresql&logoColor=67e8f9&labelColor=1e1b4b)
![MongoDB](https://img.shields.io/badge/MongoDB-0f172a?style=flat-square&logo=mongodb&logoColor=67e8f9&labelColor=1e1b4b)
![Redis](https://img.shields.io/badge/Redis-0f172a?style=flat-square&logo=redis&logoColor=67e8f9&labelColor=1e1b4b)
![SQLite](https://img.shields.io/badge/SQLite-0f172a?style=flat-square&logo=sqlite&logoColor=67e8f9&labelColor=1e1b4b)
![TypeORM](https://img.shields.io/badge/TypeORM-0f172a?style=flat-square&logo=typeorm&logoColor=67e8f9&labelColor=1e1b4b)

</td>
<td valign="top" width="50%">

**🎨 Frontend &amp; Desktop**

![React](https://img.shields.io/badge/React-0f172a?style=flat-square&logo=react&logoColor=67e8f9&labelColor=1e1b4b)
![Vite](https://img.shields.io/badge/Vite-0f172a?style=flat-square&logo=vite&logoColor=67e8f9&labelColor=1e1b4b)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-0f172a?style=flat-square&logo=tailwindcss&logoColor=67e8f9&labelColor=1e1b4b)
![Tauri](https://img.shields.io/badge/Tauri-0f172a?style=flat-square&logo=tauri&logoColor=67e8f9&labelColor=1e1b4b)

**☁️ Cloud &amp; DevOps**

![AWS](https://img.shields.io/badge/AWS-0f172a?style=flat-square&logo=amazonwebservices&logoColor=67e8f9&labelColor=1e1b4b)
![Docker](https://img.shields.io/badge/Docker-0f172a?style=flat-square&logo=docker&logoColor=67e8f9&labelColor=1e1b4b)
![Linux](https://img.shields.io/badge/Linux-0f172a?style=flat-square&logo=linux&logoColor=67e8f9&labelColor=1e1b4b)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0f172a?style=flat-square&logo=githubactions&logoColor=67e8f9&labelColor=1e1b4b)
![GitLab](https://img.shields.io/badge/GitLab-0f172a?style=flat-square&logo=gitlab&logoColor=67e8f9&labelColor=1e1b4b)

**🤖 AI-Assisted Dev**

![Claude Code](https://img.shields.io/badge/Claude_Code-0f172a?style=flat-square&logo=anthropic&logoColor=67e8f9&labelColor=1e1b4b)
![OpenAI Codex](https://img.shields.io/badge/OpenAI_Codex-0f172a?style=flat-square&logo=openai&logoColor=67e8f9&labelColor=1e1b4b)
![Copilot](https://img.shields.io/badge/GitHub_Copilot-0f172a?style=flat-square&logo=githubcopilot&logoColor=67e8f9&labelColor=1e1b4b)
![Cursor](https://img.shields.io/badge/Cursor-0f172a?style=flat-square&logo=cursor&logoColor=67e8f9&labelColor=1e1b4b)

</td>
</tr>
</table>

<br/>

<img src="assets/motion/divider.svg" width="100%" alt="" />

## 📈 GitHub Activity

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=aamer444&show_icons=true&hide_border=true&bg_color=0f172a&title_color=67e8f9&icon_color=a78bfa&text_color=cbd5e1&count_private=true&include_all_commits=true" alt="GitHub stats" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aamer444&layout=compact&hide_border=true&bg_color=0f172a&title_color=67e8f9&text_color=cbd5e1" alt="Most used languages" />

<br/><br/>

<img width="70%" src="https://streak-stats.demolab.com?user=aamer444&theme=transparent&hide_border=true&stroke=94a3b8&ring=22d3ee&fire=a78bfa&currStreakLabel=67e8f9&currStreakNum=67e8f9&sideNums=94a3b8&sideLabels=94a3b8&dates=94a3b8" alt="Contribution streak" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aamer444/aamer444/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aamer444/aamer444/output/github-snake.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/aamer444/aamer444/output/github-snake-dark.svg" alt="Animated snake eating the past year's contribution grid" />
</picture>

</div>

<br/>

## 🎯 Current Focus

- 🔐 Hardening **rbac_backend** — fine-grained permissions, session revocation and audit logs
- 🧾 Shipping **tally-helper** modules — bank statement auto-classification and credit/debit notes
- ☕ Leveling up in **Java** and **data structures &amp; algorithms**
- 🤖 Building faster with **AI-assisted engineering** while keeping tests and reviews strict

<details>
<summary><b>🧭 How I work</b></summary>

<br/>

| Principle | In practice |
|---|---|
| **Validate at the edge** | Every request goes through a DTO before it touches business logic |
| **Least privilege** | Roles and permissions are explicit; nothing is open by default |
| **Cache what's hot** | Redis in front of repeated reads, with clear invalidation |
| **Docs are part of the API** | Swagger on every service, READMEs that actually run |
| **Typed end to end** | TypeScript from DB entity to API response |
| **Small PRs, reviewed** | AI speeds up the draft; humans and tests approve the merge |

</details>

<br/>

<div align="center">

<img src="assets/motion/footer.svg" width="100%" alt="Good APIs are boring in production — predictable, secure and fast. Mohammad Aamer, Backend Engineer." />

<br/><br/>

<a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/LinkedIn-0f172a?style=for-the-badge&logo=linkedin&logoColor=67e8f9&labelColor=1e1b4b" alt="LinkedIn" /></a>
<a href="https://github.com/aamer444"><img src="https://img.shields.io/badge/GitHub-0f172a?style=for-the-badge&logo=github&logoColor=67e8f9&labelColor=1e1b4b" alt="GitHub" /></a>

<br/>

<sub>⚡ Build. Learn. Improve. Repeat. · Contribution snake refreshed by GitHub Actions.</sub>

</div>
