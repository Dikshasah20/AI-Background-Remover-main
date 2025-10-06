# ✨ AI Background Remover SaaS

A full-stack SaaS platform that removes image backgrounds effortlessly using advanced AI technology. Built with Spring Boot, React, and modern web technologies.

## 🛠️ Tech Stack

### Backend
- **Spring Boot** - RESTful API development
- **MySQL** - Database for user data and transaction history
- **JWT Security** - Secure authentication
- **Clerk Webhooks** - User management integration

### Frontend
- **React** - Component-based UI
- **Tailwind CSS** - Modern, responsive styling
- **Vite** - Fast build tool and development server

### Integrations
- **ClipDrop API** - AI-powered background removal
- **Clerk** - Authentication and user management
- **Razorpay** - Payment processing
- **Ngrok** - Local development tunneling

## ✨ Features

- 🧠 **AI Background Removal** - Instant background removal using ClipDrop API
- 🔐 **Secure Authentication** - User registration and login via Clerk
- 💳 **Payment Integration** - Seamless payments through Razorpay
- 📱 **Responsive Design** - Works perfectly on all devices
- 🔒 **JWT Security** - Protected API endpoints
- 📊 **User Dashboard** - Track usage and download history
- ⚡ **Fast Processing** - Optimized for quick image processing

## 🏗️ Architecture

```
Frontend (React + Vite)
       ↓
Backend (Spring Boot)
       ↓
MySQL Database
       ↓
External APIs (ClipDrop, Clerk, Razorpay)
```

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Node.js 18+
- MySQL 8.0+
- Git

### Backend Setup

1. Clone the repository
```bash
git clone [your-repo-url]
cd ai-background-remover
```

2. Navigate to backend directory
```bash
cd backend
```

3. Configure application.properties
```properties
# Database Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/bg_remover
spring.datasource.username=your_username
spring.datasource.password=your_password

# API Keys
clipdrop.api.key=your_clipdrop_key
clerk.secret.key=your_clerk_secret
razorpay.key.id=your_razorpay_key
razorpay.key.secret=your_razorpay_secret
```

4. Run the application
```bash
./mvnw spring-boot:run
```

### Frontend Setup

1. Navigate to frontend directory
```bash
cd frontend
```

2. Install dependencies
```bash
npm install
```

3. Configure environment variables
```env
VITE_API_BASE_URL=http://localhost:8080
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_RAZORPAY_KEY_ID=your_razorpay_key
```

4. Start development server
```bash
npm run dev
```

## 🔧 Configuration

### ClipDrop API Setup
1. Sign up at [ClipDrop](https://clipdrop.co/)
2. Get your API key
3. Add to application.properties

### Clerk Setup
1. Create account at [Clerk](https://clerk.com/)
2. Configure your application
3. Set up webhooks for user synchronization

### Razorpay Setup
1. Create merchant account at [Razorpay](https://razorpay.com/)
2. Get API credentials
3. Configure webhook endpoints

## 🎯 Key Learning Outcomes

- **Full-Stack Development** - End-to-end application development
- **Spring Boot Mastery** - RESTful APIs, security, and database integration
- **Modern Frontend** - React with Vite for optimal performance
- **Payment Integration** - Secure transaction handling
- **Third-Party APIs** - Integration with multiple external services
- **Authentication** - Modern auth patterns with Clerk
- **Responsive Design** - Mobile-first approach with Tailwind CSS

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- **ClipDrop** for the amazing AI background removal API
- **Clerk** for seamless authentication
- **Razorpay** for reliable payment processing
- **Spring Boot** community for excellent documentation
- **React** team for the awesome framework

⭐ If you found this project helpful, please give it a star!


