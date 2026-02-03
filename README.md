# BodyFix

> "뻐근함이 쾌감으로 바뀌는 1분"

만성적 신체 뻐근함을 느끼는 현대인에게 스트레칭을 통한 즉각적 이완과 쾌감을 제공하는 숏폼 헬스케어 서비스

## Tech Stack

- **Frontend**: Flutter Web (Riverpod MVVM)
- **Backend**: Vercel Serverless (Python/FastAPI)
- **Database**: Supabase (PostgreSQL)
- **AI**: OpenAI GPT-4o (Relief Coach)
- **Design**: 2D Body Map with Hotspots

## Getting Started

### Prerequisites

- Flutter SDK 3.27+
- Python 3.9+
- Vercel CLI
- Supabase CLI (optional, for local development)

### Installation

```bash
# Clone the repository
git clone https://github.com/TunaKimbab/bodyfix.git
cd bodyfix

# Install Flutter dependencies
flutter pub get

# Copy environment variables
cp .env.example .env
# Edit .env with your API keys

# Run development server
flutter run -d chrome
```

### Backend Development

```bash
# Install Vercel CLI
npm i -g vercel

# Run local dev server
vercel dev
```

## Project Structure

```
bodyfix/
├── lib/                    # Flutter source code
│   ├── app/               # App configuration
│   ├── core/              # Constants, utils, extensions
│   ├── data/              # Models, repositories, providers
│   ├── presentation/      # Screens, widgets
│   └── services/          # API services
├── api/                   # Vercel Serverless Functions
├── assets/                # Images, icons, sounds
├── docs/                  # Project documentation
└── test/                  # Test files
```

## Documentation

See the [docs](./docs) folder for detailed documentation:

- [Service Planning](./docs/산출물%201-a.%20서비스%20기획서.md)
- [Feature Specification](./docs/산출물%201-b.%20기능%20명세서.md)
- [System Architecture](./docs/산출물%203-a.%20시스템%20아키텍처%20구성도.md)
- [API Specification](./docs/산출물%203-c.%20API%20명세서.md)
- [ERD](./docs/산출물%203-b.%20ERD.md)

## Business Model

**Freemium** (Free + Pro $4.99/month)

| Feature | Free | Pro |
|---------|------|-----|
| 2D Body Map | O | O |
| Basic Routines | O | O |
| AI Relief Coach | X | O |
| Full Video Content | X | O |

## License

Private - All rights reserved

## Contributing

This is a private project. Please contact the maintainers for contribution guidelines.
