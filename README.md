
# 🧠 DebateMate – AI-Powered Debate Coach & Analyzer

![License](https://img.shields.io/github/license/Ankit27-09/DebateMate?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js-15-blue?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-✔️-3178c6?style=flat-square)
![Tailwind](https://img.shields.io/badge/TailwindCSS-✔️-38B2AC?style=flat-square)

DebateMate is an open-source platform offering personalized, AI-powered debate training and analysis. Users can engage in one-on-one practice debates, receive real-time AI feedback, and follow a tailored learning roadmap to improve their speaking and critical thinking skills.

---

## ✨ Features

- 🔐 **Secure Authentication** via Clerk and Next.js Middleware
- 🧑‍🏫 **AI Debate Feedback** powered by Gemini AI
- 🎯 **Learning Path Recommendations** customized for each user
- 📊 **Visual Analytics** for performance tracking
- 📹 **Debate Recording & Transcript Analysis**
- 💬 **ChatBot Interface** for practice & guidance
- 🌗 **Dark/Light Mode Toggle**
- 🧩 Modular & Extensible Codebase (Shadcn, Tailwind, Next.js)

---

## 📂 Project Structure

```bash
DebateMate/
├── .env.example           # API keys & environment config
├── public/                # Static files
├── src/
│   ├── app/               # Next.js app routes
│   ├── components/        # UI + reusable components
│   ├── hooks/             # Custom React hooks
│   ├── lib/               # Utility functions
│   ├── store/             # Zustand state store
│   └── middleware.ts      # Clerk authentication middleware
├── .github/               # Issue & PR templates
├── README.md              # You're here!
├── LICENSE                # MIT License
├── package.json           # Project dependencies & scripts
├── tailwind.config.js     # Tailwind theme config
├── next.config.ts         # Next.js settings
├── tsconfig.json          # TypeScript compiler options
└── postcss.config.mjs     # PostCSS config
```

---

## 🚀 Getting Started

### 📦 Prerequisites

- Node.js **v18+**
- npm or yarn
- Clerk account (for authentication)
- Gemini/OpenAI API Key

### 🛠️ Installation

1. **Clone the repo**
```bash
git clone https://github.com/Ankit27-09/DebateMate.git
cd DebateMate
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
```bash
cp .env.example .env
```
Then fill in your Clerk and Gemini API keys.

4. **Start the dev server**
```bash
npm run dev
```

Open [`http://localhost:3000`](http://localhost:3000) in your browser.

---

## 🧑‍💻 Contributing

We love contributions from the community!

- 📜 Please read [CONTRIBUTING.md](./CONTRIBUTING.md)
- 🧾 Follow our [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
- Check out `good first issue` or `help wanted` labels on issues

### ✅ Pull Request Checklist

- [ ] Lint and test your code
- [ ] Include clear and descriptive commit messages
- [ ] Add tests or update existing ones (if applicable)
- [ ] Add relevant docs or update README if necessary

---

## 📊 Tech Stack

| Layer          | Technology                      |
|----------------|----------------------------------|
| Frontend       | Next.js 15, TypeScript           |
| Styling        | Tailwind CSS, PostCSS, Shadcn UI |
| Auth           | Clerk + Next.js Middleware       |
| AI Integration | Gemini AI, OpenAI                |
| Charts         | Chart.js, Recharts               |
| Animations     | Framer Motion                    |
| State Mgmt     | Zustand                          |

---

## 📌 Notable Directories

- `src/app/`: Public and Private routing
- `src/components/`: Modular UI components
- `src/hooks/`: Utility hooks like `useToast`, `useMobile`
- `src/store/`: Zustand-based global state
- `src/app/api/`: API endpoints for debate analysis, suggestions, etc.

---

## 🌍 Vision & Roadmap

> *"To democratize debate training and improve public speaking skills through accessible AI feedback."*

### Coming Soon 🚧

- 🎭 Emotion-Aware AI Rebuttals
- 🏆 Leaderboards & Achievements
- 🌐 Multilingual Debate Support
- 👨‍🏫 Educator Dashboard
- 📈 Weekly Progress Reports

---

## 🧪 Testing

> (To be added)

---

## 📄 License

This project is licensed under the **MIT License**.  
See [LICENSE](./LICENSE) for more details.

---

## 🙋 Support

- [Open an Issue](https://github.com/Ankit27-09/DebateMate/issues)
- [Start a Discussion](https://github.com/Ankit27-09/DebateMate/discussions)

---

## 🌟 Star us on GitHub if you like the project!

> Made with 💡 by [Ankit Singh](https://github.com/Ankit27-09)
