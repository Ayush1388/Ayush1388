<div align="center">

# Hi, I'm Ayush 👋

**Backend engineer in the making: Go, PostgreSQL, and systems that don't fall over under load.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:ayushji2543@gmail.com)

</div>

I'm a CS student at **SRM Institute of Science and Technology** who likes the unglamorous parts of software: queues, backpressure, database migrations, and retries that actually work. Most of what I build now is in **Go**, and I also do ML research on fake-news detection in **Python / PyTorch**.

- 🔨 **Building now:** [`auctionEngine`](https://github.com/Ayush1388/auctionEngine), a real-time auction backend in Go with a transactional outbox, JWT auth, and SQL migrations
- 🔬 **Researching:** graph-based fake-news detection. My stacked ensemble reaches **~92% accuracy on Twitter15** ([`fakeNewsDetection`](https://github.com/Ayush1388/fakeNewsDetection))
- 📚 **Learning:** distributed systems, PostgreSQL internals, DSA in C++
- 💬 **Ask me about:** Go concurrency patterns, Postgres partitioning, HD wallets
- 🎯 **Looking for:** backend / SDE internships and new-grad roles

---

## ⭐ Featured projects

### 📊 [Log Aggregator & Observability Stack](https://github.com/Ayush1388/log-aggregator)
A self-hosted, Datadog-style log pipeline.
- Bounded Go channels + a worker pool apply **backpressure** during traffic spikes instead of letting memory grow unbounded
- Batches logs (100 events or 5 s) into **single bulk inserts**, which cuts database round trips
- PostgreSQL **monthly partitions** with automatic creation and retention cleanup; `JSONB` for schemaless metadata
- React dashboard with filtering and pagination, a Node.js SDK, graceful shutdown, and Docker Compose

`Go` `PostgreSQL` `React` `Docker`

### 🔨 [Auction Engine](https://github.com/Ayush1388/auctionEngine) *(in progress)*
Backend for live auctions with wallets and bid reservations.
- **Transactional outbox** + background worker for reliable email delivery (no lost events if SMTP is down)
- Hand-written **migration runner**, `pgxpool` connection pooling, JWT auth, bcrypt password hashing, account activation
- Schema for users, wallets, auctions, bids, bid reservations, and wallet transactions; unit tests for config, passwords, and activation

`Go` `PostgreSQL` `Docker` `SMTP`

### 🔬 [Fake News Detection (TEG-FND / GE-Stack)](https://github.com/Ayush1388/fakeNewsDetection)
Research project on rumour detection using both *what* a tweet says and *how it spreads*.
- Graph-enhanced stacked ensemble: text view + spreader-graph view + cascade-timing view → meta-learner
- **92.05% ± 0.87** accuracy on Twitter15 and **90.57% ± 1.10** on Twitter16 (5 seeds); also evaluated on a harder story-disjoint split
- Ablations show the propagation-graph features add 4–10 points over text alone
- Also includes a DeBERTa-based temporal evidence-graph model and LIME explainability

`Python` `PyTorch` `scikit-learn` `Transformers`

### 🔑 [HD Wallet](https://github.com/Ayush1388/HDWallet) · [Live demo](https://hd-wallet-yoet.vercel.app/)
Generates Ethereum and Solana accounts from a single BIP-39 seed phrase using standard derivation paths.

`React` `ethers.js` `@solana/web3.js`

<details>
<summary><b>More projects</b></summary>

- [**snippetbox**](https://github.com/Ayush1388/snippetbox): server-rendered Go web app with MySQL, session management, middleware chains, and HTTPS/TLS
- [**Food Delivery**](https://github.com/Ayush1388/Food_Delivery) · [Live demo](https://food-delivery-hazel-alpha.vercel.app): MERN food-ordering app with a customer site and admin panel
- [**Decentralized Freelancing Platform**](https://github.com/Ayush1388/decentralizedFrellancingPlatform): MERN + Google OAuth marketplace connecting clients and developers

</details>

---

## 🛠️ Tech I use

**Languages:** Go · Python · C++ · JavaScript / TypeScript · Java · SQL
**Backend:** PostgreSQL · MySQL · MongoDB · Node.js / Express · REST APIs · Docker
**ML:** PyTorch · Hugging Face Transformers · scikit-learn
**Frontend:** React · Tailwind CSS · Vite
**Tools:** Git · Linux / WSL

---

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Ayush1388&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayush1388&layout=compact&hide_border=true&langs_count=6" alt="Top languages" />

*Open to internships and backend roles. Feel free to reach out!*

</div>
