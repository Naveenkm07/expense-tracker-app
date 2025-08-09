# 💰 Expense Tracker App

A modern, responsive expense tracking application built with **Next.js**, **React**, and **Firebase**. Track your daily expenses, manage your budget, and gain insights into your spending habits with this sleek and intuitive web application.

![Expense Tracker](https://img.shields.io/badge/Next.js-14.2.5-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)
![Firebase](https://img.shields.io/badge/Firebase-10.12.4-orange?style=for-the-badge&logo=firebase)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC?style=for-the-badge&logo=tailwind-css)

## ✨ Features

- **📱 Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **⚡ Real-time Updates** - Instant synchronization with Firebase Firestore
- **🎨 Modern UI** - Beautiful dark theme with Tailwind CSS
- **💰 Expense Management** - Add, view, and delete expense items
- **📊 Automatic Calculations** - Real-time total expense calculation
- **🔒 Data Persistence** - Secure cloud storage with Firebase
- **🚀 Fast Performance** - Built with Next.js for optimal speed
- **📱 PWA Ready** - Progressive Web App capabilities

## 🛠️ Tech Stack

- **Frontend**: Next.js 14.2.5, React 18
- **Styling**: Tailwind CSS 3.4.1
- **Backend**: Firebase Firestore
- **Authentication**: Firebase Auth (ready for implementation)
- **Deployment**: Vercel, Netlify, or any static hosting

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Firebase account (for data persistence)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Naveenkm07/expense-tracker-app.git
   cd expense-tracker-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Firebase** (Optional for data persistence)
   - Create a Firebase project at [firebase.google.com](https://firebase.google.com)
   - Get your Firebase configuration
   - Update `app/firebase.js` with your config

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📖 Usage

### Adding Expenses
1. Enter the item name (e.g., "Coffee", "Movie tickets")
2. Enter the price (e.g., "4.95", "24.99")
3. Click the "+" button to add to your expense list

### Managing Expenses
- **View**: All expenses are displayed in a clean list
- **Delete**: Click the "X" button next to any item to remove it
- **Total**: Your total expenses are automatically calculated and displayed

### Features in Action
```
┌─────────────────────────────────────┐
│ 💰 Expense Tracker                 │
├─────────────────────────────────────┤
│ [Item Name] [Price] [+]           │
├─────────────────────────────────────┤
│ ☕ Coffee                    $4.95 │
│ 🎬 Movie tickets           $24.99 │
│ 🍕 Pizza                   $18.50 │
├─────────────────────────────────────┤
│ Total:                    $48.44  │
└─────────────────────────────────────┘
```

## 🔧 Configuration

### Firebase Setup (Optional)

To enable data persistence, update `app/firebase.js`:

```javascript
const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-project.firebaseapp.com",
  projectId: "your-project-id",
  storageBucket: "your-project.appspot.com",
  messagingSenderId: "your-sender-id",
  appId: "your-app-id"
};
```

### Environment Variables

Create a `.env.local` file for Firebase configuration:

```env
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

## 📁 Project Structure

```
expense-tracker-app/
├── app/
│   ├── favicon.ico
│   ├── firebase.js          # Firebase configuration
│   ├── globals.css          # Global styles
│   ├── layout.js            # Root layout
│   └── page.js              # Main expense tracker component
├── public/
│   ├── next.svg
│   └── vercel.svg
├── package.json
├── tailwind.config.js
└── README.md
```

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push

### Netlify
1. Build command: `npm run build`
2. Publish directory: `out`

### Manual Deployment
```bash
npm run build
npm run start
```

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Powered by [Firebase](https://firebase.google.com/)
- Icons from [Heroicons](https://heroicons.com/)

## 📞 Support

If you have any questions or need help, please:

- 📧 Email: naveenkm07@gmail.com
- 🐛 Report bugs: [GitHub Issues](https://github.com/Naveenkm07/expense-tracker-app/issues)
- 💡 Suggest features: [GitHub Discussions](https://github.com/Naveenkm07/expense-tracker-app/discussions)

---

<div align="center">

**Made with ❤️ by [Naveenkm07](https://github.com/Naveenkm07)**

[![GitHub stars](https://img.shields.io/github/stars/Naveenkm07/expense-tracker-app?style=social)](https://github.com/Naveenkm07/expense-tracker-app)
[![GitHub forks](https://img.shields.io/github/forks/Naveenkm07/expense-tracker-app?style=social)](https://github.com/Naveenkm07/expense-tracker-app)
[![GitHub issues](https://img.shields.io/github/issues/Naveenkm07/expense-tracker-app)](https://github.com/Naveenkm07/expense-tracker-app/issues)

</div>

