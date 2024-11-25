# 📝 PageForm: Dynamic Form Builder & Analytics Platform

## 🚀 Overview

PageForm is a powerful, full-stack web application that empowers users to create, share, and track custom forms with ease. Built with modern web technologies, it offers an intuitive drag-and-drop form builder, comprehensive analytics, and seamless user experience.

## ✨ Key Features

### 1. Form Creation
- **Drag-and-Drop Interface**: Easily build custom forms
- **Dynamic Element Management**: Add, configure, and customize form elements
- **Draft and Publish**: Save forms as drafts or publish them

### 2. Form Analytics
Track your form's performance with detailed metrics:
- Total Visits
- Total Submissions
- Submission Rate
- Bounce Rate

### 3. User Management
- Secure Authentication with Clerk
- User-specific form management
- Personal dashboard

### 4. Sharing and Submissions
- Unique share URL for each form
- Public submission page
- Real-time submission tracking

## 🛠 Tech Stack

- **Frontend**: Next.js 13 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS, Shadcn UI
- **Authentication**: Clerk
- **Database**: Prisma ORM, Vercel PostgreSQL
- **Drag and Drop**: dnd-kit

## 🔧 Getting Started

### Prerequisites
- Node.js
- npm or yarn
- Vercel PostgreSQL database
- Clerk account for authentication

### Installation

1. Clone the repository
```bash

```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Set up environment variables
- Copy `.env.example` to `.env`
- Fill in Clerk and database credentials

4. Run database migrations
```bash
npx prisma generate
npx prisma migrate dev
```

5. Start the development server
```bash
npm run dev
# or
yarn dev
```

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is open-source and available under the MIT License.
