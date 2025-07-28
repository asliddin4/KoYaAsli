# Korean Language Learning Bot

🤖 Professional Telegram bot for learning Korean and Japanese languages with AI conversation features.

## Features

- 🧠 **AI Conversation**: 12,000+ vocabulary Korean and Japanese AI tutors
- 📚 **Content Management**: Admin can upload multimedia content (text, video, audio, documents)
- 🎯 **Interactive Tests**: Topik and JLPT examination systems
- 💎 **Premium System**: Subscription-based premium features
- 👥 **Referral Program**: 10 referrals = 1 month free premium
- 📊 **Progress Tracking**: User ratings, statistics, and leaderboards
- 🔧 **Admin Panel**: Complete content and user management

## Quick Deploy to Render.com

1. **Fork this repository**
2. **Connect to Render.com**:
   - Create new Web Service
   - Connect your GitHub repository
   - Select `korean_bot_final` folder as root directory

3. **Environment Variables**:
   ```
   BOT_TOKEN=your_telegram_bot_token_here
   ```

4. **Deploy Settings**:
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `python main.py`
   - Python Version: 3.11

## Local Development

1. **Clone and setup**:
   ```bash
   git clone <your-repo>
   cd korean_bot_final
   pip install -r requirements.txt
   ```

2. **Environment setup**:
   ```bash
   export BOT_TOKEN="your_bot_token"
   python main.py
   ```

## Bot Commands

- `/start` - Start the bot and register
- `/help` - Show help information
- `/profile` - View user profile and statistics
- `/admin` - Admin panel (admin only)

## Technology Stack

- **Framework**: aiogram 3.21.0 (Telegram Bot API)
- **Database**: SQLite with aiosqlite
- **Scheduler**: APScheduler for automated tasks
- **AI System**: Custom Korean/Japanese conversation AI
- **Deployment**: Render.com compatible

## Bot Structure

```
korean_bot_final/
├── main.py              # Bot entry point
├── config.py            # Configuration settings
├── database.py          # Database operations (120+ functions)
├── keyboards.py         # Telegram keyboards
├── messages.py          # Message templates
├── handlers/            # Bot handlers
│   ├── start.py         # Start, premium, referral handlers
│   ├── admin.py         # Admin panel handlers
│   ├── sections.py      # Content sections management
│   ├── content.py       # Content upload/view handlers
│   ├── tests.py         # Quiz and test system
│   └── ai_conversation.py # AI chat handlers
└── utils/               # Utility modules
    ├── scheduler.py     # Automated messaging
    ├── subscription_check.py # Channel verification
    ├── rating_system.py # User rating calculations
    └── ai_conversation_advanced.py # AI conversation engine
```

## Features Overview

### Premium System
- Monthly subscription: 50,000 UZS
- Free access via 10 referrals
- AI conversation access
- Premium content unlock

### AI Conversation
- Korean AI: 12,000+ vocabulary
- Japanese AI: 12,000+ vocabulary  
- Cultural context awareness
- Grammar correction and learning

### Admin Features
- Content upload (multimedia)
- User management
- Premium granting
- Broadcast messaging
- Statistics and analytics

## Support

Bot created by: @Chang_chi_won
Location: South Korea (Seoul, Incheon)

For technical support or questions, contact the admin via Telegram.