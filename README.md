# ⚡ Real-Time Order Book Visualizer (Next.js 15 - Canary)

A responsive, real-time order book and trade visualizer built with **Next.js 15 (App Router)**, **TypeScript**, **Tailwind CSS**, and **Zustand**.  
It streams live market data from the **Binance WebSocket API**, showing continuously updating bids, asks, and recent trades.

---

## 🚀 Live Demo

🔗 **[https://orderbook.vercel.app](https://orderbook.vercel.app)**

---

## 🧩 Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/anmolgupta1021/orderbook.git
cd orderbook
```
### 2. Install Dependencies
```bash
npm install
```
### 3. Run the Development server
```bash
npm run dev
```
Then open your browser and visit 👉 http://localhost:3000

## 🧠 Design Choices & Trade-offs

>Next.js 15 (Canary)
Leveraged for its latest App Router features, React Server Components, and seamless Vercel deployment.

>Zustand for State Management
Selected for its minimal API, simplicity, and better performance over Redux for high-frequency WebSocket updates.

>WebSockets (Binance Combined Streams)
Streams aggTrade and depth data directly for real-time price and order book depth updates.
(For production-level consistency, one could add REST snapshot + diff sequence reconciliation per Binance docs.)

>Tailwind CSS
Provides rapid and consistent styling with minimal CSS boilerplate.

>TypeScript
Ensures type safety and more maintainable, error-free code.

## 🧰 Tech Stack
Category	-> Technology
Framework	-> Next.js 15 (Canary)
Language	-> TypeScript
Styling	-> Tailwind CSS
State Management ->	Zustand
Data Source	-> Binance WebSocket API
Deployment ->	Vercel

## ⚙️ Deployment (Vercel)

Deploy easily with Vercel in under 2 minutes:

1 Push your latest code to GitHub.

2 Go to https://vercel.com
 → “Add New Project”.

3 Select your orderbook repository.

4 Keep default build settings:
```bash
Framework Preset: Next.js
Install Command: npm install
Build Command: next build
Output Directory: .next
```
5. Click deploy
6. Your project will be live at
```bash
https://orderbook.vercel.app
```

## 🧑‍💻 Author
Anmol Gupta
📧 anmolgupta1021@gmail.com
🔗 https://github.com/anmolgupta1021
