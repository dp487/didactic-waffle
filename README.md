# didactic-waffle

A sleek, modern **Next.js TODO application** built with the App Router. This project demonstrates a clean, functional UI with smooth interactions, localStorage persistence, and a minimalist design. Perfect for showcasing Next.js 13+ App Router patterns and React state management.

## 🎯 Features

- **Add Tasks**: Create new TODO items with UUID-based IDs
- **Mark Complete**: Toggle task completion status with visual feedback
- **Edit Tasks**: Inline editing to modify task descriptions
- **Delete Tasks**: Remove completed or active tasks
- **Persistent Storage**: All tasks saved to localStorage automatically
- **Progress Tracking**: Hero component shows completion statistics
- **Responsive Design**: Mobile-first, scales beautifully to desktop
- **Smooth Animations**: Clean, intuitive interactions throughout

## 🛠️ Tech Stack

- **Framework:** Next.js 13+ (App Router)
- **Language:** React 18+
- **Styling:** Tailwind CSS
- **State Management:** React Hooks (useState, useEffect, useReducer)
- **Storage:** localStorage for persistence
- **Build:** Vite-like development experience with Next.js

## 📁 Project Structure

```
didactic-waffle/
├── src/
│   ├── app/
│   │   ├── layout.js            # Root layout with metadata
│   │   └── page.js              # Main TODO page
│   ├── components/
│   │   ├── Header.jsx           # Top navigation/header
│   │   ├── TODOHero.jsx         # Progress tracking hero
│   │   ├── Form.jsx             # Add new task form
│   │   └── TODOList.jsx         # Task list rendering
│   ├── public/                  # Static assets
│   │   └── images/              # Images, icons, etc.
│   ├── jsconfig.json            # JavaScript config
│   └── next.config.mjs          # Next.js config
├── package.json                 # npm dependencies
├── package-lock.json            # Dependency lock file
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd didactic-waffle

# Install dependencies
npm install

# Start development server
npm run dev
```

### Running

```bash
# Development
npm run dev

# Production build
npm run build
npm run start
```

### API Routes

Next.js App Router supports API routes in `src/app/api/`:

```bash
# Example API endpoint
curl http://localhost:3000/api/hello
```

## 📖 Usage

1. **Start the dev server:**
   ```bash
   npm run dev
   ```

2. **Open in browser:**
   ```bash
   # macOS
   open http://localhost:3000

   # Windows
   start http://localhost:3000

   # Linux
   xdg-open http://localhost:3000
   ```

## 🎨 Customization

### Styling

Edit Tailwind classes in components to customize:
- Color schemes
- Typography
- Spacing
- Animations

### Functionality

Extend with:
- Priority levels
- Due dates
- Categories/tags
- Drag-and-drop reordering
- Dark mode toggle
- Export/import (JSON)

### Data Storage

Replace localStorage with:
- API backend (Express/FastAPI)
- Database (MongoDB/PostgreSQL)
- Server-side state management

## 🧪 Future Work

- Add authentication (JWT/NextAuth)
- Add backend API integration
- Add drag-and-drop reordering
- Add dark mode toggle
- Add keyboard shortcuts
- Add notifications (Toast messages)
- Add export/import functionality
- Add file attachments
- Add collaboration features (Real-time with Socket.io)

## 🖼️ Demo

The app features:
- Clean, minimalist design
- Smooth, intuitive interactions
- Responsive layout (mobile to desktop)
- Progress tracking with completion stats
- In-place editing for quick updates
- Persistent storage across sessions

## 📄 License

MIT
