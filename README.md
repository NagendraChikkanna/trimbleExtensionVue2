# Vue 2 + Vite Hello World Project

A simple Hello World project built with Vue 2 and Vite build tool.

## Project Setup

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

### Development

To start the development server:
```bash
npm run dev
```

This will start the development server on `http://localhost:3000` and automatically open your browser.

### Build for Production

To build the project for production:
```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.

### Preview Production Build

To preview the production build locally:
```bash
npm run preview
```

## Project Structure

```
├── public/
├── src/
│   ├── assets/
│   │   └── logo.png
│   ├── components/
│   │   └── HelloWorld.vue
│   ├── App.vue
│   └── main.js
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Technologies Used

- **Vue 2**: Progressive JavaScript framework
- **Vite**: Next-generation frontend build tool
- **@vitejs/plugin-vue2**: Vite plugin for Vue 2 support

## Features

- ⚡️ Lightning fast HMR with Vite
- 📦 Optimized build with Vite
- 🎨 Vue 2 Single File Components
- 🔧 Simple and clean project structure