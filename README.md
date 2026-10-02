# task-manager-v1

A clean, minimal **task manager UI component** built with React and TypeScript — create, complete, and delete tasks with a polished shadcn/ui interface.

## Features

- **Add tasks** — title + description form with validation (title required)
- **Toggle completion** — mark tasks complete/incomplete with a single click
- **Delete tasks** — remove tasks instantly
- **Newest-first ordering** — latest tasks appear at the top of the list
- **Responsive layout** — centered card layout that works on any screen size
- Fully typed with TypeScript (`Task` interface: id, title, description, completed, createdAt)

## Tech Stack

- **React** (function components + hooks: `useState`)
- **TypeScript** — strict typing for tasks and event handlers
- **shadcn/ui** — `Card`, `CardHeader`, `CardTitle`, `CardContent`, `Input`, `Button` components
- **lucide-react** — `Check`, `Trash`, `Plus` icons
- **Tailwind CSS** — utility-first styling

## Quick Start

1. Make sure you have a React project with shadcn/ui and Tailwind CSS set up.
2. Copy the `task-manager v1` file into your components directory (rename to `TaskManager.tsx`).
3. Import and render it:

```tsx
import TaskManager from "./components/TaskManager";

export default function App() {
  return <TaskManager />;
}
```

4. Install dependencies if missing:

```bash
npm install lucide-react
```

> Note: tasks are held in component state (`useState`) only — state resets on page reload. For persistence, wire in `localStorage` or a backend.

## Project Structure

```
.
├── task-manager v1   # The TaskManager component (rename to TaskManager.tsx)
├── README.md
└── LICENSE           # CC0 1.0 Universal
```

## Deploy Notes

This is a standalone UI component, not a full application — it is not deployed anywhere. Drop it into any React + shadcn/ui project to use it.

---

Built by Girish Lade — https://ladestack.in
