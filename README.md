# TechExplorer - AI-Powered Tech Reviews

A modern web app for exploring tech products with AI summaries, Q&A, videos, and 3D models.

## Features

- **Search** - Find any tech product instantly
- **AI Summaries** - Detailed pros/cons and analysis
- **AI Chat** - Ask questions about any product
- **Video Reviews** - Embedded YouTube reviews and unboxings

## Getting Started

```bash
cd tech-explorer
npm install
npm run dev
```

Open http://localhost:5173 in your browser.

## Tech Stack

- React + TypeScript
- Vite
- Tailwind CSS
- Three.js / React Three Fiber (3D)
- Lucide Icons

## Extending

To add real AI responses, replace the `generateAIResponse` function in `AIChat.tsx` with an API call to OpenAI, Claude, or your preferred AI service.

To add real 3D models, update `Model3DViewer.tsx` to load GLTF/GLB files using `@react-three/drei`'s `useGLTF` hook.

