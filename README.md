# NEET Battleground (NBG) 🧠⚔️

**NEET Battleground** is a cutting-edge interactive learning platform designed specifically for students preparing for the National Eligibility cum Entrance Test (NEET) in India. The application features two engaging game modes with a modern gaming aesthetic that makes learning more interactive and enjoyable.

## 🎮 Features

### MCQ Quiz Battle
- **Real-time competitive gameplay** with live scoring and leaderboards
- **Timed multiple-choice questions** covering the entire NEET syllabus
- **Detailed explanations** for each answer to enhance learning
- **Physics, Chemistry, and Biology** topics with difficulty progression
- **Live multiplayer battles** with students worldwide

### Drawing Challenge
- **Medical pictionary-style game** (similar to skribbl.io)
- **Draw and guess medical terms**, anatomical structures, and biological concepts
- **Collaborative drawing tools** with multiple brush types and colors
- **Visual learning reinforcement** for complex medical concepts
- **Practice mode** for solo learning sessions

### 🎨 Enhanced UI/UX Features
- **Dynamic animated backgrounds** with medical-themed particles
- **3D card effects** with hover animations and glow effects
- **Gaming-inspired design** with gradient backgrounds and modern typography
- **Responsive design** optimized for all devices (mobile-first approach)
- **Interactive elements** with smooth transitions and micro-animations
- **Medical-themed decorative elements** (DNA helix, brain icons, etc.)

### 🚀 Multiplayer Functionality
- **Public rooms** for playing with random students
- **Private rooms** with invite codes for studying with friends
- **Real-time chat** for communication during games
- **Live scoring system** with instant updates
- **Room management** with create, join, and practice options

## 🛠️ Technical Implementation

This application is built with modern web technologies:

- **React 18** with TypeScript for type-safe development
- **Tailwind CSS** for utility-first styling and responsive design
- **Socket.IO** for real-time communication and multiplayer features
- **Zustand** for lightweight state management
- **React Router** for client-side navigation
- **Lucide React** for beautiful, consistent icons
- **Vite** for fast development and optimized builds

## 🎯 Design Philosophy

### Gaming Aesthetic
- **Dynamic backgrounds** with animated particles and medical themes
- **Gradient color schemes** with blue, purple, and medical green accents
- **Interactive hover effects** with scale transforms and glow effects
- **Modern typography** with bold, gaming-inspired fonts
- **Smooth animations** throughout the user experience

### Medical/Educational Integration
- **Subtle medical accents** without being overtly clinical
- **Brain and DNA-inspired decorative elements**
- **Scientific color palette** with strategic medical green accents
- **Educational focus** while maintaining gaming engagement

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/neet-battleground.git
   cd neet-battleground
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser** and navigate to `http://localhost:5173`

## 📁 Project Structure

The project follows a modular architecture optimized for scalability:

```
src/
├── components/
│   ├── ui/           # Reusable UI components (Button, Card, etc.)
│   ├── game/         # Game-specific components (DrawingCanvas, MCQQuestion)
│   ├── chat/         # Chat functionality components
│   ├── room/         # Room management components
│   └── layout/       # Layout components (Header, Footer)
├── pages/            # Application routes and pages
├── services/         # Socket and API services
├── store/            # State management with Zustand
├── types/            # TypeScript type definitions
└── lib/              # Utility functions and helpers
```

## 🎨 UI Components

### Enhanced Components
- **AnimatedBackground**: Dynamic medical-themed background with particles
- **GameModeCard**: Interactive game mode selection with 3D effects
- **Button**: Enhanced with gradient variants and gaming aesthetics
- **Card**: Glass morphism effects and hover animations

### Design System
- **Color Palette**: Blue, purple, and medical green gradients
- **Typography**: Modern, gaming-inspired fonts
- **Animations**: Smooth transitions and micro-interactions
- **Responsive**: Mobile-first design approach

## 🔧 Development

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Key Technologies
- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS with custom animations
- **State Management**: Zustand for lightweight state
- **Real-time**: Socket.IO for multiplayer features
- **Build Tool**: Vite for fast development

## 🎯 Roadmap

### Phase 1: Core Platform ✅
- [x] Dynamic homepage with gaming aesthetics
- [x] Enhanced UI components with animations
- [x] Responsive design implementation
- [x] Basic multiplayer functionality

### Phase 2: Backend Integration 🚧
- [ ] Socket.IO server implementation
- [ ] Database integration for user data
- [ ] Authentication system
- [ ] Question/word database

### Phase 3: Advanced Features 📋
- [ ] AI-powered difficulty adjustment
- [ ] Advanced analytics and progress tracking
- [ ] Social features and leaderboards
- [ ] Mobile app development

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
- Follow TypeScript best practices
- Use Tailwind CSS for styling
- Maintain responsive design principles
- Add proper error handling
- Write meaningful commit messages

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **NEET Students**: For inspiration and feedback
- **Medical Education Community**: For domain expertise
- **Open Source Community**: For amazing tools and libraries

---

**Ready to battle?** 🚀 Join the NEET Battleground and master your medical knowledge through interactive gaming!
