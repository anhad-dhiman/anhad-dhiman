# Hi, I'm Anhad 👋

Backend-focused developer and final-year **Bachelor of IT** student at Kwantlen Polytechnic University (GPA 3.77, Dean's List ×5), based in Metro Vancouver.
I build real-time backend systems in **Java / Spring Boot** and **Node.js**, and I test them properly — JUnit 5, MockMvc, Vitest — then ship them in Docker.

🔍 **Open to an 8-month co-op (January – August 2027)** in backend development, test automation or DevOps.

---

### 🚀 Featured Projects

**[Chatroom](https://github.com/anhad-dhiman/Chatroom)** — Real-time chat application
`Java 21` `Spring Boot` `WebSockets (STOMP)` `PostgreSQL` `React` `TypeScript` `Docker`
- Event-driven messaging backend that publishes events only **after the database transaction commits**, so clients never see rolled-back data
- Stateless **JWT + BCrypt** auth with authorization enforced on every read and write, over both HTTP and WebSocket
- **59 automated tests**, including WebSocket integration tests that connect real STOMP clients to verify delivery, privacy and invalid-token rejection
- One-command setup with a multi-stage Dockerfile and Docker Compose

**Build Your Setup** — Gaming setup platform
`Vue 3` `PostgreSQL` `Vercel Serverless` `IGDB API`
- Rule-based recommendation engine that builds complete gaming setups from games, budget, preferences and hardware compatibility
- bcrypt + JWT in httpOnly cookies, protected routes, and an IGDB-powered "Can I Run It?" check

**Community Resource Navigator** *(team project, in progress)*
`React` `Node.js / Express` `PostgreSQL (Supabase)` `Claude API`
- AI-assisted search that helps Metro Vancouver residents find verified community services by describing their need in plain language
- Database-first design: the AI interprets the query and explains matches, but every resource detail comes from verified records — never from the model
- Built with a prompt-injection boundary, schema-validated AI output, and a database-only fallback when the AI is unavailable

**[Cyber Rogue](https://github.com/anhad-dhiman/Cyber-Rogue)** — 2D action game engine
`Java (Processing)`
- Fixed-step game loop, dynamic camera, and finite-state-machine enemy AI (idle, patrol, chase, boss combat)

---

### 🛠️ Tech Stack

| | |
|---|---|
| **Languages** | Java · Python · JavaScript · TypeScript · SQL · C++ |
| **Backend** | Spring Boot · Spring Security · WebSockets (STOMP) · REST · Node.js · Express · JWT · Flyway |
| **Testing** | JUnit 5 · Spring Boot Test · MockMvc · AssertJ · Vitest · React Testing Library |
| **Databases** | PostgreSQL · MySQL · H2 |
| **Frontend** | React · Vue 3 · Vite · Tailwind CSS |
| **DevOps & Cloud** | Docker · Docker Compose · Git · AWS (EC2, S3, IAM, Lambda) · Vercel · Render |

---

### 🧠 Problem Solving

Practicing DSA in **Java**, currently focused on **graph algorithms**:
BFS/DFS, topological sort, cycle detection, bipartite graphs, multi-source BFS, Dijkstra, 0-1 BFS, Bellman-Ford, Floyd-Warshall.

🌱 **Currently learning:** Union-Find, Minimum Spanning Trees, SCCs · AWS Solutions Architect – Associate (exam Feb 2027)

---

### 💼 Experience

**Freelance Web Developer** — [Black Cat Security](https://blackcatltd.ca/) · Dec 2025
Designed, built and deployed a production React website for a Lower Mainland security company, from client requirements through hosting on Vercel.

### 📜 Certifications
- Machine Learning Specialization — DeepLearning.AI & Stanford (2025)
- AWS Certified Solutions Architect – Associate — *in progress*

---

📫 [LinkedIn](http://www.linkedin.com/in/anhad-dhiman-47b79a260) · anhad.dhiman003@gmail.com

<sub>Off the clock: I push shiny buttons on my smart rock to make it do smarter things.</sub>
