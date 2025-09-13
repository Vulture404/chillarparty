# 🌟 Aura Budget - Gamified Budget Tracker for Students

A modern, gamified budget tracking application designed specifically for college students at Manipal University. Track expenses, manage budgets, earn Aura Points, and compete with friends while developing healthy financial habits.

## ✨ Features

### 💰 Budget Management
- **Weekly & Monthly Budgets**: Set and track spending limits with visual progress bars
- **Overspending Alerts**: Red indicators when budgets are exceeded
- **Category-based Tracking**: Organize expenses by Food, Transport, Entertainment, etc.

### 🎮 Gamification System
- **Aura Points**: Earn points for staying within budget and completing challenges
- **Progressive Streak Bonuses**: 
  - 5 weeks → +20% bonus points
  - 10 weeks → +30% bonus points  
  - 15 weeks → +40% bonus points
  - 20+ weeks → +50% bonus points
- **Ranking System**: Progress through fun titles from Loose Chillar to AURA+
- **Daily Challenges**: Complete tasks to earn extra points
- **Leaderboard**: Compete with other students

### 📊 Expense Tracking
- **Easy Expense Entry**: Quick form to log spending
- **Edit & Delete**: Full CRUD operations for expense management
- **Visual Analytics**: Charts and progress tracking
- **Expense History**: Complete transaction log with categories

### 🎯 Student-Focused Features
- **Saving Tips**: Curated advice for college students
- **Simple Authentication**: Name-based login system
- **Mobile-First Design**: Optimized for smartphone usage
- **Dark/Light Theme**: Comfortable viewing in any environment

## 🏆 Ranking System

| Rank | Title | Points Range | Badge |
|------|-------|--------------|-------|
| 1 | Loose Chillar | 0 - 50 | 🪙 |
| 2 | Aura Pakoda | 51 - 150 | ⚡ |
| 3 | Aura Farmer | 151 - 300 | 🌱 |
| 4 | Aura Mafia | 301 - 500 | 💎 |
| 5 | Aura Legend | 501 - 800 | 🌟 |
| 6 | AURA+ | 801+ (Top 3) | 👑 |

## 🛠️ Tech Stack

### Core Framework
- **Next.js 14.2.25** - React framework with App Router
- **React 19** - UI library with latest features
- **TypeScript 5** - Type-safe development

### UI & Design
- **Tailwind CSS 4.1.9** - Utility-first styling
- **Radix UI** - Accessible component primitives
- **Lucide React** - Beautiful icon library
- **Geist Font** - Modern typography
- **next-themes** - Dark/light mode support

### Form & Validation
- **React Hook Form** - Performant form handling
- **Zod** - Schema validation
- **@hookform/resolvers** - Form validation integration

### Data Visualization
- **Recharts** - Interactive charts and graphs

### Additional Libraries
- **date-fns** - Date manipulation
- **Sonner** - Toast notifications
- **class-variance-authority** - Component variants
- **tailwind-merge** - Conditional styling

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
   \`\`\`bash
   git clone <repository-url>
   cd aura-budget
   \`\`\`

2. **Install dependencies**
   \`\`\`bash
   npm install
   # or
   yarn install
   \`\`\`

3. **Run the development server**
   \`\`\`bash
   npm run dev
   # or
   yarn dev
   \`\`\`

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

\`\`\`bash
npm run build
npm start
\`\`\`

## 📱 Usage

1. **Sign In**: Enter your name to access the app
2. **Set Budgets**: Configure weekly and monthly spending limits
3. **Track Expenses**: Log your spending with categories
4. **Earn Points**: Stay within budget and complete challenges
5. **Compete**: Check the leaderboard and climb the ranks
6. **Learn**: Read saving tips tailored for students

## 🎨 Design Philosophy

- **Student-Centric**: Designed specifically for college students' needs
- **Gamification**: Makes budgeting fun and engaging
- **Accessibility**: WCAG compliant with proper contrast ratios
- **Mobile-First**: Optimized for smartphone usage
- **Performance**: Fast loading with optimized components

## 📂 Project Structure

\`\`\`
aura-budget/
├── app/                    # Next.js App Router
│   ├── layout.tsx         # Root layout with fonts
│   ├── page.tsx           # Main application entry
│   └── globals.css        # Global styles and design tokens
├── components/            # React components
│   ├── ui/               # Reusable UI components
│   ├── dashboard.tsx     # Main dashboard
│   ├── budget-cards.tsx  # Budget display
│   ├── expense-form.tsx  # Expense entry
│   ├── expense-list.tsx  # Expense management
│   ├── aura-points.tsx   # Points and streaks
│   ├── leaderboard.tsx   # Rankings display
│   └── saving-tips.tsx   # Student tips
├── lib/                  # Utility functions
│   ├── auth.ts          # Authentication logic
│   ├── gamification.ts  # Points and ranking system
│   └── utils.ts         # Helper functions
└── README.md            # Project documentation
\`\`\`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🎓 Built for Manipal University Students

Aura Budget was specifically designed to help Manipal University students develop better financial habits through gamification and peer competition. The app understands the unique challenges of student life and provides tools to make budgeting engaging and social.

---

**Start your financial journey today and become an Aura Legend! 🌟**
