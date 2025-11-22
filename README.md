🌐 InternMatch – Smart Internship Matching Platform

InternMatch is a modern, responsive, full-stack web application built with Next.js + TypeScript, designed to help students discover internships and allow companies to post opportunities in a structured, efficient, and user-friendly way.
Developed as part of Smart India Hackathon (SIH), it focuses on clean UI, fast navigation, and a scalable architecture.



<div align="center">
🚀 Live Demo : https://internmatch-variablex.vercel.app/



</div>


🧭 Overview

InternMatch solves a common problem:
➡️ Students struggle to find internships that match their skills.
➡️ Companies struggle to filter relevant candidates.

This platform bridges that gap with smart filtering, intuitive UI, and easy job posting abilities.

Whether you're a student exploring opportunities or a company searching for talent — InternMatch gives you a streamlined experience.

✨ Key Features
👩‍🎓 For Students

Browse internships across domains

Smart filtering based on skills, location, stipend, etc.

Fast & responsive UI

Bookmark/save opportunities (future enhancement)

Simple authentication flow (optional integration)

🏢 For Companies

Post an internship in minutes

Manage internship listings

Structured data collection (title, skills, stipend, location)

Email notifications (if configured)

🔧 General Platform Features

Fully responsive (mobile → desktop)

Component-driven architecture (Next.js App Router)

Smooth routing and minimal load times

Clean navbar with subtabs

Footer with contact, copyright, and quick links

File/data import support (ZIP file for institute data)

Ready for full-stack expansion





🛠️ Tech Stack
Category	Technology Used
Frontend	Next.js 14, React 18, TypeScript
Styling	CSS Modules / Tailwind (update if you used Tailwind)
Backend	Next.js API Routes
Email Support	Nodemailer / Resend / API (your choice)
Deployment	Vercel
Version Control	Git + GitHub





📁 Project Folder Structure

Internmatch/

│

├── app/                     # Next.js App Router pages & routes

├── components/              # Reusable UI components

├── hooks/                   # Custom React hooks

├── lib/                     # Helper functions, utilities

├── public/                  # Static assets (images, icons, etc.)

├── styles/                  # Global + component-specific styling
│
├── .gitignore

├── next.config.mjs

├── package.json

├── pnpm-lock.yaml

├── tsconfig.json

└── README.md






🚀 Getting Started
✔️ Prerequisites

Make sure you have the following installed:

Node.js (v16+ recommended)

pnpm, npm, or yarn

Git





🔧 Installation

1. Clone the Repository
git clone https://github.com/Devansh-Sahu/Internmatch.git

2. Navigate to the project
cd Internmatch

3. Install dependencies
pnpm install


(Or use npm install or yarn install depending on your preference)

▶️ Run Locally

Start the dev server:

pnpm dev


Now open:

👉 http://localhost:3000

Your app should now be running locally.

🏗️ Build for Production
pnpm build
pnpm start


This builds and starts the production server.





☁️ Deployment (Vercel)

InternMatch is optimized for deployment on Vercel.

Deploy Steps:

Go to https://vercel.com

Create a new project

Import your GitHub repository

Select the repo: Internmatch

Set environment variables (if using email backend)

Click Deploy

Vercel will auto-build and host your app.
Every git push triggers an automatic redeployment.






🤝 Contributing

Contributions are welcome!

Steps:

Fork the repository

Create a feature branch

git checkout -b feature/awesome-feature


Commit changes

Push the branch

Create a Pull Request
