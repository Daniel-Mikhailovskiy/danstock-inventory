## Inventory Management Dashboard

<img width="1920" height="1118" alt="Screenshot 2025-07-16 at 15 23 42" src="https://github.com/user-attachments/assets/48779cb3-843b-4e33-8bcb-fd7a9a2a96e3" />

🚀 Full-stack Inventory Management Dashboard built from scratch to deepen understanding of full-stack development and direct AWS hosting, crafted from a Product Manager’s perspective.

As a Product Manager, I wanted to explore what it takes to go full-stack and host directly on AWS instead of using platforms like Vercel, so I designed, built, and deployed this complete system.

### 🛠 Tech Stack
Frontend: Next.js 14 + TypeScript + TailwindCSS, deployed with AWS Amplify

Backend: Node.js running on AWS EC2 behind Amazon API Gateway

Database: PostgreSQL managed via AWS RDS

State management: Redux Toolkit + RTK Query

### 📦 Features
Product CRUD operations

Sales & expense tracking

Customer and revenue insights

Dynamic dashboard with charts, badges, and skeleton loaders

Global modals and smooth loading UX

### 💡 About the Project
Inspired by a tutorial from @ed-roh, I extended this project by adding custom UI/UX, new backend endpoints, global loaders, and deployed the full stack on AWS using:

- EC2 for backend

- Amazon API Gateway for routing

- RDS for the database

- Amplify for frontend hosting

### 🧠 Lessons Learned & Future Improvements

- Refactor the database schema to support deeper relationships and enforce constraints

- Add dynamic backend endpoints for currently static components (e.g., alerts, reviews)

- Introduce authentication and roles for multi-user support

- Although PostgreSQL was chosen to gain hands-on experience with relational databases, a NoSQL option like MongoDB might better suit this project given the limited relational complexity
