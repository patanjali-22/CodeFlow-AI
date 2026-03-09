# CodeFlow-AI

![CodeFlow-AI](public/logos/logo.svg)

CodeFlow-AI is a modern, full-stack visual workflow editor and automation platform built with Next.js. It enables users to create powerful, node-based workflows that integrate AI services and various integrations seamlessly.

**I did this project.**

## Features

- **Visual Workflow Editor**: Intuitive drag-and-drop interface powered by React Flow.
- **AI Integrations**: Built-in support for multiple AI providers out of the box (OpenAI, Anthropic, Google Gemini).
- **Background Jobs**: Reliable background job execution and realtime updates using Inngest.
- **Authentication**: Secure user authentication handled by Better Auth.
- **Database**: Type-safe database operations utilizing Prisma ORM.
- **tRPC**: End-to-end typesafe APIs for seamless client-server communication.
- **Modern UI**: Beautiful and accessible component library built with Tailwind CSS and Radix UI.

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS v4
- **Database ORM**: Prisma
- **API**: tRPC
- **Workflow Engine**: Inngest
- **Auth**: Better Auth
- **AI SDK**: Vercel AI SDK
- **Diagramming**: React Flow

## Getting Started

First, install the dependencies:

```bash
npm install
```

Set up your environment variables by copying the example file:

```bash
cp .env.example .env
```

Run the development server:

```bash
npm run dev
# or for all services including Inngest
npm run dev:all
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## License

This project is open-sourced under the MIT License.
