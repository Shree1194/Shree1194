# Aadesh Kapadnis | Software Developer

I build full-stack web applications and AI-assisted tools, and I document what is tested, what is not, and where my code builds on other people's work.

## About

I am an Electronics and Telecommunication Engineering graduate (SPPU, 2026) based in Nashik, India, moving into software development. My projects so far are a voice-based AI interview practice app (Next.js, Firebase), a real-time chat application (React, Express, Socket.IO, MongoDB), and a command-line toolkit for verifiable AI-assisted development (Node.js). I care about the unglamorous parts of engineering: authorization boundaries, failing safely when an external service is down, tests, and READMEs that state limitations plainly.

I am looking for an entry-level role as a Software Developer, Python or Node.js Backend Developer, Full-Stack Developer, or AI Application Engineer.

## Featured projects

Each README lists what is verified, what is not, and any upstream attribution.

### 1. [PrepWise AI Mock Interview](https://github.com/Shree1194/prepwise-ai-mock-interview)

AI-assisted interview practice with voice interviews, structured feedback, resume analysis and PDF reports.

| | |
|---|---|
| **Stack** | Next.js 15, TypeScript, Firebase Auth and Firestore, Vercel AI SDK (Gemini, OpenAI, Anthropic), Vapi, Zod |
| **Engineering** | Owner-scoped data access with Firestore rules; AI provider fallback with retries and deadlines; code execution fails closed until a private sandbox is verified |
| **Evidence** | 15 of 15 local tests, type check and lint passing on 2026-10-16. No CI yet |
| **Not yet verified** | Voice, resume and history journeys against a staging Firebase project |
| **Attribution** | Built on the JavaScript Mastery AI Mock Interview tutorial; the README lists what I added. No license is offered because the tutorial repo has none |
| **Live demo** | None |

### 2. [Nook Chat](https://github.com/Shree1194/nook-chat)

Real-time one-to-one messaging with presence and image/video attachments.

| | |
|---|---|
| **Stack** | React 19, Vite, Express 5, Socket.IO, MongoDB (Mongoose), Clerk, ImageKit, Docker |
| **Engineering** | Clerk-verified REST and WebSocket authentication; private profile fields withheld from other users; recipient and file-content validation; single-origin Docker image |
| **Evidence** | 27 of 27 backend regression tests (authorization, recipient and upload validation, Socket.IO handshake), lint and builds passing locally on 2026-10-16. CI workflow added; no end-to-end run with real services |
| **Attribution** | Backend structure follows the MIT-licensed fullstack-chat-app tutorial by Burak (notice kept); auth, uploads, validation and tests are changes here |
| **Live demo** | None. Deployment is pending |

### 3. [Aadesh Genesis](https://github.com/Shree1194/aadesh-genesis)

[![Tests](https://github.com/Shree1194/aadesh-genesis/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/Shree1194/aadesh-genesis/actions/workflows/test.yml)

A CLI toolkit that records goals, approvals, evidence and recovery checkpoints for resumable, verifiable AI-assisted coding.

| | |
|---|---|
| **Stack** | Node.js 22 (no runtime dependencies), `node:test`, GitHub Actions on Ubuntu and Windows |
| **My contribution** | A customized fork of the open-source Genesis Kit. I added the `tasks`, `approve`, `resume` and `--version` commands, Windows process-tree termination and Python detection, a Windows CI matrix, and matching tests. The core design and most of the code are upstream's |
| **Evidence** | 75 of 75 local tests passing on 2026-10-16; CI run on the current `main` commit succeeded on Ubuntu and Windows |

## Skills

**Used in the projects above**

- **Languages:** JavaScript, TypeScript
- **Frontend:** React, Next.js, Vite, Tailwind CSS
- **Backend and APIs:** Node.js, Express, Socket.IO, REST design, Zod validation
- **Databases and cloud:** MongoDB, Firebase (Auth, Firestore), ImageKit
- **AI integration:** Vercel AI SDK, Gemini API, structured output with fallback, Vapi voice agents
- **DevOps and quality:** Git, GitHub Actions, Docker, `node:test`, ESLint

**Also used (see other repositories)**

- Python, SQL

## Contact

[Portfolio](https://shree1194.github.io/aadesh-portfolio/) · [GitHub](https://github.com/Shree1194)
