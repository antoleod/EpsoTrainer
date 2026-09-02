# EPSO Coach

Open-source, mobile-first preparation app for EPSO competitions.

> EPSO Coach is an independent project. It is not affiliated with, endorsed by, or operated by EPSO, the European Personnel Selection Office, or any EU institution.

## Status

This repository is the **public/release repository**. Development and experimentation happen separately; only reviewed, source-traceable, copyright-safe and testable work should be promoted here.

Current focus:

- Android-first React Native + Expo app
- TypeScript strict mode
- offline-first training and mock exams
- versioned `CompetitionProfile` rules per competition
- local SQLite persistence with optional Firebase Spark sync
- source provenance for official EPSO/EU information
- original/openly reusable training content

## Product loop

```text
Understand EPSO
   ↓
Understand your competition
   ↓
Diagnostic
   ↓
Learn
   ↓
Guided Practice
   ↓
Review
   ↓
Timed Training
   ↓
Strict Mock
   ↓
Analyse + Repeat
```

## Technology

- React Native
- Expo
- TypeScript
- Expo Router
- `expo-sqlite`
- Drizzle ORM
- Zod
- Zustand
- Firebase Spark (optional cloud only)
- Vitest
- GitHub Actions

## Source authority

Competition rules must come from current official sources in this order:

1. Official Journal / EUR-Lex Notice of Competition
2. corrigenda and amending notices
3. official EPSO / EU Careers operational guidance
4. official EU learning/framework sources
5. external material only as clearly labelled unofficial learning support

Never use competitor question banks, leaked/remembered live questions, or unknown-rights assets.

## Licence

Code is intended to be released under Apache-2.0. Original EPSO Coach learning content may use CC BY 4.0 where explicitly stated. Third-party material remains subject to its own licence and should normally be linked, not rehosted.

## Development stage

The project is under active construction. Public releases should only be tagged after deterministic scoring/timer tests, source validation, offline checks, accessibility review, and legal/content review pass.
