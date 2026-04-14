## About me

I'm a Computer Science graduate from **The Hebrew University of Jerusalem** who enjoys building real systems and understanding how things work under the hood. I'm interested in backend, systems-level, and security-adjacent development — projects that touch networking, infrastructure, and low-level details.

- Building personal projects with production-like architecture
- Background in data structures, algorithms, operating systems, and networking

---

## Technical Skills

**Languages**
- Python, Kotlin, TypeScript/JavaScript, C#, C++, C, Java

**Backend & Web**
- Node.js, Express, React
- REST APIs, JWT authentication, client-server architecture

**Databases**
- PostgreSQL, SQLite, Drizzle ORM

**Mobile**
- Android (Kotlin, RecyclerView, WebView)

**Cloud & DevOps**
- AWS (EC2, S3), Docker
- Git, GitHub Actions CI/CD

**Systems & Networking**
- Linux, TUN/TAP, UDP sockets, NAT, IP forwarding
- AES-256-GCM encryption

---

## Selected Projects

### **MiniVPN**
https://github.com/yonisirote/minivpn

Functional Linux VPN built from scratch. Creates TUN interfaces on client and server, encrypts all traffic with AES-256-GCM, and tunnels it over UDP. Server configures IP forwarding and NAT/masquerading to route VPN clients to the public internet. Deployed on AWS EC2 with packet-level logging for ICMP, TCP, and UDP traffic.

**Tech:** Python, TUN/TAP, UDP sockets, NAT, AES-256-GCM, AWS EC2

---

### **HostMate**
https://github.com/yonisirote/hostmate

Full-stack meal planning app — hosts manage dishes and guests, collect preferences via ranking links, and get personalized menu recommendations. JWT auth with access/refresh tokens, protected API routes, SQLite database with Drizzle ORM. Deployed on Railway with GitHub Actions CI.

**Tech:** TypeScript, Express, React, SQLite, Drizzle ORM, JWT, Railway

---

### **ReadMyFeed**
https://github.com/yonisirote/readmyfeed

Native Android app that aggregates feeds from X/Twitter and Telegram and reads them aloud. Handles X authentication through a WebView login flow with cookie capture and cursor-based pagination. Integrated Telegram via a local TDLib build with JNI bindings. RecyclerView feed UI with per-provider row layouts and text-to-speech playback.

**Tech:** Kotlin, Android, TDLib, WebView, RecyclerView, Text-to-Speech

---

## Open Source

### **Zed IDE**
Fixed and merged a bug where slash commands were lost when reopening threads — navigated a large Rust codebase and went through maintainer code review.

---

## Education

**BSc in Computer Science**
Hebrew University of Jerusalem (2021–2025)

**Boot.dev**
Backend engineering program covering HTTP, servers, databases, CI/CD, and Linux.

---

## Contact

- GitHub: https://github.com/yonisirote
- LinkedIn: https://www.linkedin.com/in/yoni-sirote/
