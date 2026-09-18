# Dohama-Systems
===========================================
FLUTTER AI MICRO-SAAS STARTER KIT
======================================================================

A complete, production-ready Flutter starter kit for building and 
monetizing AI-powered applications.


----------------------------------------------------------------------
FEATURES
----------------------------------------------------------------------
- Multi-Model AI Chat: Powered by OpenAI API with dynamic model 
  switching.
- Hands-Free Voice Input: Speech-to-text with auto-silence detection 
  and auto-send.
- Supabase Backend: Built-in support for authentication and chat 
  history persistence.
- Monetization Ready: Integrated modular Paywall UI ready for RevenueCat 
  in-app purchases.
- Modern Dark UI: Clean, responsive, user-friendly interface.
- Secure Architecture: Environment variables (.env) for safe API 
  key management.


----------------------------------------------------------------------
PROJECT STRUCTURE
----------------------------------------------------------------------
```
lib/
├── app/          # Core app routes and configuration
├── core/         # API services (OpenAI, Supabase) & themes
├── features/     # App features (AI Chat, Auth, Paywall)
└── widgets/      # Reusable UI components (PaywallDialog, etc.)
```


----------------------------------------------------------------------
TECH STACK
----------------------------------------------------------------------
- Framework: Flutter
- AI: OpenAI API (GPT-4o-mini)
- Backend & Auth: Supabase
- Monetization: RevenueCat
- Config: flutter_dotenv


----------------------------------------------------------------------
QUICK START GUIDE
----------------------------------------------------------------------
1. Open the Project
   Open the project directory in VS Code or your preferred IDE.

2. Configure Environment Variables
   Duplicate .env.example and rename the copy to .env.

3. Add Your API Keys
   Open .env and fill in your API credentials:
   - OpenAI API Key: Get yours at https://platform.openai.com
   - Supabase URL & Anon Key: Found in your Supabase Dashboard 
     under Project Settings -> API
   - RevenueCat Keys: Found in your RevenueCat Dashboard 
     under API Keys

4. Install Dependencies & Run
   flutter pub get
   flutter run
