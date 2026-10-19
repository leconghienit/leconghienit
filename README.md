<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0F172A,50:0EA5E9,100:22C55E&text=L%C3%AA%20C%C3%B4ng%20Hi%E1%BB%81n&fontColor=FFFFFF&fontSize=50&fontAlignY=36&desc=Backend%20Developer%20%E2%80%A2%20NestJS%20%E2%80%A2%20Microservices&descAlignY=58&descSize=18&animation=fadeIn" alt="Header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=800&color=38BDF8&center=true&vCenter=true&width=780&lines=Building+microservices+with+NestJS+%2B+Kafka+%2B+gRPC;Saga+orchestration%2C+Redis+locks%2C+Stripe+payments;Shipping+an+MCP+server+for+AI-powered+DevOps;Observability+first%3A+Pino+%E2%86%92+Loki+%E2%86%92+Grafana" alt="Typing SVG" />
</a>

<p>
  <img src="https://komarev.com/ghpvc/?username=leconghienit&label=Profile%20Views&color=0ea5e9&style=for-the-badge" alt="Profile views" />
  <a href="https://github.com/leconghienit?tab=followers"><img src="https://img.shields.io/github/followers/leconghienit?label=Followers&style=for-the-badge&color=22c55e&logo=github" alt="Followers" /></a>
  <img src="https://img.shields.io/badge/Open%20to-Internship%20%2F%20Junior%20Backend-f59e0b?style=for-the-badge" alt="Open to work" />
</p>

</div>

---

## 👨‍💻 About Me

```ts
const hien = {
  role: "Backend Developer",
  location: "Vietnam 🇻🇳",
  mainStack: ["TypeScript", "Node.js", "NestJS"],
  databases: ["MySQL", "PostgreSQL", "MongoDB", "Redis", "Elasticsearch"],
  messaging: ["Kafka", "gRPC", "TCP", "BullMQ"],
  architecture: ["Microservices", "BFF", "Saga Orchestration", "Event-driven"],
  observability: ["Pino", "Loki", "Promtail", "Prometheus", "Grafana"],
  currentFocus: [
    "Distributed transactions & reliability",
    "AI tooling with Model Context Protocol (MCP)",
    "Kubernetes & cloud fundamentals",
  ],
  mindset: "Learn deeply, build consistently, improve every day",
};
```

