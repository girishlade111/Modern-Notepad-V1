# Modern Notepad V1

A feature-rich, modern notepad/text-editor UI built as a standalone React component — with a formatting toolbar, multi-document tabs, and document management, styled with Tailwind CSS and shadcn/ui.

> **Note:** This repo contains a single self-contained React component file (`Modern Notepad`) — a drop-in UI component rather than a runnable application. Copy it into any React + shadcn/ui project to use it.

## Features

- **Rich text formatting** — bold, italic, underline toggles
- **Text alignment** — left, center, right, justify
- **Text color picker** — per-document color customization
- **Multi-document tabs** — create, switch, and close documents (plus / X controls)
- **Document actions** — save, import, and print buttons
- **Modern dark-friendly UI** — built with shadcn/ui components (Button, Card, Textarea) and lucide-react icons
- **Auto-resizing editor** — textarea grows with content via refs

## Tech Stack

- **React** (hooks: `useState`, `useRef`, `useEffect`)
- **Tailwind CSS** — utility styling
- **shadcn/ui** — `Button`, `Card`, `Textarea` components
- **lucide-react** — toolbar icons

## Quick Start (using it in your project)

1. Make sure your project has React, Tailwind CSS, shadcn/ui, and lucide-react installed.
2. Copy `Modern Notepad` into your components directory (e.g. `components/modern-notepad.jsx`).
3. Import and render it:

```jsx
import ModernNotepad from './components/modern-notepad'

export default function App() {
  return <ModernNotepad />
}
```

## Project Structure

```
Modern-Notepad-V1/
├── Modern Notepad   # The complete React component (358 lines)
├── LICENSE          # License terms
└── README.md        # This file
```

## License

See [LICENSE](./LICENSE) for details.

---

Built by **Girish Lade** — https://ladestack.in
