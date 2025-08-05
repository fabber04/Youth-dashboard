# IHC Youth Connect - Youth Dashboard

**Your digital hub for faith, fellowship & growth**

A comprehensive React-based youth ministry dashboard that combines practical church management with spiritual growth features. Built for the IHC Youth Ministry to foster community, encourage spiritual development, and streamline youth group activities.

## ✨ Features

### 🏠 Dashboard
- **Welcome Header** with live time and date
- **Quick Actions** for common tasks
- **Upcoming Events** preview with RSVP functionality
- **Latest Devotional** with scripture and author
- **Prayer Request Summary** with statistics
- **Announcements** with priority indicators

### 📖 Devotionals
- **Daily Devotional** with full content and sharing options
- **Weekly Archive** of past devotionals
- **Bible Reading Plans** (30/60/90-day) with progress tracking
- **Reflection Journal** with export functionality
- **Bookmark & Share** features for social media

### 📅 Events
- **Event Listings** with detailed information
- **RSVP System** for event attendance
- **Category Filtering** (Bible Study, Prayer, Social, Mission)
- **Search & Filter** functionality
- **Map View** (Google Maps integration ready)
- **Event Sharing** via WhatsApp/Telegram

### 🙏 Prayer Requests
- **Add Prayer Requests** (anonymous or named)
- **"I Prayed" Counter** to track prayer support
- **Comment System** for encouragement
- **Filter Options** (All, Active, Answered, Anonymous)
- **Real-time Updates** and notifications

### 👤 Profile
- **User Profile Management** with editable information
- **Saved Devotionals** collection
- **Journal Entries** with export to PDF
- **Prayer Request History**
- **Notification Preferences**
- **Privacy Settings**

## 🛠 Tech Stack

- **Frontend**: React.js 18.2.0
- **Styling**: TailwindCSS 3.3.0
- **Routing**: React Router DOM 6.3.0
- **Icons**: Lucide React 0.263.1
- **Notifications**: React Hot Toast 2.4.1
- **Markdown**: React Markdown 8.0.7
- **PDF Export**: jsPDF 2.5.1
- **Backend Ready**: Firebase/Supabase integration ready

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ihc-youth
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### Build for Production

```bash
npm run build
```

## 📁 Project Structure

```
src/
├── components/
│   └── Layout.js          # Main layout with navigation
├── pages/
│   ├── Dashboard.js       # Home dashboard
│   ├── Devotionals.js     # Devotional content & journal
│   ├── Events.js          # Event management
│   ├── PrayerRequests.js  # Prayer wall
│   └── Profile.js         # User profile & settings
├── App.js                 # Main app component
├── index.js              # React entry point
└── index.css             # Global styles & TailwindCSS
```

## 🎨 Design System

### Color Palette
- **Primary**: Blue gradient (#0ea5e9 to #3b82f6)
- **Secondary**: Purple gradient (#d946ef to #a21caf)
- **Faith**: Gold gradient (#facc15 to #eab308)
- **Success**: Green (#10b981)
- **Warning**: Yellow (#f59e0b)
- **Error**: Red (#ef4444)

### Typography
- **Primary Font**: Inter (Sans-serif)
- **Secondary Font**: Merriweather (Serif)
- **Icons**: Lucide React

### Components
- **Cards**: Consistent card design with hover effects
- **Buttons**: Primary, secondary, and outline variants
- **Forms**: Styled input fields with focus states
- **Modals**: Overlay modals for forms and details

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory:

```env
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
REACT_APP_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

### Firebase Setup (Optional)
1. Create a Firebase project
2. Enable Authentication (Google Sign-in)
3. Set up Firestore database
4. Add Firebase configuration to environment variables

## 📱 Responsive Design

The application is fully responsive and optimized for:
- **Desktop**: Full-featured experience
- **Tablet**: Adapted layout with touch-friendly elements
- **Mobile**: Mobile-first design with collapsible navigation

## 🔒 Security Features

- **Anonymous Prayer Requests**: Users can submit prayer requests anonymously
- **Privacy Controls**: User profile visibility settings
- **Input Validation**: Form validation and sanitization
- **Secure Routing**: Protected routes (ready for authentication)

## 🚀 Deployment

### Netlify
1. Connect your GitHub repository
2. Set build command: `npm run build`
3. Set publish directory: `build`
4. Deploy

### Vercel
1. Import your GitHub repository
2. Vercel will auto-detect React settings
3. Deploy with one click

### Firebase Hosting
```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📋 Roadmap

### Phase 1 (Current)
- ✅ Basic dashboard functionality
- ✅ Devotional system
- ✅ Event management
- ✅ Prayer requests
- ✅ User profiles

### Phase 2 (Future)
- 🔄 Firebase integration
- 🔄 Real-time notifications
- 🔄 Google Maps integration
- 🔄 Audio devotionals
- 🔄 Mobile app

### Phase 3 (Future)
- 🔄 Advanced analytics
- 🔄 Admin dashboard
- 🔄 Multi-language support
- 🔄 API for third-party integrations

## 📞 Support

For support and questions:
- **Email**: support@ihc.org
- **Youth Leader**: pastor.sarah@ihc.org
- **Technical Issues**: Create an issue on GitHub

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **IHC Youth Ministry** for the vision and requirements
- **React Community** for the amazing framework
- **TailwindCSS** for the utility-first CSS framework
- **Lucide** for the beautiful icons
- **All contributors** who help make this project better

---

**Built with ❤️ for the IHC Youth Ministry**

*"Let no one despise you for your youth, but set the believers an example in speech, in conduct, in love, in faith, in purity." - 1 Timothy 4:12* 