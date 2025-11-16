# NextSkill
# NextSkill - Interactive Learning Platform

A modern, comprehensive e-learning platform offering structured courses in programming languages and spoken languages with interactive lessons, quizzes, and certifications.

## 🌟 Overview

NextSkill is a full-featured educational platform designed to provide high-quality learning experiences across multiple domains. The platform features a clean, intuitive interface with progress tracking, interactive assessments, and official certificates upon course completion.

## ✨ Features

- **📚 Dual Learning Tracks**
  - Technical courses (Programming & Web Development)
  - Language courses (CEFR-aligned language learning)

- **🎓 Complete Learning Experience**
  - Structured modules with video tutorials
  - Interactive lessons with rich content
  - Module quizzes with instant feedback
  - Comprehensive final exams
  - Official certificates upon completion
  - Progress tracking across all courses

- **💡 User-Friendly Interface**
  - Responsive design for all devices
  - Dark/Light mode support
  - Smooth animations and transitions
  - Intuitive navigation system

- **📊 Assessment System**
  - Module-level quizzes (70% passing score)
  - Final comprehensive exams (80% passing score)
  - Practice exams with answer explanations
  - Detailed feedback and scoring

## 🛠️ Technologies & Tools

### Frontend Framework
- **Next.js 16** - React framework with App Router
- **React 19.2** - UI library with latest features
- **TypeScript** - Type-safe development

### Styling & UI
- **Tailwind CSS v4** - Utility-first CSS framework
- **Shadcn/ui** - High-quality React components
- **Radix UI** - Accessible component primitives
- **Lucide React** - Beautiful icon library

### State Management & Data
- **React Hooks** (useState, useEffect, useCallback)
- **Local Storage API** - Progress persistence
- **SWR** - Data fetching and caching

### Additional Features
- **React Markdown** - Lesson content rendering
- **Recharts** - Progress visualization
- **Framer Motion** - Smooth animations
- **date-fns** - Date manipulation

## 📖 Course Offerings

### Programming & Web Development
- **HTML** - Web structure fundamentals (3 modules, 8 lessons)
- **CSS** - Styling and layout techniques (3 modules, 7 lessons)
- **JavaScript** - Programming fundamentals (8 modules, 24 lessons)
- **React** - Modern front-end development (8 modules, 24 lessons)
- **C++** - Object-oriented programming (8 modules, 24 lessons)
- **Java** - Enterprise application development (8 modules, 24 lessons)
- **C#** - .NET development (8 modules, 24 lessons)
- **Python** - Versatile programming (8 modules, 24 lessons)

### Language Learning (CEFR Levels)
- **English** - A2 to C1 proficiency (8 modules per level)
- **French** - A2 to C1 proficiency (8 modules per level)
- **Italian** - A2 to C1 proficiency (8 modules per level)
- **Spanish** - A2 to C1 proficiency (8 modules per level)

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Clone the repository
\`\`\`bash

cd nextskill
\`\`\`

2. Install dependencies
\`\`\`bash
npm install
# or
yarn install
\`\`\`

3. Run the development server
\`\`\`bash
npm run dev
# or
yarn dev
\`\`\`


### Build for Production

\`\`\`bash
npm run build
npm start
\`\`\`

## 📁 Project Structure

\`\`\`
nextskill/
├── app/                          # Next.js App Router pages
│   ├── page.tsx                  # Homepage
│   ├── layout.tsx                # Root layout
│   ├── globals.css               # Global styles
│   ├── courses/                  # Course pages
│   │   ├── languages/            # Language courses
│   │   │   ├── english/          # English course
│   │   │   ├── french/           # French course
│   │   │   ├── italian/          # Italian course
│   │   │   └── spanish/          # Spanish course
│   │   └── technical/            # Technical courses
│   │       ├── html/
│   │       ├── css/
│   │       ├── javascript/
│   │       ├── react/
│   │       ├── cpp/
│   │       ├── java/
│   │       ├── csharp/
│   │       └── python/
│   └── certificates/             # Certificate pages
├── components/                   # React components
│   ├── ui/                       # Shadcn UI components
│   ├── navigation.tsx            # Main navigation
│   ├── footer.tsx                # Footer component
│   ├── hero-section.tsx          # Hero section
│   ├── courses-grid.tsx          # Course cards grid
│   ├── lesson-content.tsx        # Lesson viewer
│   ├── module-quiz.tsx           # Quiz component
│   ├── final-exam.tsx            # Exam component
│   ├── certificate.tsx           # Certificate generator
│   └── course-platform components # Individual course platforms
├── lib/                          # Utility functions & data
│   ├── utils.ts                  # Helper functions
│   └── course-data files         # Course content data
└── public/                       # Static assets
\`\`\`

## 🎯 Key Features Implementation

### Progress Tracking
- Automatic progress saving to localStorage
- Module completion tracking
- Quiz and exam scores persistence
- Certificate generation based on completion

### Course Platform
- Modular lesson navigation
- Video integration
- Interactive quizzes with explanations
- 50-question final exams
- Certificate download functionality

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimizations
- Touch-friendly interfaces
- Accessible navigation

## 🧪 Course Content Structure

Each course follows a consistent structure:

\`\`\`typescript
{
  modules: [
    {
      title: string
      videoUrl: string
      videoDescription: string
      lessons: Lesson[]
      quiz: Question[]
    }
  ]
  finalExam: Question[] // 50 questions
}
\`\`\`

## 🎨 Design System

- **Color Palette**: Semantic tokens for consistent theming
- **Typography**: Geist Sans and Geist Mono fonts
- **Components**: Reusable shadcn/ui components
- **Icons**: Lucide React icon library
- **Animations**: Framer Motion for smooth transitions

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - React framework
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Shadcn/ui](https://ui.shadcn.com/) - Component library
- [Vercel](https://vercel.com/) - Deployment platform
- [Lucide](https://lucide.dev/) - Icon library

## 📧 Contact

For questions or suggestions, please open an issue or contact the maintainers.

---

**Made with ❤️ using Next.js and React**
