

Nike Ecommerce

   

## 📋 <a name="table">Table of Contents</a>

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔗 [Assets](#links)
6. 🚀 [More](#more)

## 🚨 Tutorial

Nike-style eCommerce built with Devin AI, Next.js, Drizzle ORM, and Better Auth. In this project, you’ll master prompting as Devin helps generate sleek product pages powered by Next.js 15, TypeScript, and TailwindCSS. The backend runs on Neon PostgreSQL with Drizzle ORM, authentication is handled with Better Auth, and Zustand manages state — all packaged in a clean, modular UI to help you ship faster.

## ⚙️ Tech Stack

- **[Better Auth](https://www.better-auth.com/)** is a framework-agnostic authentication and authorization library for TypeScript. It provides built-in support for email and password authentication, social sign-on (Google, GitHub, Apple, and more), and multi-factor authentication, simplifying user authentication and account management.

- **[Drizzle ORM](https://orm.drizzle.team/)** is a lightweight and performant TypeScript ORM designed with developer experience in mind. It provides a seamless interface between application code and database operations while maintaining high performance and reliability.

- **[Neon](https://neon.com/)** is a fully managed, serverless PostgreSQL database platform. It offers features like instant provisioning, autoscaling, and database branching, enabling developers to build scalable applications without managing infrastructure.

- **[Next.js](https://nextjs.org/docs)** is a powerful React framework for building full-stack web applications. It simplifies development with features like server-side rendering, static site generation, and API routes, enabling developers to focus on building products and shipping quickly.

- **[TailwindCSS](https://tailwindcss.com/)** is a utility-first CSS framework that allows developers to build custom, responsive designs quickly without leaving their HTML. It provides pre-defined classes for layout, typography, colors, and more.

- **[TypeScript](https://www.typescriptlang.org/)** is a superset of JavaScript that adds static typing, providing better tooling, code quality, and error detection for developers. It is ideal for building large-scale applications and enhances the development experience.

- **[Zustand](https://zustand-demo.pmnd.rs)** is a minimal, hook-based state management library for React. It lets you manage global state with zero boilerplate, no context providers, and excellent performance through selective state subscriptions.

## 🔋 Features

👉 **Landing Page**: A fast, engaging homepage that introduces your brand and products with smooth animations and clear calls to action.

👉 **Product Listing Page**: Browse all products with filters, sorting, and real-time availability—powered by Devin AI-generated content for dynamic updates.

👉 **Product Details Page**: Detailed product info, images, and reviews with AI-enhanced descriptions to help customers make confident buying decisions.

👉 **Auth Pages**: Secure and seamless user signup, login, and password recovery using Better Auth, ensuring smooth access without backend hassles.

And many more, including code architecture and reusability.

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

** Cloning the Repository **

cd e-commerce
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
# Database
DATABASE_URL="postgresql://username:password@host:port/database"

# Better Auth
BETTER_AUTH_SECRET="your-secret-key-here"
BETTER_AUTH_URL="http://localhost:3000"

# GitHub OAuth (optional)
GITHUB_CLIENT_ID=""
GITHUB_CLIENT_SECRET=""

# Google OAuth (optional)
GOOGLE_CLIENT_ID=""
GOOGLE_CLIENT_SECRET=""
```

Replace the placeholder values with your credentials. You can get these by signing up at: [**NeonDB**](https://neon.com/), [**Better-Auth**](https://www.better-auth.com/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## 📁 Project Structure

```
src/
├── app/
│   ├── api/auth/[...all]/route.ts  # Better Auth API routes
│   └── page.tsx                    # Homepage
├── lib/
│   ├── auth/
│   │   └── index.ts               # Better Auth configuration
│   └── db/
│       ├── index.ts               # Database connection
│       └── schema.ts              # Database schema
└── store/
    ├── auth.ts                    # Authentication state
    └── cart.ts                    # Shopping cart state
```

## 🗄️ Database Schema

The application includes the following tables:

- **users**: User accounts and profiles
- **sessions**: User sessions for Better Auth
- **accounts**: OAuth accounts and credentials
- **verifications**: Email verification tokens
- **products**: Product catalog
- **orders**: Customer orders
- **order_items**: Individual items in orders

## 🔗 Assets

Assets and snippets used in the project can be found in the **[video kit](https://jsm.dev/nikecom-kit)**.

<a href="https://jsm.dev/nikecom-kit" target="_blank">
  <img src="public/readme/videokit.webp" alt="Video Kit Banner">
</a>
