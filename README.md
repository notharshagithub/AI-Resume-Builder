# 🧠 Resume AI – AI-Powered Resume Builder

Resume AI is a smart and modern web application that leverages AI to help users create personalized, professional resumes tailored to specific job descriptions. Built using React + Vite, it features a beautiful UI, form validation, PDF generation, and seamless AI integration using Google’s Gemini API.

## 🚀 Live Demo

🔗 [View Live App](https://your-live-deployment-link.vercel.app)

---

## 📸 Screenshots

| Landing Page | Resume Builder | AI Generation | PDF Output |
|--------------|----------------|----------------|------------|
| ![Landing](./screenshots/landing.png) | ![Builder](./screenshots/builder.png) | ![AI](./screenshots/ai-gen.png) | ![PDF](./screenshots/pdf.png) |

---

## ✨ Features

- 🧭 Multi-page navigation with **React Router**
- 🧠 **AI-generated** resume content using **Gemini API**
- ⚙️ **Context API** for global state management
- 📋 Form with **validation**
- 🎨 **Tailwind CSS** for beautiful, responsive UI
- 📄 Export resume as **PDF** via `@react-pdf/renderer`
- 🔄 Reset/start-over functionality
- 📱 Fully **responsive** (Mobile & Desktop)
- ♻️ Modular, reusable components
- 🌐 **Deployed** and version controlled with GitHub

---

## 🛠 Tech Stack

- **React.js** (with Hooks + Vite)
- **React Router DOM**
- **React Context API**
- **Tailwind CSS**
- **@react-pdf/renderer**
- **Gemini API (Generative AI by Google)**
- **React Hot Toast**
- **Vercel / Netlify (for deployment)**

---

## 📁 Pages / Routes

- `/` – Landing Page
- `/builder` – Resume Builder
- `/ai-generation` – AI Suggestions Page
- `/preview` – Resume Preview + PDF Download

---

## 📥 Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/notharshagithub/resume-ai.git
cd resume-ai
npm install
   

Paste your rich text content here. You can paste directly from Word or other rich text sources.

🔑 Add your Gemini API key  
Create a `.env` file in the root of the project:

env

CopyEdit

`VITE_GEMINI_API_KEY=your_gemini_api_key_here`

Then run the development server:

bash

CopyEdit

`npm run dev`

Visit: [http://localhost:5173](http://localhost:5173)

* * *

## 🧪 Form Validation

Mandatory fields: Name, Email, Experience, Job Description

* *   Users are redirected if form is incomplete
*     
* *   Dynamic error messages with toasts
*     

## 📄 Resume PDF Export

Uses `@react-pdf/renderer` for clean PDF format

* *   No pixelation (unlike HTML to canvas methods)
*     
* *   Fully formatted and AI-enhanced content
*     
* *   Professionally styled PDF layout
*     

## 🧱 Folder Structure

plaintext

CopyEdit

`src/ ├── assets/ ├── components/ ├── context/ ├── pages/ ├── styles/ ├── utils/ ├── App.jsx ├── main.jsx └── index.css`

## 🧠 AI Integration (Gemini)

Generates:

* *   Professional Summary
*     
* *   Tailored Work Experience
*     
* *   Recommended Skills
*     
* *   Improvements/Recommendations
*     

Response formatted and used across pages

## 📦 Environment Variables

Use a `.env` file to store secrets:

env

CopyEdit

`VITE_GEMINI_API_KEY=your_api_key_here`

Ensure you do not commit `.env` to GitHub.

* * *

## ✅ Good Practices Followed

* *   🔁 Reusable components
*     
* *   🧹 Clean, well-commented code
*     
* *   📦 Modular folder structure
*     
* *   💬 Meaningful commit messages (20+ commits)
*     
* *   🔐 Secure API integration via `.env`
*     

* * *

## 📤 Deployment

Deployed using Vercel (or Netlify):

🔗 Live Demo Link

📜 Commit History (20+ meaningful commits)

Example:

bash

CopyEdit

`🎉 Initial Vite + React setup ✅ Added Resume Form and Context logic ✨ Integrated Gemini API 📝 Implemented PDF export using @react-pdf/renderer 🎨 Styled resume preview with Tailwind 🚀 Deployment setup and README added`

* * *

## 📘 Project Summary

This is a college end-term React project designed to showcase modern web development practices using React, AI integration, and PDF generation. The app intelligently generates resume content based on job descriptions, ensuring a practical, real-world use case.

* * *

## 👨‍💻 Author

Harsha  
📬 notharshagithub  
Built with 💙 as part of my college final project.

* * *

## 📃 License

This project is open-source under the MIT License.

css

CopyEdit

`This should now meet your request for the entire content in markdown format.`

4o mini