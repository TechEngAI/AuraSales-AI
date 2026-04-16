🚀 AuraSales AI: Predictive Business Intelligence Console
AuraSales AI is a high-performance Strategic Decision Support System (SDSS) designed to transform static sales data into actionable, forward-looking intelligence. Built for executives and investors, it bridges the gap between raw data and strategic foresight.

https://aurasaleai.netlify.app ---> Demo

💎 The Vision
In an era of market instability, traditional dashboards only offer "hindsight." AuraSales AI provides foresight. By integrating advanced statistical modeling with real-time data visualization, we enable stakeholders to quantify risk and simulate growth before committing capital.

✨ Key Features
📊 1. Volatility Analysis (Risk Quantification)
Unlike standard revenue charts, our Volatility Engine calculates the variance and predictability of income streams.

Metric: Real-time Standard Deviation tracking.

Value: Helps executives identify "revenue noise" vs. "stable growth," allowing for better cash flow management and risk mitigation.

🔮 2. "What-If" Strategic Simulator
A digital twin for your business finances. Our interactive simulation engine allows users to manipulate key variables:

Variable Toggles: Adjust Marketing Spend, Price Points, and Conversion Rates.

Instant Projection: Real-time recalculation of revenue trajectories using linear regression and trend analysis.

🤖 3. AI-Driven Visualizations
High-density, responsive analytics powered by Recharts and Next.js.

Interactive Pie Charts: Deep-dive into product-market fit.

Dynamic Area Graphs: Visualize historical performance against predictive benchmarks.

🔐 4. Enterprise-Grade Security
Identity Management: Secure authentication via Supabase.

Protected Routes: Middleware-level authorization to ensure data privacy across all endpoints.

## 🛠️ The Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | Next.js 14 (App Router), TypeScript, Tailwind CSS |
| **Backend/Auth** | Supabase (PostgreSQL, GoTrue Auth) |
| **Analytics** | Recharts, Math.js (Statistical calculations) |
| **Deployment** | Netlify (CI/CD Pipeline) |
| **Icons/UI** | Lucide React, Radix UI |



🏗️ Architecture & Implementation
Data Flow
AuraSales utilizes a Decoupled Architecture. The frontend consumes real-time data streams from Supabase, processing complex calculations (like Volatility and Projections) on the client side to ensure a low-latency, snappy user experience.

Performance Optimization
Hydration Guards: Prevents layout shifts during heavy SVG rendering.

Dynamic Imports: Optimized bundle sizes for faster mobile loading.

Caching Strategy: Forced cache invalidation on session changes to prevent stale data leaks.


🚀 Getting Started
Prerequisites
Node.js 18+
Supabase Account

Installation
1. Clone the Repository
   git clone https://github.com/your-username/AuraSales-AI-Final.git
   cd AuraSales-AI-Final
2. Install Dependencies
   npm install
3. Environment Variables
   Create a .env.local file and add your credentials:
   NEXT_PUBLIC_API_BASE_URL=http://127.0.0.1:3000
   NEXT_PUBLIC_SUPABASE_URL=
   NEXT_PUBLIC_SUPABASE_ANON_KEY=
   SUPABASE_SERVICE_ROLE_KEY=
   GOOGLE_GENERATIVE_AI_API_KEY=
   HUGGINGFACE_API_KEY=
   RESEND_API_KEY=
   ALPHA_VANTAGE_KEY=
   FMP_API_KEY=
   NEWS_API_KEY=
   CRON_SECRET=
   MARKET_DATA_TICKERS=
   STRIPE_SECRET_KEY=
   NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
   NEXT_PUBLIC_STRIPE_PRICE_PRO_MONTHLY=
   NEXT_PUBLIC_STRIPE_PRICE_PRO_YEARLY=


🛡️ Presentation & Pitch
This project was designed for high-level stakeholders. When presenting, focus on:

The Decision-Maker's Pain: Managing unpredictable revenue.

The AuraSales Solution: Using the What-If Simulator to stress-test strategies.

Scalability: Mention the modular component architecture that allows for new AI model integrations.

👨‍💻 Author
Abdulhammed Muhammed-Awwal Olanrewaju

LinkedIn: 

Developed for by AuraSales Team at Yomi Denzel Foundation— Transforming the future of Sales Intelligence.
