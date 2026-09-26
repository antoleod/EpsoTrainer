# EPSO Coach

[![Powered by RustChain](https://img.shields.io/badge/Powered%20by-RustChain-orange)](https://rustchain.org)

**Mobile-first preparation for EPSO competitions, built around traceable sources and offline practice.**

EPSO Coach is an open-source React Native application designed to support structured preparation for EPSO competitions. The project combines guided learning, practice, mock exams and progress review while keeping competition rules tied to official source material.

> EPSO Coach is an independent project. It is not affiliated with, endorsed by, or operated by EPSO, the European Personnel Selection Office, or any EU institution.

## Why this project

Preparation tools are most useful when they are clear about what is official, what is training content and what changes between competitions. EPSO Coach is being designed around that distinction.

## Product loop

```text
Understand EPSO
      ↓
Understand the competition
      ↓
Diagnostic
      ↓
Learn + Guided Practice
      ↓
Review
      ↓
Timed Training
      ↓
Strict Mock
      ↓
Analyse + Repeat
```

## Current focus

- Android-first React Native + Expo application
- TypeScript strict mode
- Offline-first training and mock exams
- Versioned `CompetitionProfile` rules per competition
- Local SQLite persistence
- Optional Firebase Spark synchronization
- Source provenance for official EPSO / EU information
- Original or openly reusable training content
- Deterministic scoring and timer behavior

## Technology

![React Native](https://img.shields.io/badge/React_Native-0F172A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-0F172A?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=3178C6)
![SQLite](https://img.shields.io/badge/SQLite-0F172A?style=flat-square&logo=sqlite&logoColor=58A6D6)
![Firebase](https://img.shields.io/badge/Firebase-0F172A?style=flat-square&logo=firebase&logoColor=FFCA28)

Core stack: **React Native · Expo · TypeScript · Expo Router · expo-sqlite · Drizzle ORM · Zod · Zustand · Vitest · GitHub Actions**

## Source authority

Competition rules should come from current official sources in this order:

1. Official Journal / EUR-Lex Notice of Competition
2. Corrigenda and amending notices
3. Official EPSO / EU Careers operational guidance
4. Official EU learning/framework sources
5. External material only when clearly labelled as unofficial learning support

Competitor question banks, leaked or remembered live questions and assets with unclear rights are intentionally excluded.

## Quality bar

Public releases should only be tagged after the relevant scoring/timer tests, source validation, offline checks, accessibility review and legal/content review pass.

## Repository role

This is the **public/release repository**. Development and experimentation happen separately so the public branch can remain reviewable and source-traceable.

## Licence

Code is intended to be released under Apache-2.0. Original EPSO Coach learning content may use CC BY 4.0 where explicitly stated. Third-party material remains subject to its own licence and should normally be linked rather than rehosted.

---

Built by [Juan Carlos Dioses](https://github.com/antoleod) · [LinkedIn](https://www.linkedin.com/in/juan-dioses)
