# ❤️ LocateHope

> A community-driven platform that helps connect individuals in need with shelters, support organizations, volunteers, and community resources through reporting, donations, and engagement.

![License](https://img.shields.io/badge/license-MIT-blue)
![Stack](https://img.shields.io/badge/stack-React%20%7C%20TypeScript-green)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

---

## 📌 Problem Statement

Many individuals experiencing homelessness or hardship struggle to access available shelters and support services due to a lack of awareness, visibility, and coordination. At the same time, communities often want to help but lack a centralized platform to discover shelters, report cases, donate resources, or participate in support initiatives.

LocateHope aims to bridge this gap by providing a unified platform where users can explore shelters, submit reports, contribute donations, earn community rewards, and engage with organizations working to create social impact.

---

## 🚀 Features

| Feature                  | Description                                                   |
| ------------------------ | ------------------------------------------------------------- |
| 📍 Location Mapping      | Interactive map interface for location-based services         |
| 🏠 Shelter Directory     | Browse partner shelters and available support services        |
| 📝 Reporting System      | Submit and track reports for individuals requiring assistance |
| 🎁 Rewards Program       | Community engagement through rewards and recognition          |
| 💰 Donation Platform     | Support shelters and initiatives through donations            |
| 🔐 Authentication System | User registration, login, and protected routes                |
| 📊 User Dashboard        | Centralized view of user activity and engagement              |
| 🤝 Sponsor Directory     | Showcase corporate and community sponsors                     |
| 📱 Responsive Design     | Optimized for desktop, tablet, and mobile devices             |

---

## 🏗️ Tech Stack

### Frontend

* ⚛️ React 18
* 🔷 TypeScript
* 🎨 Tailwind CSS
* 🛣️ React Router

### State Management

* 🔐 AuthContext
* 📋 ReportContext
* 🎁 RewardContext

### Maps & Visualization

* 📍 Location Mapping Components

### Build Tools

* ⚡ Vite
* 📦 npm

### Deployment

* 🌐 Netlify

---

## 📂 Project Structure

```text
LocateHope-Project/
│
├── public/
│   └── favicon.svg
│
├── src/
│   ├── components/
│   │   ├── auth/
│   │   │   └── ProtectedRoute.tsx
│   │   │
│   │   ├── layout/
│   │   │   ├── Navbar.tsx
│   │   │   └── Footer.tsx
│   │   │
│   │   ├── maps/
│   │   │   └── LocationMap.tsx
│   │   │
│   │   ├── reports/
│   │   │   └── ReportCard.tsx
│   │   │
│   │   └── rewards/
│   │       └── RewardCard.tsx
│   │
│   ├── contexts/
│   │   ├── AuthContext.tsx
│   │   ├── ReportContext.tsx
│   │   └── RewardContext.tsx
│   │
│   ├── pages/
│   │   ├── About.tsx
│   │   ├── Dashboard.tsx
│   │   ├── Donate.tsx
│   │   ├── Home.tsx
│   │   ├── Login.tsx
│   │   ├── NotFound.tsx
│   │   ├── Register.tsx
│   │   ├── Report.tsx
│   │   ├── Rewards.tsx
│   │   ├── Shelters.tsx
│   │   └── Sponsors.tsx
│   │
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│   └── vite-env.d.ts
│
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── tailwind.config.js
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
├── vite.config.ts
│
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Node.js 18+
* npm

### 1. Clone the Repository

```bash
git clone https://github.com/asifa-h/LocateHope-Project.git

cd LocateHope-Project
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Development Server

```bash
npm run dev
```

Application runs at:

```text
http://localhost:5173
```

### 4. Build for Production

```bash
npm run build
```

### 5. Preview Production Build

```bash
npm run preview
```

---

## 🧠 How It Works

### User Registration Flow

1. User creates an account.
2. Authentication state is managed through AuthContext.
3. Protected routes ensure secure access to authorized pages.
4. User gains access to reporting, rewards, and dashboard features.

---

### Reporting Flow

1. User identifies an individual requiring assistance.
2. Report is submitted through the reporting interface.
3. Report data is managed through ReportContext.
4. Reports can be viewed and tracked within the platform.

---

### Shelter Discovery Flow

1. User browses partner shelters.
2. Shelter information is displayed through dedicated shelter pages.
3. Available services and support opportunities are presented.
4. Users can discover organizations providing assistance.

---

### Rewards Flow

1. Users engage with community initiatives.
2. Reward data is managed through RewardContext.
3. Reward cards display achievements and participation metrics.
4. Community engagement is encouraged through recognition.

---

### Donation Flow

1. User selects a donation amount.
2. Donation options are presented through the donation page.
3. Users can support community initiatives and shelters.
4. Contributions help strengthen the support ecosystem.

---

## 📈 Scalability

* Modular React component architecture
* Context-based state management for future expansion
* TypeScript support for maintainability and reliability
* Easily deployable through modern hosting platforms
* Extensible structure for backend and API integrations
* Ready for future NGO, volunteer, and shelter onboarding features

---

## 💡 Feasibility

LocateHope is built using modern frontend technologies that are lightweight, scalable, and easy to maintain. The project follows a component-based architecture with reusable UI elements, centralized state management, and responsive design principles. This approach allows future integrations such as databases, authentication providers, payment gateways, and real-time reporting systems without major architectural changes.

---

## 🌟 Novelty

Unlike traditional shelter directories or donation websites that focus on a single aspect of community support, LocateHope combines multiple engagement channels into one platform. Users can explore shelters, submit reports, participate in reward programs, support causes through donations, and discover sponsors contributing to social impact initiatives.

The platform emphasizes community participation and accessibility while maintaining a clean and user-friendly experience.

---

## 🔧 Feature Depth

* **Protected Route System** enables controlled access to authenticated pages.
* **Context-Based State Management** provides centralized handling of authentication, reports, and rewards.
* **Interactive Mapping Components** support location-focused functionality.
* **Shelter Discovery Interface** presents organizations and available support resources.
* **Reward Management System** promotes community engagement and participation.
* **Donation Platform UI** provides structured contribution workflows.
* **Responsive Layout Components** ensure accessibility across devices.

---

## ⚠️ Ethical Use & Disclaimer

LocateHope is intended solely for social welfare, community engagement, and awareness purposes.

Users should provide accurate information when submitting reports and use the platform responsibly. Any future integrations involving personal information, donations, or location data should comply with applicable privacy, security, and legal requirements.

Use responsibly and ethically.

---

## 📜 License

Licensed under the MIT License.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add feature-name"`
4. Push and open a Pull Request

---

## 🧩 Author

**Asifa H**

📧 [asifa.h.2024.aiml@rajalakshmi.edu.in](mailto:asifa.h.2024.aiml@rajalakshmi.edu.in)

🔗 GitHub: https://github.com/asifa-h

---

## ❤️ Vision

Empowering communities to connect, support, and create meaningful impact through technology-driven social engagement.
