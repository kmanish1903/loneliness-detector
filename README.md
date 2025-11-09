# MindCare AI - Mental Health Support Application

AI-powered mental health support with mood tracking, crisis intervention, and personalized wellness recommendations.

## 🌟 Features
- AI mood detection & analysis using Google Gemini
- Crisis intervention with 24/7 hotlines
- Personalized daily goals generation
- Progress tracking & analytics dashboard
- PWA with offline support
- HIPAA-compliant secure data storage
- Real-time mood insights and recommendations
- Export personal data functionality

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Supabase account
- Google AI API key

### Installation

```sh
# Clone the repository
git clone <repository-url>
cd loneliness_detector

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your Supabase and Google AI credentials

# Start development server
npm run dev
```

### Environment Variables

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
GOOGLE_AI_API_KEY=your_google_ai_api_key
```

## 🏗️ Tech Stack

- **Frontend**: React 18, TypeScript, Tailwind CSS
- **Backend**: Supabase (PostgreSQL, Edge Functions)
- **AI**: Google Gemini 2.5 Flash
- **Authentication**: Supabase Auth
- **Deployment**: Vercel, Netlify compatible
- **PWA**: Vite PWA plugin

## 📚 Documentation

- [DEPLOYMENT.md](./DEPLOYMENT.md) - Production deployment guide
- [PHASE_9_REVIEW.md](./PHASE_9_REVIEW.md) - Complete feature review & security audit

## 🔐 Security & Compliance

- **HIPAA Compliance**: Row Level Security (RLS) on all tables
- **Data Encryption**: End-to-end encryption for sensitive data
- **Authentication**: Secure email/password with session management
- **Privacy**: User data isolation and secure deletion
- **Audit Trail**: Crisis events and user actions logged

## 🆘 Crisis Support

Built-in emergency resources:
- 988 Suicide & Crisis Lifeline
- Crisis Text Line (Text HOME to 741741)
- Location-based crisis resources
- Immediate access from any screen

## 📱 Progressive Web App

- Install on any device (iOS, Android, Desktop)
- Offline functionality with service workers
- Native app-like experience
- Push notifications (future feature)

## 🧪 Testing

```sh
# Run unit tests
npm run test

# Run e2e tests
npm run test:e2e

# Type checking
npm run type-check
```

## 🚀 Deployment

See [DEPLOYMENT.md](./DEPLOYMENT.md) for detailed deployment instructions.

### Quick Deploy to Vercel

```sh
npm run build
npx vercel --prod
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## ⚠️ Disclaimer

This application is for informational and wellness purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of qualified health providers with questions about medical conditions.

---

**Live Demo**: (https://mentalhealth-delta.vercel.app/)
