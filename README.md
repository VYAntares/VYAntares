<h1 align="center">Endrit Ahmeti</h1>

<p align="center">
  <b>Software engineer · 42 Lausanne</b><br/>
  I build systems from the ground up — and ship them.
</p>

<p align="center">
  <a href="https://catalog.discado.ch"><img src="https://img.shields.io/badge/Production_ERP-catalog.discado.ch-2ea44f?style=for-the-badge" alt="Production ERP"/></a>
  <a href="https://42lausanne.ch"><img src="https://img.shields.io/badge/42_Lausanne-Common_Core-000000?style=for-the-badge&logo=42&logoColor=white" alt="42 Lausanne"/></a>
</p>

---

### About

I trained at **42 Lausanne**, a peer-to-peer school with no teachers and no lectures, where
every project forbids the library that would have made it easy — no `printf` until you have
written `printf`, no `std::vector` until you have written one, no web framework until you
have implemented HTTP yourself.

That left me with a habit more than a language: read the specification, handle the edge
cases, free what you allocate, and verify instead of assuming.

Alongside it I built and shipped **[catalog.discado.ch](https://catalog.discado.ch)**, a
wholesale ERP that has been running a real business — real orders, real stock, real Swiss
QR invoices — rather than sitting on localhost.

---

### Featured work

**[catalog.discado.ch](https://github.com/VYAntares/catalog.discado.ch)** — a B2B wholesale
ERP in production. Client portal and admin back office in one codebase, separated by a
database-driven permission system: catalogue, ordering, stock, suppliers, delivery notes,
accounting, statistics, and compliant Swiss QR invoicing. Node.js, Express, SQLite, PWA and
a Capacitor iOS build, in four languages. *Version 2 continues in a private repository.*

**[webserv](https://github.com/VYAntares/webserv)** — an HTTP/1.1 server written from
scratch in C++98. Sockets, non-blocking I/O multiplexing, request parsing, CGI, and an
NGINX-style configuration file. No networking library beyond the POSIX syscalls.

**[minishell](https://github.com/VYAntares/minishell)** — a POSIX-style shell in C:
quote-aware tokenizer, recursive-descent parser, AST, and an executor handling pipes,
redirections, heredocs, subshells, logical operators, wildcards and job signals. Measured
against `bash` itself.

---

### Tech

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white" alt="NGINX"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GNU_Make-A42E2B?style=flat-square&logo=gnu&logoColor=white" alt="Make"/>
  <img src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white" alt="Neovim"/>
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
| [webserv](https://github.com/VYAntares/webserv) | An HTTP/1.1 server from scratch | Sockets, multiplexing, CGI |
| [Inception](https://github.com/VYAntares/Inception) | A multi-container infrastructure | Docker, networking, volumes |
| [ft_transcendence](https://github.com/VictorBro/ft_transcendence) | The capstone: real-time multiplayer web app | Full-stack, TypeScript |

---

### Also

[app-deploy](https://github.com/VYAntares/app-deploy) · a lightweight application deployer  
[tr-template](https://github.com/VYAntares/tr-template) · a TypeScript starter template  
[jsvanilla](https://github.com/VYAntares/jsvanilla) · core JavaScript, HTML and CSS without a framework

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=VYAntares&show_icons=true&hide_border=true&theme=github_dark&count_private=true"/>
    <img height="160" src="https://github-readme-stats.vercel.app/api?username=VYAntares&show_icons=true&hide_border=true&theme=graywhite&count_private=true" alt="GitHub stats"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=VYAntares&layout=compact&hide_border=true&theme=github_dark&langs_count=8"/>
    <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VYAntares&layout=compact&hide_border=true&theme=graywhite&langs_count=8" alt="Most used languages"/>
  </picture>
</p>

---

<p align="center">
  <a href="mailto:endroahm@hotmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email"/></a>
  <a href="https://profile.intra.42.fr/users/eahmeti"><img src="https://img.shields.io/badge/42_Intra-000000?style=for-the-badge&logo=42&logoColor=white" alt="42 Intra"/></a>
</p>
