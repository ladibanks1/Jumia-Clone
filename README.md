# Jumia Clone

A full-stack e-commerce platform inspired by Jumia, built with Vite + React for the frontend and NestJS for the backend. This application simulates a real online marketplace, featuring product listings, search and filter functionality, shopping cart management, and order processing. The project is organized as a pnpm monorepo with separate client and server packages for modular development.

---

## **Table of Contents**

- [Tech Stack](#tech-stack)  
- [Project Structure](#project-structure)  
- [Getting Started](#getting-started)  
- [Development](#development)
- [Contributing](#contributing)    
- [License](#license)  

---

## **Tech Stack**

- **Frontend:** React, Vite, TypeScript  
- **Backend:** NestJS, TypeScript, RxJS  
- **Package Management:** pnpm Workspaces  
- **Database:** Postgres  
- **Hosting:** Render (Frontend as Static Site, Backend as Web Service)  

---

## **Project Structure**

```text
Jumia_Clone/
│
├── client/               # Vite + React frontend
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── .env              # Frontend environment variables (VITE_*)
│
├── server/               # NestJS backend
│   ├── src/
│   ├── package.json
│   └── .env              # Backend environment variables (DB, JWT, etc.)
│
├── node_modules/         # hoisted dependencies (pnpm workspace)
├── package.json          # root workspace
└── pnpm-workspace.yaml   # pnpm workspace config
```

---

## **Getting Started**

**Prerequisites**
- Node.js >= 20.x
- pnpm >= 8.x
- Database server (PosrtgreSQL)

**Clone the Repositiory**
```bash
git clone https://github.com/yourusername/jumia-clone.git
cd jumia-clone
```

**Install Dependencies**
```bash
pnpm install
```
This will install all dependencies for both client and server thanks to the pnpm workspace setup.

---
**Developement**

**Run Frontend**
``` bash
pnpm run start:client
```
This starts the React Vite dev server at http://localhost:5173 (default).

**Run Backend**
``` bash
pnpm run start:server
```
Backend runs on http://localhost:3000 (default).


**Contributing**
1. Fork the repository

2. Create a feature branch: git checkout -b feature/your-feature

3. Commit your changes: git commit -m "Add some feature"

4. Push to the branch: git push origin feature/your-feature

5. Open a pull request
Please follow the coding standards and use ESLint / Prettier formatting.


**License** 
This project is licensed under the MIT License.

