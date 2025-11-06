# 📰 Blog Page CMS

This project serves as a **personal portfolio build**, showcasing back-end architecture, modular design, and CMS functionality — all deployable on **Vercel**.

---

## ✨ Overview

Blog Page CMS provides a fast, simple, and developer-friendly foundation for publishing and managing blog content.
It’s built with scalability in mind and supports API-driven extensions and theming — making it ideal for personal sites, documentation hubs, or content platforms.

---

## 🚀 Features

* ⚡ **Fast Node.js backend** — built on Express
* 🧩 **Modular structure** for easy customization
* 🗞️ **Content management** for posts, tags, and users
* 🧭 **Admin interface** (custom Ghost Admin base)
* 🔒 **Secure authentication** with session & JWT options
* 🌍 **SEO-optimized** URLs and metadata
* ⚙️ **Docker-ready** setup for quick local deployment
* ☁️ **Deployable on Vercel** with one click

---

## 🧠 Tech Stack

| Layer          | Technologies          |
| -------------- | --------------------- |
| **Core**       | Node.js, Express      |
| **CMS Base**   | Ghost framework (MIT) |
| **Database**   | SQLite / MySQL        |
| **Auth**       | JWT & session-based   |
| **UI Engine**  | Handlebars            |
| **Deployment** | Vercel, Docker        |
| **Language**   | JavaScript (ES2022)   |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/tanaykini/Blog-page-CMS.git
cd Blog-page-CMS
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Configure environment variables

Create a `.env` file in the project root:

```env
PORT=2368
NODE_ENV=development
DATABASE_URL=sqlite://content/data/blog.db
```

*(Your `.env` is already ignored by Git — safe to use for local secrets.)*

### 4️⃣ Run locally

```bash
npm run dev
```

Visit **[http://localhost:2368](http://localhost:2368)** to view your CMS dashboard.

---

## 🌐 Deploying to Vercel

You can deploy this project instantly using [Vercel](https://vercel.com):

1. Push your repo to GitHub (you’ve already done this 🎉).
2. Go to [vercel.com/import](https://vercel.com/import) and select your repository.
3. Configure your environment variables in the dashboard.
4. Click **Deploy** — and you’re live 🚀.

---

## 🧱 Project Structure

```
.
├── apps/               # Frontend & admin apps
├── ghost/              # Core Ghost engine
├── content/            # Data, images, themes
├── config/             # Configuration files
├── .docker/            # Docker environment setup
├── .github/            # CI/CD workflows
├── LICENSE             # MIT license (from Ghost)
└── README.md           # Project documentation
```

---

## 📦 Common Commands

| Command         | Description                |
| --------------- | -------------------------- |
| `npm run dev`   | Start in development mode  |
| `npm start`     | Run the CMS in production  |
| `npm test`      | Run unit/integration tests |
| `npm run build` | Build admin & core assets  |

---

## 🧭 Roadmap

* [ ] Add markdown editor improvements
* [ ] Enable API-based theme switching
* [ ] Integrate image uploads with Cloudinary
* [ ] Add content scheduling & drafts
* [ ] Optional Next.js frontend integration

---

## 📄 License & Attribution

Ghost is licensed under the **MIT License** — see the `LICENSE` file for details.
Custom modifications and configuration © 2025 **Tanay Kini**.

---

> 🧠 *“Build. Write. Iterate.”* — A personal experiment in crafting a better publishing workflow.
