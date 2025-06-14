# AgileOne

## 🏆 Streamline Your Sprints with AgileOne

### 🔗 Description

**AgileOne** is a powerful software project management tool designed to help teams collaborate, manage projects, and deliver results efficiently. From creating and managing organizations to visualizing tasks on Kanban boards, AgileOne provides a streamlined experience for project and sprint management.

---

## 🔎 Features

### 1. **🔼 Organization Management**

- Create and manage multiple organizations within the application.
- Invite team members to your organization via email invitations.

### 2. **📊 Project Management**

- Manage multiple projects under a single organization.
- Assign team members to specific projects for seamless collaboration.

### 3. **📏 Sprint Planning and Management**

- Create sprints with customizable start and end dates.
- Assign issues or tasks to team members within a sprint.
- Set task priorities: Low, Medium, High, Urgent.

### 4. **🔢 Task Assignment and Tracking**

- Each team member can view tasks assigned to them.
- Task details include the issue name, description, and priority.

### 5. **🗃 Kanban Board Visualization**

- Visualize tasks across different stages:
  - **To Do**
  - **In Progress**
  - **In Review**
  - **Completed**
- Optimize team productivity with an intuitive drag-and-drop interface.

---

## 🚀 Future Scope

We are continuously improving AgileOne to make project management more efficient. Here are the upcoming features:

- Track individual team members' progress in detail.
- Gain actionable insights into team performance.
- Generate customizable reports and analytics for data-driven decisions.

---

## 🛠️ Tech Stack

AgileOne is built using modern web development technologies to ensure a fast, reliable, and beautiful user experience:

- **Frontend**: [Next.js](https://nextjs.org/)
- **Authentication**: [Clerk](https://clerk.dev/)
- **UI Components**: [shadcn](https://shadcn.dev/) and [Tailwind CSS](https://tailwindcss.com/)
- **Database**: [NeonDB](https://neon.tech/) with [Prisma](https://www.prisma.io/)


---

## 📖 Installation and Setup

Follow these steps to set up AgileOne locally:

### Prerequisites

- Node.js (v16+)
- npm or yarn
- NeonDB instance
- Clerk account for authentication


- Configure environment variables:
   Make sure to create a `.env` file with the following variables:
   ```env
   DATABASE_URL=

   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_bGl2ZS10aXRtb3VzZS0wLmNsZXJrLmFjY291bnRzLmRldiQ
   CLERK_SECRET_KEY=sk_test_dC37RANmA4ah18rKskNHrRlcngJENvgttw1ThymhHy

   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
   ```
