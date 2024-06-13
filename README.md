Certainly! Here's the revised README file without the image:

---

# Event Planner App

## Table of Contents

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)
5. [Links](#links)

## Introduction <a name="introduction"></a>

The Event Planner App, built on Next.js 14, is a comprehensive platform for managing events. It allows users to discover, create, and manage events globally. The app integrates seamless payment processing through Stripe, enabling users to purchase event tickets effortlessly.

## Tech Stack <a name="tech-stack"></a>

- Node.js
- Next.js 14
- TypeScript
- TailwindCSS
- Stripe
- Zod
- React Hook Form
- Shadcn
- uploadthing

## Features <a name="features"></a>

- **Authentication (CRUD) with Clerk:** Secure user management and authentication.
- **Events (CRUD):** Create, read, update, and delete events with full control.
- **Related Events:** Display related events to enhance user engagement.
- **Organized Events:** Efficiently organize and display events.
- **Search & Filter:** Robust search and filter functionality for events.
- **New Category:** Dynamic event categorization.
- **Checkout and Pay with Stripe:** Secure payment transactions.
- **Event Orders:** Comprehensive order management system.

## Quick Start <a name="quick-start"></a>

### Prerequisites

- Git
- Node.js
- npm

### Clone the Repository

```bash
git clone https://github.com/your-username/your-project.git
cd your-project
```

### Installation

```bash
npm install
```

### Set Up Environment Variables

Create a `.env` file in the root directory with the following:

```env
# Replace with your actual credentials
NEXT_PUBLIC_SERVER_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_CLERK_WEBHOOK_SECRET=
MONGODB_URI=
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

### Running the Project

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## Links <a name="links"></a>

- [Live Demo](https://event-platform-dev.vercel.app/)
- [Repository](https://github.com/Adarsh01208/event_planner)

---

This README provides an overview of the Event Planner App, including its tech stack, features, setup instructions, and relevant links. Adjust the content and links to match your actual project details.