<div align="center">

# 📋 TaskPilot — Enterprise Agile Kanban & Workflow Engine

<p align="center">
  <strong>Fluid Drag-and-Drop Task Management, Sprint Velocity Tracking, and Real-Time Team Collaboration</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Architecture-Full--Stack%20Kanban-blue?style=for-the-badge&logo=trello" alt="Architecture" />
  <img src="https://img.shields.io/badge/UI-React%20%7C%20Tailwind%20CSS-38B2AC?style=for-the-badge&logo=react" alt="UI" />
  <img src="https://img.shields.io/badge/Security-Sanitized%20Showcase-success?style=for-the-badge&logo=shield" alt="Security" />
  <img src="https://img.shields.io/badge/License-Showcase%20Edition-8b5cf6?style=for-the-badge" alt="License" />
</p>

<p align="center">
  <a href="#-system-overview">Overview</a> •
  <a href="#-architecture--drag--drop-engine">Architecture</a> •
  <a href="#-features">Features</a> •
  <a href="#-local-preview">Quick Start</a>
</p>

</div>

---

## 📌 System Overview

TaskPilot provides agile engineering teams with an intuitive, zero-latency board management solution:
- **Optimistic Drag-and-Drop:** Smooth column reordering and card transfers with instant visual feedback.
- **Priority & Due Date Flags:** Color-coded urgency matrices for deadline prioritization.
- **Sprint Lane Filtering:** Instant filtering by assignee, tag, or milestone.

---

## 🛠️ Architecture & Drag-&-Drop Engine

```mermaid
graph LR
    User[Team Member] --> Board[React Drag & Drop Board UI]
    Board --> Optimistic[Optimistic Local State Update]
    Optimistic --> Persistence[REST Persistence API]
    Persistence --> DB[(Task & Column Datastore)]
```

---

## ✨ Features

- 🎯 **Smooth Physics-Based Dragging:** Responsive gesture handling on desktop and touch devices.
- 🏷️ **Tagging & Metadata Customization:** Create bespoke labels for bugs, features, spikes, and chores.
- ⚡ **Offline Resilient:** Changes queue locally during intermittent network drops.

---

## 🚀 Local Preview

```bash
# 1. Frontend
cd frontend
npm install
npm run dev
```

Open `http://localhost:5173` to interact with the task board.

---

<div align="center">

**Architected & Engineered by Nikhil**  
*Lead Full-Stack & Systems Platform Developer*

</div>
