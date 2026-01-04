<div align="center">

# 🚗 Autorent

### Modern Car Rental Platform

**Rent a car anywhere and anytime**

[🌐 Live Demo](https://autorent-frontend-1iz7.onrender.com/) | [📖 Documentation](#-documentation) | [🚀 Quick Start](#-quick-start)

<br/>

![Frontend CI](https://github.com/Autorent-Project-2025/autorent-frontend/actions/workflows/ci.yml/badge.svg)
![Backend CI](https://github.com/Autorent-Project-2025/autorent-backend/actions/workflows/tests.yml/badge.svg)

</div>

---

## 📋 About

**Autorent** is a full-stack car rental platform that allows users to browse available vehicles, make bookings, and manage their reservations with ease. Built with modern technologies and best practices, it provides a seamless experience for both customers and administrators.

### ✨ Key Features

- 🔐 **JWT Authentication** - Secure user registration and login
- 🚙 **Car Catalog** - Browse and search available vehicles
- 📅 **Smart Booking** - Real-time availability checking and booking management
- 👤 **User Dashboard** - Manage personal bookings and account
- 🎨 **Modern UI/UX** - Premium design with dark mode support
- 🔔 **Toast Notifications** - User-friendly feedback system
- 📱 **Responsive Design** - Works seamlessly on all devices

---

## 🛠 Tech Stack

### Frontend
- **Vue 3** - Progressive JavaScript framework
- **TypeScript** - Type-safe development
- **Vite** - Lightning-fast build tool
- **Tailwind CSS** - Utility-first styling
- **Axios** - HTTP client

### Backend
- **.NET 10** - Modern C# framework
- **ASP.NET Core** - Web API
- **PostgreSQL** - Reliable database
- **Entity Framework Core** - ORM
- **JWT** - Secure authentication
- **Clean Architecture** - Maintainable code structure

### Infrastructure
- **Docker** - Containerization
- **Docker Compose** - Multi-container orchestration
- **GitHub Actions** - CI/CD pipelines

---

## 📦 Repositories

| Repository | Description | Status |
|------------|-------------|--------|
| [autorent-frontend](https://github.com/Autorent-Project-2025/autorent-frontend) | Vue 3 + TypeScript frontend application | ![CI](https://github.com/Autorent-Project-2025/autorent-frontend/actions/workflows/ci.yml/badge.svg) |
| [autorent-backend](https://github.com/Autorent-Project-2025/autorent-backend) | .NET 10 backend API with Clean Architecture | ![Tests](https://github.com/Autorent-Project-2025/autorent-backend/actions/workflows/tests.yml/badge.svg) |
| [autorent-infrastructure](https://github.com/Autorent-Project-2025/autorent-infrastructure) | Docker configurations and deployment scripts | - |

---

## 🚀 Quick Start

### Prerequisites

- Docker & Docker Compose
- .NET 10 SDK (for backend development)
- Node.js 18+ (for frontend development)

### 1. Clone the repositories

```bash
# Clone all repositories
git clone https://github.com/Autorent-Project-2025/autorent-frontend
git clone https://github.com/Autorent-Project-2025/autorent-backend
git clone https://github.com/Autorent-Project-2025/autorent-infrastructure
```

### 2. Start the database

```bash
cd autorent-infrastructure/docker/postgres
cp .env.example .env
docker compose up -d
```

### 3. Start the backend

```bash
cd autorent-backend
cp .env.example .env
# Edit .env and set JWT key (min 32 characters)
docker compose up -d
```

The API will be available at `http://localhost:5000`

### 4. Start the frontend

```bash
cd autorent-frontend
npm install
npm run dev
```

The app will be available at `http://localhost:5173`

---

## 📖 Documentation

- [Frontend Documentation](https://github.com/Autorent-Project-2025/autorent-frontend#readme)
- [Backend API Documentation](https://github.com/Autorent-Project-2025/autorent-backend#readme)
- [Infrastructure Setup](https://github.com/Autorent-Project-2025/autorent-infrastructure#readme)

---

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues or pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is part of the Autorent Project 2025.

---

<div align="center">

**Made with ❤️ by the Autorent Team**

[⬆ Back to Top](#-autorent)

</div>