- 🎓 Information Technology student, all-in on **Backend Engineering**
- 🏗️ Designing **NestJS microservices** in an **Nx monorepo**, talking over **TCP, gRPC & Kafka**
- 🔁 Handling distributed orders with a **Saga orchestrator** and **Redis Redlock** for concurrency
- 🤖 Building an **MCP server** so AI agents can safely operate Docker, services and logs
- 📊 Every service ships with **structured logs, metrics and dashboards**, not an afterthought

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🍔 [Food Delivery Platform](https://github.com/leconghienit/food-delivery-app-server)

Microservices backend in an **Nx + pnpm monorepo** with 7 services:
`bff` · `authorizer` · `user` · `restaurant` · `order` · `payment` · `notification`

- 🔌 TCP + **gRPC** between services, **Kafka** for events
- 🔁 **Saga orchestration** for create-order flow
- 💳 **Stripe** payments, ✉️ email notifications (Nodemailer + EJS)
- 🔐 JWT access / refresh tokens, roles & permissions
- 🗄️ MySQL (Prisma) + MongoDB (Mongoose) + Redis
- 📈 Pino → **Loki/Promtail**, **Prometheus** metrics, **Grafana** dashboards
- 🐳 Full infra in Docker Compose

<p>
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/Nx-143055?style=flat-square&logo=nx&logoColor=white" />
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
</p>

</td>
<td width="50%" valign="top">

### 🛒 [E-commerce Server](https://github.com/leconghienit/ecommerce-server)

Production-style **NestJS** e-commerce API with ~20 domain modules.

- 🛍️ Products, variants & attributes, brands, categories
- 🛒 Cart, orders, **order tracking**, coupons, **flash sales**
- ⭐ Reviews, wishlist, **multilingual** product content
- 🔐 JWT + **Google OAuth**, device & refresh-token management, RBAC
- 🔎 **Elasticsearch** product search
- ⚙️ **BullMQ** queues: PDF invoices (Puppeteer), abandoned-cart emails
- 🔒 **Redlock** to avoid overselling, 💳 **Stripe** payments
- 📚 Swagger docs, Zod validation, Docker deploy

<p>
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" />
</p>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🤖 [MCP Server — AI DevOps Toolkit](https://github.com/leconghienit/MCP_SERVER)

A **Model Context Protocol** server (NestJS 11 + MCP SDK v2, Streamable HTTP) that lets AI clients like **Claude** inspect and operate a machine — **safely**.

| 🧰 Tool group | What it does |
| --- | --- |
| 🖥️ System | CPU, memory, disk, OS info |
| 🐳 Docker management | List / inspect / start / stop containers, logs |
| ⚙️ Services & processes | Check and control services, inspect processes |
| 📄 Files & logs | Read files, analyze logs |
| 🧠 AI troubleshooting | Collect context to diagnose problems |

🛡️ **Deny-by-default security policy** per tool, path sandboxing with `realpath` checks, and every call written to a **PostgreSQL audit log** (Prisma 7).

<img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

</td>
</tr>
</table>

---

## 🧰 Tech Stack

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,express,prisma&perline=12" alt="Backend" />
</a>
<br/>
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,redis,elasticsearch,kafka&perline=12" alt="Data" />
</a>
<br/>
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=docker,linux,grafana,prometheus,git,github,githubactions&perline=12" alt="DevOps" />
</a>
<br/>
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=react,redux,tailwind,materialui,c,postman,vscode,pnpm&perline=12" alt="Others" />
</a>

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=leconghienit&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" alt="GitHub trophies" />

</div>

## 📈 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=leconghienit&show_icons=true&include_all_commits=true&count_private=true&rank_icon=github&hide_border=true&theme=tokyonight&bg_color=00000000" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=leconghienit&layout=compact&hide_border=true&theme=tokyonight&bg_color=00000000&langs_count=8" alt="Top languages" />

<img width="80%" src="https://streak-stats.demolab.com/?user=leconghienit&theme=tokyonight&hide_border=true&background=00000000&ring=38BDF8&fire=22C55E&currStreakLabel=38BDF8" alt="GitHub streak" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=leconghienit&theme=tokyo-night&hide_border=true&bg_color=00000000&color=38BDF8&line=22C55E&point=FFFFFF&area=true" alt="Contribution graph" />

</div>

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/leconghienit/leconghienit/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/leconghienit/leconghienit/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/leconghienit/leconghienit/output/github-snake.svg" />
</picture>

</div>

---

## 🎯 Learning Roadmap

```text
Backend Engineering                 DevOps & Cloud
├── ✅ NestJS & TypeScript          ├── ✅ Linux & Docker
├── ✅ Microservices (TCP/gRPC)     ├── ✅ Logging & Metrics (Loki, Prometheus)
├── ✅ Event-driven with Kafka      ├── 🔄 CI/CD with GitHub Actions
├── ✅ Saga & distributed locks     ├── 🔄 Kubernetes
├── 🔄 System Design                ├── ⏳ Cloud (AWS / GCP)
└── 🔄 Testing & Security           └── ⏳ Infrastructure as Code
```

---

## 🤝 Connect With Me

<div align="center">

<a href="https://github.com/leconghienit"><img src="https://img.shields.io/badge/GitHub-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<!-- Thay link LinkedIn / email thật của bạn vào 2 dòng dưới, hoặc xoá đi nếu không dùng -->
<a href="https://www.linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:YOUR_EMAIL@example.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

### “Strong systems are built from clear thinking, consistent practice and simple code.”

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0F172A,50:0EA5E9,100:22C55E" alt="Footer" />

</div>
