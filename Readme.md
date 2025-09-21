# Laravel + React Template for Lovable Projects

A fully-configured, production-ready template combining **Laravel** (API-first backend) with **React** (frontend) — designed for [Lovable](lovable.dev) projects that need a fast start without fighting boilerplate.

## 🚀 Features

* **Laravel 12** backend
* **radix UI** UI components
* **Lovable UI** Lovable UI components
* **React 18 + Vite** frontend – blazing-fast dev server & build
* **Tailwind 3** css framework
* **TypeScript support** out of the box
* **Prettier + ESLint** for consistent code formatting
* **Laravel Pint** for backend code style
* **Environment management** using `.env` files
* **Hot Reloading** for both backend & frontend

## 📦 Tech Stack

| Layer        | Tooling                                     |
| ------------ | --------------------------------------------|
| **Backend**  | Laravel, MySQL/Postgres (configurable)      |
| **Frontend** | React, TypeScript, TailwindCSS              |
| **Tooling**  | Docker, Composer, npm/yarn, ESLint, Prettier|
| **Testing**  | Pest (PHP)                                  |

## 🛠️ Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/babak271/lara_lovable.git my-lovable-project
cd my-lovable-project
```

### 2. Set up environment

```bash
cp .env.example .env
```

Update `.env` with your database and app configuration.

### 3. Install dependencies

```bash
composer install
php artisan key:generate
php artisan migrate
composer dev
```

### 4. Open in browser

* Your website: [http://localhost:8000](http://localhost:8000)

You’re ready to start building.

## 🧪 Running Tests

```bash
composer test
```

## 📄 Project Structure

```
.
├── app           # Laravel application
├── bootstrap
├── config
├── database
├── node_modules
├── public
├── resources     # Frontend application
├── routes
├── storage
├── tests
└── vendor
```
## 🔢 Versioning

This template follows **Laravel's major versioning** for releases.

* **Major version** of the template matches the major version of Laravel it ships with (e.g. `v12.x.x` uses Laravel 12).
* **Minor version** increments introduce new features or improvements to the template without breaking compatibility.
* **Patch version** increments are for bug fixes and small tweaks.

This ensures you always know which Laravel version you’re getting when starting a new project.

See [CHANGELOG.md](./CHANGELOG.md) for a list of all notable changes.

## 🤝 Contributing

PRs are welcome! Please follow code style and run tests before submitting.

## 📜 License

This project is open-source and available under the [MIT License](./LICENSE).
