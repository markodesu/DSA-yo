# DSA Dashboard

An interactive learning platform for Data Structures and Algorithms with visual demonstrations and animations.

## Features

- **Search Algorithms**: Linear Search, Binary Search
- **Sorting Algorithms**: Bubble Sort, Quick Sort, Merge Sort, Insertion Sort, Selection Sort, Radix Sort, Counting Sort, Heap Sort
- **Data Structures**: Stack, Queue, Linked List, Hash Function
- **Trees**: Binary Tree, AVL Tree, Red-Black Tree
- **Graphs**: Graph visualization with BFS, DFS, Dijkstra's, Prim's, and Kruskal's algorithms

## Tech Stack

- **Frontend**: React 19 + Vite
- **Styling**: Tailwind CSS + PostCSS
- **Routing**: React Router v7
- **Animations**: Framer Motion
- **Linting**: ESLint

## Development

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Setup

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server with HMR
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build locally

## Deployment

This project is configured for deployment on **Vercel**.

### Deploy to Vercel

#### Option 1: Using Vercel CLI
```bash
npm install -g vercel
vercel
```

#### Option 2: Using GitHub Integration
1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will auto-detect the React + Vite configuration
6. Click "Deploy"

### Environment Variables
No environment variables are required for this project.

### Build Configuration
The project uses `vite build` for production builds, which outputs to the `dist` folder. The `vercel.json` configuration handles routing for client-side React Router.

## Project Structure

```
dsa-dashboard/
├── src/
│   ├── components/
│   │   ├── DataStructures/
│   │   ├── Graphs/
│   │   ├── SearchAlgorithms/
│   │   ├── SortingAlgorithms/
│   │   ├── Trees/
│   │   └── home.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── public/
├── vite.config.js
├── vercel.json
├── tailwind.config.cjs
├── postcss.config.cjs
└── package.json
```

## Contributing

To contribute:
1. Create a new branch for your feature
2. Make your changes and ensure linting passes: `npm run lint`
3. Commit with descriptive messages
4. Push and create a pull request
