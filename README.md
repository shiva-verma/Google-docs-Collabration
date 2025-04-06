# 📝 LiveDocs – Real-Time Collaborative Document Editor

![License](https://img.shields.io/badge/license-MIT-green)
![Tech](https://img.shields.io/badge/built%20with-Next.js%2C%20Liveblocks%2C%20Clerk%2C%20Sentry-blue)
![Status](https://img.shields.io/badge/status-production-brightgreen)

LiveDocs is a blazing-fast, real-time collaborative document editor built using **Next.js** and powered by **Liveblocks**, **Clerk**, and **Sentry**. Whether you're drafting notes or co-authoring documents, LiveDocs provides a seamless and secure writing experience.

<div align="center">
  <img src="https://your-image-link.com/preview.png" alt="LiveDocs Preview" width="80%" />
</div>

---

## 🚀 Features

- ✍️ **Real-time Collaboration** — Edit documents with multiple users simultaneously using Liveblocks Presence & Storage.
- 👥 **Authentication with Clerk** — Seamless sign-up, sign-in, and session management.
- 💬 **Inline Comments & Mentions** — Collaborators can comment directly in the doc and tag teammates.
- 📄 **Document Sharing** — Share view/edit links easily.
- 🧠 **Error Monitoring with Sentry** — Get instant feedback on crashes and performance issues.
- 📱 **Responsive Design** — Fully optimized for mobile, tablet, and desktop screens.

---

## 🛠️ Tech Stack

| Category      | Tools Used                                              |
|---------------|----------------------------------------------------------|
| **Frontend**  | Next.js, TypeScript, Tailwind CSS                        |
| **Real-time** | Liveblocks (Presence, Storage, Broadcast)               |
| **Auth**      | Clerk (User management, sessions, secure routes)        |
| **Backend**   | Node.js, Express (API server if applicable)             |
| **Database**  | MongoDB (optional, for doc persistence)                 |
| **Monitoring**| Sentry                                                  |
| **Deployment**| Vercel (Frontend), Render/Heroku (Backend - if separate)|

---

## 📸 Screenshots

| Dashboard | Live Editor |
|----------|-------------|
| ![Dashboard](https://your-image-link.com/dashboard.png) | ![Editor](https://your-image-link.com/editor.png) |

---

## 🧪 Getting Started

### 🧰 Prerequisites
- Node.js >= 16.x
- Liveblocks account
- Clerk project setup
- Sentry project DSN

### ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/your-username/livedocs.git
cd livedocs

# Install dependencies
npm install

# Run the development server
npm run dev
