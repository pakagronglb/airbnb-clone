# 🏠 Modern Airbnb Clone with Next.js 13 

[![Next.js](https://img.shields.io/badge/Next.js-13-black?style=flat&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18-blue?style=flat&logo=react)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-38B2AC?style=flat&logo=tailwind-css)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/Prisma-4-2D3748?style=flat&logo=prisma)](https://www.prisma.io/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6-47A248?style=flat&logo=mongodb)](https://www.mongodb.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-4-007ACC?style=flat&logo=typescript)](https://www.typescriptlang.org/)

A full-stack Airbnb clone built with modern web technologies, featuring a responsive design and comprehensive booking system.

*Original implementation by [Antonio Erdeljac](https://github.com/AntonioErdeljac/next13-airbnb-clone)*

## ✨ Features

### Authentication & Security
- Multi-provider authentication (Credentials, Google, GitHub)
- Secure session management with NextAuth
- Protected routes and API endpoints

### User Experience
- Responsive Tailwind design with animations
- Interactive calendar selection
- Real-time form validation
- Toast notifications for user feedback
- Optimized loading states
- Empty state handling

### Core Functionality
- Property listing creation and management
- Advanced search with multiple filters:
  - Categories
  - Date ranges
  - Location via map
  - Guest capacity
  - Room/bathroom count
- Intelligent reservation system
- Favorite properties system
- Shareable filtered URLs
- Image upload via Cloudinary CDN

### Technical Highlights
- Server-side React components
- Direct database access without API
- Next.js 13 App Router
- Error boundary implementation
- Loading state management
- Efficient data relations handling

## 🚀 Getting Started

### Prerequisites
- Node.js 14.x or higher
- npm or yarn package manager

### Installation

1. Clone the repository
```bash
git clone https://github.com/pakagronglb/airbnb-clone.git
```

2. Install dependencies
```bash
npm install
```

3. Configure environment variables
Create a `.env` file with the following:
```env
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```

4. Initialize the database
```bash
npx prisma db push
```

5. Start development server
```bash
npm run dev
```

## 📝 Available Scripts

| Command         | Description                              |
|----------------|------------------------------------------|
| `npm run dev`  | Starts development server on port 3000   |
| `npm run build`| Creates production build                 |
| `npm start`    | Runs production server                   |
| `npm lint`     | Runs ESLint for code quality checks      |

## 🙏 Acknowledgments

This project is based on the original work by [Antonio Erdeljac](https://github.com/AntonioErdeljac/next13-airbnb-clone). Modified and maintained by [Pakagrong Lebel](https://github.com/pakagronglb).

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
