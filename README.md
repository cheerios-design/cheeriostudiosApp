Cheerio Studios Website

Where Digital Dreams Take Flight 🚀

A cutting-edge website for Cheerio Studios, built with Next.js 14, TypeScript, Framer Motion, and Tailwind CSS. This project showcases modern web development techniques including scroll-based animations, parallax effects, and glassmorphism.
🎯 Project Overview
Cheerio Studios is a boutique digital agency specializing in:

Web Design & Development
Brand Identity Creation
Digital Marketing
Strategic Consulting

🛠️ Tech Stack

Framework: Next.js 14 (App Router)
Language: TypeScript
Styling: Tailwind CSS + CSS Modules
Animations: Framer Motion + GSAP
Smooth Scrolling: Lenis
Font: Inter (Google Fonts)
Deployment: Vercel

🚀 Getting Started
Prerequisites

Node.js 18+
npm or yarn
Git

Installation

Clone the repository:

bashgit clone https://github.com/cheerios-design/cheeriostudiosApp.git
cd cheeriostudiosApp

Checkout development branch:

bashgit checkout development

Install dependencies:

bashnpm install

Run the development server:

bashnpm run dev

Open http://localhost:3000 in your browser.

📁 Project Structure
cheeriostudiosApp/
├── app/ # Next.js 14 app directory
│ ├── layout.tsx # Root layout with metadata
│ ├── page.tsx # Homepage
│ └── globals.css # Global styles
├── components/
│ ├── layout/ # Layout components
│ │ ├── Navigation.tsx # Sticky navigation
│ │ ├── Footer.tsx # Site footer
│ │ └── SmoothScroll.tsx # Lenis wrapper
│ ├── sections/ # Page sections
│ │ ├── Hero.tsx # Hero section
│ │ ├── Services.tsx # Services showcase
│ │ ├── Projects.tsx # Portfolio section
│ │ └── Contact.tsx # Contact form
│ ├── ui/ # Reusable UI components
│ │ ├── Button.tsx # Button variants
│ │ ├── Card.tsx # Card component
│ │ └── Typography.tsx # Text components
│ └── animations/ # Animation components
│ ├── ScrollAnimation.tsx # Scroll triggers
│ ├── ParallaxSection.tsx # Parallax effects
│ └── TextReveal.tsx # Text animations
├── hooks/ # Custom React hooks
├── utils/ # Utility functions
├── types/ # TypeScript types
└── public/ # Static assets
🎨 Design System
Colors

Primary: #FF6B6B (Coral)
Secondary: #4ECDC4 (Turquoise)
Accent: #FFE66D (Yellow)
Dark: #000000 - #2a2a2a

Typography

Display Font: Inter (Bold)
Body Font: Inter (Regular)
Hero Size: clamp(3rem, 10vw, 8rem)
Section Size: clamp(2rem, 6vw, 4rem)

Animations

Scroll-triggered fade-ins
Parallax sections
Text reveal effects
Smooth page transitions
Micro-interactions on hover

🔧 Available Scripts
bash# Development
npm run dev # Start development server
npm run build # Build for production
npm run start # Start production server

# Code Quality

npm run lint # Run ESLint
npm run type-check # TypeScript type checking
npm run format # Format with Prettier

# Git Workflow

git checkout development # Switch to development branch
git checkout backend # Switch to backend branch
git checkout main # Switch to main branch
🌿 Git Branch Strategy

main: Production-ready code
development: Active development branch
backend: Backend API development
Feature branches: feature/branch-name
Bugfix branches: bugfix/issue-name

📋 Development Workflow

Always work on the development branch for new features
Create feature branches from development
Make small, focused commits
Write descriptive commit messages
Create pull requests for code review
Merge to main only after thorough testing

🎯 Performance Optimization

Lazy Loading: Components load on-demand
Image Optimization: Next.js Image component
Code Splitting: Automatic with Next.js
Font Optimization: Next/font for web fonts
Animation Performance: GPU-accelerated transforms
Bundle Size: Tree-shaking and minification

🔍 SEO Features

Server-side rendering (SSR)
Dynamic meta tags
Open Graph integration
Twitter Cards
Sitemap generation
Robots.txt configuration
Schema markup

♿ Accessibility

Semantic HTML structure
ARIA labels and roles
Keyboard navigation
Focus indicators
Screen reader friendly
WCAG AA compliant colors
Respects prefers-reduced-motion

📱 Responsive Design

Mobile-first approach
Breakpoints:

sm: 640px
md: 768px
lg: 1024px
xl: 1280px
2xl: 1536px

🚀 Deployment
The site is configured for deployment on Vercel:

Push changes to main branch
Vercel automatically builds and deploys
Preview deployments for pull requests

Environment Variables
Create a .env.local file:
env# Analytics (optional)
NEXT_PUBLIC_GA_ID=your-google-analytics-id
NEXT_PUBLIC_PLAUSIBLE_DOMAIN=your-domain

# Contact Form (if using external service)

NEXT_PUBLIC_FORM_ENDPOINT=your-form-endpoint

# Other APIs

NEXT_PUBLIC_API_URL=your-api-url
👩‍💻 VS Code Extensions
Recommended extensions are listed in .vscode/extensions.json. Install them for the best development experience:

ES7+ React snippets
Tailwind CSS IntelliSense
Prettier
ESLint
GitLens
And more...

🤝 Contributing

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📝 Code Style

Use TypeScript for type safety
Follow ESLint rules
Format with Prettier
Write meaningful component names
Comment complex logic
Keep components small and focused

🐛 Known Issues

None at the moment

📞 Contact
Sam Daramroei - Founder, Cheerio Studios

Website: cheeriostudios.com
Email: sam.d@cheeriostudios.com

📄 License
This project is proprietary and confidential. All rights reserved by Cheerio Studios.

Built with ❤️ by Cheerio Studios
