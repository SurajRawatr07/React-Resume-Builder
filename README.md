Resume Builder — Professional ATS-Optimized Resume Creator

A modern, high-performance Resume Builder Web Application designed to help users create ATS-friendly, industry-standard resumes with speed, precision, and professional formatting.

This platform delivers a seamless experience for building, customizing, and exporting resumes using real-time preview, reusable templates, and persistent state management.

✨ Features
🔐 Authentication System
Login & Signup Pages with modern UI design
Forgot Password UI Flow (ready for backend integration)
Protected Routes for secure access
LocalStorage-based Authentication for session persistence
Auto Logout System for security handling
📝 Resume Builder
6 Professional ATS-Optimized Templates
Modern Professional (Corporate / IT)
Minimal Clean (Academic / Government)
Creative Designer (Marketing / Design)
Executive Premium (Senior Management)
Tech Developer (Software Engineering)
Student / Fresher (Entry Level)
Real-Time Live Preview with instant updates
Dynamic Template Switching without data loss
Auto-Save Feature using LocalStorage
One-click PDF Export via browser print engine
🎨 Modern UI/UX
Glassmorphism-based UI design system
Smooth animations & micro-interactions
Gradient-based modern theme
Fully responsive (mobile, tablet, desktop)
Clean typography with professional spacing
Premium UI component integration
🚀 Tech Stack
React 18 — Component-based frontend architecture
TypeScript — Type-safe development
Vite — Fast build and development tool
Tailwind CSS — Utility-first styling framework
Zustand — Lightweight state management
shadcn/ui — Prebuilt modern UI components
Lucide Icons — Modern icon library
📁 Project Structure
src/
├── components/
│   ├── ui/                 # UI components (shadcn)
│   ├── features/
│   │   ├── forms/          # Resume form sections
│   │   ├── ResumeForm.tsx
│   │   ├── ResumePreview.tsx
│   │   ├── TemplateGallery.tsx
│   │   ├── TemplateSelector.tsx
│
│   ├── templates/
│       ├── ModernTemplate.tsx
│       ├── MinimalTemplate.tsx
│       ├── CreativeTemplate.tsx
│       ├── ExecutiveTemplate.tsx
│       ├── TechTemplate.tsx
│       ├── StudentTemplate.tsx
│
├── hooks/
│   └── useAuth.tsx         # Authentication logic
├── lib/
│   └── utils.ts            # Utility helpers
├── pages/
│   ├── LandingPage.tsx
│   ├── LoginPage.tsx
│   ├── SignupPage.tsx
│   ├── ForgotPasswordPage.tsx
│   ├── EditorPage.tsx
│
├── stores/
│   └── resumeStore.ts      # Global state management
├── types/
│   └── resume.ts           # TypeScript types
├── App.tsx
├── main.tsx
└── index.css
🛠️ Installation & Setup
1. Install Dependencies
npm install
2. Start Development Server
npm run dev

App runs at:
👉 http://localhost:5173

3. Production Build
npm run build
🌐 Deployment
Netlify / Vercel
Build command: npm run build
Output folder: dist
📖 Usage Guide
1. Authentication
Create account using Signup
Login with credentials
Access protected dashboard
2. Build Resume
Fill personal details
Add experience, education, skills
Add projects & certifications
3. Templates
Choose from 6 professional designs
Switch anytime without losing data
Live preview updates instantly
4. Export Resume
Click Export PDF
Save via browser print option
Ready for job applications
🎨 Customization
Change Theme Colors

Edit:

tailwind.config.ts
Add New Sections
Update types/resume.ts
Modify resumeStore.ts
Create form component
Add to templates
🐛 Troubleshooting
Issue: Layout not updating
Clear LocalStorage
Hard refresh browser
Issue: Login not working
Check browser console
Clear auth storage
Issue: PDF not correct
Use Chrome / Edge
Set print to A4 format
📌 License

This project is licensed under the MIT License.

🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.

❤️ Built With

React • TypeScript • Vite • Tailwind CSS • Zustand • shadcn/ui

⭐ Final Note

This project demonstrates production-level frontend engineering, scalable architecture, and professional UI/UX design suitable for real-world deployment.