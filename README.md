# FixMyCode-AI

/FixMyCode-AI/
├── /FixMyCode-AI-dashboard/
│   ├── /app/
│   │   ├── /api/
│   │   │   └── razorpay.ts    # Payment API (Razorpay integration)
│   │   ├── /dashboard/
│   │   │   └── page.tsx       # Main dashboard page
│   │   ├── /auth/
│   │   │   └── login.tsx      # Login page/component
│   │   ├── layout.tsx         # Root layout for dashboard
│   │   └── globals.css        # Global styles (Tailwind CSS)
│   ├── /components/
│   │   ├── Navbar.tsx         # Navigation bar
│   │   ├── ReportCard.tsx     # Usage report/stats card
│   │   └── Sidebar.tsx        # Sidebar for navigation
│   ├── /lib/
│   │   ├── auth.ts            # JWT or session auth utilities
│   │   └── api.ts             # API fetch helpers
│   ├── /public/               # Static assets
│   │   ├── /images/
│   │   └── favicon.ico
│   ├── package.json           # Dependencies (Next.js, React, etc.)
│   ├── tailwind.config.js     # Tailwind CSS config
│   ├── tsconfig.json          # TypeScript config
│   └── README.md              # Dashboard setup guide
│
├── /FixMyCode-AI-backend/
│   ├── /app/
│   │   ├── __init__.py        # Flask/FastAPI app setup
│   │   ├── routes.py          # API endpoints (e.g., code fixing, payments)
│   │   ├── models.py          # Database models (e.g., users, code snippets)
│   │   ├── ai_service.py      # AI code fixing logic
│   │   └── utils.py           # Helper functions
│   ├── /tests/
│   │   ├── test_routes.py     # API route tests
│   │   └── test_ai_service.py # AI service tests
│   ├── config.py              # Config (DB, API keys, etc.)
│   ├── requirements.txt       # Python dependencies
│   ├── .env                   # Environment variables (not in Git)
│   ├── run.py                 # Entry point to start backend
│   └── README.md              # Backend setup instructions
│
├── /FixMyCode-AI-extension/
│   ├── /src/
│   │   ├── extension.ts       # Main extension logic (VS Code integration)
│   │   ├── api.ts             # Backend API calls
│   │   ├── auth.ts            # License key or user auth handling
│   │   └── utils.ts           # Helper utilities
│   ├── /assets/
│   │   ├── icon.png           # Extension icon
│   │   └── manifest.json      # Extension manifest (if needed)
│   ├── package.json           # Extension metadata and dependencies
│   ├── tsconfig.json          # TypeScript config
│   ├── webpack.config.js      # Build config (optional)
│   └── README.md              # Extension setup and usage
│
├── .gitignore                 # Root-level Git ignore (node_modules, __pycache__, etc.)
└── README.md                  # Project overview
