# 🚀 Turbo HTTP+WS Monorepo Boilerplate

[![Built with Turborepo](https://img.shields.io/badge/built%20with-turborepo-ef4444?style=flat&logo=turborepo)](https://turbo.build/repo)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A production-ready monorepo template featuring **HTTP API** + **WebSocket** servers with Turborepo, TypeScript, and modern tooling. Perfect for real-time applications.

![Architecture Diagram](https://user-images.githubusercontent.com/35267447/266492123-4567b9f2-7c3e-4f3d-b1d2-3d4e5f6a7a3a.png)  
*(Example architecture - replace with your actual diagram)*

## ✨ Features

- ⚡ **Blazing Fast** with Turborepo caching
- 🌐 **Dual Server Architecture**
  - REST/GraphQL HTTP API (Express/Fastify)
  - Real-time WebSocket server (ws/Socket.IO)
- 🔒 **Type Safety** with TypeScript
- 📦 **Zero-Config** workspaces with pnpm
- � **Docker-Ready** containerization
- 🧪 **Testing** pre-configured (Jest/Vitest)
- 🔍 **ESLint + Prettier** code quality

## 🛠 Tech Stack

| Area          | Technology              |
|---------------|-------------------------|
| Monorepo      | Turborepo               |
| Package Mgmt  | pnpm                    |
| HTTP Server   | Express.js              |
| WebSocket     | Socket.IO               |
| Language      | TypeScript 5.x          |
| Testing       | Vitest + Supertest      |
| Linting       | ESLint + Prettier       |

## 🚀 Quick Start

### Prerequisites
- Node.js ≥18
- pnpm (`npm install -g pnpm`)
- Docker (optional)

### Installation
```bash
# Clone and setup
npx degit ShubhamSingh-dev/turbo-boilerplate my-app
cd my-app
pnpm install
```

### Development
```bash
# Start all servers in dev mode
pnpm dev

# Start specific service
pnpm dev:api     # HTTP server only
pnpm dev:ws      # WebSocket only
```

### Production Build
```bash
pnpm build       # Build all packages
pnpm start       # Start production servers
```

## 📦 Scripts

| Command          | Description                          |
|------------------|--------------------------------------|
| `pnpm dev`       | Start all dev servers                |
| `pnpm build`     | Build all packages                   |
| `pnpm test`      | Run all tests                        |
| `pnpm lint`      | Lint all packages                    |
| `pnpm docker:up` | Start with Docker Compose            |


## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feat/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feat/amazing-feature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📬 Contact

Shubham Singh - [shbhm_X0](https://x.com/shbhm_X0) - mine.shubhamsingh@gmail.com

Project Link: [turbo-boilerplate](https://github.com/ShubhamSingh-dev/turbo-boilerplate)
```
