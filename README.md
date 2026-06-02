# GaGcodes

> Engineered for structured AI application development. Precision at the speed of thought.

GaGcodes is an AI-assisted app builder interface that helps developers shape application ideas step by step. The project focuses on structured prompts, clean frontend flow, and a practical development experience for turning rough ideas into working app plans.

[Live Demo](https://gagankumar44.github.io/GaGcodes/) · [Repository](https://github.com/Gagankumar44/GaGcodes)

## Highlights

- Structured AI workflow for building apps without losing context.
- React + TypeScript frontend powered by Vite.
- Tailwind-ready styling setup for fast UI iteration.
- Motion and Lucide dependencies for polished interactions and icons.
- Environment placeholders for Gemini API and app hosting configuration.

## Tech Stack

| Area | Tools |
| --- | --- |
| Frontend | React 19, TypeScript, Vite |
| Styling | Tailwind CSS, clsx, tailwind-merge |
| Motion & Icons | motion, lucide-react |
| AI | Google GenAI SDK |
| Tooling | npm, TypeScript, Vite |

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Gagankumar44/GaGcodes.git
cd GaGcodes
```

Install dependencies:

```bash
npm install
```

Create your environment file:

```bash
cp .env.example .env
```

Fill in the required values:

```env
GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
APP_URL="YOUR_APP_URL"
```

Run the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Run the TypeScript check:

```bash
npm run lint
```

## Project Structure

```text
GaGcodes/
├── index.html
├── metadata.json
├── package.json
├── tsconfig.json
├── vite.config.ts
└── .env.example
```

## Roadmap

- Add clearer onboarding for first-time users.
- Improve generated app planning steps and prompt structure.
- Add more saved workflow states.
- Expand examples for common app types.
- Add screenshots or a short demo walkthrough.

## Notes

This repository does not include real API keys. Add your own values in `.env` when running locally.
