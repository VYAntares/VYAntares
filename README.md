<h1 align="center">Endrit Ahmeti</h1>

<p align="center">
  <b>Software engineer · 42 Lausanne</b><br/>
  I build systems from the ground up and ship them.
</p>

<p align="center">
  <a href="https://shop.discado.ch"><img src="https://img.shields.io/badge/Production_ERP-shop.discado.ch-2ea44f?style=for-the-badge" alt="Production ERP"/></a>
  <a href="https://42lausanne.ch"><img src="https://img.shields.io/badge/42_Lausanne-Common_Core-000000?style=for-the-badge&logo=42&logoColor=white" alt="42 Lausanne"/></a>
</p>

---

### About

I trained at **42 Lausanne**, a peer-to-peer school with no teachers and no lectures, where
every project forbids the library that would have made it easy, no `printf` until you have
written `printf`, no `std::vector` until you have written one, no web framework until you
have implemented HTTP yourself.

That left me with a habit more than a language: read the specification, handle the edge
cases, free what you allocate, and verify instead of assuming.

Alongside it I built and shipped **[shop.discado.ch](https://shop.discado.ch)**, a wholesale
ERP that runs a business, orders, stock, Swiss QR invoices.

---

### 🚧 Currently building

**[ft_transcendence](https://github.com/VictorBro/ft_transcendence)** — an AI-driven platform
for learning a foreign language, built by a team of five.

A learner takes an **adaptive placement test** that establishes their real CEFR level, and
gets a **personalised roadmap** of topics aligned to their daily goals. From there an **AI
tutor** takes over: explanations, exercises, corrections, and conversation practice that
picks up where the last session left off instead of restarting from zero every time.

The tutor is **retrieval-augmented** rather than a bare chatbot. Answers are grounded in
language material retrieved from a vector store, so feedback stays tied to the learner's
actual level and mistakes. Add live peer practice and progress analytics on top, and the
system is meant to keep pushing the level up rather than just answering questions.

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS"/>
  <img src="https://img.shields.io/badge/PostgreSQL_+_pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL and pgvector"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright"/>
</p>

A pnpm monorepo with Zod-typed contracts shared between front and back, Caddy in front,
Docker Compose for local and production, and Vitest, Supertest and Playwright covering it.

---

### Featured work

**[Discado ERP](https://shop.discado.ch)** — a B2B wholesale platform in production at
**[shop.discado.ch](https://shop.discado.ch)**. Client portal and admin back office in one
codebase, separated by a database-driven permission system: catalogue, ordering, stock,
suppliers, delivery notes, accounting, statistics, and compliant Swiss QR invoicing.
Version 2 is a **React + Vite + Tailwind** PWA; the v1 Node.js/Express/SQLite implementation
that took it into production is now in private.

**[webserv](https://github.com/VYAntares/webserv)** — an HTTP/1.1 server written from
scratch in C++98. `epoll`-driven non-blocking I/O across every socket and CGI pipe,
asynchronous CGI execution, and NGINX-style configuration. No networking library beyond the
POSIX syscalls.

**[minishell](https://github.com/VYAntares/minishell)** — a POSIX-style shell in C:
quote-aware tokenizer, recursive-descent parser, AST, and an executor handling pipes,
redirections, heredocs, subshells, logical operators and wildcards. Measured against `bash`
itself.

---

### Tech

**Systems**
<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/GNU_Make-A42E2B?style=flat-square&logo=gnu&logoColor=white" alt="Make"/>
  <img src="https://img.shields.io/badge/Valgrind-782A90?style=flat-square&logo=gnu&logoColor=white" alt="Valgrind"/>
</p>

**Web**
<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS"/>
</p>

**Data & infrastructure**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white" alt="NGINX"/>
  <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white" alt="Caddy"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
</p>

---

### 42 Common Core

The full curriculum, in order. C and C++98 under `-Wall -Wextra -Werror`, no external
libraries, no memory leaks.

| Project | What it is | Focus |
|---|---|---|
| [libft](https://github.com/VYAntares/libft) | A static library reimplementing the C standard library | Memory, strings, linked lists |
| [ft_printf](https://github.com/VYAntares/ft_printf) | `printf` rebuilt from scratch | Variadic functions, formatting |
| [gnl](https://github.com/VYAntares/gnl) | Read any file descriptor line by line | Static state, buffered I/O |
| Born2beroot | A hardened Debian VM — LVM, LUKS, UFW, sudo policy, cron monitoring | System administration |
| [push_swap](https://github.com/VYAntares/push_swap) | Sorting with two stacks and eleven operations | Algorithmic complexity |
| [so_long](https://github.com/VYAntares/so_long) | A 2D tile game on MiniLibX | Graphics, event loops, parsing |
| [minitalk](https://github.com/VYAntares/minitalk) | Client/server messaging over UNIX signals alone | IPC, bit-level protocols |
| [philosophers](https://github.com/VYAntares/philosophers) | The dining philosophers, threaded | Concurrency, deadlock, timing |
| [minishell](https://github.com/VYAntares/minishell) | A POSIX-style shell | Processes, pipes, signals |
| [cpp](https://github.com/VYAntares/cpp) | Modules 00–09, the complete C++ track | OOP, templates, the STL |
| [cub3D](https://github.com/VYAntares/cub3d) | A textured raycasting engine | 3D projection, DDA, rendering |
| [webserv](https://github.com/VYAntares/webserv) | An HTTP/1.1 server from scratch | Sockets, epoll, CGI |
| [Inception](https://github.com/VYAntares/Inception) | A multi-container Docker infrastructure | NGINX, WordPress, MariaDB |
| [ft_transcendence](https://github.com/VictorBro/ft_transcendence) | The capstone: an AI language-learning platform | Full-stack, RAG, teamwork |

---

### Also

[app-deploy](https://github.com/VYAntares/app-deploy) · a lightweight application deployer  
[tr-template](https://github.com/VYAntares/tr-template) · a TypeScript starter template  
[jsvanilla](https://github.com/VYAntares/jsvanilla) · core JavaScript, HTML and CSS without a framework

---

<p align="center">
  <a href="mailto:contact@vyantares.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email"/></a>
  <a href="https://profile.intra.42.fr/users/eahmeti"><img src="https://img.shields.io/badge/42_Intra-000000?style=for-the-badge&logo=42&logoColor=white" alt="42 Intra"/></a>
</p>
