# MediNotes Pro application

The runnable application for the [MediNotes Pro prototype](../README.md).

## Components

- `pages/index.tsx` — public product page and Clerk sign-in.
- `pages/product.tsx` — authenticated consultation form, plan gate, streaming client, and Markdown result rendering.
- `api/index.py` — Clerk-protected FastAPI endpoint and streaming OpenAI request.

## Local development

```bash
npm install
npm run dev
```

Copy `.env.example` to `.env.local` and replace every placeholder. The Python endpoint also requires the dependencies in `requirements.txt`.

## Important safety limitation

This is a portfolio prototype—not a clinical system. Do not submit real patient information. It is not certified for HIPAA compliance, diagnosis, treatment recommendations, or unsupervised patient communication. All generated content requires qualified clinician review.

