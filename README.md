# 🧠 OMNIX

OMNIX is an advanced, AI-powered personal companion designed to provide an intelligent and empathetic conversational experience. It features voice interaction, persistent memory, emotional intelligence, smart reminders, and productivity analytics — all running locally in your browser with complete privacy.

## 🌟 Features

- 💬 **Intelligent Conversations**: Natural language processing with contextual awareness and multi-turn dialogue
- 🎙️ **Voice Interaction**: Speak to OMNIX and receive spoken responses with voice synthesis
- 📞 **Live Call Mode**: Continuous voice conversation like ChatGPT/Gemini live call
- 🌍 **Multi-Language Support**: Switch between 8+ languages (English, Urdu, Hindi, Arabic, French, Spanish, German, Chinese)
- 🤖 **Gemini AI Integration**: Optional Google Gemini API for enhanced AI responses (free tier)
- ☁️ **Cloud Sync**: Automatic cloud backup with Supabase/Firebase integration (free tier)
- ♾️ **Unlimited Chats & Memory**: No limits on conversations or stored data
- 🧠 **Persistent Memory**: Remembers your name, goals, learning topics, habits, and conversation history
- 😊 **Emotional Intelligence**: Detects mood and responds with empathy
- ⏰ **Smart Reminders**: Schedule tasks and receive timely notifications
- 📊 **Personal Analytics**: Track productivity, consistency, and interaction patterns
- 📅 **Daily Planning**: Optimized schedule based on your habits and goals
- 📚 **Learning Assistant**: Structured learning paths for any topic
- 🕓 **Chat History**: Full conversation log with export, search, and management
- 🎨 **Dark/Light Mode**: Toggle between dark and light themes
- 🔄 **Advanced Reset Options**: Granular control to reset specific data or everything
- 🔒 **100% Privacy**: All data stored locally with optional cloud sync

## 🛠️ Technology Stack

**Frontend:** Pure HTML5, CSS3, JavaScript (ES6+)  
**UI Design:** Custom CSS with glassmorphism, animations & dark/light themes  
**AI Engine:** Local AI + Optional Google Gemini API (Free Tier)  
**Voice Input:** Web Speech API (SpeechRecognition)  
**Voice Output:** Web Speech API (SpeechSynthesis) + Multi-language TTS  
**Data Storage:** localStorage + Cloud Sync (Supabase/Firebase - Free Tier)  
**State Management:** Vanilla JavaScript with reactive state  
**Deployment:** Static hosting (Vercel, Netlify, GitHub Pages)

## 🚀 Getting Started

### Prerequisites

- **Modern Web Browser** (Chrome, Edge, Firefox recommended)
- **No server required** - runs entirely in your browser
- **Optional:** Google Gemini API key for enhanced AI

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/imsnippet/Omnix-Ai.git
   cd Omnix-Ai
   ```

2. **Open in Browser:**
   ```bash
   # Simply double-click index.html
   # OR run a local server:
   python -m http.server 8000
   # OR
   npx serve
   ```

3. **Access OMNIX:**
   - Open `http://localhost:8000` in your browser
   - Start chatting immediately!

## 💡 Voice Commands

### Language Switching
- `"Speak Urdu"` — Switch to Urdu
- `"Speak Hindi"` — Switch to Hindi
- `"Speak Arabic"` — Switch to Arabic
- `"Speak English"` — Switch to English
- Or click the 🌐 button to select from 8+ languages

### Live Call Mode
- `"Start live call"` — Begin continuous voice conversation
- `"End call"` — Exit live mode
- Or click the 📞 button to toggle

## ⚙️ Settings Panel

Click the ⚙️ Settings button in the sidebar to access:

### 🤖 AI Configuration
- Add your Gemini API key (optional)
- Verify API key with one click
- Get free key at: [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
- Status indicator shows connection state

### 🌍 Language Selection
- Choose from 8+ languages
- Visual language selector with flags
- Instant switching with confirmation

### 🎨 Appearance
- Toggle Dark Mode / Light Mode
- Beautiful themes for day and night
- Preference saved automatically

### 💾 Data Management
- Export all data as JSON backup
- Clear all data with confirmation
- Full control over your information

## 📊 Storage & Privacy

### Data Storage
- **Location:** Browser localStorage (your device only)
- **Capacity:** ~5-10MB per domain (50,000+ messages)
- **Cloud Sync:** Optional Supabase/Firebase for unlimited storage
- **Backup:** Export chat history as JSON anytime

### Privacy Guarantee
- ✅ No data sent to external servers (unless cloud sync enabled)
- ✅ No tracking or analytics
- ✅ No cookies
- ✅ No account required
- ✅ Complete user control over data

## 📦 Testing

> 🧪 **Live Demo**: https://omnix-ai-lemon.vercel.app

## 🔄 Reset Options

- 💬 **Reset Chat History Only** - Keep memory & settings
- 🧠 **Reset Memory Only** - Clear learned information
- ⏰ **Reset Reminders & Tasks** - Clear scheduled items
- ⚙️ **Reset Settings Only** - Restore default settings
- 🗑️ **Reset Everything** - Complete factory reset
- 📥 **Backup Before Reset** - Export data first

## 👨‍💻 Developed By

Developed with ❤️ by **Subhan Kashif**.
