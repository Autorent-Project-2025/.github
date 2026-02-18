<div align="center">

# 🚗 Autorent

### Современная платформа аренды автомобилей

**Арендуйте автомобиль где угодно и когда угодно**

[🌐 Демо](https://autorent-frontend-1iz7.onrender.com/) | [📖 Документация](#-документация) | [🚀 Быстрый старт](#-быстрый-старт)

<br/>

![Frontend CI](https://github.com/Autorent-Project-2025/autorent-frontend/actions/workflows/ci.yml/badge.svg)
![Backend CI](https://github.com/Autorent-Project-2025/autorent-backend/actions/workflows/tests.yml/badge.svg)

</div>

---

## 📋 О проекте

**Autorent** — это full-stack платформа аренды автомобилей, которая позволяет пользователям просматривать доступные машины, оформлять бронирования и удобно управлять своими заказами. Проект создан с использованием современных технологий и лучших практик, обеспечивая удобный опыт как для клиентов, так и для администраторов.

### ✨ Ключевые возможности

- 🔐 **JWT-аутентификация** - Безопасная регистрация и вход пользователей
- 🚙 **Каталог автомобилей** - Просмотр и поиск доступных автомобилей
- 📅 **Умное бронирование** - Проверка доступности в реальном времени и управление бронированиями
- 👤 **Личный кабинет** - Управление личными бронированиями и аккаунтом
- 🎨 **Современный UI/UX** - Премиальный дизайн с поддержкой тёмной темы
- 🔔 **Toast-уведомления** - Удобная система обратной связи для пользователей
- 📱 **Адаптивный дизайн** - Корректно работает на всех устройствах

---

## 🛠 Технологический стек

### Frontend
- **Vue 3** - Прогрессивный JavaScript-фреймворк
- **TypeScript** - Типобезопасная разработка
- **Vite** - Молниеносно быстрый инструмент сборки
- **Tailwind CSS** - Утилитарный подход к стилизации
- **Axios** - HTTP-клиент

### Backend
- **.NET 10** - Современный C#-фреймворк
- **ASP.NET Core** - Web API
- **PostgreSQL** - Надёжная база данных
- **Entity Framework Core** - ORM
- **JWT** - Безопасная аутентификация
- **Clean Architecture** - Поддерживаемая структура кода

### Инфраструктура
- **Docker** - Контейнеризация
- **Docker Compose** - Оркестрация нескольких контейнеров
- **GitHub Actions** - CI/CD-пайплайны

---

## 📦 Репозитории

| Репозиторий | Описание | Статус |
|------------|-------------|--------|
| [autorent-frontend](https://github.com/Autorent-Project-2025/autorent-frontend) | Frontend-приложение на Vue 3 + TypeScript | ![CI](https://github.com/Autorent-Project-2025/autorent-frontend/actions/workflows/ci.yml/badge.svg) |
| [autorent-backend](https://github.com/Autorent-Project-2025/autorent-backend) | Backend API на .NET 10 с Clean Architecture | ![Tests](https://github.com/Autorent-Project-2025/autorent-backend/actions/workflows/tests.yml/badge.svg) |
| [autorent-infrastructure](https://github.com/Autorent-Project-2025/autorent-infrastructure) | Docker-конфигурации и скрипты деплоя | - |

---

## 🚀 Быстрый старт

### Требования

- Docker & Docker Compose
- .NET 10 SDK (для backend-разработки)
- Node.js 18+ (для frontend-разработки)

### 1. Клонируйте репозитории

```bash
# Клонируйте все репозитории
git clone https://github.com/Autorent-Project-2025/autorent-frontend
git clone https://github.com/Autorent-Project-2025/autorent-backend
git clone https://github.com/Autorent-Project-2025/autorent-infrastructure
```

### 2. Запустите базу данных

```bash
cd autorent-infrastructure/docker/postgres
cp .env.example .env
docker compose up -d
```

### 3. Запустите backend

```bash
cd autorent-backend
cp .env.example .env
# Отредактируйте .env и задайте JWT-ключ (минимум 32 символа)
docker compose up -d
```

API будет доступен по адресу `http://localhost:5000`

### 4. Запустите frontend

```bash
cd autorent-frontend
npm install
npm run dev
```

Приложение будет доступно по адресу `http://localhost:5173`

---

## 📖 Документация

- [Документация Frontend](https://github.com/Autorent-Project-2025/autorent-frontend#readme)
- [Документация Backend API](https://github.com/Autorent-Project-2025/autorent-backend#readme)
- [Настройка инфраструктуры](https://github.com/Autorent-Project-2025/autorent-infrastructure#readme)

---

## 🤝 Вклад в проект

Мы приветствуем вклад в проект. Не стесняйтесь создавать issues и отправлять pull request'ы.

1. Сделайте fork репозитория
2. Создайте ветку для вашей задачи (`git checkout -b feature/amazing-feature`)
3. Закоммитьте изменения (`git commit -m 'Add amazing feature'`)
4. Отправьте ветку в удалённый репозиторий (`git push origin feature/amazing-feature`)
5. Создайте Pull Request

---

## 📄 Лицензия

Этот проект является частью Autorent Project 2025.

---

<div align="center">

**Сделано с ❤️ командой Autorent**

[⬆ Наверх](#-autorent)

</div>
