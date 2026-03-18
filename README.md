# AlgoVisualizer - Interactive Algorithm Learning Platform
A comprehensive web application for visualizing and understanding classic algorithms and data structures through interactive animations.



# 🌟 Features
# 🔄 Sorting Algorithms
Bubble Sort: Watch elements bubble up to their correct positions

Merge Sort: See the divide-and-conquer approach in action

Interactive controls for speed, array size, and step-by-step execution

Color-coded visualization showing comparisons, swaps, and sorted elements
# 🗺️ Pathfinding Algorithms
Breadth-First Search (BFS): Explore level by level

Dijkstra’s Algorithm: Find the shortest path with weighted edges

Interactive grid where you can draw walls and obstacles

Real-time animation showing visited nodes and final path
# 🕸️ Graph Algorithms
Depth-First Search (DFS): Explore as deep as possible before backtracking

Breadth-First Search (BFS): Visit all neighbors before going deeper

Visual graph representation with animated node and edge highlighting

Step-by-step traversal visualization
# 🎨 User Experience
Dark Mode Support: Toggle between light and dark themes

Responsive Design: Works seamlessly on desktop and mobile

Interactive Controls: Play, pause, reset, and adjust speed

Algorithm Information: Learn about time/space complexity

Visual Legend: Understand what each color represents
# 🚀 Quick Start
# Prerequisites
Node.js 18+
pnpm (recommended) or npm
# Installation
# Clone the repository
<pre>
git clone <repository-url>
cd algovisualizer
</pre>
# Install dependencies
<pre>
pnpm install
</pre>

# Start development server
<pre>
pnpm run dev
</pre>

Open your browser Navigate to http://localhost:5173

# Build for Production
<pre>
pnpm run build
</pre>
# 🏗️ Project Structure
<pre>
src/
├── components/
│   ├── ui/                 # Shadcn/ui components
│   ├── sorting/           # Sorting-specific components
│   └── Navigation.tsx     # Main navigation
├── pages/
│   ├── Index.tsx          # Landing page
│   ├── SortingVisualizer.tsx
│   ├── PathfindingVisualizer.tsx
│   └── GraphVisualizer.tsx
├── algorithms/
│   ├── sorting.ts         # Sorting implementations
│   ├── pathfinding.ts     # Pathfinding implementations
│   └── graph.ts           # Graph algorithms
├── hooks/
│   ├── useAnimation.ts    # Animation control logic
│   └── useDarkMode.ts     # Dark mode functionality
├── types/
│   └── algorithms.ts      # TypeScript interfaces
└── utils/
    └── constants.ts       # App constants and colors
</pre>
  # 🎯 Available Algorithms
# Sorting Algorithms
<table>
<thead>
<tr>
<th>Algorithm</th>
<th>Time Complexity</th>
<th>Space Complexity</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>O(n²)</td>
<td>O(1)</td>
<td>Simple comparison-based sorting</td>
</tr>
<tr>
<td>Merge Sort</td>
<td>O(n log n)</td>
<td>O(n)</td>
<td>Divide-and-conquer approach</td>
</tr>
</tbody>
</table>

# Pathfinding Algorithms
<table>
<thead>
<tr>
<th>Algorithm</th>
<th>Time Complexity</th>
<th>Space Complexity</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>BFS</td>
<td>O(V + E)</td>
<td>O(V)</td>
<td>Guarantees shortest path (unweighted)</td>
</tr>
<tr>
<td>Dijkstra’s</td>
<td>O((V + E) log V)</td>
<td>O(V)</td>
<td>Shortest path with weights</td>
</tr>
</tbody>
</table>

# Graph Algorithms
<table>
<thead>
<tr>
<th>Algorithm</th>
<th>Time Complexity</th>
<th>Space Complexity</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>DFS</td>
<td>O(V + E)</td>
<td>O(V)</td>
<td>Deep exploration using stack/recursion</td>
</tr>
<tr>
<td>BFS</td>
<td>O((V + E)</td>
<td>O(V)</td>
<td>Level-by-level exploration using queue</td>
</tr>
</tbody>
</table>


# 🎮 How to Use
# Sorting Visualizer
Select an algorithm from the dropdown

Adjust array size and animation speed

Click “Shuffle” to generate a new random array

Press “Play” to start the visualization

Use “Pause” and “Reset” to control playback
# Pathfinding Visualizer
Choose between BFS and Dijkstra’s algorithm

Click and drag on the grid to draw walls

Green node is start, red node is end

Click “Start Pathfinding” to begin visualization

Watch as the algorithm explores and finds the shortest path
# Graph Visualizer
Select DFS or BFS algorithm

Click “Start Traversal” to begin

Watch nodes light up as they’re visited

See the order of traversal in real-time
# 🛠️ Technology Stack
Frontend Framework: React 18 with TypeScript

Styling: Tailwind CSS + Shadcn/ui components

Build Tool: Vite

State Management: React hooks (useState, useEffect, useCallback)

Animations: CSS transitions and JavaScript timers

Routing: React Router DOM
# 🎨 Design Principles
Educational Focus: Clear, step-by-step visualizations

Interactive Learning: Hands-on exploration with controls

Modern UI: Clean, accessible interface with dark mode

Performance: Optimized animations and efficient algorithms

Responsive: Works on all device sizes
# 🚀 Deployment
# Vercel (Recommended)
Push your code to GitHub

Connect your repository to Vercel

Deploy automatically with zero configuration
# Netlify
Build the project: pnpm run build

Upload the dist folder to Netlify

Configure redirects for SPA routing
# Manual Deployment
<pre>
pnpm run build
</pre>
# Upload contents of 'dist' folder to your web server
# 🤝 Contributing
Fork the repository

Create a feature branch: git checkout -b feature/amazing-feature

Commit your changes: git commit -m 'Add amazing feature'

Push to the branch: git push origin feature/amazing-feature

Open a Pull Request
# 📝 Future Enhancements
<pre>
[ ] More sorting algorithms (Quick Sort, Heap Sort)
[ ] Advanced pathfinding (A*, Greedy Best-First)
[ ] Minimum Spanning Tree algorithms (Kruskal’s, Prim’s)
[ ] Recursion tree visualization
[ ] Dynamic programming table animations
[ ] Custom algorithm editor
[ ] User authentication and progress saving
[ ] Algorithm comparison mode
</pre>

# 🙏 Acknowledgments
Inspired by algorithm visualization tools like VisuAlgo

Built with amazing open-source libraries

Special thanks to the React and Tailwind CSS communities
<div align="center">
# Made by ❤️ Lakshya Sachin Bhardwaj

⭐ Star this repository if you found it helpful!
</div>
