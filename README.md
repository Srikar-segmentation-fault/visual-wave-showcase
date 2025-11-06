#VisualWave - AI-Powered 3D Algorithm Visualizer

#🚀 LIVE DEMO 🚀 [visit: https://retina-book.vercel.app]

###(Note: The AI model may take a few moments to generate the 3D visualization)

**What is VisualWave?**

VisualWave is a full-stack web application that transforms LeetCode-style DSA problems into dynamic, step-by-step 3D animations. Instead of reading static explanations, users can see algorithms in motion, with each step visualized and explained by an AI.

This project was built to explore the power of generative AI in creating on-the-fly educational content.

Features

* AI-Powered Generation : Enter a LeetCode problem ID or Title, and an AI (powered by Groq and Mixtral) generates a unique 3D animation from scratch.

* Step-by-Step Animation : Don't just see the final result. A "Start" button initiates a guided animation that highlights comparisons, swaps, and data changes.

* Live Explanations : An info box on-screen explains each step of the algorithm as it happens.

* Full 3D Interaction : Pan, zoom, and rotate the 3D scene using your mouse to inspect the visualization from any angle.

* Instant Search : The entire LeetCode problem database is searchable instantly from the frontend.

###Tech Stack & Architecture

This is a full-stack monorepo application with a clear separation of concerns:

**Frontend (Hosted on Vercel)**

* Framework : React.js (Vite)

* 3D Graphics : Three.js

* API Client : Axios

* Styling : CSS (Inlined)

**Backend (Hosted on Render)**

* Framework : FastAPI (Python)

* AI Model : Groq (using mixtral-8x7b-32768)

* Data : Local JSON database (merged_problems.json)

A Note on Source Code

The complete source code for this project is hosted in a private repository. This public showcase is meant to demonstrate the live application and its architecture.

