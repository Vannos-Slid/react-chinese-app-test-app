## Overview
Features:

- 📱 Cross-platform iOS/Android app with Expo + Expo Router
- 🔐 Passwordless authentication with Supabase magic links
- 🧭 Personalized onboarding flow (level, motivation, interests)
- 📚 Structured Japanese curriculum (12 chapters, 75 lessons)
- 🎧 Listening + speaking practice modes with progress tracking
- 🎙️ Voice recording and AI transcription for pronunciation practice
- 💬 Real-time AI roleplay conversations with scenario goals/tasks
- ✨ Custom scenario generation
- 📈 Speaking/listening stats and lesson completion tracking
- 💳 In-app paywall flow

## Setup

### Supabase Setup

Login and link your project:

```bash
npx supabase login
npx supabase link --project-ref usggeagiaedngaafbckz
```

Deploy Edge Functions:

```bash
npx supabase functions deploy chat-completion
npx supabase functions deploy transcribe-audio
npx supabase functions deploy scenario-generate
npx supabase functions deploy start-trial
```

### Frontend

Run the app:

```bash
npm run start
```

Run on iOS simulator:

```bash
npm run ios
```

Run on Android emulator:

```bash
npm run android
```
