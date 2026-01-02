# Micro-Task Platform - Client

Frontend application for the Micro-Task and Earning Platform built with React, Vite, and Tailwind CSS.

## Tech Stack

- **React 18** - UI library
- **Vite** - Build tool and dev server
- **React Router v6** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **Firebase Auth** - Authentication
- **Axios** - HTTP client
- **Stripe** - Payment processing
- **Swiper** - Modern slider library
- **React Icons** - Icon library
- **React Hot Toast** - Toast notifications

## Project Structure

```
src/
├── components/
│   ├── shared/          # Navbar, Footer
│   ├── home/            # Homepage sections
│   └── dashboard/       # Dashboard components
├── pages/
│   ├── dashboard/
│   │   ├── buyer/       # Buyer dashboard pages
│   │   ├── worker/      # Worker dashboard pages
│   │   └── admin/       # Admin dashboard pages
│   ├── Home.jsx
│   ├── Login.jsx
│   └── Register.jsx
├── contexts/            # React contexts (Auth)
├── hooks/               # Custom hooks
├── utils/               # Helper functions
└── routes/              # Route configurations
```

## Getting Started

### Prerequisites

- Node.js 18+ and npm

### Installation

1. Install dependencies:
```bash
npm install
```

2. Create `.env.local` file:
```bash
cp .env.example .env.local
```

3. Add your environment variables to `.env.local`

4. Start development server:
```bash
npm run dev
```

The app will open at `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## Features

### For Workers
- Browse available tasks
- Submit task completions
- Track earnings
- Request withdrawals

### For Buyers
- Create and manage tasks
- Review submissions
- Purchase coins
- Track payments

### For Admins
- Manage users
- Manage tasks
- Approve withdrawals
- View platform statistics

## Environment Variables

See `.env.example` for required environment variables.

## Screenshots

### Homepage
![Homepage](https://i.ibb.co.com/4nFppdJD/localhost-5173-7.png)

### Dashboards

**Admin Dashboard**
![Admin Dashboard](https://i.ibb.co.com/MkfyYSXL/localhost-5173-8.png)

**Buyer Dashboard**
![Buyer Dashboard](https://i.ibb.co.com/xKYtrGs7/localhost-5173-9.png)

## What I Learned in this Vibe Coding Project

This project was built using a "Vibe Coding" approach, leveraging AI assistance to accelerate development while maintaining code quality. Key learnings include:

- **AI-Assisted Workflow:** Integrating AI agents to handle boilerplate code, debugging, and rapid prototyping.
- **Complex State Management:** Handling multi-role authentication (Worker/Buyer/Admin) and real-time state updates.
- **Secure Payments:** Implementing Stripe for secure financial transactions and coin-based economy logic.
- **System Architecture:** Designing a scalable MERN stack architecture with clean separation of concerns.
- **Responsive Design:** Using Tailwind CSS and DaisyUI to create a modern, mobile-first interface.

## ⏱Development Time

- **Estimated Build Time:** ~15-20 Hours
- **Core Features:** 10 Hours
- **UI/UX Refinement:** 5 Hours
- **Testing & Debugging:** 3 Hours
- **Built with:** ♥️ and AI Assistance

## Developer

**Ashikur Rahman**
- GitHub: [@ashikurahman1](https://github.com/ashikurahman1)
- [LinkedIn](https://linkedin.com/in/ashikur-dev)

## License

MIT