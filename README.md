# FlipEarn 🚀
Buy & sell social profiles — a full‑stack marketplace built with React, Tailwind, Clerk authentication, Prisma (Neon), ImageKit, Stripe, Nodemailer, Inngest, and more.
A marketplace for buying and selling social profiles (Instagram, YouTube, TikTok, etc.) built with modern web technologies.


![Flipearn](https://github.com/user-attachments/assets/563fe3ab-7a0c-462d-b166-5c0686e7eed6)
<img width="669" height="544" alt="flipearnbygyan1" src="https://github.com/user-attachments/assets/3124acc2-198b-4abe-9dc8-3e0b90e717a7" />

# 🚀 FlipEarn

![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?logo=vercel)
![React](https://img.shields.io/badge/Frontend-React%2019-blue?logo=react)
![Vite](https://img.shields.io/badge/Bundler-Vite-purple?logo=vite)
![TailwindCSS](https://img.shields.io/badge/Styling-TailwindCSS-38B2AC?logo=tailwindcss)
![Node](https://img.shields.io/badge/Backend-Node.js-green?logo=node.js)
![Express](https://img.shields.io/badge/Framework-Express-black?logo=express)
![Postgres](https://img.shields.io/badge/Database-PostgreSQL-336791?logo=postgresql)
![Prisma](https://img.shields.io/badge/ORM-Prisma-2D3748?logo=prisma)
![Stripe](https://img.shields.io/badge/Payments-Stripe-635BFF?logo=stripe)
![Auth](https://img.shields.io/badge/Auth-Clerk-6C47FF)
![License](https://img.shields.io/badge/License-MIT-yellow)

---


  <a href="https://flip-earn-gps.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-Click%20Here-22c55e?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://github.com/Gyanthakur/Flip-Earn">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.figma.com/design/V20KaGeBHmsho04b3X88pG/FlipEarn">
    <img src="https://img.shields.io/badge/Figma-Design-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  </a>
  <a href="https://flip-earn-server-nu.vercel.app">
    <img src="https://img.shields.io/badge/Backend-API-0ea5e9?style=for-the-badge&logo=node.js&logoColor=white" />
  </a>

---


## 📸 Screenshots

### 🌐 User Interface

| Hero Section | Latest Listings |
|-------------|----------------|
| ![Hero](https://github.com/user-attachments/assets/81c0f9e5-829f-4475-b6ad-40c15122a136) | ![Latest Listing](https://github.com/user-attachments/assets/be35a1ec-3fc4-4a62-88df-6392dfa899d5) |

| Plans | Marketplace |
|------|------------|
| ![Plans](https://github.com/user-attachments/assets/1dff9efa-b35c-4913-89fa-a972d1e413df) | ![Marketplace](https://github.com/user-attachments/assets/5ae2da3b-9aaf-4d11-8b21-5aa4f00aaa4c) |

| Messages | My Listings |
|---------|-------------|
| ![Messages](https://github.com/user-attachments/assets/6a5f1925-0f1e-46a9-9ff4-46f4387502d9) | ![My Listings](https://github.com/user-attachments/assets/0deb740c-787d-4e5e-84ce-9604eb6518af) |

| Listing Details | My Orders |
|----------------|-----------|
| ![Listing Details](https://github.com/user-attachments/assets/74ebb813-2538-4103-aa75-24132ab0bf1e) | ![My Orders](https://github.com/user-attachments/assets/8e8a0a49-bd38-4971-ad39-988d17e76381) |

| Footer |
|--------|
| ![Footer](https://github.com/user-attachments/assets/58730a49-bbf3-47a9-8fca-93722b5f8f39) |

---

### 🛠️ Admin Panel

| Admin Dashboard | Verify Credentials |
|-----------------|-------------------|
| ![Admin Dashboard](https://github.com/user-attachments/assets/53b34756-22c8-4a5d-93b4-8422be44af38) | ![Verify Credentials](https://github.com/user-attachments/assets/20cfa52a-773f-4bde-a62c-7d39e58fd8db) |

| All Listings | Admin Footer |
|-------------|--------------|
| ![All Listings](https://github.com/user-attachments/assets/aa3dfdfd-440c-4af6-8ce5-dc4457744c25) | ![Admin Footer](https://github.com/user-attachments/assets/903fd54e-3765-4a03-9d64-1fbca86b08cc) |

<img width="1918" height="580" alt="Footer" src="https://github.com/user-attachments/assets/1572ca0d-1179-4f3f-855f-07ceb8b979c4" />

## Table of Contents

- [About](#about)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Local Setup](#local-setup)
- [Environment Variables](#environment-variables)
- [Database Setup](#database-setup)
- [Deployment](#deployment)
- [Development Tips](#development-tips)
- [Troubleshooting](#troubleshooting)
- [License](#license)
- [Contact](#contact)

---

## About

FlipEarn is a full-stack marketplace platform that enables users to buy and sell social media profiles with secure authentication, payment processing, and admin verification. The application features a responsive frontend built with React and a robust backend powered by Express.js.

---

## Key Features

- **Responsive UI** with TailwindCSS
- **User Authentication** via Clerk
- **Listings CRUD** with media upload (create, edit, delete)
- **Advanced Filters** sidebar (sticky, mobile modal)
- **Admin Dashboard** for verification, credential changes, and transactions
- **Secure Payments** via Stripe integration
- **Email Notifications** using Nodemailer
- **Image Management** through ImageKit
- **Background Tasks** with Inngest
- **Real-time Features** using WebSocket
- **Search & Filters** for marketplace discovery

---

## Tech Stack

### Frontend
- **React 19** (Vite)
- **Tailwind CSS** for styling
- **React Router DOM** for routing
- **Redux Toolkit** for state management
- **Clerk** for authentication
- **Axios** for API requests
- **react-toastify & react-hot-toast** for notifications
- **lucide-react** for icons

---

## Project Structure

```
Flip-Earn-Frontend/
├── client/
│   ├── public/
│   ├── src/
│   │   ├── app/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── admin/
│   │   │   │   ├── AdminFooter.jsx
│   │   │   │   ├── AdminNavbar.jsx
│   │   │   │   ├── AdminSidebar.jsx
│   │   │   │   ├── AdminTitle.jsx
│   │   │   │   ├── CredentialChangeModal.jsx
│   │   │   │   ├── CredentialVerifyModal.jsx
│   │   │   │   ├── ListingDetailsModal.jsx
│   │   │   │   └── WithdrawalDetail.jsx
│   │   │   ├── ChatBox.jsx
│   │   │   ├── CredentialSubmission.jsx
│   │   │   ├── CTA.jsx
│   │   │   ├── FilterSidebar.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── Hero.jsx
│   │   │   ├── LatestListing.jsx
│   │   │   ├── ListingCard.jsx
│   │   │   ├── Logger.jsx
│   │   │   ├── Navbar.jsx
│   │   │   ├── Plans.jsx
│   │   │   ├── Projects.jsx
│   │   │   ├── StatCard.jsx
│   │   │   ├── Title.jsx
│   │   │   └── WithdrawModal.jsx
│   │   ├── configs/
│   │   ├── pages/
│   │   │   ├── admin/
│   │   │   │   ├── AllListings.jsx
│   │   │   │   ├── CredentialChange.jsx
│   │   │   │   ├── CredentialVerify.jsx
│   │   │   │   ├── Dashboard.jsx
│   │   │   │   ├── Layout.jsx
│   │   │   │   ├── Transactions.jsx
│   │   │   │   └── Withdrawal.jsx
│   │   │   ├── Home.jsx
│   │   │   ├── ListingDetails.jsx
│   │   │   ├── Loading.jsx
│   │   │   ├── ManageListing.jsx
│   │   │   ├── MarketPlace.jsx
│   │   │   ├── Messages.jsx
│   │   │   ├── MyListings.jsx
│   │   │   └── MyOrders.jsx
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   ├── .env
│   ├── package.json
│   └── vite.config.js
└── README.md
```

---

## Prerequisites

Before you begin, ensure you have the following installed and set up:

- **Node.js** v18 or higher
- **npm** or **yarn** package manager
- **Git** for version control
- **Neon/PostgreSQL** database account
- **Clerk** account (authentication)
- **ImageKit** account (image uploads)
- **Stripe** account (payment processing)
- **SMTP credentials** (for sending emails via Nodemailer or SendGrid)

---

## Local Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Gyanthakur/Flip-Earn-Frontend.git
cd Flip-Earn
```

### Step 2: Frontend (Client) Setup

```bash
# Navigate to client directory
cd client

# Install dependencies
npm install

# Create .env file in client directory
### Add environment variables
.env  

# Start development server
npm run dev
```




- The frontend will run on ```http://localhost:5173``` by default.

### Step 3: Backend (Server) Setup

```bash
# Navigate to server directory (from project root)
cd server

# Install dependencies
npm install

# Create .env file in server directory
# Add environment variables (see Environment Variables section)
nano .env  # or use your preferred editor

# Generate Prisma client
npx prisma generate

#push in database
npx prisma db push

# Start development server
npm run server

# Or start production server
npm start
```

The backend will run on the port specified in your `.env` file (default: 8000).

### Step 4: Verify Setup

Open your browser and navigate to:
- **Frontend:** http://localhost:5173
---

## Environment Variables

### Client (.env)

Create a `.env` file in the `client/` directory:

```env
VITE_BASE_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=pk_xxx
```

**Note:** Replace placeholder values with your actual credentials.


**Important:** Never commit `.env` files to version control. Add them to `.gitignore`.

---



**For Vercel Serverless:**
- Ensure webhooks (Stripe, etc.) are reachable
- Consider using persistent hosting for background tasks

### Database (Neon)

1. Create a Neon project at https://console.neon.tech
2. Get production `DATABASE_URL`
3. Add to your backend deployment environment variables
4. Run migrations in production


---

## License

MIT © Gyan Pratap Singh

---

## 🎯 Contributors

👤 **Gyan Pratap Singh** – *Developer & Maintainer*  
📧 Contact: [gps.96169@gmail.com](mailto:gps.96169@gmail.com)  
🔗 GitHub: [@gyanthakur](https://github.com/Gyanthakur)  


## 🌐 Connect with Us

Contact Us:  📲<a href="https://wa.me/918957818597?text=Hey%20%F0%9F%91%8B%2C%20how%20can%20I%20help%20you%3F">
    <img src="https://img.shields.io/badge/WhatsApp-Click%20Me-25D366?style=for-the-badge&logo=whatsapp" alt="WhatsApp" />
  </a>

- **Name**: Gyan Pratap Singh
- **Email**: [gps.96169@gmail.com](mailto:gps.96169@gmail.com)
- **GitHub**: [Gyanthakur](https://github.com/Gyanthakur)
- **Portfolio**: [Gyan's Portfolio](https://gyan-pratap-singh.vercel.app/)

---



## Thank you for checking out the **Flip Earn** project! Happy coding! 😊

---
## ⭐ Support
Give a ⭐ if you like this project!

---
Made with ❤️ by Gyan Pratap Singh

### ⭐ Show Some Love!

If you like this project, don't forget to leave a **⭐ Star** on GitHub! 🚀

<img width="669" height="544" alt="flipearnbygyan1" src="https://github.com/user-attachments/assets/8db20a3d-655c-4ed5-b8a6-e910a40077c5" />
