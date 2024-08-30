# DashCraft

DashCraft is a powerful Next.js-based web application designed for creating and managing dashboards, agencies, and subaccounts. It offers a robust set of features for user management, file uploads, tag creation, and more.

## Features

- Next.js 14 with App Router
- User authentication and authorization with Clerk
- Prisma ORM for database management
- File uploads with UploadThing
- UI components with Radix UI and Shadcn UI
- Form handling with React Hook Form and Zod validation
- State management with React Context
- Styling with Tailwind CSS
- Icons from Lucide React
- Date handling with date-fns
- Drag and drop functionality with react-beautiful-dnd
- Toast notifications with Sonner
- Payment integration with Stripe

## Getting Started

1. Clone the repository:
git clone https://github.com/pallaviriyer/dashcraft.git

2. Install dependencies:
cd dashcraft npm install

3. Set up environment variables:
Create a `.env` file in the root directory and add necessary environment variables (refer to `.env.example` if available).

4. Run the development server:
npm run dev

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `/src/app`: Contains the main application code
- `/src/components`: Reusable React components
- `/src/lib`: Utility functions and custom hooks
- `/src/providers`: React context providers
- `/prisma`: Database schema and migrations
