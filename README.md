# Yuki — Virtual AI Companion

> **A personality beyond AI.**

Yuki is a fictional virtual AI companion project built around a consistent character identity, natural conversations, user-controlled memory, and a recognizable visual avatar.

## Project identity

- **Name:** Yuki
- **Project:** Yuki AI Companion
- **Character age in the fictional profile:** 18
- **Role:** Virtual AI companion
- **Visual reference:** [`public/avatar/yuki-reference.png`](public/avatar/yuki-reference.png)
- **Project status:** Planning and foundation

## Vision

Create a virtual companion whose identity and communication style remain consistent across conversations and supported AI model providers. The AI implementation may change; Yuki's versioned character definition remains the source of truth.

## Planned capabilities

- Consistent character identity and personality
- Conversational interface with streaming responses
- Conversation history
- User-controlled long-term memory
- Configurable AI model providers
- Expressive avatar and visual assets
- Optional voice and multimodal capabilities
- Account security and privacy controls

These are planned capabilities, not claims about features already implemented.

## Character files

- [`persona/yuki/identity.md`](persona/yuki/identity.md) — canonical identity
- [`persona/yuki/visual-reference.md`](persona/yuki/visual-reference.md) — appearance and visual reference
- [`persona/yuki/personality.md`](persona/yuki/personality.md) — stable character traits
- [`persona/yuki/communication.md`](persona/yuki/communication.md) — conversational style
- [`persona/yuki/boundaries.md`](persona/yuki/boundaries.md) — transparency and interaction boundaries

## Documentation

- [`docs/VISION.md`](docs/VISION.md) — product vision
- [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md) — proposed technical architecture
- [`docs/ROADMAP.md`](docs/ROADMAP.md) — development phases
- [`docs/PRIVACY.md`](docs/PRIVACY.md) — privacy and memory principles

## Proposed technology direction

- Next.js and TypeScript for the web application
- Tailwind CSS and an accessible component system for the UI
- A provider-independent AI integration layer
- PostgreSQL for application data
- Optional vector search for semantic memory
- Automated tests for character consistency, privacy, and core flows

Exact dependency versions and infrastructure choices should be pinned when implementation begins.

## Security principles

- Never commit API keys, access tokens, passwords, or real `.env` files.
- Keep provider credentials on the server only.
- Enforce per-user data access in the database, not only in the UI.
- Let users inspect, correct, and delete saved memories.
- Treat uploaded media and conversation content as private user data.

## License

No open-source license is currently granted. All rights reserved unless the repository owner adds a license.
