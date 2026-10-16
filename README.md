<h1 align="center">Hi there! 🎧 I'm Sofi</h1>

<p align="center">
  <b>Informatics Engineering student at FIUBA (University of Buenos Aires) 🇦🇷</b><br>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=rivasofi&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

---

## 👩‍💻 About me

- 🎓 Informatics Engineering student at the Faculty of Engineering, University of Buenos Aires
- 🤝 Used to working in teams
- 🌱 Always learning something new

---

## 🚀 Tech Stack

**Languages**

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" alt="Rust" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" alt="Bash" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="Go" width="45" height="45" />
</p>

**Frameworks & Web**

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="Next.js" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="45" height="45" />
</p>

**Databases, Tools & Environment**

<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" alt="SQLite" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" width="45" height="45" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cassandra/cassandra-original.svg" alt="Cassandra" width="45" height="45" />          
</p>

---

## 📌 Featured Projects

### 🧑‍💼 [Orgalancer](https://github.com/rivasofi/orgalancer_gdsi)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude%20API-D97757?style=flat&logo=anthropic&logoColor=white)
 
A **freelance management platform with a built-in AI assistant**, built for the *Information Systems Development Management* course (FIUBA, 1C26). It brings everything a freelancer needs into one place: projects, clients, tasks, time tracking, finances and budgets.
 
**🤖 AI assistant powered by Claude (Anthropic)**
- Chat assistant for questions and suggestions
- Takes the **expenses uploaded by the freelancer** into account to **suggest rates** and calculate **budgets based on real costs**
**🔗 Client portal**
- Freelancers can generate **read-only, shareable links (token-based)** so clients can follow project progress and review budgets and rates
**Main features:** Dashboard · Projects · Clients · Kanban tasks · Time tracking · Finances · Budgets · Reports (cash flow & profitability per project) · Notifications · Settings
**Under the hood:** Next.js frontend, FastAPI backend with interactive API docs, SQLite database, and Docker Compose for containerized setups. Developed collaboratively with 400+ commits and a pull-request based workflow.

---

### 🚲 [Concurrent Bike Rental System](https://github.com/rivasofi/sistema_bicicletas_concurrentes)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![TCP](https://img.shields.io/badge/TCP%20Sockets-555555?style=flat)
![Actor Model](https://img.shields.io/badge/Actor%20Model-8A2BE2?style=flat)

A **distributed bike-sharing system** written in Rust for the *Concurrent Programming* course (FIUBA, 1C26), built as a team of three.

- **Actor model**: stations, users and a payment gateway run as independent actors, so concurrent requests on the same bike slot are serialized without explicit locks
- **Bully algorithm** for coordinator election, with heartbeat-based failure detection
- **Two-phase commit** for bike returns across stations and the payment gateway, with a fallback to eventual consistency when a participant is down
- **Payment flow** with pre-authorization and capture, idempotent retries and pending queues for offline recovery
- Real **TCP** communication between processes, plus integration tests that spin up actual listeners

---

### 📹 [RoomRTC](https://github.com/rivasofi/roomRTC)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat&logo=webrtc&logoColor=white)

A **video-conferencing app with its own WebRTC implementation**, written in Rust for the *Programming Workshop* course (FIUBA, 2C25), built as a team of three.

- Peer-to-peer audio and video between two users on different devices
- Signaling server for registration, login and call setup
- Connection negotiation with **SDP** and **ICE**
- Secure channels with **DTLS** and media transport over **SRTP**
- Chat and **file transfer** through **SCTP data channels**
- Desktop GUI with login, lobby and call screens

> 🔎 More repositories on my [profile page](https://github.com/rivasofi?tab=repositories).

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=rivasofi&theme=jolly&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rivasofi&theme=jolly&show_icons=true&hide_border=true&layout=compact" alt="Top languages" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/rivasofi/rivasofi/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</p>

---

## 💬 Let's connect

<p align="center">
  <a href="mailto:sofiarivass106@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://instagram.com/soofirivas">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

<p align="center">🦥 <i>Thanks for stopping by!</i> 🦥</p>
