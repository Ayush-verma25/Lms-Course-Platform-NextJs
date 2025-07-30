# 📚 Lms-Course-Platform-NextJs

A **fully functional LMS (Learning Management System)** built with the latest tech stack including **Next.js 15**, **Clerk authentication**, **Sanity CMS + Studio**, **Stripe payments**, and more. This platform enables users to **create and publish courses as tutors** or **enroll and learn as students** — offering a complete education ecosystem.

> 🚀 Deployed with [Vercel](https://vercel.com)

---

## 🔗 Live Demo

👉 [Check it out here](https://lms-course-platform-next-js.vercel.app/)

---

## ⚙️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/)
- **Authentication**: [Clerk](https://clerk.dev/)
- **CMS**: [Sanity.io](https://www.sanity.io/)
- **CMS Studio**: Sanity Studio (for course/content management)
- **UI Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Utility Management**: [Class Variance Authority (CVA)](https://cva.style/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **State Management**: [Redux Toolkit](https://redux-toolkit.js.org/)
- **Payment Gateway**: [Stripe](https://stripe.com/)
- **Deployment**: [Vercel](https://vercel.com/)

---

## ✨ Features

### 👨‍🏫 For Tutors
- Sign up / Sign in via Clerk
- Create & publish new courses using **Sanity Studio**
- Manage course details, pricing, and content

### 👨‍🎓 For Students
- Browse available courses
- Purchase courses using **Stripe**
- Access purchased courses through their personal dashboard

### 🔒 Authentication & User Management
- Secure login/signup with Clerk
- Role-based views and permissions

### 💳 Payments
- Seamless course purchase flow using **Stripe**
- Secure and scalable payment integration

### 📦 CMS & Studio
- Intuitive backend content management via **Sanity Studio**
- Course metadata, modules, thumbnails, and pricing

---

Install Dependencies

bash
Copy
Edit
npm install
Set up Environment Variables

Create a .env.local file and add:

ini
Copy
Edit
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

SANITY_PROJECT_ID=your_sanity_project_id
SANITY_DATASET=production
SANITY_API_TOKEN=your_sanity_token

STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_public_key

NEXT_PUBLIC_BASE_URL=http://localhost:3000
Start the Development Server

bash
Copy
Edit
npm run dev
Run Sanity Studio
Navigate to your studio/ directory and run:

bash
Copy
Edit
sanity dev
🚀 Deployment
This project is deployed on Vercel. To deploy your own version:

Push the code to your GitHub repository

Import the project into Vercel

Add the environment variables in the Vercel dashboard

Deploy 🎉

📁 Project Structure Overview
php
Copy
Edit
.
├── app/                     # Next.js 15 app directory
├── components/              # Reusable components
├── lib/                     # Utility functions (e.g., sanity, stripe clients)
├── redux/                   # Redux store & slices
├── sanity/                  # Sanity schema definitions
├── studio/                  # Sanity Studio project
├── styles/                  # Tailwind and global styles
├── types/                   # TypeScript types
├── pages/                   # Fallback (if used outside app/)
├── public/                  # Static assets
📸 Screenshots
Landing Page	Course Detail	Sanity Studio

🙌 Contribution
Feel free to fork this repo and submit a pull request. If you have suggestions or issues, open an issue to discuss.

📜 License
This project is licensed under the MIT License.

📫 Contact
For any questions or collaboration:

Name: Ayush Verma

Email: your.email@example.com

GitHub: @your-github

Built with ❤️ using modern web technologies.

## 🧑‍💻 Installation & Setup
**Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Lms-Course-Platform-NextJs.git
   cd Lms-Course-Platform-NextJs
