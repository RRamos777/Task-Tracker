
# 🧠 Task Tracker TS

A minimalist Task Tracker app built with **Next.js**, **TypeScript**, **Tailwind CSS**, and **Firebase Firestore**.

## 🔧 Tech Stack

- Next.js 13 (App Router)
- React 18
- TypeScript
- Tailwind CSS
- Firebase Authentication
- Firestore Database

## ✨ Features

- 🔐 Login with Firebase Auth
- ✅ Create / Complete / Delete Tasks
- 📡 Real-time Sync with Firestore
- 🎨 Responsive UI with Tailwind CSS

## 🚀 Project Structure

```
/app
  /tasks
    page.tsx          # Displays list of tasks
    create.tsx        # Task creation form
/firebase
  config.ts           # Firebase config + init
/components
  TaskCard.tsx        # Reusable task card
  Navbar.tsx
/styles
  globals.css
```

## 🧪 TypeScript Highlights

- Strong typing via interfaces (`Task`, `User`)
- API response validation
- Optional chaining and null safety
- Modular and reusable hooks

## 🖥️ Demo (Mock)

You can run the project locally:
```bash
git clone https://github.com/rennielramos/task-tracker-ts.git
cd task-tracker-ts
npm install
npm run dev
```

## 📁 Sample File: Task Interface

```ts
export interface Task {
  id: string;
  title: string;
  description?: string;
  completed: boolean;
  createdAt: string;
}
```

---

> ⚠️ *Note: This is a mock repo used for demo purposes during developer interviews.*
