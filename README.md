# CareerConnect – University Career Services Portal

CareerConnect is a modern, student-centric web application that transforms traditional university career services into an intelligent, personalized platform. It helps students find internships and job opportunities, build professional resumes, connect with career advisors, and engage with employers – all in one place.

## 🔍 Problem Statement

Many students miss out on career opportunities due to lack of awareness, outdated platforms, or insufficient guidance. CareerConnect addresses this by providing an all-in-one portal with intelligent suggestions, real-time engagement tools, and powerful job-matching algorithms.

---

## 🎯 Features

### Core MVP Features
- **🎓 Student Dashboard**: Personalized job/internship recommendations based on user profile and preferences.
- **📝 Resume & Cover Letter Builder**: Interactive templates with real-time feedback.
- **📅 Career Events Calendar**: Register for workshops, fairs, mock interviews.
- **🧑‍💼 One-Click Apply**: Apply for jobs directly from the platform.
- **💬 Career Coach Chat**: Live chat support with career advisors.

### 🎯 Unique Feature
- **AI-Powered Career Matching Engine**: Dynamically matches students with relevant job and internship listings based on their academic history, skills, interests, and resume.

---

## 👥 Target Users

- **University Students**: Seeking internships, jobs, and resume help.
- **Career Advisors**: Managing appointments, providing guidance.
- **Employers**: Posting jobs, browsing candidate profiles.
- **University Admins**: Overseeing system analytics and engagement.

---

## 🔁 User Flow

1. **Landing Page**: Welcome page with app overview.
2. **Sign Up / Log In**: Users register or authenticate via email/password.
3. **Student Dashboard**: View job matches, upcoming events, and progress.
4. **Resume Builder**: Create and update resumes using templates.
5. **Career Events**: Browse and register for workshops or fairs.
6. **Apply for Jobs**: Use one-click apply or save jobs to profile.
7. **Live Chat**: Connect with career coaches for resume/CV feedback.

---

## 🧱 Tech Stack

### Frontend
- **React + TypeScript**
- **Tailwind CSS** for styling
- **Vite** for fast development

### Backend & Services
- **Supabase** for:
  - Database (PostgreSQL)
  - Authentication (student, employer, admin roles)
  - Edge Functions (API endpoints for resume scoring, matching)
- **Stripe** (optional for premium employer features or CV review services)

---

## 💡 Folder Structure

```bash
careerconnect/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── layouts/
│   ├── hooks/
│   └── App.tsx
├── supabase/
│   ├── edge-functions/
│   └── schema.sql
├── README.md
├── vite.config.ts
├── package.json
└── tailwind.config.js
